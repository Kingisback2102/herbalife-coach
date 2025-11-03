# 🌿 Herbalife Product Recommendation Coach

Eine interaktive Web-App zur personalisierten Herbalife Produktberatung mit über 90 Produkten.

## ✨ Features

- **90+ Herbalife Produkte** aus allen Kategorien
- **Intelligente Empfehlungslogik** basierend auf:
  - Zielgruppe (Erwachsene, Kinder, Schwangere, Postpartum)
  - Persönliche Ziele (Abnehmen, Energie, Sport, Beauty, Gesundheit)
  - Lifestyle & Energielevel
  - Ernährungspräferenzen (vegan, koffeinfrei)
- **Responsive Design** - funktioniert auf allen Geräten
- **Deutsche Benutzeroberfläche**
- **Direkte Kontaktmöglichkeiten** (Telegram & WhatsApp)

## 📦 Produktkategorien

- **Formula 1** Shakes (9 Geschmacksrichtungen)
- **Tees & Energie-Drinks** (LiftOff, Iced Coffee)
- **Aloe Vera** (Original, Mango, AloeMax)
- **Sport & Regeneration** (H24 Serie, CR7 Drive)
- **Protein** (Riegel, Pulver, Snacks)
- **Beauty & Haut** (Collagen, SKIN Serie)
- **Vitamine & Supplements** (Omega-3, Multivitamine)
- **Kinder** (Kids Shakes)
- und viele mehr...

## 🚀 Installation & Verwendung

### Option 1: Direkt im Browser öffnen

1. Lade `index.html` herunter
2. Öffne die Datei in deinem Browser
3. Fertig! Keine Installation nötig.

### Option 2: GitHub Pages

1. Fork dieses Repository
2. Gehe zu Settings → Pages
3. Source: Deploy from branch `main`
4. Deine App ist online unter: `https://deinusername.github.io/herbalife-coach/`

### Option 3: Lokaler Webserver

```bash
# Mit Python
python -m http.server 8000

# Mit Node.js
npx http-server

# Öffne dann: http://localhost:8000
```

## 🎯 Verwendung

1. Wähle die Zielgruppe (für dich, Kind, Schwangerschaft, etc.)
2. Beantworte 4-5 einfache Fragen zu Zielen und Lifestyle
3. Erhalte eine personalisierte Produktempfehlung
4. Sieh dir Details, Benefits und Preise an
5. Kontaktiere direkt per Telegram oder WhatsApp

## 🛠️ Technologie

- **React** (via CDN - keine Build-Tools nötig)
- **Tailwind CSS** für modernes Design
- **Vanilla JavaScript** - keine Abhängigkeiten
- **Single HTML File** - einfach zu deployen

## 📝 Anpassung

### Kontaktlinks ändern

In `index.html` Zeile ~850-860:

```html
<a href="https://t.me/DEIN_TELEGRAM" target="_blank">
<a href="https://wa.me/DEINE_NUMMER" target="_blank">
```

### Produkte anpassen

Die Produktdatenbank findest du in Zeile ~30-200:

```javascript
const products = {
    F1_VAN: { name: 'Formula 1 Vanilla', price: 45, ... },
    // weitere Produkte...
};
```

### Empfehlungslogik anpassen

Die Logik findest du in der `getRecs()` Funktion (Zeile ~220-400).

## 📱 Features

- ✅ Mobile-optimiert
- ✅ Progress Bar
- ✅ Mehrfachauswahl bei Fragen
- ✅ Intelligente Produktfilterung
- ✅ Kostenberechnung (pro Monat & Tag)
- ✅ Warnhinweise (Koffein, Schwangerschaft, etc.)
- ✅ Erfolgsgeschichten
- ✅ 30-Tage Geld-zurück-Garantie Info

## 🎨 Design

- Grün/Türkis Farbschema (Herbalife Branding)
- Moderne Card-basierte UI
- Smooth Transitions
- Emojis für bessere UX
- Glassmorphism-Effekte

## 📊 Produktumfang

- **Frühstück & Mahlzeiten**: 16 Produkte
- **Energie & Fokus**: 13 Produkte
- **Verdauung & Detox**: 5 Produkte
- **Sport & Regeneration**: 12 Produkte
- **Snacks & Drinks**: 10 Produkte
- **Beauty & Haut**: 17 Produkte
- **Vitamine & Supplements**: 16 Produkte
- **Spezialprodukte**: 11 Produkte

**Gesamt: 90+ Produkte**

## 🤝 Mitwirken

Contributions sind willkommen! Bitte:

1. Fork das Repository
2. Erstelle einen Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit deine Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen Pull Request

## 📄 Lizenz

MIT License - siehe [LICENSE](LICENSE) Datei

## 👤 Autor

Herbalife Coach
- Telegram: [@Thebillioairesclubphuket](https://t.me/Thebillioairesclubphuket)
- WhatsApp: [+66 62 849 5572](https://wa.me/66628495572)

## ⭐ Erfolgsgeschichten

> "Jürgen: 120kg → 97kg in 10 Monaten!"

## 🔗 Links

- [Herbalife Official](https://www.herbalife.com/)
- [Herbalife Deutschland](https://www.herbalife.de/)

## 🐛 Bug Reports

Bitte öffne ein Issue auf GitHub mit:
- Browser & Version
- Beschreibung des Problems
- Screenshots (falls relevant)

## 📞 Support

Bei Fragen zur App oder den Produkten:
- 💬 Telegram: https://t.me/Thebillioairesclubphuket
- 📞 WhatsApp: https://wa.me/66628495572

---

Made with 💚 for a healthier life
