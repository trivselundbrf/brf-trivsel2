<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trivselanalys för BRF:er</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f4f4f4;
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background: #1a73e8;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
    }

    header p {
      font-size: 1.2rem;
    }

    main {
      max-width: 800px;
      margin: 2rem auto;
      padding: 1rem;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: #1a73e8;
    }

    ul {
      padding-left: 1.2rem;
    }

    a {
      color: #1a73e8;
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #666;
    }
  </style>
</head>
<body>

  <header>
    <h1>Trivselanalys för BRF:er</h1>
    <p>Digitala enkäter och smart analys för din bostadsrättsförening till ett rimligt pris</p>
  </header>

  <main>
    <h2>Vad erbjuder vi?</h2>
    <ul>
      <li>Standardiserad digital trivselenkät</li>
      <li>Index: Trivsel, Trygghet, Gemenskap</li>
      <li>Fritextanalys och ordmoln</li>
      <li>PDF-rapport med diagram och kommentarer</li>
    </ul>
    <p>
      Du behöver endast förse oss med mejladresser till medlemmar i din BRF, så sköter vi resten.
    </p>
    <p>
      <strong>Pris för standardval:</strong> från 2 800 kr exkl moms för enkät- och rapportframställning enligt dina val i vårt standardutbud
    </p>
    <p>
      Om ytterligare frågor eller analyser än vårt standardutbud önskas tillkommer pris enligt överenskommelse.
    </p>
    <p>
      <a href="#">Klicka här för att läsa mer om vårt standardutbud</a>
    </p>
  </main>

  <footer>
    &copy; 2025 Trivselanalys för BRF:er
  </footer>

</body>
</html>
<h2>Beställningsformulär</h2>
<form action="https://formsubmit.co/trivselundbrf@gmail.com" method="POST">
  <p><strong>Vad vill du beställa?</strong></p>
  <label><input type="checkbox" name="Standardanalys" value="Ja"> Nivå 1: Trivselanalys, standard (2 800 kr exkl moms)</label><br>
  <label><input type="checkbox" name="Fritextanalys" value="Ja"> Nivå 2: Nivå 1 + Fritextanalys (3 800 kr exkl moms) </label><br>
   <label><input type="checkbox" name="Fritextanalys" value="Ja"> Nivå 3: Nivå 1 + Nivå 2 + Delresultat per vald grupp (3 800 kr exkl moms + 700 kr per vald grupp, kan vara kön, port eller ålder) </label><br>
  <label><input type="checkbox" name="Extraanalys" value="Ja"> Nivå 4: Nivå 3 + tilläggsbeställning utanför standardutbudet i Nivå 1-3 (3 800 kr exkl moms + 500 kr/timme för tilläggsbeställning)) </label><br><br>

  <p><strong>Kontaktuppgifter</strong></p>
  <label>Namn på beställare:<br><input type="text" name="Namn" required></label><br><br>
  <label>Mejladress:<br><input type="email" name="Email" required></label><br><br>
  <label>Telefon:<br><input type="tel" name="Telefon"></label><br><br>
  <label>BRF Namn:<br><input type="text" name="BRF" required></label><br><br>

  <p><strong>Övriga meddelanden</strong></p>
  <textarea name="Meddelande" rows="4" style="width:100%;"></textarea><br><br>

  <!-- Skicka tillbaks användaren till din hemsida efter inskick -->
  <input type="hidden" name="_next" value="https://dinhemsida.se/tack">
  <input type="hidden" name="_captcha" value="false">

  <button type="submit">Skicka beställning</button>
</form>
  

