<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>SOS Fête LCD</title>
  <style>
    body { margin:0; font-family:Arial, sans-serif; background:#f7f7f7; color:#333; }
    header { background:#007BFF; color:white; padding:20px; text-align:center; }
    h1 { margin:0; font-size:2em; }
    .slogan { font-size:1.2em; margin-top:5px; }
    .container { padding:20px; max-width:1000px; margin:auto; }
    .section { margin-bottom:40px; }
    .services { display:flex; flex-wrap:wrap; gap:20px; }
    .service-card {
      flex:1 1 250px;
      background:white;
      padding:20px;
      border-radius:10px;
      box-shadow:0 0 10px rgba(0,0,0,0.05);
    }
    .btn {
      display:inline-block;
      background:#28A745;
      color:white;
      padding:12px 20px;
      text-decoration:none;
      border-radius:5px;
      margin-top:10px;
      cursor:pointer;
      border:none;
      font-size:1em;
    }
    footer {
      text-align:center;
      background:#333;
      color:#ccc;
      padding:15px;
      font-size:0.9em;
    }
    form {
      background:white;
      padding:20px;
      border-radius:10px;
      box-shadow:0 0 10px rgba(0,0,0,0.05);
      max-width:600px;
      margin:auto;
    }
    form label {
      display:block;
      margin-bottom:8px;
      font-weight:bold;
    }
    form input, form textarea {
      width:100%;
      padding:10px;
      margin-bottom:15px;
      border:1px solid #ccc;
      border-radius:5px;
      font-size:1em;
      resize: vertical;
    }
    form textarea {
      min-height:100px;
    }
    .testimonials {
      background:#e9f0fb;
      padding:20px;
      border-radius:10px;
    }
    .testimonial {
      background:white;
      padding:15px 20px;
      border-radius:8px;
      box-shadow:0 0 5px rgba(0,0,0,0.1);
      margin-bottom:15px;
    }
    .testimonial p {
      font-style: italic;
      margin:0 0 10px 0;
    }
    .testimonial .author {
      text-align:right;
      font-weight:bold;
      color:#007BFF;
    }
    @media(max-width:600px){
      .services { flex-direction:column; }
    }
  </style>
</head>
<body>

<header>
  <h1>SOS Fête LCD</h1>
  <div class="slogan">Intervention d'urgence après fêtes et dégradations dans vos locations courte durée</div>
</header>

<div class="container">

  <div class="section">
    <h2>Qui sommes-nous ?</h2>
    <p>SOS Fête LCD intervient rapidement dans vos logements en location courte durée après des soirées non autorisées ou des dégradations. Nous vous aidons à constituer votre dossier de réclamation (photos, constats, rapport) pour les assurances et plateformes.</p>
  </div>

  <div class="section">
    <h2>Nos services</h2>
    <div class="services">
      <div class="service-card">
        <h3>Constat & Photos</h3>
        <p>Réalisation d'un constat détaillé avec photos des dégradations et anomalies constatées sur place.</p>
      </div>
      <div class="service-card">
        <h3>Rapport détaillé</h3>
        <p>Rédaction d’un rapport clair et complet à joindre à votre dossier de réclamation.</p>
      </div>
      <div class="service-card">
        <h3>Aide AirCover & Assurances</h3>
        <p>Accompagnement dans la constitution de votre demande auprès des plateformes et assurances.</p>
      </div>
    </div>
  </div>

  <div class="section testimonials">
    <h2>Témoignages clients</h2>
    <div class="testimonial">
      <p>« Grâce à SOS Fête LCD, j'ai pu faire ma réclamation rapidement après une soirée qui a mal tourné. Service efficace et rapide ! »</p>
      <div class="author">– Camille D.</div>
    </div>
    <div class="testimonial">
      <p>« Intervention rapide et rapport détaillé, parfait pour obtenir un remboursement via AirCover. Je recommande ! »</p>
      <div class="author">– Julien M.</div>
    </div>
    <div class="testimonial">
      <p>« Professionnel et rassurant, SOS Fête LCD m'a beaucoup aidé dans la gestion des dégradations. »</p>
      <div class="author">– Sophie L.</div>
    </div>
  </div>

  <div class="section" id="contact">
    <h2>Contactez-nous</h2>
    <form action="https://formspree.io/f/mayvlrqd" method="POST">
      <label for="name">Nom</label>
      <input type="text" id="name" name="name" required />
      <label for="email">Email</label>
      <input type="email" id="email" name="_replyto" required />
      <label for="message">Message</label>
      <textarea id="message" name="message" required></textarea>
      <button type="submit" class="btn">Envoyer</button>
    </form>
  </div>

</div>

<footer>
  &copy; 2025 SOS Fête LCD — Tous droits réservés.
</footer>

</body>
</html>
