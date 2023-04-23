<script lang="ts">
	import { drawerStore } from '@skeletonlabs/skeleton';

	function drawerClose(): void {
		drawerStore.close();
	}
</script>

<nav class="list-nav p-4">
	<ul>
		<li><a href="/" on:click={drawerClose}>Notes</a></li>
		<li><a href="/?test=1" on:click={drawerClose}>Other Page 1</a></li>
		<li><a href="/?test=2" on:click={drawerClose}>Other Page 2</a></li>
		<li><a href="/?test=3" on:click={drawerClose}>Other Page 3</a></li>
	</ul>
</nav>
