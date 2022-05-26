<script>
	import Dropzone from "dropzone";

	function dropzoneAction(node) {
		let svd = new Dropzone(node, {
			url: "#"
		})
	}
</script>

<div class="container">
	<div use:dropzoneAction></div>
</div>

<style>
	.container {
		border: 1px solid black;
		width: 300px;
		height: 300px;
	}
</style>