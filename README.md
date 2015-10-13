# CanvasTest
Just to test my Canvas


<!DOCTYPE html>
<html lang="en-US">
<head>
 <meta charset="UTF-8" http-equiv="refresh" content="2"/>
 <link rel="stylesheet" href="Style.css"/>
</head>
<body>
 <canvas id="MCanvas" width="400" height="400" style="border: 1px solid black;"></canvas>
 
 <script>
 var c =document.getElementById("MCanvas");
 var ctx = c.getContext("2d");
 
 ctx.fillStyle = "#ff0000" 
 
 ctx.fillRect(100,100,200,200);
 
 ctx.beginPath();
 ctx.arc(100,100,50,0,2*Math.PI);
 ctx.stroke();
 ctx.beginPath();
 ctx.arc(100,300,50,0,2*Math.PI);
 ctx.stroke();
 ctx.beginPath();
 ctx.arc(300,100,50,0,2*Math.PI);
 ctx.stroke();
 ctx.beginPath();
 ctx.arc(300,300,50,0,2*Math.PI);
 ctx.stroke();

 ctx.moveTo(100,100);
 ctx.lineTo(300,300);

 ctx.moveTo(0,400);
 ctx.lineTo(100,300);
 
 ctx.moveTo(400,0);
 ctx.lineTo(300,100);
 
 ctx.moveTo(175,225);
 ctx.lineTo(225,175)
 
 ctx.stroke();
 
 //Create gradient var
 var grd =ctx.createLinearGradient
 
 
 
 
 
 
 
 
</script>
 
</body>
</html>
