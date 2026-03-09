<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DAKSHITHA TECH LK</title>

<style>

body{
margin:0;
font-family:Arial, sans-serif;
color:#fff;
background:#000;
}

/* BACKGROUND IMAGE */

body::before{
content:"";
position:fixed;
top:0;
left:0;
width:100%;
height:100%;

background:url("logo.png") center/contain no-repeat;

opacity:0.15;   /* image eka fade karanna */

z-index:-1;
}

/* HEADER */

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 50px;
background:linear-gradient(90deg,#000000,#1c1c1c,#c0c0c0,#ffd700);
box-shadow:0 0 25px #ffd700;
}

header h1{
color:#ffd700;
letter-spacing:3px;
font-size:28px;
}

/* NAV */

nav a{
margin:15px;
color:#e6e6e6;
text-decoration:none;
font-weight:bold;
transition:0.3s;
}

nav a:hover{
color:#ffd700;
}

/* HERO */

.hero{
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
}

.hero h2{
font-size:55px;
color:#ffd700;
text-shadow:0 0 25px #ffd700;
}

.hero p{
font-size:20px;
color:#c0c0c0;
}

.btn{
margin-top:25px;
padding:15px 35px;
border:none;
background:linear-gradient(45deg,#ffd700,#c0c0c0);
border-radius:30px;
font-size:18px;
cursor:pointer;
font-weight:bold;
}

.btn:hover{
transform:scale(1.1);
box-shadow:0 0 25px #ffd700;
}

/* CARDS */

.cards{
display:flex;
justify-content:center;
gap:40px;
padding:80px;
flex-wrap:wrap;
}

.card{
background:linear-gradient(145deg,#111,#2a2a2a);
padding:40px;
width:250px;
border-radius:20px;
text-align:center;
box-shadow:0 0 20px #c0c0c0;
transition:0.4s;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 0 30px #ffd700;
}

.card h3{
color:#ffd700;
}

.card p{
color:#c0c0c0;
}

.card a{
display:inline-block;
margin-top:10px;
padding:10px 20px;
background:linear-gradient(45deg,#ffd700,#c0c0c0);
color:black;
text-decoration:none;
border-radius:10px;
font-weight:bold;
}

/* FOOTER */

footer{
background:#111;
text-align:center;
padding:20px;
color:#c0c0c0;
}

</style>

</head>

<body>

<header>
<h1>DAKSHITHA TECH LK</h1>

<nav>
<a href="#">Home</a>
<a href="#">Videos</a>
<a href="#">Tutorials</a>
<a href="#">Social</a>
<a href="#">Contact</a>
</nav>
</header>

<section class="hero">
<h2>Welcome To Dakshitha Tech LK</h2>
<p>Tech Reviews • Tutorials • Gadgets • Tips</p>
<button class="btn">Explore Now</button>
</section>

<section class="cards">

<div class="card">
<h3>YouTube</h3>
<p>Watch latest tech videos</p>
<a href="#">Visit Channel</a>
</div>

<div class="card">
<h3>Tech Tutorials</h3>
<p>Learn new tech skills</p>
<a href="#">View Tutorials</a>
</div>

<div class="card">
<h3>Social Media</h3>
<p>Follow for daily tech content</p>
<a href="#">Follow Now</a>
</div>

</section>

<footer>
<p>© 2026 DAKSHITHA TECH LK</p>
</footer>

</body>
</html>
