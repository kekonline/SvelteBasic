<script>
  import Nested from "./Nested.svelte";
</script>

<p>This is a paragraph.</p>
<Nested />

<!-- <script>
	let count = 0;
$: {console.log(`The count is:  ${count}`)
	 console.log("Triggered when changed")
if(count >= 10){

	alert("count is very hight")
	count = 0;
}
		
	 }	
	function handleClick() {
		count += 1;
	}
</script>

<button on:click={handleClick}>
	Clicked {count}
	{count === 1 ? 'time' : 'times'}
</button> -->

<!-- test -->

<!-- <script>
	let string = `this string contains some <strong>HTML!!!</strong>`;
</script>

<p>{@html string}</p> -->

<!-- <script>
	let count = 0;
	$: double = count * 2;

	function increment() {
		count += 1;
	}
</script>

<button on:click={increment}>
	Clicked {count}
	{count === 1 ? 'time' : 'times'}
</button>

<p>{count} double is {double}</p> -->

<style>
  p {
    color: goldenrod;
    font-family: "Comic Sans MS", cursive;
    font-size: 2em;
  }
</style>
