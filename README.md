# Geb-udereinigung-Tsakalis-
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <title>Gebäudereinigung Tsakalis | Professionelle Reinigung in München</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="topbar">
    <div class="topbar-inner">
      <span class="logo-text">Gebäudereinigung Tsakalis</span>
      <a class="topbar-phone" href="tel:+498900000000">📞 089 / 000 00 000</a>
    </div>
  </header>

  <section class="hero">
    <div class="hero-inner">
      <div>
        <h1>Sauberkeit, auf die du dich verlassen kannst.</h1>
        <p class="hero-subtitle">
          Zuverlässige Gebäudereinigung in München und Umgebung – für Büros,
          Treppenhäuser, Praxen und private Haushalte.
        </p>
        <div class="hero-buttons">
          <a href="#kontakt" class="btn primary">Kostenloses Angebot anfragen</a>
          <a href="#leistungen" class="btn secondary">Unsere Leistungen</a>
        </div>
      </div>
      <div class="hero-box">
        <ul>
          <li>✅ Zuverlässig & pünktlich</li>
          <li>✅ Faire, transparente Preise</li>
          <li>✅ Individuelle Reinigungskonzepte</li>
        </ul>
      </div>
    </div>
  </section>

  <nav class="nav">
    <a href="#ueber-uns">Über uns</a>
    <a href="#leistungen">Leistungen</a>
    <a href="#vorteile">Warum wir?</a>
    <a href="#kontakt">Kontakt</a>
  </nav>

  <main class="content">

    <section id="ueber-uns" class="card">
      <h2>Über Gebäudereinigung Tsakalis</h2>
      <p>
        Wir sind ein modernes, zuverlässiges Reinigungsunternehmen aus München.
        Unser Fokus liegt auf sauberer Arbeit, klarer Kommunikation und
        langfristigen Kundenbeziehungen. Egal ob kleine Praxis oder großes Büro –
        wir passen uns deinem Objekt und deinem Budget an.
      </p>
      <p>
        Durch flexible Arbeitszeiten reinigen wir, wenn es für dich am besten
        passt – früh morgens, abends oder am Wochenende.
      </p>
    </section>

    <section id="leistungen" class="card">
      <h2>Unsere Leistungen</h2>
      <div class="grid-2">
        <div>
          <h3>Unterhaltsreinigung</h3>
          <ul>
            <li>Büros & Agenturen</li>
            <li>Treppenhäuser & Wohnanlagen</li>
            <li>Arztpraxen & Studios</li>
          </ul>
        </div>
        <div>
          <h3>Spezial- & Zusatzleistungen</h3>
          <ul>
            <li>Glas- & Fensterreinigung</li>
            <li>Grundreinigung</li>
            <li>Baureinigung / Endreinigung</li>
          </ul>
        </div>
      </div>
      <p class="note">
        Nicht dabei, was du suchst? Schreib uns einfach – wir finden eine Lösung.
      </p>
    </section>

    <section id="vorteile" class="card">
      <h2>Warum du mit uns arbeiten solltest</h2>
      <div class="grid-3">
        <div class="feature">
          <h3>Persönlicher Kontakt</h3>
          <p>
            Du hast immer einen festen Ansprechpartner und keine anonyme Hotline.
          </p>
        </div>
        <div class="feature">
          <h3>Transparente Preise</h3>
          <p>
            Klare Angebote ohne versteckte Kosten – auf Wunsch Pauschalpreise.
          </p>
        </div>
        <div class="feature">
          <h3>Flexible Zeiten</h3>
          <p>
            Wir reinigen dann, wenn dein Betrieb nicht gestört wird.
          </p>
        </div>
      </div>
    </section>

    <section id="kontakt" class="card card-highlight">
      <h2>Kontakt & unverbindliches Angebot</h2>
      <p>
        Schreib uns ein paar Infos zu deinem Objekt (Art, Größe, Standort) –
        wir melden uns schnell mit einem passenden Vorschlag.
      </p>

      <div class="contact-grid">
        <div>
          <p><strong>Telefon:</strong> <a href="tel:+498900000000">089 / 000 00 000</a></p>
          <p><strong>E-Mail:</strong> <a href="mailto:info@tsakalis-reinigung.de">info@tsakalis-reinigung.de</a></p>
          <p><strong>Standort:</strong> München und Umgebung</p>
        </div>
        <form class="contact-form">
          <label>
            Name
            <input type="text" placeholder="Dein Name" required />
          </label>
          <label>
            E-Mail
            <input type="email" placeholder="deine@mail.de" required />
          </label>
          <label>
            Nachricht
            <textarea rows="4" placeholder="Objekt, Größe, gewünschte Leistung..."></textarea>
          </label>
          <button type="submit" class="btn primary full-width">Anfrage senden</button>
        </form>
      </div>
      <p class="tiny">
        * Das Formular ist aktuell nur ein Beispiel. Für echte Anfragen bitte
        direkt per E-Mail oder Telefon melden.
      </p>
    </section>

  </main>

  <footer class="footer">
    <p>&copy; 2025 Gebäudereinigung Tsakalis · München</p>
    <p class="footer-small">
      Impressum & Datenschutz können hier später verlinkt werden.
    </p>
  </footer>
