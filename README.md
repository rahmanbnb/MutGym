<!DOCTYPE html><html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MutRaum Pre-Order</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f2f2f2; margin: 0; padding: 0; }
    .container { max-width: 600px; margin: 50px auto; background: white; padding: 30px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    h1 { text-align: center; color: #333; }
    label { display: block; margin-top: 15px; font-weight: bold; }
    input, select, textarea { width: 100%; padding: 10px; margin-top: 5px; border: 1px solid #ccc; border-radius: 4px; }
    button { background: #0d6efd; color: white; padding: 10px 15px; border: none; border-radius: 4px; cursor: pointer; margin-top: 20px; width: 100%; }
    button:hover { background: #0b5ed7; }
  </style>
</head>
<body>
  <div class="container">
    <h1>Reserviere deinen privaten Trainingsplatz</h1>
    <form action="#" method="POST">
      <label for="name">Vollständiger Name</label>
      <input type="text" id="name" name="name" required /><label for="email">E-Mail-Adresse</label>
  <input type="email" id="email" name="email" required />

  <label for="zeitfenster">Bevorzugtes Zeitfenster</label>
  <select id="zeitfenster" name="zeitfenster">
    <option value="5-12">05:00 - 12:00 (60€/Monat oder 90€ Premium)</option>
    <option value="13-21">13:00 - 21:00 (85€/Monat oder 120€ Premium)</option>
    <option value="22-00">22:00 - 00:00 (70€/Monat oder 100€ Premium)</option>
  </select>

  <label for="dauer">Gewünschte Vertragsdauer</label>
  <select id="dauer" name="dauer">
    <option value="monatlich">Monatlich kündbar</option>
    <option value="12monate">12 Monate</option>
    <option value="24monate">24 Monate (10% Rabatt)</option>
  </select>

  <label for="trinkpaket">Möchtest du ein Getränkepaket?</label>
  <select id="trinkpaket" name="trinkpaket">
    <option value="nein">Nein</option>
    <option value="ja30">Ja – 30€/Monat für unbegrenzte Nutzung</option>
    <option value="taglich">Tageskauf im Automaten</option>
  </select>

  <label for="ziel">Was ist dein Trainingsziel?</label>
  <textarea id="ziel" name="ziel" rows="3"></textarea>

  <label for="anmerkungen">Anmerkungen oder besondere Wünsche</label>
  <textarea id="anmerkungen" name="anmerkungen" rows="3"></textarea>

  <button type="submit">Jetzt Platz sichern</button>
</form>

  </div>
</body>
</html>
