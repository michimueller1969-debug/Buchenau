# Hesse-Buchenau — Website

Website des Bestattungsunternehmens Hesse-Buchenau (Sontra, seit 1872).

## Struktur

```
index.html          Startseite (React via CDN, kein Build-Schritt nötig)
css/styles.css      Design-Tokens: Farben, Typografie, Abstände
assets/             Bilder und Grafiken
```

## Lokal starten

Einfach `index.html` im Browser öffnen — oder in VS Code die Erweiterung **Live Server** installieren und "Go Live" klicken.

Kein npm, kein Build-Prozess: React und Babel werden per CDN geladen.

## Design-System

- **Primärfarbe:** Sage-Grün `#3D5541`
- **Akzent:** Heritage-Gold `#A8884A`, Kupfer `#B87040`
- **Schriften:** Playfair Display (Überschriften), Source Sans 3 (Fließtext) — via Google Fonts
- **Basis:** warmes Creme `#FAF8F5`
