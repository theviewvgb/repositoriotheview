<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>The View | Alquiler Temporario en Villa General Belgrano</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Departamento de alquiler temporario en Salta 5, Villa General Belgrano. Hasta 5 personas. Vista a las Sierras Chicas, cochera, parrilla, Wi-Fi y más.">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --primary: #1f2937;
      --accent: #2563eb;
      --bg: #f9fafb;
      --text: #374151;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: "Inter", sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
      color: var(--primary);
      text-align: center;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 4rem 1.5rem;
    }

    /* HERO */
    header {
      min-height: 90vh;
      background: linear-gradient(rgba(0,0,0,.45), rgba(0,0,0,.45)), url("images/foto19.jpg") center/cover no-repeat;
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 2rem;
    }

    header h1 {
      font-size: clamp(2.5rem, 5vw, 3.8rem);
      font-weight: 700;
      margin-bottom: 1rem;
    }

    header p {
      max-width: 720px;
      margin: auto;
      font-size: 1.1rem;
      opacity: .95;
    }

    /* SERVICES */
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5rem;
      margin-top: 2rem;
    }

    .service {
      background: #fff;
      border-radius: 18px;
      padding: 1.5rem;
      box-shadow: 0 6px 18px rgba(0,0,0,.06);
      transition: transform .2s ease;
    }

    .service:hover {
      transform: translateY(-5px);
    }

    .service h3 {
      margin-bottom: .5rem;
      font-size: 1.1rem;
      color: var(--primary);
    }

    /* GALLERY */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      margin-top: 2rem;
    }

    .gallery img {
      width: 100%;
      height: 230px;
      object-fit: cover;
      border-radius: 16px;
      transition: transform .3s ease;
    }

    .gallery img:hover {
      transform: scale(1.03);
    }

    /* VIEW */
    .view {
      background: linear-gradient(rgba(0,0,0,.55), rgba(0,0,0,.55)), url("images/vista.jpg") center/cover no-repeat;
      color: #fff;
      border-radius: 26px;
      padding: 4rem 2rem;
      text-align: center;
      margin: 4rem 0;
    }

    .view h2 {
      color: #fff;
      margin-bottom: 1rem;
    }

    .view p {
      max-width: 700px;
      margin: auto;
      font-size: 1.1rem;
    }

    /* MAP */
    .map {
      border-radius: 18px;
      overflow: hidden;
      box-shadow: 0 10px 25px rgba(0,0,0,.1);
      margin-top: 2rem;
    }

    /* FOOTER */
    footer {
      background: #111827;
      color: #fff;
      padding: 2rem;
      text-align: center;
      font-size: .95rem;
      opacity: .9;
    }

    /* WHATSAPP */
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: #fff;
      padding: 14px 22px;
      border-radius: 50px;
      font-weight: 600;
      box-shadow: 0 8px 20px rgba(0,0,0,.25);
      text-decoration: none;
      z-index: 999;
    }

    .whatsapp:hover {
      transform: scale(1.05);
    }

    @media (max-width: 768px) {
      header {
        min-height: 70vh;
      }
    }
  </style>
</head>

<body>

<!-- HERO -->
<header style="
  min-height:100vh;
  background:
    linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)),
    url('images/portada.jpg') center/cover no-repeat;
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  text-align:center;
  color:#ffffff;
  padding:2.5rem;
">

  <h2 class="fade-up" style="
    font-size:1.7rem;
    font-weight:400;
    margin-bottom:1.2rem;
    max-width:820px;
    color:#ffffff;
    text-shadow:0 4px 12px rgba(0,0,0,0.8);
  ">
    Alquiler temporario en Villa General Belgrano
  </h2>

  <p class="fade-up delay" style="
    max-width:680px;
    font-size:1.15rem;
    line-height:1.7;
    text-shadow:0 3px 10px rgba(0,0,0,0.8);
  ">
    Departamento totalmente equipado para hasta 5 personas,
    con balcón, cochera, asador y una vista única a las Sierras Chicas.
  </p>

