<script>
	export let name;
	export let age;

	function incrementAge() {
		age += 1;
	}
</script>

<style>
	h1 {
		color: purple;
	}
	p {
		color: red;
	}
</style>

<h1>Hello {name}, my age is {age}!</h1>
<p>Ploty</p>
<button on:click="{incrementAge}">Change Age</button>
