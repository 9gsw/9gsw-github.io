<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>InfoHub | Professional Informational Website</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f4f6f9;
    color:#333;
    line-height:1.7;
}

header{
    background:#0f172a;
    color:white;
    padding:18px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
}

header h2{
    font-size:28px;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    transition:.3s;
}

nav a:hover{
    color:#60a5fa;
}

.hero{
    background:linear-gradient(135deg,#2563eb,#1e3a8a);
    color:white;
    text-align:center;
    padding:90px 20px;
}

.hero h1{
    font-size:48px;
    margin-bottom:20px;
}

.hero p{
    max-width:700px;
    margin:auto;
    font-size:18px;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
    padding:60px 0;
}

.section-title{
    text-align:center;
    font-size:34px;
    margin-bottom:50px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:30px;
    border-radius:12px;
    box-shadow:0 8px 20px rgba(0,0,0,.08);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h3{
    margin-bottom:15px;
    color:#2563eb;
}

.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:40px;
    align-items:center;
}

.about img{
    width:100%;
    border-radius:12px;
}

.about-text h2{
    margin-bottom:20px;
    font-size:36px;
}

.stats{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
    margin-top:50px;
}

.stat{
    background:#2563eb;
    color:white;
    padding:35px;
    text-align:center;
    border-radius:10px;
}

.stat h2{
    font-size:40px;
}

footer{
    background:#0f172a;
    color:white;
    text-align:center;
    padding:30px;
    margin-top:60px;
}

@media(max-width:900px){

.about{
grid-template-columns:1fr;
}

.hero h1{
font-size:36px;
}

header{
flex-direction:column;
gap:15px;
}

nav a{
margin:0 10px;
}

}
</style>

</head>

<body>

<header>

<h2>InfoHub</h2>

<nav>
<a href="#">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#statistics">Statistics</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="hero">

<h1>Professional Information Platform</h1>

<p>
Providing clear, reliable, and well-organized information for individuals,
businesses, and organizations through a modern and responsive web experience.
</p>

</section>

<section class="container" id="services">

<h2 class="section-title">Our Services</h2>

<div class="cards">

<div class="card">
<h3>Research</h3>
<p>
We collect and organize accurate information from trusted sources to help users
understand complex topics quickly.
</p>
</div>

<div class="card">
<h3>Educational Content</h3>
<p>
Professional articles, guides, and learning materials designed for students,
professionals, and lifelong learners.
</p>
</div>

<div class="card">
<h3>Knowledge Base</h3>
<p>
An organized collection of resources, FAQs, and documentation that is easy to
navigate and continuously updated.
</p>
</div>

</div>

</section>

<section class="container" id="about">

<div class="about">

<img src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=900&q=80">

<div class="about-text">

<h2>About Us</h2>

<p>
InfoHub is dedicated to presenting high-quality information in a professional
and accessible format. Our goal is to simplify knowledge while maintaining
accuracy, reliability, and excellent user experience.
</p>

<br>

<p>
Whether you are looking for educational resources, industry insights, or
general information, our platform is designed to provide valuable content in a
clean and intuitive interface.
</p>

</div>

</div>

</section>

<section class="container" id="statistics">

<h2 class="section-title">Our Impact</h2>

<div class="stats">

<div class="stat">
<h2>100+</h2>
<p>Published Articles</p>
</div>

<div class="stat">
<h2>25K+</h2>
<p>Monthly Visitors</p>
</div>

<div class="stat">
<h2>99%</h2>
<p>User Satisfaction</p>
</div>

<div class="stat">
<h2>24/7</h2>
<p>Content Availability</p>
</div>

</div>

</section>

<footer id="contact">

<h3>InfoHub</h3>

<p>Email: info@example.com</p>

<p>Phone: +1 (000) 123-4567</p>

<p style="margin-top:10px;">
© 2026 InfoHub. All rights reserved.
</p>

</footer>

</body>
</html>
