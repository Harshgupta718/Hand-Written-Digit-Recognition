<!DOCTYPE html>
<html>
<head>
	<meta charset='utf-8'>
	<meta http-equiv='X-UA-Compatible' content='IE=edge'>
	<meta name='viewport' content='width=device-width, initial-scale=1'>
	<title>Hand Written Digit Recognition</title>
	<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
	<script src="js/chart.min.js"></script>
	<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@latest"></script>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" >    
	<link rel="stylesheet" type="text/css" href="style/digit.css">
</head>
<body>
	<header>
		<div class="container mt-1">
			<div class="digit-demo-container">
				<h3>Hand Written Digit Recognition</h3>
					<div class="flex-two">
						<div id="canvas_box_wrapper" class="canvas-box-wrapper">
							<div id="canvas_box" class="canvas-box"></div>
							<div class="col-12">
								<button id="clear-button" class="btn btn-dark">Clear</button>
							</div>
							<div class="col-12">
								<button id="predict-button" class="btn btn-dark">Predict</button>
							</div>
						</div>
						<div class="col-6">
							<div id="result_box" class="col-12 col-md-7">
								<canvas id="chart_box" width="110" height="180"></canvas>
							</div>
							<div class="col-12 d-block mt-2 mt-md-0 text-md-left prediction-text"></div>
						</div>
					</div>
			</div>
		</div>
	</header>   

	<script src="js/digit-recognition.js"></script>
</body>
</html>
