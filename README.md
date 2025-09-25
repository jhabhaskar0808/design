# design
Design Consultancy
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>My Free Website</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="site-header">
    <h1>Your Name or Brand</h1>
    <nav><a href="#about">About</a><a href="#projects">Projects</a><a href="#contact">Contact</a></nav>
  </header>

  <main>
    <section id="about" class="card">
      <h2>About</h2>
      <p>Short intro — who you are and what you do.</p>
    </section>

    <section id="projects" class="card">
      <h2>Projects</h2>
      <ul>
        <li>Project 1 — short note</li>
        <li>Project 2 — short note</li>
      </ul>
    </section>

    <section id="contact" class="card">
      <h2>Contact</h2>
      <p>Email: yourname@example.com</p>
    </section>
  </main>

  <footer class="site-footer">© <span id="year"></span> Your Name</footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