</body>
</html>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

body {
  background: #f5f7fb;
  color: #111827;
  line-height: 1.5;
}

/* Topbar */

.topbar {
  background: #0b1120;
  color: #e5e7eb;
  padding: 0.5rem 1rem;
}

.topbar-inner {
  max-width: 1100px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  font-size: 0.95rem;
}

.logo-text {
  font-weight: 700;
  letter-spacing: 0.03em;
}

.topbar-phone {
  color: #e5e7eb;
  text-decoration: none;
  font-weight: 600;
}

.topbar-phone:hover {
  text-decoration: underline;
}

/* Hero */

.hero {
  background: linear-gradient(135deg, #0f172a, #1d4ed8);
  color: #f9fafb;
  padding: 3rem 1.25rem 3.5rem;
}

.hero-inner {
  max-width: 1100px;
  margin: 0 auto;
  display: grid;
  gap: 2rem;
}

@media (min-width: 768px) {
  .hero-inner {
    grid-template-columns: minmax(0, 2.2fr) minmax(0, 1.3fr);
    align-items: center;
  }
}

.hero h1 {
  font-size: clamp(2rem, 3vw, 2.8rem);
  margin-bottom: 0.75rem;
}

.hero-subtitle {
  font-size: 1rem;
  max-width: 32rem;
  margin-bottom: 1.5rem;
}

.hero-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
}

.hero-box {
  background: rgba(15, 23, 42, 0.75);
  border-radius: 1rem;
  padding: 1.25rem 1.5rem;
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.6);
}

.hero-box ul {
  list-style: none;
  display: grid;
  gap: 0.4rem;
}

/* Buttons */

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.7rem 1.3rem;
  border-radius: 999px;
  font-size: 0.95rem;
  font-weight: 600;
  text-decoration: none;
  border: 1px solid transparent;
  cursor: pointer;
}

.btn.primary {
  background: #facc15;
  color: #111827;
  border-color: #facc15;
}

.btn.primary:hover {
  filter: brightness(0.95);
}

.btn.secondary {
  background: transparent;
  color: #e5e7eb;
  border-color: rgba(249, 250, 251, 0.5);
}

.btn.secondary:hover {
  background: rgba(15, 23, 42, 0.4);
}

.btn.full-width {
  width: 100%;
}

/* Navigation */

.nav {
  position: sticky;
  top: 0;
  z-index: 10;
  background: #ffffff;
  border-bottom: 1px solid #e5e7eb;
  display: flex;
  gap: 1.5rem;
  justify-content: center;
  padding: 0.7rem 1rem;
}

.nav a {
  color: #4b5563;
  text-decoration: none;
  font-size: 0.95rem;
  font-weight: 500;
}

.nav a:hover {
  color: #1d4ed8;
}

/* Main content */

.content {
  max-width: 1100px;
  margin: 2rem auto 3rem;
  padding: 0 1.25rem;
  display: grid;
  gap: 1.75rem;
}

.card {
  background: #ffffff;
  border-radius: 1.25rem;
  padding: 1.75rem 1.5rem;
  box-shadow: 0 10px 30px rgba(15, 23, 42, 0.06);
}

.card h2 {
  font-size: 1.4rem;
  margin-bottom: 0.75rem;
}

.card p + p {
  margin-top: 0.5rem;
}

.card-highlight {
  border: 1px solid #dbeafe;
  background: #eff6ff;
}

/* Grids */

.grid-2,
.grid-3 {
  display: grid;
  gap: 1.3rem;
  margin-top: 0.75rem;
}

@media (min-width: 700px) {
  .grid-2 {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (min-width: 900px) {
  .grid-3 {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }
}

.feature h3 {
  font-size: 1.05rem;
  margin-bottom: 0.4rem;
}

.feature p {
  font-size: 0.95rem;
  color: #4b5563;
}

/* Kontaktbereich */

.contact-grid {
  display: grid;
  gap: 1.5rem;
  margin-top: 1rem;
}

@media (min-width: 800px) {
  .contact-grid {
    grid-template-columns: minmax(0, 1.1fr) minmax(0, 1.4fr);
  }
}

.contact-form {
  display: grid;
  gap: 0.75rem;
}

.contact-form label {
  font-size: 0.9rem;
  display: grid;
  gap: 0.25rem;
  color: #374151;
}

.contact-form input,
.contact-form textarea {
  padding: 0.55rem 0.7rem;
  border-radius: 0.6rem;
  border: 1px solid #d1d5db;
  font-size: 0.92rem;
}

.contact-form input:focus,
.contact-form textarea:focus {
  outline: 2px solid #2563eb;
  outline-offset: 1px;
  border-color: #2563eb;
}

.note {
  margin-top: 0.9rem;
  font-size: 0.9rem;
  color: #4b5563;
}

.tiny {
  margin-top: 0.75rem;
  font-size: 0.78rem;
  color: #6b7280;
}

/* Footer */

.footer {
  text-align: center;
  padding: 1.2rem 1rem 2rem;
  background: #0b1120;
  color: #9ca3af;
  font-size: 0.85rem;
}

.footer-small {
  margin-top: 0.25rem;
  font-size: 0.78rem;
}
