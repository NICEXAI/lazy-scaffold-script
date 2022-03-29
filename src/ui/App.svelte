<script lang="ts">
	import { onMount } from "svelte"
	import {hello} from "../content/index"

	onMount(() => {
		hello()
	})
</script>
