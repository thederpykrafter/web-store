<script>
	import '../app.css';
	let { children } = $props();
  import NavBar from './NavBar.svelte';
</script>
 
<NavBar />

{@render children()}
