# 🚀 Webcraftiq Launch Handleiding

**Versie**: V2.14.2  
**Datum**: 11 mei 2026  
**Domein**: webcraftiq.be

---

## ✅ PRE-LAUNCH CHECKLIST

### Stap 1: Domein registratie

- [ ] Registreer **webcraftiq.be** bij een Belgische registrar:
  - **Combell** (aanbevolen, Belgisch) — €13/jaar
  - **OpenProvider** — €11/jaar
  - **Cloudflare Registrar** — kostprijs ~€10/jaar (geen markup)

### Stap 2: Cloudflare setup

1. [ ] Maak gratis Cloudflare account aan: https://dash.cloudflare.com/sign-up
2. [ ] Add Site → enter `webcraftiq.be`
3. [ ] Volg de instructies om je nameservers te wijzigen bij je registrar
4. [ ] Wacht 10-60 minuten voor DNS-propagation
5. [ ] In Cloudflare → SSL/TLS → instellen op **"Full"** (NIET "Flexible")

### Stap 3: Cloudflare Pages deploy

1. [ ] Cloudflare Dashboard → Workers & Pages → Create application
2. [ ] Connect Git → koppel je `stefweyts/webcraftiq` GitHub-repo
3. [ ] Configure build:
   - Build command: *(leeg)*
   - Build output directory: `/`
4. [ ] Deploy → wacht 30-60 seconden
5. [ ] Custom domains → Add custom domain → `webcraftiq.be`
6. [ ] Voeg ook `www.webcraftiq.be` toe (Cloudflare regelt 301-redirect)

### Stap 4: Verifieer dat alles werkt

Open in browser en check:
- [ ] https://webcraftiq.be → laadt homepage
- [ ] https://www.webcraftiq.be → redirect naar webcraftiq.be
- [ ] https://webcraftiq.be/cases → werkt
- [ ] https://webcraftiq.be/care → werkt
- [ ] https://webcraftiq.be/sitemap.xml → toont XML
- [ ] https://webcraftiq.be/robots.txt → toont robots
- [ ] https://webcraftiq.be/og-image.jpg → laadt OG image
- [ ] https://webcraftiq.be/favicon.ico → laadt favicon
- [ ] Browser tab toont Webcraftiq icon

---

## 🔍 GOOGLE SEARCH CONSOLE SETUP

### Stap 1: Property toevoegen

1. [ ] Ga naar https://search.google.com/search-console
2. [ ] Add Property → kies **"Domain"** (recommended, vangt zowel webcraftiq.be als www.webcraftiq.be)
3. [ ] Verifieer via **DNS record** (Cloudflare):
   - Search Console geeft je een TXT-record
   - Cloudflare → DNS → Add record → Type: TXT → Name: `@` → Content: *plak waarde*
   - Save & terug naar Search Console → click "Verify"

### Stap 2: Sitemap indienen

1. [ ] Search Console → Sitemaps (left menu)
2. [ ] Enter sitemap URL: `sitemap.xml`
3. [ ] Submit → wacht op "Success" status (kan 1-2 dagen duren voor indexering begint)

### Stap 3: Request indexing voor cruciale pagina's

Voor sneller indexering (handmatig per pagina):

1. [ ] Top zoekbalk in Search Console → enter URL: `https://webcraftiq.be/`
2. [ ] Klik "REQUEST INDEXING"
3. [ ] Herhaal voor:
   - https://webcraftiq.be/website-laten-maken
   - https://webcraftiq.be/redesign
   - https://webcraftiq.be/cases/voltrix
   - https://webcraftiq.be/cases/gevanti
   - https://webcraftiq.be/care
   - https://webcraftiq.be/contact

### Stap 4: Performance monitoring

Na 2-4 weken kun je in Search Console zien:
- Welke zoektermen leiden naar je site
- Click-through rates per pagina
- Indexering status van alle pagina's
- Mogelijke crawling issues

---

## 🔍 BING WEBMASTER TOOLS (optioneel maar aanbevolen)

Bing wordt vaak vergeten, maar dekt ~10% van Belgische searches:

