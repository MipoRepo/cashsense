# CashSENSE HTML/CSS Refactor – Edistymistoraportti

## Vaihe 1: styles.css (Valmis ✅)

Lisättiin seuraavat CSS-luokat inline-tyyleille:

### Navigation
- `.nav-btn-pdf` – PDF-napin margina vasemmalla

### Hero Banner
- `.hero-banner-container` – bannerin pohja (margin, border-radius, shadow, border)
- `.hero-banner-img` – kuvan responsive tyylit

### Hero Highlight Card (jaetut molemmissa tiedostoissa)
- `.hero-highlight-card` – gradient-taustan, padding, margin
- `.hero-highlight-card--project` – project.html-erityispiirit (h3 1.5rem, p 0.95rem)
- `.hero-highlight-card-content` – sisäinen flex-sarakkeellinen järjestely
- `.hero-highlight-card h3` / `p` – perustyylit

### Features
- `.features-list` – iconit sisältävä flex
- `.feature-item` – yksittäinen ominaisuus
- `.feature-icon-gold` / `.feature-icon-green` – ✦-ikonit

### Status Badges
- `.stat-badge.status-risk` – punainen riskipilvi (korvaa hardcoded #FEF2F2/#DC2626)

### Utilities
- `.dashboard-grid--spaced`, `.card--top-spacing`
- `.mb-1`, `.mb-1-25` spacing-apu

### Index-sivun komponentit
- `.chart-legend`, `.legend-item`, `.legend-swatch`, `.legend-swatch--grey/green`, `.legend-text--em`
- `.form-range`, `.form-range-labels`, `.form-range-value`
- `.ai-insight-box`, `.ai-insight-box .ai-insight-text`
- `.table-cell--emphasis`, `.table-cell--gold`, `.table-cell--emerald`

### Project-sivun komponentit
- `.content-list`, `.body-text`, `.body-text--small`
- `.tech-list`
- `.arch-diagram`, `.arch-endpoint-box`, `.arch-arrow`, `.arch-arrow--subtle`
- `.arch-vm-box`, `.arch-vm-header`, `.arch-vm-inner`, `.arch-vm-component`, `.arch-vm-component--engine`
- `.dev-steps-grid`, `.dev-step-box`
- `.arch-pre`

## Vaihe 2: index.html ✅ käynnissä
Seuraavat tehtävät:
- [ ] Navbutton → `.nav-btn-pdf`
- [ ] Hero banner → `.hero-banner-container` + `.hero-banner-img`
- [ ] Hero highlight-card → CSS-luokka + sisältö-flex
- [ ] Features → `.features-list`, `.feature-item`, iconit
- [ ] KPI risk badge → `.stat-badge.status-risk`
- [ ] Chart legend → luokat
- [ ] Form range → `.form-range` + labelit
- [ ] AI insight box → `.ai-insight-box`
- [ ] Table → `.card--top-spacing` + table-cell-luokat
- [ ] Lisää `<main>` elementti
- [ ] Tarkista ettei ole enää `style=` attribuutteja

## Vaihe 3: project.html – vasta siellä
Seuraavat tehtävät:
- [ ] Hero komponentit → jakautuvat `.hero-highlight-card--project`
- [ ] Otsikot → h1→h2→h3 hierarkia
- [ ] Body-tekstit → `.body-text` / `.body-text--small`
- [ ] Listat → `.content-list`
- [ ] Arkkitehtuuri → `.arch-diagram`, `.arch-vm-box` jne.
- [ ] Dev-steps → `.dev-steps-grid`, `.dev-step-box`
- [ ] Pre → `.arch-pre`
- [ ] Taulukot → `.table-cell--emphasis`
- [ ] Lisää `<main>` elementti
- [ ] Poista kaikki inline-tyylit

## Vaihe 4: Vahvistus ✅ (vasta lopussa)
- [ ] Grep `style=` kaikista HTMListä → tyhjä
- [ ] Avaa selaimessa tarkistaaksesi ulkonäön
- [ ] Varmista että sivut näyttävät samalta
