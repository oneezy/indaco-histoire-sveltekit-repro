<script lang="ts">
	// the alias fixes lint error 'Hst' is already defined
	import type { Hst as Histoire } from '@histoire/plugin-svelte';
	import { URLpath } from '$components/URLpath/index.js';

	export let Hst: Histoire;
</script>

<!--❌ THIS BREAKS! ❌-->
<Hst.Story title="Example/URLpath">
	<URLpath />
</Hst.Story>
