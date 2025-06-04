<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SOS Fête LCD</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #FF6B00, #007BFF);
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      margin-top: 0.5rem;
      font-size: 1.2rem;
    }
    section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: auto;
    }
    .highlight {
      background: #ffffff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      border-radius: 12px;
      padding: 2rem;
      margin-bottom: 2rem;
    }
    .testimonials {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1rem;
    }
    .testimonial {
      background: #ffffff;
      border-left: 5px solid #FF6B00;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    }
    form input, form textarea, form button {
      width: 100%;
      padding: 0.8rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1rem;
    }
    form button {
      background: #FF6B00;
      color: white;
      border: none;
      cursor: pointer;
      transition: 0.3s;
    }
    form button:hover {
      background: #007BFF;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #333;
      color: #fff;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>SOS Fête LCD</h1>
    <p>Interventions d'urgence après soirées et dégradations en Airbnb</p>
  </header>

  <section class="highlight">
    <h2>Notre mission</h2>
    <p>Nous intervenons 7j/7 pour constater les dégradations dans les logements Airbnb et LCD, établir des preuves et vous assister pour activer votre couverture AirCover. Réactivité, efficacité et discrétion assurées.</p>
  </section>

  <section>
    <h2>Témoignages clients</h2>
    <div class="testimonials">
      <div class="testimonial">
        "Merci à l'équipe SOS Fête LCD pour leur intervention rapide après une soirée non autorisée. Le dossier AirCover a été validé sans problème."
        <strong>— Thomas, Lyon</strong>
      </div>
      <div class="testimonial">
        "Professionnels et discrets, ils ont géré la situation parfaitement. Service indispensable pour tout gestionnaire Airbnb."
        <strong>— Claire, Paris</strong>
      </div>
      <div class="testimonial">
        "Très rassurant de pouvoir compter sur un service aussi réactif, même le week-end !"
        <strong>— Mehdi, Marseille</strong>
      </div>
    </div>
  </section>

  <section class="highlight">
    <h2>Contactez-nous</h2>
    <form>
      <input type="text" placeholder="Votre nom" required>
      <input type="email" placeholder="Votre email" required>
      <textarea placeholder="Votre message..." rows="5" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
  </section>

  <footer>
    &copy; 2025 SOS Fête LCD — Tous droits réservés
  </footer>

</body>
</html>
