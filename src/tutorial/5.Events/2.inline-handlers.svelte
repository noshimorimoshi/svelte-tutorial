<script>
	let m = { x: 0, y: 0 };
</script>
	<!-- inline events 👇 -->
<div on:mousemove={e => m = { x: e.clientX, y: e.clientY }}>
		<!-- inline events 👆 -->
	The mouse position is {m.x} x {m.y}
</div>

<style>
	div { width: 100%; height: 100%; }
</style>