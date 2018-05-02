<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>youku</title>
		<style>
			div {
				height: 100px;
				width: 100px;
				background: red;
				animation: qq 3s 1s linear infinite;
				
				position: relative;
				
			}
			
			/*火狐*/
			/*@-moz-keyframes qq{
				from{background: red;}
				to{background: yellow;}
			}*/
			
			/*ie*/
			@keyframes qq{
				0% {background: red;left: 0px; top: 0px;}
				25% {background: yellow;left: 500px; top: 0px;}
				50% {background: blue;left: 500px; top: 500px;}
				75% {background: green;left: 0px; top: 500px;}
				100% {background: darkcyan;left: 0px; top: 0px;}
			}
		</style>
	</head>
	<body>
		
		<div>
			
		</div>
		
	</body>
</html>
