# 📖 KI MagicBook for Kids

> Personalisierte KI-generierte Kinderbücher – einfach, schnell, magisch ✨

## Features

- 🧒 Kind als Hauptfigur (Name, Alter, Geschlecht)
- 🎨 Buchstil wählen (Comic, Märchen, Abenteuer, Gute-Nacht, Reime & mehr)
- 🌍 Mehrsprachig (Deutsch, Englisch, Kurdisch, Zweisprachig, Türkisch, Arabisch)
- 📸 Foto hochladen + Avatar-Erstellung
- 🤖 KI generiert einzigartiges Buch (Anthropic Claude)
- ✏️ Jede Seite einzeln bearbeitbar
- 📦 eBook (PDF) oder Druckversion
- 💳 Checkout mit TWINT, Kreditkarte, PayPal
- 📧 Bestellung per E-Mail

## Setup

### 1. GitHub Pages aktivieren
Gehe in deinem Repo zu `Settings → Pages → Source: main / root`. Die Seite ist dann erreichbar unter:
`https://sasemufc.github.io/magicbook`

### 2. API Key konfigurieren
- Öffne die Webseite
- Klicke auf **⚙️ API Key** (oben rechts)
- Gib deinen [Anthropic API Key](https://console.anthropic.com) ein
- Wird nur lokal im Browser gespeichert (localStorage)

> Ohne API Key läuft die App im **Demo-Modus** mit einer Beispielgeschichte.

### 3. Bestellungs-E-Mail
Bestellungen öffnen automatisch den Mail-Client mit vorausgefüllter Mail an `sasemufc@gmail.com`.

Für vollautomatisches E-Mail-Versenden ohne Mail-Client: [EmailJS](https://www.emailjs.com) integrieren (kostenlos bis 200 Mails/Monat).

## Preise

| Format | Preis |
|--------|-------|
| 💻 eBook (PDF) | CHF 9.90 |
| 📚 Druckversion | CHF 34.90 + CHF 5.90 Versand |

## Technologie

- Reines HTML/CSS/JS – kein Framework, kein Build-Step
- [Anthropic Claude API](https://www.anthropic.com) für KI-Buchgenerierung
- Google Fonts: Fredoka One, Nunito, Caveat

## Nächste Schritte (Ideen)

- [ ] Echte TWINT-Integration via [TWINT API](https://www.twint.ch)
- [ ] PDF-Generierung im Browser (z.B. jsPDF)
- [ ] EmailJS für automatische Bestellbestätigung
- [ ] Backend/Datenbank für Bestellverwaltung (Supabase, Firebase)
- [ ] KI-generierte Illustrationen (DALL-E, Stable Diffusion)
