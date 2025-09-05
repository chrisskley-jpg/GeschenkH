# Schnitzeljagd-Website

Statische Website (nur `index.html` + `images/`), optimiert für Netlify & GitHub Pages.

## Struktur
```
schnitzeljagd-site/
├─ index.html
└─ images/
   ├─ hero-hochzeit.jpg
   ├─ wandern.jpg
   ├─ ablauf-pfeil.webp
   ├─ berge-wald.jpg
   ├─ mountains-warm.jpg
   └─ familie-kley.jpg
```

## Deploy mit Netlify
1. Repo auf GitHub pushen.
2. Netlify: **Add new site → Import from Git** → Repo wählen.
3. Build: **kein Build Command**, **Publish directory:** `/`.
4. Deploy. Optional: **Password protect** in den Site-Settings aktivieren.

## Deploy mit GitHub Pages
1. Repo anlegen, Ordner hochladen.
2. Im Repo: **Settings → Pages** → Source: Branch `main`, Folder `/ (root)` → Save.
3. Seite erscheint unter `https://DEIN-NAME.github.io/REPO-NAME/`.

## Code-Sperre
- Aktiv ab **04.09.2025** (siehe `ACTIVATION_ISO` im Script).
- Code lautet **06.09.2025**.
- Hinweis: Clientseitig – für echte Privatheit zusätzlich Netlify-Passwortschutz nutzen.
