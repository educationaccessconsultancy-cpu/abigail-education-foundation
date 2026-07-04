<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abigail Education Access Foundation</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:Arial,sans-serif;color:#1A2B4A;line-height:1.6}
.nav{background:#fff;padding:1rem 2rem;position:fixed;width:100%;top:0;box-shadow:0 2px 10px rgba(0,0,0,0.1);z-index:1000;display:flex;justify-content:space-between;align-items:center}
.logo{font-size:1.2rem;font-weight:800;color:#1A2B4A}
.logo span{color:#2D7A3E}
.hero{min-height:100vh;background:linear-gradient(135deg,#1A2B4A,#0F1A2E);display:flex;align-items:center;justify-content:center;text-align:center;color:#fff;padding:2rem;padding-top:80px}
.hero h1{font-size:2.5rem;margin-bottom:1rem}
.hero h1 span{color:#F5A623}
.hero p{font-size:1.1rem;max-width:600px;margin:0 auto 2rem;opacity:0.9}
.btn{display:inline-block;padding:1rem 2rem;border-radius:50px;text-decoration:none;font-weight:700;margin:0.5rem;transition:all 0.3s}
.btn-primary{background:#2D7A3E;color:#fff}
.btn-outline{border:2px solid rgba(255,255,255,0.3);color:#fff}
.mission{background:linear-gradient(135deg,#2D7A3E,#1E5A2A);color:#fff;padding:2rem;text-align:center;font-size:1.2rem;font-weight:700}
.section{padding:4rem 2rem;max-width:1200px;margin:0 auto}
.section h2{text-align:center;font-size:2rem;margin-bottom:2rem}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:2rem;margin-top:2rem}
.card{background:#fff;border-radius:15px;padding:2rem;text-align:center;box-shadow:0 5px 20px rgba(0,0,0,0.08);border:1px solid #E2E8F0}
.card i{font-size:2.5rem;color:#2D7A3E;margin-bottom:1rem}
.card h3{margin-bottom:0.5rem}
.card p{color:#64748B;font-size:0.9rem}
.programs{background:#F8FAFC}
.program-card{background:#fff;border-radius:15px;overflow:hidden;box-shadow:0 5px 20px rgba(0,0,0,0.08)}
.program-header{background:linear-gradient(135deg,#1A2B4A,#0F1A2E);color:#fff;padding:1.5rem}
.program-header.green{background:linear-gradient(135deg,#2D7A3E,#1E5A2A)}
.program-header.gold{background:linear-gradient(135deg,#F5A623,#D4880F)}
.program-body{padding:1.5rem}
.program-body ul{list-style:none}
.program-body li{padding:0.5rem 0;border-bottom:1px solid #E2E8F0;display:flex;align-items:center;gap:0.5rem}
.program-body li i{color:#2D7A3E}
.impact{background:linear-gradient(135deg,#1A2B4A,#0F1A2E);color:#fff;text-align:center;padding:4rem 2rem}
.impact-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:2rem;max-width:1000px;margin:2rem auto 0}
.impact-item h3{font-size:2.5rem;color:#F5A623}
.ebook{background:#FFF3E0;padding:4rem 2rem;text-align:center}
.ebook h2 span{color:#F5A623}
.contact{background:#F8FAFC;padding:4rem 2rem}
.contact-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:2rem;max-width:1000px;margin:0 auto}
.contact-item{display:flex;align-items:center;gap:1rem;padding:1rem;background:#fff;border-radius:10px;margin-bottom:1rem}
.contact-item i{width:40px;height:40px;background:#E8F5E9;border-radius:10px;display:flex;align-items:center;justify-content:center;color:#2D7A3E}
.footer{background:#0F1A2E;color:#fff;padding:3rem 2rem;text-align:center}
.footer a{color:#F5A623;text-decoration:none}
.social{display:flex;justify-content:center;gap:1rem;margin-top:1rem}
.social a{width:40px;height:40px;background:rgba(255,255,255,0.1);border-radius:50%;display:flex;align-items:center;justify-content:center;color:#fff;text-decoration:none}
@media(max-width:768px){.hero h1{font-size:1.8rem}.grid{grid-template-columns:1fr}}
</style>
</head>
<body>
<nav class="nav">
<div class="logo">Abigail Education Access <span>Foundation</span></div>
</nav>
<section class="hero">
<div>
<h1>Every Foot in a <span>Nice Shoe</span>,<br>Every Child in <span>School</span>.</h1>
<p>We bridge educational access gaps by providing practical school support that ensures every child walks into school with dignity, confidence, and hope for a brighter future.</p>
<a href="#programs" class="btn btn-primary"><i class="fas fa-hands-helping"></i> Our Programs</a>
<a href="#ebook" class="btn btn-outline"><i class="fas fa-book"></i> Buy an E-Book</a>
</div>
</section>
<div class="mission">
<i class="fas fa-bullseye"></i> To bridge educational access

