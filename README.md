# Webcraftiq — V1.0

Premium webdesign voor Belgische KMO's. Volledige sites op maat met multi-step formulieren en lokale SEO.

**Versie:** V1.0 (6 mei 2026)
**Live URL:** https://webcraftiq.be (zodra domein gekoppeld)
**Staging:** https://webcraftiq.pages.dev

---

## 📁 Belangrijke documenten

| Bestand | Wat staat erin |
|---------|----------------|
| **CHANGELOG.md** | Versie-geschiedenis: wat zat in V0.1 → V1.0 |
| **ROADMAP.md** | Wat komt er in V1.1, V2.0, V3.0 |
| **LAUNCH-CHECKLIST.md** | To-do lijst voor je live gaat |
| **README.md** | Dit document |

---

## 🌳 Site-structuur

```
webcraftiq/
├── index.html                  # Homepage
├── website-laten-maken.html    # SEO landing page (top keyword)
├── aanpak.html                 # Werkmethode
├── over.html                   # Over Stef Weyts
├── cases.html                  # Portfolio overzicht
│   ├── cases/voltrix.html      # Voltrix case study (echt)
│   └── cases/gevanti.html      # Gevanti BV case study (echt)
├── blog.html                   # Blog overzicht
│   └── blog/multi-step-...html # Blog post over conversie
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

## 🚀 Hoe deze site werken

**Tech:** pure HTML/CSS — geen build step, geen framework, geen Node.js.

**Hosting:** Cloudflare Pages (gratis tier, automatische deploys via GitHub).

**Workflow:**
1. Wijzig HTML lokaal (in editor)
2. Push naar GitHub via GitHub Desktop
3. Cloudflare deployt automatisch in 30-60 seconden
4. Test op staging URL (incognito!)
5. Tag in CHANGELOG.md welke versie

---

## ✏️ Hoe maak je wijzigingen

### Tekst wijzigen
Open `.html` bestand in editor (VS Code, Sublime, Notepad). Zoek tekst, pas aan, opslaan, push.

### Nieuwe blog post
1. Kopieer `blog/multi-step-formulier-vs-klassiek.html` als template
2. Hernoem naar `blog/jouw-nieuwe-post.html`
3. Pas titel, content, meta-tags aan
4. Voeg toe aan `blog.html` overzicht
5. Voeg URL toe aan `sitemap.xml`
6. Update versie-marker bovenaan
7. Update CHANGELOG.md

### Nieuwe case
1. Kopieer `cases/voltrix.html` als template
2. Hernoem naar `cases/klant-naam.html`
3. Pas alle content aan met echte info
4. Voeg toe aan `cases.html` + `index.html`
5. Update `sitemap.xml`
6. Update versie-marker
7. Update CHANGELOG.md

---

## 🏷️ Versie-systeem

Elke pagina heeft bovenaan in `<head>`:
```html
<!-- Webcraftiq v1.0 | 2026-05-06 | Stef Weyts -->
```

Open de live site → rechtsklik → "Bron weergeven" → je ziet welke versie live staat.

**Versie-bumping**:
- `V1.x` voor kleine fixes en content
- `V2.x` voor design-wijzigingen of nieuwe pagina's
- `V3.x` voor structurele wijzigingen (CMS, framework migratie, etc.)

Zie `CHANGELOG.md` voor de volledige versie-geschiedenis.

---

## 📞 Contact

**Webcraftiq** — Stef Weyts
- Email: info@webcraftiq.be
- BTW: BE0803.343.103
- Antwerpen, België

---

© 2026 Webcraftiq · Stef Weyts · BTW BE0803.343.103
