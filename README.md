# anichur-portfolio
Graphic Designer Portfolio Website - Anichur
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Anichur | Graphic Designer Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#0f172a;
color:#fff;
}

header{
position:fixed;
top:0;
width:100%;
padding:20px 8%;
display:flex;
justify-content:space-between;
align-items:center;
background:rgba(15,23,42,.9);
backdrop-filter:blur(10px);
z-index:1000;
}

.logo{
font-size:28px;
font-weight:700;
color:#f97316;
}

nav a{
color:white;
text-decoration:none;
margin-left:25px;
font-weight:500;
transition:.3s;
}

nav a:hover{
color:#f97316;
}

.hero{
height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding:0 10%;
}

.hero-content h1{
font-size:4rem;
margin-bottom:15px;
}

.hero-content span{
color:#f97316;
}

.hero-content p{
font-size:1.2rem;
max-width:700px;
margin:auto;
margin-bottom:30px;
}

.btn{
display:inline-block;
padding:14px 30px;
background:#f97316;
color:white;
text-decoration:none;
border-radius:50px;
font-weight:600;
transition:.3s;
}

.btn:hover{
transform:translateY(-4px);
}

section{
padding:100px 10%;
}

.section-title{
font-size:2.5rem;
text-align:center;
margin-bottom:50px;
color:#f97316;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
align-items:center;
}

.about img{
width:100%;
border-radius:20px;
}

.about-text h3{
font-size:2rem;
margin-bottom:15px;
}

.skills{
display:flex;
flex-wrap:wrap;
gap:15px;
margin-top:20px;
}

.skill{
background:#1e293b;
padding:10px 20px;
border-radius:30px;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:#1e293b;
padding:30px;
border-radius:20px;
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card h3{
margin-bottom:15px;
color:#f97316;
}

.portfolio{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:20px;
}

.project{
height:250px;
background:#1e293b;
border-radius:20px;
display:flex;
justify-content:center;
align-items:center;
font-size:20px;
font-weight:600;
}

.stats{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
text-align:center;
}

.stat{
background:#1e293b;
padding:30px;
border-radius:20px;
}

.stat h2{
color:#f97316;
font-size:2.5rem;
}

.contact{
text-align:center;
}

.contact-info{
margin-top:30px;
line-height:2;
font-size:18px;
}

.contact-info a{
color:#f97316;
text-decoration:none;
}

footer{
padding:30px;
text-align:center;
background:#020617;
}

@media(max-width:768px){

.hero-content h1{
font-size:2.8rem;
}

.about{
grid-template-columns:1fr;
}

nav{
display:none;
}

}

</style>
</head>

<body>

<header>
<div class="logo">ANICHUR</div>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#portfolio">Portfolio</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero" id="home">

<div class="hero-content">

<h1>Hi, I'm <span>Anichur</span></h1>

<p>
Professional Graphic Designer & Content Creator.
I create eye-catching social media posts, posters,
thumbnails, branding materials and creative visual content.
</p>

<a href="#portfolio" class="btn">View Portfolio</a>

</div>

</section>

<section id="about">

<h2 class="section-title">About Me</h2>

<div class="about">

<img src="https://via.placeholder.com/500x600" alt="Profile">

<div class="about-text">

<h3>Graphic Designer</h3>

<p>
Hello! I'm Anichur, a passionate graphic designer who loves creating
modern and impactful visual designs. I specialize in social media posts,
poster design, thumbnail design, branding and portfolio creation.
</p>

<div class="skills">

<div class="skill">Photoshop</div>
<div class="skill">Illustrator</div>
<div class="skill">Canva</div>
<div class="skill">Branding</div>
<div class="skill">Thumbnail Design</div>
<div class="skill">Social Media Design</div>

</div>

</div>

</div>

</section>

<section id="services">

<h2 class="section-title">My Services</h2>

<div class="services">

<div class="card">
<h3>Social Media Design</h3>
<p>Professional Instagram, Facebook and Social Media Post Design.</p>
</div>

<div class="card">
<h3>Poster Design</h3>
<p>Creative promotional and event posters.</p>
</div>

<div class="card">
<h3>YouTube Thumbnail</h3>
<p>High CTR and attractive thumbnail designs.</p>
</div>

<div class="card">
<h3>Branding</h3>
<p>Logo, banner and complete brand identity design.</p>
</div>

</div>

</section>

<section id="portfolio">

<h2 class="section-title">Portfolio</h2>

<div class="portfolio">

<div class="project">Project 01</div>
<div class="project">Project 02</div>
<div class="project">Project 03</div>
<div class="project">Project 04</div>
<div class="project">Project 05</div>
<div class="project">Project 06</div>

</div>

</section>

<section>

<h2 class="section-title">Achievements</h2>

<div class="stats">

<div class="stat">
<h2>100+</h2>
<p>Projects</p>
</div>

<div class="stat">
<h2>50+</h2>
<p>Clients</p>
</div>

<div class="stat">
<h2>2+</h2>
<p>Years Experience</p>
</div>

<div class="stat">
<h2>100K+</h2>
<p>Reach</p>
</div>

</div>

</section>

<section id="contact">

<h2 class="section-title">Contact Me</h2>

<div class="contact">

<p>Let's work together on your next project.</p>

<div class="contact-info">

📧 Email:
<a href="mailto:sk3130187@gmail.com">
sk3130187@gmail.com
</a>

<br>

📱 WhatsApp:
<a href="https://wa.me/919134159070">
+91 9134159070
</a>

<br>

📸 Instagram:
<a href="https://instagram.com/anichur11">
@anichur11
</a>

<br>

📘 Facebook:
<a href="#">
Anipix Lab
</a>

</div>

</div>

</section>

<footer>

© 2026 ANICHUR | Graphic Designer Portfolio

</footer>

</body>
</html>
