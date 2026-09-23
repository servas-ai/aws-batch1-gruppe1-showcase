# Megaprompt Pro: bamou ERP Single-File One-Shot

> **Ziel:** Vollständiges, hochmodernes B2B-ERP-System für österreichische KMU in einer einzigen `index.html`.  
> **Brand:** bamou · `#4fc17e` · Inter · Slate-950 UI

```markdown
Baue ein vollständiges, hochmodernes und interaktives B2B-ERP-System für zukunftsorientierte KMU als eigenständige, produktionsreife Single-File-Webanwendung (`index.html`).

### 0. Verlinkte Live-Assets & Referenzen (GitHub & CDN)
- **GitHub Repository:** https://github.com/servas-ai/aws-batch1-gruppe1-showcase
- **Live Referenz-Implementierung:** https://servas-ai.github.io/aws-batch1-gruppe1-showcase/apps/bamou-erp.html
- **Vollständiger Quellcode (GitHub Raw):** https://raw.githubusercontent.com/servas-ai/aws-batch1-gruppe1-showcase/master/apps/bamou-erp.html
- **Offizielle Startup-Website:** https://bamou.at
- **Offizielles SVG-Logo Asset:** https://bamou.at/assets/bamou-logo-BKZjl5i1.svg
- **CSS Framework (CDN):** https://cdn.tailwindcss.com
- **Icons (CDN):** https://unpkg.com/lucide@latest
- **Charts Engine (CDN):** https://cdn.jsdelivr.net/npm/chart.js
- **Google Fonts (CDN):** https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500;600&display=swap

---

### 1. bamou Brand Identity & Design System
Die gesamte Anwendung muss zu 100 % in der visuellen Identität, Typografie und Tonalität der Marke **bamou** gehalten sein (Claim: *"Zettel, Tabellen und Post-its – Digitalisierung sieht anders aus"*):
- **Brand Tokens:**
  - Primary: `#4fc17e` (bamou Mint-Grün), Hover: `#41a86b`, Accent Subtle: `rgba(79, 193, 126, 0.08)`
  - Background: `#fcfdfd`, Karten `#ffffff`, Sidebar in Deep Slate `#0f172a`, Borders `#e8ecef`
  - Typography: Google Font `Inter` (`font-sans`), Tabular Figures (`font-mono` für Beträge/IBANs)
- **Original 3-Säulen-Logo (Inline-SVG):**
  `<svg viewBox="0 0 552 552"><rect x="0" y="0" width="97" height="551" rx="48.5" fill="#4fc17e"/><rect x="227" y="0" width="97" height="551" rx="48.5" fill="#4fc17e"/><rect x="454" y="0" width="97" height="551" rx="48.5" fill="#4fc17e"/></svg>`

---

### 2. Module & Funktionalitäten
1. **Dashboard:** KPIs (Monatsumsatz, Offene Posten, Verrechenbare Stunden, Bankguthaben), Chart.js 6-Monats-Umsatzverlauf in `#4fc17e`, Aktivitäts-Feed.
2. **Faktura / Rechnungen:** Rechnungsliste mit Status-Pills (`Bezahlt`, `Offen`, `Überfällig`), 1-Klick-Statuswechsel, Druck- und PDF-Vorschau (DIN-A4 mit Firmenkopf, UID, 20% USt nach österr. UStG, Bankverbindung) via `window.print()`.
3. **Kunden / CRM:** Tabelle mit UID-Nummer (ATU...), Ansprechpartnern, offenem Saldo und Neuanlage-Modal.
4. **Projekt-Zeiterfassung:** Integriertes Timer-Widget (Start/Stopp), manuelle Schnellerfassung, Projektzuordnung.
5. **BMD-Export:** 1-Klick-Download einer buchungsfertigen CSV-Datei für Steuerberater (BMD NTCS Buchungszeilen).
6. **Persistenz:** Volle `localStorage`-Persistenz aller Änderungen + Vorbefüllung mit realistischen Demodaten.

Gib die vollständige, sofort lauffähige `index.html` ohne Auslassungen in einem einzigen Codeblock aus.
```
