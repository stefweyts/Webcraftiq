# Webcraftiq — Changelog

Versie-geschiedenis van de Webcraftiq website. Elke versie is gebaseerd op de vorige + concrete wijzigingen.

---

## V2.5 — 7 mei 2026 ✅ ACTIEF

**Status:** Drie Care-pakketten + dedicated /care pagina.

### Nieuwe pagina
- ✅ **`/care`** — volledige uitleg over 3 maandelijkse Care-pakketten
- Hero, "Waarom Care", drie tier-cards, deep-dive over update-rondes en SEO-pagina's, FAQ, CTA

### Care herzien naar 3 pakketten
- ✅ **Care Basis — €49/m** (was €45/m): hosting, security, backups, monitoring
- ✅ **Care Actief — €179/m** (NIEUW): + 2u maandelijkse content-updates + performance-rapport + prioriteit-support
- ✅ **Care Groei — €449/m** (NIEUW): + maandelijks 1 SEO-geoptimaliseerde pagina + ranking-monitoring + strategie-call
- ✅ **Allemaal verplicht** bij elke website (klant kiest welk pakket — minimum is Basis)

### Visuele wijzigingen
- ✅ Homepage Care-blok herzien naar **3 tier-mini-cards** met direct doorklik naar /care#actief
- ✅ Tier-cards op homepage tonen nu "+ Care vanaf €49/m" (was "€45/m")
- ✅ Pricing-intro verwijst naar /care voor Care-uitleg

### Updates op andere pagina's
- ✅ **/website-laten-maken**: FAQ over Care vermeldt 3 pakketten + link naar /care
- ✅ **/redesign**: Care-vermelding bijgewerkt met 3 pakketten
- ✅ **/contact**: form step 2A toont "+ Care" achter elk pakket + Care-uitleg in subtekst
- ✅ **/contact**: Care-blok onderaan vermeldt 3 prijzen + CTA naar /care

### Schema & SEO
- ✅ JSON-LD Service-schemas voor 3 Care-pakketten op /care
- ✅ Sitemap.xml bijgewerkt met /care (priority 0.9)

### Footer
- ✅ "Care" toegevoegd aan footer "Pagina's"-lijst op alle 16 pagina's

### Versie-marker
- ✅ Alle 17 pagina's bijgewerkt naar `<!-- Webcraftiq v2.5 | 2026-05-07 | Stef Weyts -->`

---

## V2.4 — 7 mei 2026

**Status:** Prijsbijstelling + cleanup balken homepage. Vervangen door V2.5.

### Pricing wijzigingen
- ✅ **Essential**: €2.999 → **€2.499** ex BTW (eenmalig)
- ✅ **Pro**: €4.999 → **€4.499** ex BTW (eenmalig)
- ✅ **Custom**: vanaf €7.500 — ongewijzigd
- ✅ **Care**: €45/maand — ongewijzigd, blijft verplicht bij elk pakket

### Visuele wijzigingen homepage
- ✅ Verwijderd: donkere marquee-balk onder de menubalk
- ✅ Verwijderd: trust-strip ("Sinds 2026 · 2 live projecten · ...")
- ✅ Hero top-padding verhoogd (160px desktop, 130px mobiel) om visuele balans te behouden

