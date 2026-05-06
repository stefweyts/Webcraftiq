# Webcraftiq — Changelog

Versie-geschiedenis van de Webcraftiq website. Elke versie is gebaseerd op de vorige + concrete wijzigingen.

---

## V2.0 — 6 mei 2026 ✅ ACTIEF

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
