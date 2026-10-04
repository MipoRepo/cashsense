# CashSENSE HTML/CSS Refactor – Edistymistoraportti v2.0

## Vaihe 1: styles.css ✅ Valmis
Katso todo1.0.md. Kaikki yhteiset CSS-luokat lisätty (hero, navigation, forms, tables, arch-diagram).

## Vaihe 2: index.html ✅ Valmis
- [x] Nav button → `.nav-btn-pdf`
- [x] Hero banner → `<section class="hero-banner-container">` + `.hero-banner-img`
- [x] Hero highlight card → `.hero-highlight-card` + `.hero-highlight-card-content` + `.hero-highlight-card h3/p`
- [x] Features → `.features-list`, `.feature-item`, `.feature-icon-gold/.feature-icon-green`
- [x] KPI risk badge → `.stat-badge.status-risk`
- [x] Chart legend → `.chart-legend`, `.legend-item`, `.legend-swatch--grey/green`, `.legend-text--em`
- [x] Chart subtitle → `.text-subtle`
- [x] Form range → `.form-range`, `.form-range-labels`, `.form-range-value`
- [x] AI insight box → `.ai-insight-box`, `.ai-insight-label`, `.ai-insight-text`
- [x] Simulate button → `.form-action-btn`
- [x] Table → `.card--top-spacing` + `.table-cell--emphasis/gold/emerald`
- [x] Lisätty `<main>` elementti pakkaukseksi
- [x] Grep `style=` → tyhjä (ei inline-tyylejä)

## Vaihe 3: project.html 🔄 Käynnissä
Seuraavat tehtävät:
- [ ] Nav button → `.nav-btn-pdf` (yhteinen)
- [ ] Hero banner → `.hero-banner-container` + `.hero-banner-img` (yhteinen)
- [ ] Hero highlight card → `.hero-highlight-card--project` + content (yhteinen muotoilu eri fonteilla)
- [ ] Otsikot → h1→h2→h3 hierarkia korjaus
- [ ] Body-tekstit → `.body-text` / `.body-text--small` + margina-apu
- [ ] Listat → `.content-list` + `.content-list li`
- [ ] Arkkitehtuuri → `.arch-diagram`, `.arch-endpoint-box`, `.arch-arrow`, `.arch-arrow--subtle`, `.arch-vm-box`, `.arch-vm-header`, `.arch-vm-inner`, `.arch-vm-component`, `.arch-vm-component--engine`
- [ ] Dashboard-gridin margin-bottom → `.dashboard-grid--spaced`
- [ ] Dev-steps ruudukko → `.dev-steps-grid`, `.dev-step-box`
- [ ] Pre-koodi → `.arch-pre`
- [ ] DoD-taulukko → `.table-cell--emphasis`
- [ ] Lisää `<main>` elementti
- [ ] Poista kaikki inline-tyylit (`style=`)

## Vaihe 4: Vahvistus (vasta lopussa)
- [ ] Grep `style=` kaikista HTMListä → tyhjä
- [ ] Avaa molemmat sivut selaimessa tarkistaaksesi ulkonäön
- [ ] Varmista että CSS ei aiheuta syntaksivirheitä
