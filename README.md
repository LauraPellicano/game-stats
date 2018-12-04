<!-- MAIN PAGE --><html>
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


<div class="dropdown">
<button onclick="myFunction()" class="dropbtn">Menu</button>
<div id="myDropdown" class="dropdown-content">
<a href="https://laurapellicano.github.io/Home-Page/">Home</a>
<a href="https://laurapellicano.github.io/Page2/">Page2</a>
<a href="https://laurapellicano.github.io/Page3/">Page3</a>
</div>
</div>

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


<h1> Volleyball Statistics</h1>
<p1>Team Profile</p1>
<div>
<table id= "table1" style="width:100%">

<tr>
<form action="https://laurapellicano.github.io/volleyball-stats/" method="get"> 
<th><label for="teamname">Team Name:</label>
<input type="text" name="teamname"></th>
<th><label for="coachname">Coach Name:</label>
<input type="text" name="coachname"></th>
<th><label for="player">Player Name:</label>
<input type="text" number="player"></th>
<th><label for="gamesanddates">Game and Date:</label>
<input type="text" name = "gamesanddates"></th>
<div class="button">
    <button type="submit">Send your message</button>
      </div>
</form>
</table>
      
      
      <table id= "table1" style="width:100%">
      
      <tr>
      <form action="https://laurapellicano.github.io/volleyball-stats/" method="get"> 
      <th><label for="teamname">Team Name:</label>
      <input type="text" name="teamname"></th>
      <th><label for="coachname">Coach Name:</label>
      <input type="text" name="coachname"></th>
      <th><label for="player">Player Name:</label>
      <input type="text" number="player"></th>
      <th><label for="gamesanddates">Game and Date:</label>
      <input type="text" name = "gamesanddates"></th>
      <div class="button">
          <button type="submit">Send your message</button>
                </div>
                </form>
                </table>  

<table>
<tr>
<form action="mailto:someone@example.com" method="post" enctype="text/plain">
<th><label for="Name">Team Name:</label>  Name:<br>
<input type="text" name="name"><br>
<th><label for="Email">Team Name:</label> E-mail:<br>
<input type="text" name="mail"><br>
<th><label for="Comment">Team Name:</label>Comment:<br>
<input type="text" name="comment" size="50"><br><br>
<input type="submit" value="Send">
<input type="reset" value="Reset">
</form>
</table>

<form action="mailto:someone@example.com" method="post" enctype="text/plain">
 Name:<br>
<input type="text" name="name"><br>
 E-mail:<br>
 <input type="text" name="mail"><br>
Comment:<br>
<input type="text" name="comment" size="50"><br><br>
<input type="submit" value="Send">
<input type="reset" value="Reset">
 </form>

      
      <br/><br/>
      
     
      
      </body>
      </html>
      
      
      
