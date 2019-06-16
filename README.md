# cv4


<html>
<head>

<link rel="stylesheet"
		href="web1.css" type="text/css">

 


<style>/* Stylesheet 3: */
body {
    font: 100% Verdana;
    margin: 20px;
    line-height: 26px;
	background-image: url("color.gif");
	
    
}

.container {
    xmin-width: 900px;
}

.wrapper {
    position: relative;
    overflow: auto;
}

#sidebar {
    background-color: #f1f1f1;
    border: 1px solid #d4d4d4;
    padding-left: 10px;
}

#bottom {
    text-align: center;
    padding: 10px;
    font-size: 70%;
    line-height: 14px;
}

h1, h2, h3 {
    color: #4CAF50;
}

#menulist {
    padding: 0;
    position: relative;
    overflow: auto;
}

.menuitem {
    width: 165px;
    float: left;
    background-color: #555555;
    color: #ffffff;
    list-style-type: none;
    margin: 4px;
    padding: 2px;
    text-align: center;
    cursor: pointer;
}

.menuitem:nth-child(3) {
   background-color:#4CAF50;
}

.menuitem:hover {
    background-color: #999999;
}

a {
    color: #000000;
}

a:hover {
    color: #84c754;
}

h1 {
  color: white;
  text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;
}


html { 
  background: url(color.gif) no-repeat center fixed; 
  background-size: cover;
}




</style>

<style>
img {
  border-radius: 50%;
}
</style>




</head>
<body>



<div class="container wrapper">
  <div id="top">

    
    
  </div>




  <div class="wrapper">
   <div id="menubar">
     <ul id="menulist">
       
       
       
     </ul>
    </div>
    <div id="main">


      <h1>Harshitha's profile</h1>
      <p>
<table cellspacing="10">
 <tr align="left" valign="top">
	<td>	
		<br>
			<style>
			#borderimg 
			{ 
  			border: 10px solid transparent;
  			padding: 15px;
 			 border-image:img src(harshi.jpg) 30 round;
			}
			</style>


		<img src ="harshi.jpg" alt="Harshitha's profile photo" height = "200" width = "200" allign= "centre">
 
	</td>
	<td>
		  <p style="color:chocolate;font-weight:bold;font-family:Arial,Helvetica,sans-serif">   <font size="4"> <b>Harshitha H T </b> </font> <br>
		  <font size="2"><i> email id:</i><em>harshithaht03@gmail.com </em> <br>
		    
		    
		   </font> </p>	
	</td>
 </tr>
<hr>
<table cellspacing="5">


 <tr align="left" valign="top">

<style>
table, td, th {
  border: 1px solid black;
}

table {
  border-collapse: collapse;
  width: 100%;
}

th {
  text-align: left;
}

</style>

	<tr>
		<br>
		<p class="leftah" style="background-color:green;font-weight:bold">EDUCATION </p>
	</tr>

<table>
  <tr>
  <th>Cource</th>
  <th>Name of institute</th>
  <th>Percentage</th>
  </tr>
  <tr>
  <td>BE</td>
  <td>SIT</td>
  <td>CGPA:7.26</td>
  </tr>
  <tr>
  <td>PU</td>
  <td>Deeksha integrated</td>
  <td>80</td>
  </tr>
  <tr>
  <td>SSLC</td>
  <td>Bhoomi public school</td>
  <td>89</td>
  </tr>
  
</table>






 
<tr align="left" valign="top">
	<td>
		<br>
		<p class="leftah" style="background-color:green;font-weight:bold"> TECHNICAL SKILLS </p>
	</td>
	<td>
		<p class="leftall"> <font size="3"><i>Languages known</i><li>c</li>
							<li>c++</li></font></p>
		
		 
	</td>
 </tr>

<tr align="left" valign="top">
	<td>
		<p class="leftah" style="background-color:green;font-weight:bold"> WORKSHOP </p>
	</td>
	<td>
		<p class="leftall"> <font size="3"><i><li>Attended the workshop of Artifical intelligence</li></i>
						<i><li>Attended the workshop of latex</li></i><br></font>
		 </p> 
	</td>
 </tr>

<tr align="left" valign="top">
	<td>
		<br>
		<p class="leftah" style="background-color:green;font-weight:bold"> INTERESTS </p>
	</td>
	<td>
		<p class="leftall"> <font size="3"><i><li>Travelling</li></i>
		<i><li>Dancing</li></i></font> </p> 
	</td>
 </tr>

</table>
<hr>

<table>
<h4> Feedback </h4>
<tr>
<td>
<form action="web1.html" method="get">
First Name:<input type="text" name="fname"> <br>
Last Name :<input type="text" name="lname"> <br>
Email ID  :<input type="text" name="mail"> <br>

<input type="Submit" value="submit">
</form>
</td>
</tr>
</table>
<hr style="background-color:olive;">
<p calss="last" style="background-color:olive;"> <font size="3">Contact details</font> <br style="background-color:olive;">
 Website link- <a href="http://www.sit.ac.in"> link </a> <br style="background-color:olive;">
 Mail address- <a href="mailto:harshithaht03@gmail.com"> maillink </a> </p>
 </p>
      
<script>
function noStyles() {
    document.styleSheets[0].disabled = true;
    document.styleSheets[1].disabled = true;
    document.styleSheets[2].disabled = true;
    document.styleSheets[3].disabled = true;
}

function reStyle(n) {
    noStyles()
    document.styleSheets[n].disabled = false;
}

function closeBlackdiv() {
    var blackdiv, stylediv;
    blackdiv = document.getElementById("blackdiv")
    blackdiv.parentNode.removeChild(blackdiv);
    stylediv = document.getElementById("stylediv")
    stylediv.parentNode.removeChild(stylediv);
}

function showStyle(n) {
var div, text, blackdiv;
blackdiv = document.createElement("DIV");
blackdiv.setAttribute("style","background-color:laverder;position:absolute;width:100%;height:100%;top:0;opacity:0.5;margin-left:-20px;");
blackdiv.setAttribute("id","blackdiv");
blackdiv.setAttribute("onclick","closeBlackdiv()");
document.body.appendChild(blackdiv);
div = document.createElement("DIV");
div.setAttribute("id","stylediv");
div.setAttribute("style","background-color:#ffffff;padding-left:5px;position:absolute;width:auto;height:auto;top:100px;bottom:50px;left:200px;right:200px;overflow:auto;font-family: monospace; white-space: pre;line-height:16px;");
text = document.createTextNode(document.getElementsByTagName("STYLE")[n].innerHTML);
div.appendChild(text);
document.body.appendChild(div);
//alert(document.getElementsByTagName("STYLE")[n].innerHTML);
}
reStyle(0);
</script>

</body>
</html>

