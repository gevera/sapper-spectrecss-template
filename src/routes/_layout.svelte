<style lang="scss" global>
	 @import "../../static/styles/global.scss";
</style>
<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<Nav {segment}/>

<div class="flex-centered">
	<main>
		<slot></slot>
	</main>
</div>
	