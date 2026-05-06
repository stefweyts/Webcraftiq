# Webcraftiq — Changelog

Versie-geschiedenis van de Webcraftiq website. Elke versie is gebaseerd op de vorige + concrete wijzigingen.

---

## V1.0 — 6 mei 2026 ✅ LIVE

**Status:** Stabiele basis, klaar voor live productie.

### Wat zit er in V1
- ✅ 13 pagina's: home, /website-laten-maken, /aanpak, /cases, /over, /blog, 2 case studies, 1 blog post, 3 wettelijke pagina's, 404
- ✅ 2 echte cases: Voltrix (voltrix.be) + Gevanti BV (gevanti.be)
- ✅ Identiteit overal correct: Stef Weyts · BTW BE0803.343.103 · info@webcraftiq.be
- ✅ Geen fake content (geen avatar bubbels, geen verzonnen bedrijven, geen fake stats)
- ✅ Wettelijke pagina's: privacy, voorwaarden, cookies (GDPR-conform, Belgisch recht)
- ✅ Consistente navigatie op alle pagina's
- ✅ SEO geoptimaliseerd voor "website laten maken" + Belgische steden
- ✅ Schema.org JSON-LD op alle pagina's
- ✅ 21 bestanden in totaal, 104 KB ZIP

### Bekend voor V2
Lijst van dingen die kunnen verbeteren in V2 — zie `ROADMAP.md`.

---

## V0.x — pre-launch (geschiedenis)

### V0.9 — 6 mei 2026 (laatste pre-launch)
- Verwijderd: fake "Verstraeten Schilders Gent" mockup → vervangen met Voltrix
- Verwijderd: fake "JV / SD / MK" avatar bubbels in hero
- Verwijderd: fake "+38% conversielift" stats (3 plekken)
- Verwijderd: fake "12+ projecten" sector counts → vervangen met dienst-omschrijvingen
- Verwijderd: placeholder telefoonnummer +32 470 12 34 56 (3 plekken)
- Verwijderd: fake "5.0★ beoordeling" in marquee
- Gefixt: dubbele "info@webcraftiq.be" in footer (vervangen met BTW)
- Gefixt: Privacy/Voorwaarden/Cookies links waren `href="#"` → echte URLs
- Gefixt: homepage menu was anchors-only → echte links naar sub-pages
- Toegevoegd: Stef Weyts als founder + Voltrix als origin-project (/over)

### V0.8 — 5 mei 2026
- Hernoemd: /manifest → /aanpak (betere SEO + UX voor KMO doelgroep)
- Toegevoegd: /website-laten-maken landing page voor primaire keyword
- SEO optimalisatie: H1/H2 keyword-rijk, internal linking, FAQ uitgebreid

### V0.7 — 4 mei 2026
- Eerste production-ready package met 22 files
- Multi-step contactformulier
- Schema.org structured data
- Cloudflare/Netlify/Vercel deployment configs

### V0.1 - V0.6 — april/mei 2026
- Brand naming exploratie → "Webcraftiq" gekozen
- Visuele identiteit (Bricolage Grotesque + DM Sans + JetBrains Mono)
- 3 design-iteraties op homepage
- Pricing strategie: €2.495 / €4.500 / vanaf €7.995
- Belgische pricing research + conversie-onderzoek

---

## Hoe versies werken

Elke versie heeft een **marker** in de HTML:
```html
<!-- Webcraftiq v1.0 | 2026-05-06 | Stef Weyts -->
```

Deze staat bovenaan in `<head>` van elke pagina. Open je site → rechtsklik → "Bron weergeven" → je ziet meteen welke versie live staat.

---

## Naming-conventie voor versies

- **V1.0** → eerste live versie
- **V1.1, V1.2** → kleine fixes en content updates (geen design wijzigingen)
- **V2.0** → grotere wijzigingen (design refresh, nieuwe pagina's, structuur-wijzigingen)
- **V2.1, V2.2** → verbeteringen op V2

Niet elke wijziging is een nieuwe versie — alleen mijlpalen.
