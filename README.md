# Webcraftiq — Production Site

Premium webdesign voor Belgische KMO's. Volledige sites op maat met multi-step formulieren, lokale SEO en CRM-integraties.

**Live URL:** https://webcraftiq.be (of webcraftiq.pages.dev voor staging)

---

## 📁 Structuur

```
webcraftiq/
├── index.html                  # Homepage
├── website-laten-maken.html    # SEO landing page (top keyword)
├── aanpak.html                 # Manifest / werkmethode
├── over.html                   # Over Stef Weyts
├── cases.html                  # Portfolio overzicht
│   ├── cases/voltrix.html      # Voltrix case study
│   └── cases/gevanti.html      # Gevanti BV case study
├── blog.html                   # Blog overzicht
│   └── blog/multi-step-...html # Blog post
├── 404.html                    # Error page
├── privacy.html                # GDPR privacybeleid
├── voorwaarden.html            # Algemene voorwaarden
├── cookies.html                # Cookiebeleid
├── styles.css                  # Gedeelde styling
├── _redirects                  # Cloudflare URL redirects
├── _headers                    # Cloudflare HTTP headers
├── sitemap.xml                 # SEO sitemap
├── robots.txt                  # Crawl-instructies
└── site.webmanifest            # PWA manifest
```

---

## 🚀 Deployment

### Methode 1: Cloudflare Pages directe upload (snelst, zonder Git)

1. Pak deze ZIP uit op je computer
2. Login op [dash.cloudflare.com](https://dash.cloudflare.com) → **Workers & Pages**
3. **Create** → tab **Pages** → **Upload assets**
4. Projectnaam: `webcraftiq`
5. Sleep alle losse bestanden (niet de map!) in de upload-zone
6. **Deploy site**

### Methode 2: GitHub + Cloudflare Pages (voor automatische deploys)

**A. GitHub repo aanmaken:**
1. Ga naar [github.com/new](https://github.com/new)
2. Repository name: `webcraftiq-site`
3. Visibility: **Private** aanbevolen
4. **Niet** "Initialize with README" aanvinken
5. **Create repository**

**B. Bestanden uploaden — gebruik GitHub Desktop (betrouwbaarst):**

GitHub.com drag-and-drop is onbetrouwbaar voor mappen. Veel beter:

1. Download GitHub Desktop: [desktop.github.com](https://desktop.github.com)
2. Login met je GitHub account
3. **File** → **Clone repository** → kies je nieuwe `webcraftiq-site` repo
4. Open de gekloonde folder in Finder/Explorer
5. **Kopieer alle bestanden** uit deze ZIP naar die folder
6. Terug in GitHub Desktop: zie je dat alle bestanden zijn toegevoegd
7. Schrijf commit message: `Initial commit — Webcraftiq site`
8. Klik **Commit to main** → daarna **Push origin**

**C. Koppelen aan Cloudflare:**
1. Cloudflare → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**
2. Selecteer je `webcraftiq-site` repo
3. Build settings:
   - Build command: **leeg laten**
   - Build output directory: **/** (root)
4. **Save and Deploy**

Vanaf nu deployt elke `git push` automatisch een nieuwe versie.

---

## 🔧 Aanpassingen maken

### Tekst wijzigen
Open het juiste `.html` bestand in een editor (VS Code, Sublime, of zelfs Notepad). Zoek de tekst, pas aan, sla op.

### Nieuwe blogpost toevoegen
1. Kopieer `blog/multi-step-formulier-vs-klassiek.html` als template
2. Hernoem naar `blog/jouw-nieuwe-post.html`
3. Pas titel, content, meta-tags aan
4. Voeg toe aan `blog.html` (overzicht) en `sitemap.xml`

### Nieuwe case toevoegen
1. Kopieer `cases/voltrix.html` als template
2. Hernoem naar `cases/jouw-klant.html`
3. Pas alle content aan met echte info
4. Voeg toe aan `cases.html` en homepage `index.html`
5. Update `sitemap.xml`

---

## 📋 Voor je live gaat — checklist

Zie `LAUNCH-CHECKLIST.md` voor de volledige to-do lijst.

**Cruciaal:**
- [ ] Domein webcraftiq.be registreren
- [ ] Contact-formulier koppelen (Formspree ID in `index.html`)
- [ ] OG-image (`og-image.jpg`, 1200×630px) maken
- [ ] Google Search Console + sitemap submitten
- [ ] Calendly link instellen voor intake-call

---

## 🛠 Tech Stack

- **Pure HTML/CSS** — geen build step, geen frameworks
- **Custom design** in Bricolage Grotesque + DM Sans + JetBrains Mono
- **Lokaal SEO** geoptimaliseerd voor "website laten maken" en Belgische steden
- **Schema.org JSON-LD** structured data op alle pagina's

---

## 📞 Contact

**Webcraftiq** — Stef Weyts
- Email: info@webcraftiq.be
- BTW: BE0803.343.103
- Antwerpen, België

---

© 2026 Webcraftiq · Stef Weyts · BTW BE0803.343.103