1. [ ] Ga naar https://www.bing.com/webmasters
2. [ ] Add site → enter `https://webcraftiq.be`
3. [ ] **Snel pad**: "Import from Google Search Console" → automatische sync
4. [ ] Of: verifieer via DNS record (zelfde procedure als Google)
5. [ ] Sitemap submitten: `sitemap.xml`

---

## 📱 SOCIAL MEDIA META-CHECKS

### Test Open Graph previews

Voordat je promo's deelt, test hoe je site eruitziet op social media:

- [ ] **Facebook/LinkedIn**: https://developers.facebook.com/tools/debug → enter `https://webcraftiq.be`
- [ ] **Twitter/X**: https://cards-dev.twitter.com/validator → enter `https://webcraftiq.be`
- [ ] **LinkedIn**: https://www.linkedin.com/post-inspector → enter `https://webcraftiq.be`

Verwacht resultaat: OG image (1200x630) verschijnt + title + description.

---

## 📊 ANALYTICS SETUP

### Optie 1: Plausible Analytics (privacy-friendly, aanbevolen)

1. [ ] Account: https://plausible.io (€9/mo) of self-hosted
2. [ ] Add site `webcraftiq.be`
3. [ ] Snippet toevoegen aan `<head>` van alle pagina's:
   ```html
   <script defer data-domain="webcraftiq.be" src="https://plausible.io/js/script.js"></script>
   ```
4. [ ] Voordeel: GDPR-compliant zonder cookie-banner nodig

### Optie 2: Google Analytics 4 (gratis)

1. [ ] https://analytics.google.com → Create property
2. [ ] Voeg snippet toe aan `<head>`:
   ```html
   <script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
   <script>
     window.dataLayer = window.dataLayer || [];
     function gtag(){dataLayer.push(arguments);}
     gtag('js', new Date());
     gtag('config', 'G-XXXXXXXXXX');
   </script>
   ```
3. [ ] **LET OP**: GA4 vereist cookie consent banner — je hebt al `cookies.html` maar moet GA4 expliciet toevoegen aan cookie-policy

---

## 🏢 GOOGLE BEDRIJFSPROFIEL (cruciaal voor lokale SEO)

Vakmannen zoeken op "webdesigner Antwerpen" — daar wil je in Google Maps verschijnen:

1. [ ] Ga naar https://business.google.com
2. [ ] Add business → Webcraftiq
3. [ ] Categorie: **"Web Designer"** + secondair "Webdesign Agency"
4. [ ] Adres: jouw zakelijk adres in Antwerpen
5. [ ] Telefoonnummer + website (webcraftiq.be)
6. [ ] Beschrijving: gebruik onderstaande tekst (zie hieronder)
7. [ ] Upload 10+ foto's: logo, je werkplek, Voltrix-screenshot, Gevanti-screenshot, jezelf
8. [ ] Verifieer (kaartje per post, kan 1 week duren)
9. [ ] Vraag Voltrix-eigenaar om een Google review zodra geverifieerd

### GBP Beschrijving (gebruik dit):

> Webcraftiq is een premium webdesign-bureau uit Antwerpen, gespecialiseerd in custom websites voor Belgische KMO's. We bouwen sites die meer doen dan goed eruitzien — multi-step formulieren, prijs-calculators, CRM-integraties en Google Bedrijfsprofiel-koppelingen die je werk uit handen nemen en leads opleveren. Vaste prijzen vanaf €2.499. Custom HTML zonder WordPress-overhead. Geen verrassingen achteraf. Werkend in heel Vlaanderen — Antwerpen, Gent, Brussel, Hasselt en daarbuiten.

---

## 📋 META DESCRIPTIONS PER PAGINA (REFERENTIE)

Hier de complete lijst van titels + meta descriptions zoals ze nu staan. Gebruik deze als referentie voor Search Console of als je later iets wil aanpassen.

### Homepage
- **URL**: https://webcraftiq.be/
- **Title** (51c): Webcraftiq · Premium webdesign voor Belgische KMO's
- **Description** (135c): Premium websites op maat voor Belgische KMO's. Custom code, multi-step offerteformulieren, vaste prijs vanaf €2.499. Klaar in 14 dagen.

