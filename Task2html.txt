<!DOCTYPE html>
<html>
<head>
	<title>control pannel</title>

	<style>

		#h1{
			text-align:center;
			color:grey;
			text-transform: capitalize;
		    }

        body{
        	background-color:#99B898;
        	color: black;      	
        }

        button{
        	border:#E5EEC1;

        	background-color: #F09B93;
        }



	</style>

</head>

<body>
<form action="coconut.php" method="post">
<h1 id="h1">ContorlMe</h1><br>

<br><br><br><br><br><br>

<hr>
<p style="text-align: center;">
<button type="submit" name="forward" >Forward</button>
</p>


<p 
style="text-align: center;">
<button type="submit" name="left" >Left</button>
<button type="submit" name="stop" >stop</button>
<button type="submit" name="right" >Right</button>

</p>

<p style="text-align: center;">
<button type="submit" name="backward" >backward</button>
</p>

<br>

<hr>
</form>




</body>


</html>