# Webcraftiq V1 — Launch Checklist

Wat moet je nog doen voordat de site echt productie-klaar is.

---

## ✅ Al klaar (in V1)

- [x] Alle pagina's gebouwd en gevalideerd
- [x] Echte cases: Voltrix + Gevanti
- [x] Identiteit overal correct: Stef Weyts + BTW + email
- [x] Wettelijke pagina's: privacy, voorwaarden, cookies (GDPR)
- [x] Geen fake content (alle cases, stats, telefoonnummers gecheckt)
- [x] Site live op staging: webcraftiq.pages.dev
- [x] Versie-marker V1.0 in alle bestanden

---

## 🔥 Cruciaal — voor je echt live gaat

### Domein & DNS
- [ ] **Registreer webcraftiq.be** bij combell.be of gandi.net (~€15/jaar)
- [ ] **Koppel domein aan Cloudflare**: dashboard → project → "Custom domains" → "Set up a custom domain"
- [ ] **Wacht op SSL** (~5 min na koppeling)
- [ ] Test: `https://webcraftiq.be` werkt

### Contactformulier (anders kan niemand contact opnemen!)
- [ ] **Maak Formspree account** op formspree.io (gratis voor 50 submissions/maand)
- [ ] Maak een nieuw formulier aan, kopieer het ID (vb. `xpzajklw`)
- [ ] Open `index.html` in editor → zoek `JOUW_FORMSPREE_ID` → vervang met je ID
- [ ] Push naar GitHub
- [ ] Test: vul het formulier in op live site, check of je een mail krijgt

### Calendly link voor "Plan intake-call"
- [ ] **Maak Calendly account** (gratis tier)
- [ ] Maak event "Intake-call (45 min)" met je beschikbaarheid
- [ ] Kopieer publieke URL (vb. `calendly.com/stefweyts/intake`)
- [ ] Open `index.html` → zoek `#contact` bij CTA-knoppen → vervang met je Calendly URL
- [ ] Test: knop opent Calendly correct

---

## 📊 Belangrijk — voor data en groei

### Analytics
- [ ] **Plausible Analytics** (€9/maand, EU servers, GDPR-conform)
  OF **Google Analytics 4** (gratis, maar privacy-implicaties)
- [ ] Snippet toevoegen aan alle HTML pagina's (in `<head>`)
- [ ] Dashboard checken na 24u: zie je bezoekers binnenkomen?

### Google Search Console
- [ ] Account aanmaken op search.google.com/search-console
- [ ] **Verify ownership** via DNS-record of HTML-tag
- [ ] **Submit sitemap**: `https://webcraftiq.be/sitemap.xml`
- [ ] Wacht 1-2 weken voor eerste indexering
- [ ] Check welke queries je krijgt impressies voor

### LinkedIn / Social
- [ ] Webcraftiq company page op LinkedIn aanmaken
- [ ] Eerste post: "Webcraftiq is live!"
- [ ] Verbind je persoonlijk LinkedIn met de page
- [ ] Eerste outreach via LinkedIn DM (volgens je eerdere outreach playbook)

---

## 🎨 Cosmetisch — voor professionele uitstraling

### Open Graph image (voor link previews)
- [ ] Maak in Canva: 1200×630 px, met logo + tagline
- [ ] Sla op als `og-image.jpg`
- [ ] Upload naar GitHub repo (in root)
- [ ] Test op opengraph.xyz: deel `webcraftiq.be` URL → zie je de image?

### Favicon variants
- [ ] **apple-touch-icon.png** (180×180) — voor iOS bookmarks
- [ ] **favicon-32x32.png** — moderne browsers
- [ ] **favicon-192x192.png** — Android Chrome

Kan je in 5 min maken op realfavicongenerator.net.

---

## 🧪 Testen — voor lancering

- [ ] **Desktop**: open in Chrome, Firefox, Safari (Mac) of Edge (Windows)
- [ ] **Mobiel iOS**: open op iPhone (Safari + Chrome)
- [ ] **Mobiel Android**: open op Android (Chrome)
- [ ] **PageSpeed test**: pagespeed.web.dev → mobiel + desktop, mikken op 90+
- [ ] **Mobile-friendly test**: search.google.com/test/mobile-friendly
- [ ] **Werken alle links?** Klik door menu's, footer, CTA's
- [ ] **Werkt formulier?** Test echte submission
- [ ] **Werkt 404?** Ga naar webcraftiq.be/iets-wat-niet-bestaat
- [ ] **Werken redirects?** webcraftiq.be/manifest → moet naar /aanpak gaan

---

## 📣 Lanceringsdag

- [ ] **LinkedIn post** met link
- [ ] **Persoonlijke mail** naar 10 contacten met link + uitleg
- [ ] **Voltrix en Gevanti** bedanken + delen op hun social
- [ ] **Updates aan vrienden/familie** via WhatsApp
- [ ] **Eerste outreach mail** naar 5 prospects volgens je outreach playbook

---

## 🚦 Wanneer is V1 echt "live productie-klaar"?

Pas als al deze 4 minimums klaar zijn:
1. ✅ Domein webcraftiq.be is gekoppeld
2. ✅ Contactformulier werkt en stuurt mail naar info@webcraftiq.be
3. ✅ Analytics is actief
4. ✅ Search Console is actief

Pas dan kan je starten met **outreach naar prospects**.
Daarvoor: het is een staging/preview site die je intern kan testen.

---

**Volgende mijlpaal:** zie ROADMAP.md voor V1.1 en V2.0 plannen.