### Website laten maken
- **URL**: https://webcraftiq.be/website-laten-maken
- **Title** (55c): Website laten maken in België vanaf €2.499 | Webcraftiq
- **Description** (155c): Website laten maken voor je KMO in België? Custom code, multi-step formulier, vaste prijs vanaf €2.499. Klaar in 14 dagen. Voor heel Vlaanderen en Brussel.

### Redesign
- **URL**: https://webcraftiq.be/redesign
- **Title** (61c): Redesign · Bestaande website opnieuw laten maken | Webcraftiq
- **Description** (164c): Je bestaande website werkt niet — geen leads, traag op mobiel, oogt verouderd? Krijg een gratis website-audit van Webcraftiq en een redesign-voorstel binnen 48 uur.

### Aanpak
- **URL**: https://webcraftiq.be/aanpak
- **Title** (60c): Onze aanpak · Een website is geen visitekaartje | Webcraftiq
- **Description** (133c): Waarom een mooie website alleen niet genoeg is. Een website moet werken: leads binnenhalen, werk automatiseren. De Webcraftiq aanpak.

### Care
- **URL**: https://webcraftiq.be/care
- **Title** (64c): Webcraftiq Care · Maandelijks onderhoud & SEO-groei | Webcraftiq
- **Description** (194c): Drie maandelijkse Care-pakketten voor je Webcraftiq website. Hosting, updates, SEO-groei en Google Bedrijfsprofiel-beheer vanaf €49/maand. Eén partij, één factuur, geen losse hosting-rekeningen.

### Contact
- **URL**: https://webcraftiq.be/contact
- **Title** (38c): Contact · Plan je project | Webcraftiq
- **Description** (152c): Klaar om je website te laten maken of bestaande site te laten herbouwen? Vul het formulier in en je krijgt binnen 24u een persoonlijk antwoord van Stef.

### Over
- **URL**: https://webcraftiq.be/over
- **Title** (56c): Over Webcraftiq · Premium webdesign agency uit Antwerpen
- **Description** (160c): Wie is Webcraftiq? Een Belgisch webdesign-bureau dat sites bouwt voor KMO's die meer willen dan een visitekaartje. Custom code, vaste prijs, 14 dagen levertijd.

### Cases (portfolio)
- **URL**: https://webcraftiq.be/cases
- **Title** (52c): Werk · Webcraftiq Portfolio | Belgische KMO websites
- **Description** (145c): Bekijk onze portfolio: premium websites op maat voor installateurs, restaurants, ateliers, architecten en B2B consultants in België. Echte cases.

### Voltrix case study
- **URL**: https://webcraftiq.be/cases/voltrix
- **Title** (33c): Voltrix · Case Study | Webcraftiq
- **Description** (186c): Hoe we voor Voltrix — elektricien Antwerpen — een slim multi-step formulier bouwden dat zich aanpast per dienst. Resultaat: complete intakes, geen mailpingpong, offertes op dezelfde dag.

### Gevanti case study
- **URL**: https://webcraftiq.be/cases/gevanti
- **Title** (36c): Gevanti BV · Case Study | Webcraftiq
- **Description** (152c): Hoe we voor Gevanti BV — maatwerk keukens en interieur in provincie Antwerpen — een visuele portfolio-website ontwikkelden die het ambacht laat spreken.

### Blog (overzicht)
- **URL**: https://webcraftiq.be/blog
- **Title** (55c): Blog · Webcraftiq | Inzichten over webdesign voor KMO's
- **Description** (143c): Praktische inzichten over webdesign, conversie en SEO voor Belgische KMO's. Geschreven voor zaakvoerders die meer uit hun website willen halen.

### Blog: Multi-step vs klassiek
- **URL**: https://webcraftiq.be/blog/multi-step-formulier-vs-klassiek
- **Title** (62c): Multi-step formulier vs klassiek contactformulier · Webcraftiq
- **Description** (180c): Waarom een gestructureerd multi-step formulier 3-5x meer (en betere) leads oplevert dan een klassiek tekstvak. Onderbouwd met cijfers uit conversie-onderzoek en Belgische praktijk.

