<script>
	import Dropzone from "dropzone";

	function dropzoneAction(node) {
		let svd = new Dropzone(node, {
			url: "#"
		})
	}
</script>

<div class="container">
	<div use:dropzoneAction class="dropzone"></div>
</div>

<style>
	.container {
		width: 400px;
		height: 400px;
	}

	.dropzone {
		width: inherit;
		height: inherit;
	}

</style>