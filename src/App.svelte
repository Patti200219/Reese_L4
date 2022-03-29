<script>
	import Todo from './Todo.svelte';
</script>

<main>
	
	
	<h1>To-Do List!</h1>
	<Todo/>
	
</main>

<style>
	main {
		text-align: center;
		
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color:#f0631c;
		text-transform: uppercase;
		font-size: 5em;
		font-weight: bold;
		font-family: 'Patrick Hand', cursive;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
	
</style>

