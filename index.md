<html>


	<head>


		<title>Javascript</title>


	</head>


	<body>
		<p>What is the magic word?</p>

		<input type="text" id="input">

		<button id="button">Try!!!</button>

		<script type="text/javascript">


			document.getElementById("button").onclick=function(){
				var magic_word="abcd";
				var enteredmagicword=document.getElementById("input").value;
				if(magic_word==enteredmagicword){
					alert(Math.floor((Math.random()*5)+1));
				}
				else{
					alert("try again!");
				}


			}
		</script>
	</body>
</html> 