### Blog: Website werkpaard
- **URL**: https://webcraftiq.be/blog/website-geen-visitekaartje
- **Title** (73c): Een website is geen visitekaartje, het is een werkpaard | Webcraftiq Blog
- **Description** (156c): Waarom 9 van de 10 KMO-websites in België falen — en wat een site écht moet doen om je business vooruit te helpen. Een uitgebreide manifesto van Webcraftiq.

### Privacy
- **URL**: https://webcraftiq.be/privacy
- **Title** (26c): Privacybeleid · Webcraftiq
- **Description** (129c): Privacybeleid van Webcraftiq — hoe we persoonsgegevens verwerken in overeenstemming met de GDPR en de Belgische privacywetgeving.

### Voorwaarden
- **URL**: https://webcraftiq.be/voorwaarden
- **Title** (33c): Algemene Voorwaarden · Webcraftiq
- **Description** (100c): Algemene voorwaarden van Webcraftiq — voor webdesign opdrachten en samenwerking met Belgische KMO's.

### Cookies
- **URL**: https://webcraftiq.be/cookies
- **Title** (25c): Cookiebeleid · Webcraftiq
- **Description** (145c): Cookiebeleid van Webcraftiq — welke cookies we gebruiken, waarvoor en hoe je je voorkeuren beheert. Conform de Belgische cookiewetgeving en GDPR.

---

## 🎯 POST-LAUNCH WEEK 1 ACTIES

### Direct (binnen 24u)
- [ ] Cloudflare deployment werkt op webcraftiq.be
- [ ] SSL-certificaat actief (groen slotje in browser)
- [ ] Alle pagina's bereikbaar
- [ ] OG images verschijnen bij delen op WhatsApp/LinkedIn
- [ ] Form-submit getest (Formspree of waar je hosting voor formulieren regelt)

### Binnen week 1
- [ ] Search Console + Bing Webmaster Tools setup compleet
- [ ] Sitemap submitted bij beide
- [ ] Google Bedrijfsprofiel aangevraagd (verificatie-kaart komt 1-2 weken)
- [ ] Plausible of GA4 analytics actief
- [ ] Eerste warme klant-introducties verstuurd

### Binnen maand 1
- [ ] Google Bedrijfsprofiel verifieerd + 10+ foto's geupload
- [ ] Voltrix-eigenaar gevraagd om Google review + LinkedIn-recommendation
- [ ] LinkedIn post over Voltrix case study
- [ ] 30 cold outreach mails verstuurd
- [ ] 3-5 echte verkoop-gesprekken gevoerd

---

## 🐛 TROUBLESHOOTING

### "Site werkt niet na DNS-wijziging"
- Wacht 1-2 uur voor volledige DNS-propagation
- Test met `dig webcraftiq.be` (Mac/Linux) of `nslookup webcraftiq.be`
- Check Cloudflare DNS records: A record `@` → `192.0.2.1` (placeholder, Pages regelt dit) of CNAME records voor Pages

### "OG image verschijnt niet op LinkedIn"
- Test in https://www.linkedin.com/post-inspector
- Klik "Inspect" — LinkedIn cached oude versies, gebruik "Refresh" button
- Verifieer `og:image` URL accessible: open `https://webcraftiq.be/og-image.jpg` direct

### "Google indexeert mijn site niet"
- Indexering kan 1-7 dagen duren na sitemap submission
- Check Coverage report in Search Console voor errors
- Force indexing via "URL Inspection" → "Request indexing"

### "Site is traag"
- Cloudflare Pages biedt CDN globally — automatisch snel
- Check Lighthouse score: open in Chrome → DevTools → Lighthouse → "Generate report"
- Target: 90+ score voor Performance + 100 voor SEO

---

## 📞 NA LAUNCH — WAT TE DOEN

Je site staat live. **Stop met aanpassen.** Begin met **verkopen**.

1. Bel de 5+ warme contacten deze week
2. Zet Webcraftiq Google Bedrijfsprofiel op (1 uurtje werk = 5+ leads/jaar mogelijk)
3. Vraag Voltrix-eigenaar voor 2 introducties
4. Voer 10 echte verkoop-gesprekken voor je pricing wijzigt

De site is een **tool**, niet het doel. Verkoop is het doel.

Veel succes, Stef. 🎯
