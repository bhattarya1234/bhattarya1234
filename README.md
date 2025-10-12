<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Arya Bhatt — Full-Stack Portfolio</title>
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<!-- FontAwesome for icons -->
<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
<style>
  /* ===== Global Styles ===== */
  body {
    font-family: 'Roboto', sans-serif;
    background: #1e1e2f;
    color: #cdd6f4;
    margin: 0;
    padding: 0;
  }
  a { text-decoration: none; color: #89b4fa; }
  a:hover { color: #f38ba8; }

  /* ===== Container ===== */
  .container { max-width: 1000px; margin: auto; padding: 2rem; }

  /* ===== Header ===== */
  header { text-align: center; padding-bottom: 2rem; }
  header h1 { font-size: 3rem; color: #f5c2e7; margin-bottom: 0.5rem; }
  header p { font-size: 1.2rem; color: #89b4fa; }

  /* ===== Section ===== */
  section { margin-bottom: 2rem; }
  h2 { color: #f5c2e7; border-bottom: 2px solid #89b4fa; padding-bottom: 0.3rem; margin-bottom: 1rem; }

  /* ===== Cards ===== */
  .card-container { display: flex; flex-wrap: wrap; gap: 1rem; }
  .card {
    background: #313244;
    padding: 1rem;
    border-radius: 10px;
    flex: 1 1 250px;
    transition: transform 0.3s;
  }
  .card:hover { transform: translateY(-5px); }

  /* ===== Socials ===== */
  .socials a {
    display: inline-block;
    margin: 0 0.5rem;
    font-size: 1.5rem;
    transition: color 0.3s;
  }
  .socials a:hover { color: #f38ba8; }

  /* ===== Tech Stack ===== */
  .tech-stack img { margin: 0.3rem; height: 40px; }

  /* ===== GitHub Stats & Memes ===== */
  .stats img, .meme img { width: 100%; border-radius: 10px; margin-bottom: 1rem; }

  /* ===== Footer ===== */
  footer { text-align: center; padding: 2rem 0; color: #89b4fa; font-size: 0.9rem; }
</style>
</head>
<body>
<div class="container">

  <!-- Header -->
  <header>
    <h1>👋 Hi, I'm Arya</h1>
    <p>Full-stack enthusiast from Nepal 🇳🇵 — turning coffee ☕ and curiosity into code 💻</p>
  </header>

  <!-- Work & Learning -->
  <section>
    <h2>💼 Work & Learning</h2>
    <div class="card-container">
      <div class="card">
        <h3>🔭 Currently Building</h3>
        <p>Personal projects using <b>JavaScript</b>, <b>React</b>, and <b>Node.js</b></p>
      </div>
      <div class="card">
        <h3>🌱 Currently Learning</h3>
        <p><b>Git</b>, <b>Docker</b>, and <b>Node.js</b> — full-stack foundation</p>
      </div>
      <div class="card">
        <h3>💬 Ask Me About</h3>
        <p><b>JavaScript</b>, <b>React</b>, backend basics</p>
      </div>
      <div class="card">
        <h3>⚡ Fun Fact</h3>
        <p>I break things just to rebuild them better 😎</p>
      </div>
    </div>
  </section>

  <!-- Socials -->
  <section>
    <h2>🌐 Socials</h2>
    <div class="socials">
      <a href="https://facebook.com/AryaBhattZeroLag" target="_blank"><i class="fab fa-facebook"></i></a>
      <a href="https://instagram.com/shad0w_mistx" target="_blank"><i class="fab fa-instagram"></i></a>
      <a href="https://pinterest.com/bhattarya190" target="_blank"><i class="fab fa-pinterest"></i></a>
      <a href="https://twitter.com/AryaBhatt298280" target="_blank"><i class="fab fa-twitter"></i></a>
    </div>
  </section>

  <!-- Tech Stack -->
  <section>
    <h2>💻 Tech Stack</h2>
    <div class="tech-stack">
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white" />
    </div>
  </section>

  <!-- GitHub Stats -->
  <section class="stats">
    <h2>📊 GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=bhattarya1234&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=bhattarya1234&theme=tokyonight&hide_border=true" />
  </section>

  <!-- Meme -->
  <section class="meme">
    <h2>😂 Random Dev Meme</h2>
    <img src="https://random-memer.herokuapp.com/" />
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 Arya Bhatt — Made with ❤️ and code
  </footer>

</div>
</body>
</html>
