# Description

- Web component that allows for Collada object to be placed in a 3D scene with a camera

# Usage

	<!DOCTYPE html>
	<html>
		<head>
			<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	
			<!-- Polyfill -->
			<script src="https://cdnjs.cloudflare.com/ajax/libs/webcomponentsjs/0.7.7/webcomponents.min.js"></script>
			<link rel="import" href="camera-object.html">
	
			<style>
				body, html {
					height: 100%;
					padding: 0;
					margin: 0;
					background-color: #ff0000;
				}
			</style>
		</head>
		<body>
			<div style="width: 90%; height: 90%; display: inline-block; background-color: #333333">
				<camera-object background-image="https://www.blueskyexhibits.com/website/wp-content/uploads/sky-home.jpg" src="models/plane2/plane2.dae" objectpositionx="0" objectpositiony="-3" objectpositionz="-3" objectrotationx="0" objectrotationy="45" objectrotationz="0" camerapositionx="0" camerapositiony="0" camerapositionz="30" camerarotationx="0" camerarotationy="0" camerarotationz="0"></camera-object>
			</div>
		</body>
	</html>