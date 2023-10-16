<script>
  let m = { x: 0, y: 0 };

  function handleMove(event) {
    m.x = event.clientX;
    m.y = event.clientY;
  }
</script>

<div on:pointermove={handleMove}>
  The pointer is at {m.x} x {m.y}
</div>

<!-- <script>
	let m = { x: 0, y: 0 };
</script>

<div
	on:pointermove={(e) => {
		m = { x: e.clientX, y: e.clientY };
	}}
>
	The pointer is at {m.x} x {m.y}
</div>

<style>
	div {
		position: fixed;
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
		padding: 1rem;
	}
</style> -->

<style>
  div {
    position: fixed;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    padding: 1rem;
  }
</style>
