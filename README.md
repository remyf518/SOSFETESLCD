<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SOS Fête LCD</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c') no-repeat center/cover;
      color: white;
      padding: 6rem 1rem;
      text-align: center;
      position: relative;
    }
    header::after {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.5);
    }
    header h1, header p {
      position: relative;
      z-index: 2;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
    }
    header p {
      margin-top: 1rem;
      font-size: 1.3rem;
    }
    section {
      padding: 4rem 1rem;
      max-width: 1200px;
      margin: auto;
    }
    .highlight {
      background: #fff;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      border-radius: 16px;
      padding: 3rem;
      margin-bottom: 3rem;
    }
    .btn {
      display: inline-block;
      background: #FF6B00;
      color: #fff;
      padding: 0.8rem 1.6rem;
      border-radius: 50px;
      text-decoration: none;
      transition: 0.3s;
    }
    .btn:hover {
      background: #007BFF;
    }
    .testimonials {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }
    .testimonial {
      background: #fff;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.06);
    }
    form input, form textarea, form button {
      width: 100%;
      padding: 0.9rem;
      margin-bottom: 1rem;
      border: 1px solid #ddd;
      border-radius: 8px;
      font-size: 1rem;
    }
    form button {
      background: #FF6B00;
      color: white;
      border: none;
      cursor: pointer;
    }
    form button:hover {
      background: #007BFF;
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      background: #333;
      color: #fff;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>SOS Fête LCD</h1>
    <p>Interventions d'urgence après fêtes en Airbnb & LCD</p>
  </header>

  <section data-aos="fade-up">
    <div class="highlight">
      <h2>Notre mission</h2>
      <p>Nous intervenons 7j/7 pour constater les dégradations dans les logements en location courte durée (Airbnb & LCD), établir des preuves, et vous assister pour activer votre couverture AirCover. Rapidité, efficacité et discrétion garanties.</p>
      <a href="#contact" class="btn">Contactez-nous</a>
    </div>
  </section>

  <section data-aos="fade-up">
    <h2 style="text-align:center;">Témoignages clients</h2>
    <div class="testimonials">
      <div class="testimonial">
        <p>"Merci à SOS Fête LCD pour leur réactivité après une soirée non autorisée. Dossier AirCover validé sans souci."</p>
        <strong>Thomas, Lyon</strong>
      </div>
      <div class="testimonial">
        <p>"Professionnels et discrets, ils ont parfaitement géré la situation. Service indispensable."</p>
        <strong>Claire, Paris</strong>
      </div>
      <div class="testimonial">
        <p>"Très rassurant de pouvoir compter sur eux, même le week-end !"</p>
        <strong>Mehdi, Marseille</strong>
      </div>
    </div>
  </section>

  <section id="contact" data-aos="fade-up">
    <div class="highlight">
      <h2>Contactez-nous</h2>
      <form>
        <input type="text" placeholder="Votre nom" required>
        <input type="email" placeholder="Votre email" required>
        <textarea placeholder="Votre message..." rows="5" required></textarea>
        <button type="submit">Envoyer</button>
      </form>
    </div>
  </section>

  <footer>
    &copy; 2025 SOS Fête LCD — Tous droits réservés
  </footer>

  <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
  <script>AOS.init();</script>
</body>
</html>
