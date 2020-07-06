
<html>
<head>
<title> Calculator</title>
</head>
<body>
<script>
document.write("Note:Upward, rightward and clockwise motions are considered positive while others are considered negative");
var fx = parseInt(prompt("Enter Summation of horizontal forces"));
var fy = parseInt(prompt("Enter Summation of vertical forces"));
var m = parseInt(prompt("Enter Summation of moments"));
var Rm= Math.sqrt(fx*fx + fy*fy);
var angle=Math.atan(fy/fx);
var xint= m/fy;
var yint = y/fx;
document.write("Magnitude of resultant force is"+Rm);
document.write("Inclination of resultant force is"+atan);
document.write("X Intercept of resultant force is"+xint);
document.write("Y intercept of resultant force is"+yint);
</script>
</body></html>
