<!-- GAME-STATS --><html>
<head>
<title>Page Title</title>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}

table {
font-family: arial, sans-serif;
border-collapse: collapse;
width: 100%;
}

td, th {
border: 1px solid #F9F9F9;
text-align: left;
padding: 8px;
}

tr:nth-child(even) {
background-color: #F9F9F9;
}
.dropbtn {
background-color: #3498DB;
color: white;
padding: 16px;
font-size: 16px;
border: none;
cursor: pointer;
}

.dropbtn:hover, .dropbtn:focus {
background-color: #2980B9;
}

.dropdown {
position: relative;
display: inline-block;
}

.dropdown-content {
display: none;
position: absolute;
background-color: #f1f1f1;
min-width: 160px;
overflow: auto;
box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
z-index: 1;
}

.dropdown-content a {
color: black;
padding: 12px 16px;
text-decoration: none;
display: block;
}

.dropdown a:hover {background-color: #ddd;}

.show {display: block;}
</style>
</head>
<body>

<h1 align="center">Volleyball Statistics</h1>

<div class="dropdown">
<button onclick="myFunction()" class="dropbtn">Menu</button>
<div id="myDropdown" class="dropdown-content">
<a href="https://laurapellicano.github.io/game-stats/">Home</a>
<a href = "https://laurapellicano.github.io/volleyball-stats/?teamname=&coachname=&gamesanddates=/"> Statistics</a>
<a href="https://laurapellicano.github.io/Page2/">Page2</a>
<a href="https://laurapellicano.github.io/Page3/">Page3</a>
</div>
</div>
<h2 align = "center"> Welcome!</h2>
<p1 align = "center"> Please fill our the name of the person doing the registration, an appropriate email, any comments you want to be made, the team name, and the coach's name. <p1>
<p2 align= "center"> Once you have filled this out it will produce an email that will be sent to you recording your data then you will be ready to start taking statistcs for your team during each game <p2>
<p3 align = "center"> Head over to the statistics page to begin <p3>

<script>
/* When the user clicks on the button, 
toggle between hiding and showing the dropdown content */
function myFunction() {
document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(event) {
if (!event.target.matches('.dropbtn')) {

var dropdowns = document.getElementsByClassName("dropdown-content");
var i;
for (i = 0; i < dropdowns.length; i++) {
var openDropdown = dropdowns[i];
if (openDropdown.classList.contains('show')) {
openDropdown.classList.remove('show');
}
}
}
}

</script>



      
      
<table>
<tr>
<form action="mailto:someone@example.com" method="post" enctype="text/plain">
<th><label for="Name"></label>  Name:<br>
<input type="text" name="name"><br>
<th><label for="Email"></label> E-mail:<br>
<input type="text" name="mail"><br>
<th><label for="Comment"></label>Comment:<br>
<input type="text" name="TeamName"><br>
<th><label for="Comment"></label>Team Name:<br>
<input type="text" name="CoachesName"><br>
<th><label for="Comment"></label>Coaches Name:<br>
<div> 
<input type="text" name="comment" size="50"><br><br>
<input type="submit" value="Send">
<input type="reset" value="Reset">
</form>
</div>
</table>


<form method="get" action="https://laurapellicano.github.io/volleyball-stats/?teamname=&coachname=&gamesanddates=/">
<button type="submit">Next</button>
</form>
x      <br/><br/>

      
      
