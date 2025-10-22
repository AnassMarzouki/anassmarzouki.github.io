<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Anass Marzouki | GIS & Engineering</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: "Inter", sans-serif;
      background: #f8fafc;
      color: #1f2937;
      margin: 0;
      line-height: 1.6;
    }
    header {
      background: #1e3a8a;
      color: white;
      text-align: center;
      padding: 2.5rem 1rem;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    header p {
      margin: 0.5rem 0 0;
      font-size: 1rem;
      opacity: 0.8;
    }
    nav {
      text-align: center;
      background: #3b82f6;
      padding: 0.75rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: 600;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      max-width: 850px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    h2 {
      color: #1e3a8a;
      border-bottom: 2px solid #3b82f6;
      padding-bottom: 0.25rem;
    }
    footer {
      text-align: center;
      background: #111827;
      color: #9ca3af;
      padding: 1.5rem 0;
      margin-top: 3rem;
      font-size: 0.9rem;
    }
    .project {
      background: white;
      padding: 1rem;
      border-radius: 8px;
      margin-bottom: 1rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    }
    .project h3 {
      margin-top: 0;
    }
  </style>
</head>
<body>

<header>
  <h1>Anass Marzouki</h1>
  <p>Architect & GIS Engineer | Spatial Data | Open Source Mapping</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#projects">Projects</a>
  <a href="#publications">Publications</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About</h2>
  <p>Hello! I'm <strong>Anass Marzouki</strong>, an architect and GIS engineer passionate about geospatial technologies, digital mapping, and urban planning. I work with tools like <em>Mapbender</em>, <em>QGIS</em>, and <em>PostGIS</em> to create spatial analysis platforms and visualizations.</p>
  <p>This page showcases my projects, research, and personal explorations in GIS, architecture, and data visualization.</p>
</section>

<section id="projects">
  <h2>Projects</h2>

  <div class="project">
    <h3>Mapbender Deployment on VPS</h3>
    <p>Setup and configuration of Mapbender on a private VPS (Debian) for spatial data services — including map visualization, user management, and WMS/WFS integration.</p>
    <a href="#">→ View details</a>
  </div>

  <div class="project">
    <h3>Morocco 1km Grid Mapping</h3>
    <p>Computation and visualization of a 1×1 km national grid for Morocco, integrating land use data and built-up area detection using open satellite imagery.</p>
    <a href="#">→ View on GitHub</a>
  </div>

  <div class="project">
    <h3>Urban Morphology Analysis</h3>
    <p>Study of building patterns in Moroccan cities using QGIS and Python for morphological indicators and density metrics.</p>
    <a href="#">→ Learn more</a>
  </div>
</section>

<section id="publications">
  <h2>Publications & Talks</h2>
  <ul>
    <li>“Spatial Planning and GIS in the Moroccan Context” – Presented at UIR & UCLA Joint Conference, 2024.</li>
    <li>“Integrating Open Data into Local Urban Design” – forthcoming article.</li>
  </ul>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>📧 <a href="mailto:anass.marzouki@example.com">anass.marzouki@example.com</a></p>
  <p>🌐 <a href="https://github.com/anassmarzouki" target="_blank">github.com/anassmarzouki</a></p>
  <p>💼 <a href="https://www.linkedin.com/in/anassmarzouki/" target="_blank">LinkedIn</a></p>
</section>

<footer>
  © <span id="year"></span> Anass Marzouki — Built with ❤️ on GitHub Pages
</footer>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>

</body>
</html>
