# Arta — Websites & KI-Automation für kleine Betriebe

Freiberufliches Studio von Purija Ardeshirzadeh, Reutlingen.

Website: https://lumen-ai.de

## Dateistruktur

```
├── index.html           (Hauptdatei — umbenennen von arta-prototyp.html)
├── anong-old.png       (Screenshot: alte Anong-Website)
├── anong-new.png       (Screenshot: neue Anong-Website)
├── portrait.jpg        (Profilbild für About-Sektion)
└── README.md           (diese Datei)
```

## Deployment zu Netlify

1. **Repository auf GitHub erstellen**
   ```bash
   git init
   git add .
   git commit -m "initial: lumen-ai website"
   git branch -M main
   git remote add origin https://github.com/USERNAME/lumen-ai
   git push -u origin main
   ```

2. **Mit Netlify verbinden**
   - netlify.com
   - "Add new site" → "Import an existing project"
   - GitHub-Repo auswählen
   - Auto-Deploy ist aktiv

3. **Custom Domain lumen-ai.de einrichten**
   - Netlify Dashboard → Domain settings
   - "Add custom domain" → lumen-ai.de
   - DNS-Anweisungen folgen

## Kontaktformular

Das Kontaktformular ist bereits konfiguriert und funktioniert automatisch auf Netlify.

Anfragen erhältst du in:
- **Netlify Dashboard → Forms**
- Optional: E-Mail-Benachrichtigungen konfigurieren

---

**Build:** September 2026 · Design System: Bauplan · Tech: Vanilla HTML/CSS/JS
