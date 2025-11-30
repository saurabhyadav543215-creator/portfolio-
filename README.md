# portfolio-
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Digital Portfolio</title>
<style>
 body{margin:0;font-family:Arial, sans-serif;background:#f7f9fc;color:#222;}
 header{background:#0d47a1;color:white;padding:28px;text-align:center;font-size:28px;font-weight:600;}
 section{padding:40px;max-width:900px;margin:auto;}
 h2{margin-bottom:10px;color:#0d47a1;}
 .hero{display:flex;gap:30px;align-items:center;flex-wrap:wrap;}
 .hero img{width:180px;height:180px;border-radius:50%;object-fit:cover;border:5px solid #0d47a1;}
 .hero-text{max-width:500px;}
 .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px;margin-top:20px;}
 .card{background:white;padding:20px;border-radius:10px;box-shadow:0 2px 6px rgba(0,0,0,0.1);} 
 .project-img{width:100%;height:150px;background:#ddd;border-radius:8px;margin-bottom:10px;object-fit:cover;}
 a.btn{display:inline-block;background:#0d47a1;color:white;padding:10px 18px;border-radius:6px;text-decoration:none;margin-top:10px;}
 footer{text-align:center;padding:20px;background:#0d47a1;color:white;margin-top:40px;}
</style>
</head>
<body>
<header>My Digital Portfolio</header>

<section class="hero">
  <img src="https://via.placeholder.com/180" alt="profile" />
  <div class="hero-text">
    <h2>Hello, I'm Aman</h2>
    <p>I'm a passionate web developer skilled in HTML, CSS, JavaScript, and modern UI design. I create clean, responsive, and user-friendly applications.</p>
    <a href="#projects" class="btn">View My Work</a>
  </div>
</section>

<section>
  <h2>Skills</h2>
  <div class="grid">
    <div class="card">HTML • CSS • JavaScript</div>
    <div class="card">React • TailwindCSS</div>
    <div class="card">Node.js • Express</div>
    <div class="card">Python • SQL</div>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="grid">
    <div class="card">
      <img class="project-img" src="https://via.placeholder.com/350x150" />
      <h3>Project 1</h3>
      <p>A responsive website built using HTML, CSS, and JS.</p>
      <a href="#" class="btn">View Project</a>
    </div>
    <div class="card">
      <img class="project-img" src="https://via.placeholder.com/350x150" />
      <h3>Project 2</h3>
      <p>A modern dashboard UI built with React + Tailwind.</p>
      <a href="#" class="btn">View Project</a>
    </div>
    <div class="card">
      <img class="project-img" src="https://via.placeholder.com/350x150" />
      <h3>Project 3</h3>
      <p>Full-stack web app using Node.js and MongoDB.</p>
      <a href="#" class="btn">View Project</a>
    </div>
  </div>
</section>

<section>
  <h2>Contact Me</h2>
  <p>Email: yourmail@example.com</p>
  <p>LinkedIn: linkedin.com/in/yourprofile</p>
  <p>GitHub: github.com/yourprofile</p>
</section>

<footer>
  © 2025 Aman • Portfolio Website
</footer>
</body>
</html>