### Bijgewerkt op
- Homepage prijzensectie + tier-cards
- /website-laten-maken (prijzen + Service-schema's JSON-LD + FAQ)
- /redesign (tarieven-sectie + Care-vermelding)
- /contact (multi-step form stap 2A + pricing recap)

### Versie-marker
- ✅ Alle 16 pagina's bijgewerkt naar `<!-- Webcraftiq v2.4 | 2026-05-07 | Stef Weyts -->`

---

## V2.3 — 6 mei 2026

**Status:** Nieuwe prijzenstructuur + verplicht Care-pakket. Vervangen door V2.4.

### Pricing wijzigingen
- ✅ **Essential**: €2.495 → **€2.999** ex BTW (eenmalig)
- ✅ **Pro**: €4.500 → **€4.999** ex BTW (eenmalig)
- ✅ **Custom**: vanaf €7.995 → **vanaf €7.500** ex BTW (eenmalig)
- ✅ **Webcraftiq Care**: €45/maand ex BTW — **verplicht inbegrepen bij elk pakket**

### Nieuwe Care-positionering
Care vervangt het oude "optioneel maandcontract van €79". Nu één duidelijk verhaal:
- **Wat zit erin**: hosting (Cloudflare), SSL, daily backups (30d historiek), security-updates, 24/7 monitoring
- **Wat NIET inbegrepen**: content-aanpassingen of nieuwe pagina's → apart aan €85/u ex BTW
- **Verplicht**: bij elk pakket, geen losse hosting mogelijk

### Visuele wijzigingen
- ✅ **Homepage**: nieuwe Care-blok met donker amber-gloed onder de tier-cards (4 features: Hosting, Security, Backups, Monitoring)
- ✅ **Tier-cards**: elke kaart toont nu prominent "+ €45/m Care" als amber pill
- ✅ **Pricing-intro**: gewijzigd naar "Eén vaste prijs. Care inbegrepen."
- ✅ **/website-laten-maken**: prijzen + Service-schema (JSON-LD) bijgewerkt + FAQ over Care
- ✅ **/redesign**: prijzen bijgewerkt + Care-vermelding in tarieven-sectie
- ✅ **/contact**: pricing recap + multi-step form (stap 2A) bijgewerkt + Care-blok onderaan

### FAQ updates
- ✅ Op homepage en /website-laten-maken: FAQ over support/onderhoud volledig herschreven naar Care-positionering
- ✅ Verwijderd: oude tekst "twee opties: zelfstandig hosten of maandcontract"

### Versie-marker
- ✅ Alle 16 pagina's bijgewerkt naar `<!-- Webcraftiq v2.3 | 2026-05-06 | Stef Weyts -->`

---

## V2.2 — 6 mei 2026

**Status:** Dedicated /contact pagina met multi-step formulier. Vervangen door V2.3.

### Nieuwe features
- ✅ **Nieuwe `/contact` pagina** — alle CTA's leiden hier naartoe
- ✅ **Multi-step formulier** met conditionele branching:
  - **Stap 1**: Type project (Nieuwe website / Redesign / Anders)
  - **Stap 2A** (nieuw): Pakket-voorkeur (Essential €2.495 / Pro €4.500 / Custom / weet niet)
  - **Stap 2B** (redesign): Wat werkt niet? (multi-select: geen leads / verouderd / mobiel / plug-ins / SEO / weet niet)
  - **Stap 2C** (anders): Vrije omschrijving
  - **Stap 3**: Project-details (bedrijf, sector, huidige URL, tijdlijn, beschrijving)
  - **Stap 4**: Contactgegevens (naam, e-mail, telefoon, GDPR)
- ✅ **Pricing recap** onderaan /contact (zelfde 3 pakketten als homepage)
- ✅ **JSON-LD ContactPage schema** op /contact
- ✅ **Honeypot field** tegen spam
- ✅ **Inline validatie** met Nederlandstalige errors
- ✅ **Personaliseerde succesmelding** met voornaam

### Wijzigingen
- ✅ **Menu-CTA** "Plan een call" → "Contacteer ons" (alle 15 pagina's)
- ✅ **Alle CTA's** leiden nu naar `/contact` ipv `#contact` of mailto
- ✅ **Homepage formulier verwijderd** — vervangen met korte teaser-CTA "Vraag vrijblijvend een voorstel aan"
- ✅ **Prijzen blijven op homepage** (`#pricing` anchor) en zijn ook beschikbaar op /contact
- ✅ **Footer "Pagina's"** krijgt /contact-link op alle 13 pagina's

### Formspree integratie
- ⏳ **Formulier verstuurt nog niet** — placeholder `JOUW_FORMSPREE_ID` in `<form action>`
- ⏳ Bij submit toont het succes-state na 600ms (preview-modus)
- ⏳ **TODO**: Stef levert Formspree-ID, dan wordt het echt verstuurd

### Versie-marker
- ✅ Alle 15 pagina's bijgewerkt naar `<!-- Webcraftiq v2.2 | 2026-05-06 | Stef Weyts -->`

---

## V2.1 — 6 mei 2026

**Status:** Mobile menu fix. Vervangen door V2.2.

### Critical fix
- ✅ **Hamburger-menu** toegevoegd op alle 14 pagina's — was kritieke bug in V2.0 waardoor mobile users vastgepind zaten op de homepage
- ✅ Volledig-scherm overlay met grote tikbare links (26px font)
- ✅ Geanimeerde hamburger ↔ X transitie
- ✅ Staggered fade-in van menu-items
- ✅ Sluit op link-klik én Escape-toets
- ✅ Body-scroll lock wanneer menu open
- ✅ Toegankelijk: ARIA labels, focus management, keyboard navigation
- ✅ Mobile menu toont contact info onderaan (info@webcraftiq.be · BTW · Antwerpen)

### Versie-marker
- ✅ Alle 15 pagina's bijgewerkt naar `<!-- Webcraftiq v2.1 | 2026-05-06 | Stef Weyts -->`

---

## V2.0 — 6 mei 2026

**Status:** Volledige IA-restructure + nieuwe redesign-pagina + structured data.

### Nieuwe features
- ✅ **Nieuw menu** op alle 13 pagina's: Onze aanpak / Website laten maken / Redesign / Portfolio / Over ons + CTA "Plan een call"
- ✅ **Nieuwe `/redesign` pagina** — lead magnet met "gratis website-audit" als CTA
  - Eigen content: 5 herkenbare klachten, 4-stap aanpak, wat we wel/niet migreren, FAQ
  - Verwijst naar homepage `#pricing` voor tarieven
  - Mailto-CTA met voorgevulde audit-aanvraag
- ✅ **Nieuwe blog post** `/blog/website-geen-visitekaartje` — manifesto als echt artikel met author, datePublished, Article schema
- ✅ **Trust-strip** onder marquee op homepage: "Sinds 2026 · 2 live projecten · Vaste prijs vanaf €2.495 · BTW BE0803.343.103"
- ✅ **Redesign-promo sectie** op homepage tussen hero en portfolio

### Structured data
- ✅ **Organization schema** sitewide op alle 13 pagina's
- ✅ **Person schema** (Stef Weyts) op `/over`
- ✅ **3x Service schema** op `/website-laten-maken` (Essential €2.495, Pro €4.500, Custom €7.995)
- ✅ **Service schema** op `/redesign` (gratis audit)
- ✅ **BreadcrumbList** op `/cases`, `/cases/voltrix`, `/cases/gevanti`, `/blog`, `/blog/website-geen-visitekaartje`
- ✅ **Article schema** op blog posts

### IA & Navigation
- ✅ Menu-labels gewijzigd: "Werk" → "Portfolio", "Aanpak" → "Onze aanpak", "Over" → "Over ons"
- ✅ "Plan een call" als CTA-tekst (was "Start project")
- ✅ Footer "Pagina's"-sectie geconsolideerd met alle 7 hoofdpagina's
- ✅ `/aanpak` blijft `/aanpak` (bewust niet hernoemd naar `/werkwijze` — SEO continuiteit)
- ✅ `/website-laten-maken` blijft `/website-laten-maken` (bewust niet hernoemd naar `/pakketten` — top SEO keyword)

### Redirects opschoning
- ✅ `_redirects` minimaal gehouden: alleen 4 essentiële redirects
- ✅ Verwijderd: problematische `/aanpak/ /aanpak 301` regel die conflict gaf met Cloudflare routing
- ✅ Verwijderd: alle www-redirect regels (Cloudflare doet dit zelf)

### Content cleanup
- ✅ Coming-soon blog posts: 1 verwijderd, 1 herschreven naar "Komt er aan"
- ✅ Featured blog post linkt nu naar `/blog/website-geen-visitekaartje` ipv `/aanpak`
- ✅ Sitemap geüpdatet met `/redesign` en nieuwe blog post

### Versie-marker
- ✅ Alle 13 pagina's bijgewerkt naar `<!-- Webcraftiq v2.0 | 2026-05-06 | Stef Weyts -->`

---

## V1.0 — 6 mei 2026 (vorige stabiele versie)

**Status:** Eerlijke basis zonder fake content. Vervangen door V2.0.

### Wat zat in V1
- 13 pagina's: home, /website-laten-maken, /aanpak, /cases, /over, /blog, 2 case studies, 1 blog post, 3 wettelijke pagina's, 404
- 2 echte cases: Voltrix (voltrix.be) + Gevanti BV (gevanti.be)
- Identiteit: Stef Weyts · BTW BE0803.343.103 · info@webcraftiq.be
- Geen fake content (geen avatar bubbels, geen verzonnen bedrijven, geen fake stats)
- Wettelijke pagina's: privacy, voorwaarden, cookies (GDPR-conform, Belgisch recht)
- Consistente navigatie op alle pagina's
- SEO geoptimaliseerd voor "website laten maken" + Belgische steden

---

## V0.x — pre-launch (geschiedenis)

### V0.9 — 6 mei 2026 (laatste pre-V1)
- Verwijderd: fake "Verstraeten Schilders Gent" mockup → vervangen met Voltrix
- Verwijderd: fake "JV / SD / MK" avatar bubbels in hero
- Verwijderd: fake "+38% conversielift" stats (3 plekken)
- Verwijderd: fake "12+ projecten" sector counts
- Verwijderd: placeholder telefoonnummer +32 470 12 34 56
- Verwijderd: fake "5.0★ beoordeling" in marquee
- Gefixt: dubbele "info@webcraftiq.be" in footer
- Gefixt: Privacy/Voorwaarden/Cookies links waren `href="#"`
- Gefixt: homepage menu was anchors-only → echte links

### V0.8 — 5 mei 2026
- Hernoemd: /manifest → /aanpak (betere SEO)
- Toegevoegd: /website-laten-maken landing page voor primaire keyword
- SEO optimalisatie: H1/H2 keyword-rijk, internal linking

### V0.1 - V0.7 — april/mei 2026
- Brand naming exploratie → "Webcraftiq" gekozen
- Visuele identiteit (Bricolage Grotesque + DM Sans + JetBrains Mono)
- 3 design-iteraties op homepage
- Pricing strategie: €2.495 / €4.500 / vanaf €7.995

---

## Hoe versies werken

Elke versie heeft een **marker** in de HTML:
```html
<!-- Webcraftiq v2.0 | 2026-05-06 | Stef Weyts -->
```

Deze staat bovenaan in `<head>` van elke pagina. Open je site → rechtsklik → "Bron weergeven" → je ziet meteen welke versie live staat.

---

## Naming-conventie voor versies

- **V1.0** → eerste stabiele eerlijke versie
- **V2.0** → IA restructure + nieuwe Redesign-pagina + structured data
- **V2.x** → kleine fixes en content updates op V2
- **V3.0** → grote wijzigingen (Astro migratie, CMS, multi-language)

Niet elke wijziging is een nieuwe versie — alleen mijlpalen.
