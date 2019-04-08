# parallax

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Under Water</title>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/parallax/3.1.0/parallax.min.js"></script>
	<style>
		body {
			padding: 0;
			margin:0;
			width: 100%;
			height: 100vh;
		}
		.scene {
			width: 100%;
			height: 100vh;
			background: url(1.jpg) center no-repeat;
			background-size: cover;
			overflow: hidden;
		}

		img {
			max-width: 100%;
			height: auto;
		}
	</style>
</head>
<body>
	<div class="scene" id="scene">
		<div class="item" data-depth="0.4"><img src="2.png" alt="" /></div>
		<div class="item" data-depth="1"><img src="3.png" alt="" /></div>
		<div class="item" data-depth="0.8"><img src="4.png" alt="" /></div>
		<div class="item" data-depth="0.6"><img src="5.png" alt="" /></div>
		<div class="item" data-depth="1.2"><img src="6.png" alt="" /></div>
		<div class="item" data-depth="3.6"><img src="7.png" alt="" /></div>
	</div>

	<script>
		var scene = document.getElementById('scene');
		var parallaxInstance = new Parallax(scene);
	</script>
</body>
</html>
```
