<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Algin Marquez | Portfolio</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
background:#f4f4f4;
color:#333;
line-height:1.6;
}

header{
background:#111;
color:white;
padding:20px 0;
text-align:center;
}

nav{
display:flex;
justify-content:center;
background:#222;
}

nav a{
color:white;
padding:14px 20px;
text-decoration:none;
}

nav a:hover{
background:#555;
}

.container{
width:90%;
max-width:1000px;
margin:auto;
padding:40px 0;
}

section{
margin-bottom:60px;
}

h2{
margin-bottom:20px;
color:#111;
}

.skills span{
display:inline-block;
background:#111;
color:white;
padding:8px 12px;
margin:5px;
border-radius:5px;
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
gap:20px;
}

.project{
background:white;
padding:20px;
border-radius:8px;
box-shadow:0 2px 5px rgba(0,0,0,0.1);
}

footer{
text-align:center;
padding:20px;
background:#111;
color:white;
}
</style>
</head>

<body>

<header>
<h1>Algin Marquez</h1>
<p>Web Developer | Designer | Freelancer</p>
</header>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

<div class="container">

<section id="about">
<h2>About Me</h2>
<p>
Hello! I'm a passionate developer who enjoys building websites and learning new technologies.
I specialize in creating simple, responsive, and user-friendly websites.
</p>
</section>

<section id="skills">
<h2>Skills</h2>
<div class="skills">
<span>HTML</span>
<span>CSS</span>
<span>JavaScript</span>
<span>Python</span>
<span>UI Design</span>
</div>
</section>

<section id="projects">
<h2>Projects</h2>

<div class="projects">

<div class="project">
<h3>Project One</h3>
<p>A website built using HTML and CSS.</p>
</div>

<div class="project">
<h3>Project Two</h3>
<p>A responsive landing page design.</p>
</div>

<div class="project">
<h3>Project Three</h3>
<p>A simple JavaScript web application.</p>
</div>

</div>
</section>

<section id="contact">
<h2>Contact</h2>
<p>Email: alginmarquez@email.com</p>
<p>GitHub: github.com/alginmarquez</p>
<p>LinkedIn: linkedin.com/in/alginmarquez</p>
</section>

</div>

<footer>
<p>© 2026 Algin marquez | Portfolio</p>
</footer>

</body>
</html>
