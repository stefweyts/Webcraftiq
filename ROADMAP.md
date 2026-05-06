# Webcraftiq — Roadmap

Wat er kan verbeteren na V1, georganiseerd op prioriteit.

---

## 🔥 V1.1 — Direct na launch (deze week)

### Externe afhankelijkheden — JIJ moet doen
- [ ] **Domein registreren**: webcraftiq.be (~€15/jaar bij combell.be of gandi.net)
- [ ] **Domein koppelen** aan Cloudflare Pages (Custom domains in dashboard)
- [ ] **Contactformulier koppelen** aan Formspree (vervang `JOUW_FORMSPREE_ID` in `index.html`)
- [ ] **Calendly link** instellen voor "Plan intake-call" knoppen
- [ ] **Google Search Console** account aanmaken + sitemap submitten
- [ ] **Plausible Analytics** of **Google Analytics 4** toevoegen (voor data!)
- [ ] **OG-image** maken (1200×630px in Canva) → uploaden als `og-image.jpg`

### Content — klein maar zichtbaar
- [ ] **Inconsistente prijsformatting** fixen: `€2.495` vs `€ 2.495` → één keuze (`€ 2.495` is Belgisch standaard)
- [ ] **Apple touch icon** — 180×180 PNG voor iOS bookmark
- [ ] **Favicon PNG** — 512×512 voor moderne browsers (nu alleen SVG)

---

## 🎨 V2.0 — Visuele optimalisatie (volgende stap)

Dit was je oorspronkelijke vraag waar we nog niet aan toegekomen zijn.

### Hero opschonen
- [ ] **Te druk** — 6 elementen onder elkaar (badge, H1, hero-zin, 2 CTA's, trust-line, mockup, stats). Verminderen tot 3-4.
- [ ] Hero-mockup mobiel: nu te klein/te complex voor smartphone schermen
- [ ] CTA-buttons op mobiel: te smal? Test op iPhone SE (375px breed)

### Mobiele optimalisaties
- [ ] **H1 typografie**: `clamp(2.8rem, 8vw, 6rem)` is te aggressief op smalle schermen — minimum verhogen naar `2.2rem`
- [ ] **Hero padding**: 80px verticaal is te veel op mobiel — 50-60px is genoeg
- [ ] **Pricing kaarten**: stapelen ze goed boven elkaar? Check op iPhone & Android
- [ ] **Marquee**: leesbaarheid op mobiel checken
- [ ] **Cases-mockups in homepage**: zijn ze leesbaar op smartphone?

### Layout consistency
- [ ] **Sectie-spacing**: niet alle secties hebben dezelfde verticale ruimte
- [ ] **Container max-widths**: harmoniseren tussen `container` en `container-narrow`
- [ ] **Border-radius** harmoniseren: nu mix van 12px, 14px, 16px, 18px, 22px

---

## 📈 V2.x — Conversie optimalisatie (na eerste data)

Pas zinvol als je analytics hebt en weet hoe bezoekers zich gedragen.

### A/B test kandidaten
- [ ] Hero H1 varianten: "Een website laten maken" vs "Premium webdesign" vs "Websites die werken"
- [ ] Pricing tier order: Essential-Pro-Custom of Pro-Essential-Custom (Pro centraal)
- [ ] CTA-tekst: "Plan een intake-call" vs "Vraag offerte aan" vs "Start project"

### Nieuwe content
- [ ] **2-3 extra blog posts** (bv. "WordPress vs custom code voor KMO's", "Wat kost een website in 2026?")
- [ ] **Voltrix case study** uitbreiden met meer details + screenshots
- [ ] **Gevanti case study** uitbreiden
- [ ] **Tweede case** zodra een derde klant binnen is

### Features die conversie kunnen verhogen
- [ ] **Live chat widget** (Intercom/Crisp) — pas zinvol als je tijd hebt om snel te reageren
- [ ] **Exit-intent popup** met "Krijg een gratis website-audit"
- [ ] **Sticky CTA** op mobiel onderaan scherm

---

## 🚀 V3.0 — Schaal-features (over 3-6 maanden)

Pas relevant als de business groeit.

- [ ] **CMS integratie** (Sanity of Tina) — zodat je zelf blog posts en cases kan toevoegen zonder HTML
- [ ] **Migratie naar Astro** — als je portfolio groeit naar 10+ cases
- [ ] **Multi-language** (FR/EN versies) — voor Brusselse en internationale klanten
- [ ] **Klantportaal** — waar klanten projectstatus kunnen checken

---

## 🐛 Bekende issues (laag prioriteit)

- [ ] OG-image bestaat niet (alleen referentie in meta-tags) — link previews op WhatsApp/LinkedIn zien er nu kaal uit
- [ ] Apple touch icon ontbreekt (iOS gebruikers krijgen geen mooie bookmark icon)
- [ ] Op `/cases/voltrix` en `/cases/gevanti` zijn de mockups misschien te abstract — echte screenshots zouden sterker zijn

---

## ✅ Manier van werken

**Bij elke wijziging:**
1. Versie-marker bijwerken in HTML (`<!-- Webcraftiq vX.X | DATUM -->`)
2. CHANGELOG.md updaten met wat er gewijzigd is
3. Deployen via GitHub
4. Testen op pc + mobiel (incognito!)

**Niet doen:**
- Direct code wijzigen op GitHub-website (zonder lokaal te testen)
- Meerdere wijzigingen tegelijk zonder ze te taggen in changelog
- Vergeten te checken of versie-marker is bijgewerkt

---

**Versie van deze roadmap:** opgesteld bij V1.0 launch (6 mei 2026)