</header>
<!-- SERVICES -->
<section class="container">
  <h2>Servicios</h2>
  <div class="services">
    <div class="service"><h3>🏡 Capacidad</h3><p>Hasta 5 personas.</p></div>
    <div class="service"><h3>🚗 Cochera</h3><p>Cochera cubierta con ingreso directo al departamento.</p></div>
    <div class="service"><h3>🌄 Balcón</h3><p>Amplio balcón equipado con mesa y sillas y una vista privilegiada a las sierras.</p></div>
    <div class="service"><h3>🔥 Parrilla</h3><p>Patio parquizado con asador.</p></div>
    <div class="service"><h3>📺 Smart TV 65”</h3><p>Streaming y entretenimiento.</p></div>
    <div class="service"><h3>📶 Wi-Fi & Lavarropas</h3><p>Totalmente equipado.</p></div>
  </div>
</section>

<!-- GALLERY -->
<section class="container">
  <h2>Galería de Fotos</h2>
  <div class="gallery">
    <img src="images/foto1.jpg" alt="Departamento">
    <img src="images/foto2.jpg" alt="Departamento">
    <img src="images/foto3.jpg" alt="Departamento">
    <img src="images/foto4.jpg" alt="Departamento">
    <img src="images/foto5.jpg" alt="Departamento">
    <img src="images/foto6.jpg" alt="Departamento">
    <img src="images/foto7.jpg" alt="Departamento">
    <img src="images/foto8.jpg" alt="Departamento">
    <img src="images/foto9.jpg" alt="Departamento">
    <img src="images/foto10.jpg" alt="Departamento">
    <img src="images/foto11.jpg" alt="Departamento">
    <img src="images/foto12.jpg" alt="Departamento">
    <img src="images/foto13.jpg" alt="Departamento">
    <img src="images/foto14.jpg" alt="Departamento">
    <img src="images/foto15.jpg" alt="Departamento">
    <img src="images/foto16.jpg" alt="Departamento">
    <img src="images/foto18.png" alt="Departamento">
  </div>
</section>

<!-- VIEW -->
<section class="container">
  <div class="view">
    <h2>Vista a las Sierras</h2>
    <p>
      Disfrutá de una vista única a las Sierras Chicas desde el balcón y los espacios exteriores,
      con la tranquilidad de estar en pleno centro.
    </p>
  </div>
</section>

<!-- LOCATION -->
<section id="ubicacion" style="padding:4rem 1rem; background:#f8f8f8;">
  <h2 style="text-align:center; font-size:2rem; margin-bottom:1rem;">
    📍 Ubicación
  </h2>

  <p style="text-align:center; max-width:700px; margin:0 auto 2rem; color:#555;">
    Nos encontramos en <strong>Julio A. Roca 310, Villa General Belgrano, Córdoba</strong>,
    en una ubicación privilegiada con vistas a las Sierras Chicas.
  </p>

  <div style="max-width:900px; margin:0 auto; border-radius:16px; overflow:hidden; box-shadow:0 10px 25px rgba(0,0,0,0.15);">
    <iframe
      src="https://www.google.com/maps?q=Julio+A+Roca+310+Villa+General+Belgrano+Córdoba&z=17&output=embed"
      width="100%"
      height="400"
      style="border:0;"
      loading="lazy"
      allowfullscreen>
    </iframe>
  </div>

  <div style="margin-top:2rem; display:flex; justify-content:center; gap:1rem; flex-wrap:wrap;">
    <a href="https://www.google.com/maps?q=Julio+A+Roca+310+Villa+General+Belgrano+Córdoba"
       target="_blank"
       style="background:#222; color:#fff; padding:0.8rem 1.5rem; border-radius:30px; text-decoration:none; font-weight:500;">
       📍 Cómo llegar (Google Maps)
    </a>

    <a href="https://waze.com/ul?q=Julio%20A.%20Roca%20310%20Villa%20General%20Belgrano"
       target="_blank"
       style="background:#05c8f7; color:#fff; padding:0.8rem 1.5rem; border-radius:30px; text-decoration:none; font-weight:500;">
       🚗 Abrir en Waze
    </a>
  </div>
</section>

<!-- FOOTER -->
<footer>
  © 2026 The View · Julio A. Roca 310 · Villa General Belgrano · Córdoba
</footer>

<!-- WHATSAPP -->
<a class="whatsapp" href="https://wa.me/5493546458477" target="_blank">
  📲 WhatsApp
</a>

</body>
</html>
