<!DOCTYPE html>
<html>
<head>
	<style>
		#offsetdiv {
			top: 80px;
			margin: 20px;
			padding: 10px;
			width: 350px;
			position: absolute;
			border: 5px solid green
		}
        button{
            background-color: rgb(75, 158, 236);
            color: white;
            border-radius: 10px;
            height: 30px;
        }
        h1{
            text-align: center;
        }
	</style>
</head>

<body>
	
	<h1>Welcome to our website</h1>
	<div id="offsetdiv">
		
<p>
			<button onclick="offtop()">Show Offset Top</button>
            <button onclick="offh()">Show Offset Height</button>
		</p>

		
<p> <span id="gfg"></span></p>


	</div>
	<script>
        var x = document.getElementById("offsetdiv");
		function offtop() {
			var x = document.getElementById("offsetdiv");
			document.getElementById("gfg").innerHTML ="OffsetTop: "+
			x.offsetTop;
		}
        function offh() {
			
			document.getElementById("gfg").innerHTML ="OffsetHight: "+
			x.offsetHeight;
		}
	</script>
</body>
</html>
