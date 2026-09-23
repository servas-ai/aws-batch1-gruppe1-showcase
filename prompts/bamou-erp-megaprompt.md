# Megaprompt Pro: bamou ERP Single-File One-Shot

> **Ziel:** Vollständiges, hochmodernes B2B-ERP-System für österreichische KMU in einer einzigen `index.html`.  
> **Brand:** bamou (https://bamou.at) · `#4fc17e` · Inter · Slate-950 UI

```markdown
Baue ein vollständiges, hochmodernes und interaktives B2B-ERP-System für zukunftsorientierte KMU als eigenständige, produktionsreife Single-File-Webanwendung (`index.html`).

Die gesamte Anwendung muss zu 100 % in der visuellen Identität, Typografie und Tonalität der Marke **bamou** (https://bamou.at) gehalten sein – getreu dem Markenversprechen: 
*"Zettel, Tabellen und Post-its – Digitalisierung sieht anders aus."* 

### 1. Design & Tokens
- Primary Color: `#4fc17e` (bamou Mint-Grün), Hover: `#41a86b`, Accent Subtle: `rgba(79, 193, 126, 0.1)`
- Background: `#fcfdfd` mit weißem Card-Layer und Sidebar in Deep Slate `#0f172a`
- Typography: Inter (`font-sans`), Tabular Figures (`font-mono` für Beträge/IBANs)
- Original 3-Säulen-Logo (SVG):
  `<svg viewBox="0 0 552 552"><rect x="0" y="0" width="97" height="551" rx="48.5" fill="#4fc17e"/><rect x="227" y="0" width="97" height="551" rx="48.5" fill="#4fc17e"/><rect x="454" y="0" width="97" height="551" rx="48.5" fill="#4fc17e"/></svg>`

### 2. Module
- **Dashboard:** KPIs (Monatsumsatz, Offene Posten, Verrechenbare Stunden, Bankguthaben), Chart.js 6-Monats-Umsatzverlauf in `#4fc17e`, Aktivitäts-Feed.
- **Faktura / Rechnungen:** Rechnungsliste mit Status-Pills (`Bezahlt`, `Offen`, `Überfällig`), 1-Klick-Statuswechsel, Druck- und PDF-Vorschau (DIN-A4 mit Firmenkopf, UID, 20% USt nach österr. UStG, Bankverbindung) via `window.print()`.
- **Kunden / CRM:** Tabelle mit UID-Nummer (ATU...), Ansprechpartnern, offenem Saldo und Neuanlage-Modal.
- **Projekt-Zeiterfassung:** Integriertes Timer-Widget (Start/Stopp), manuelle Schnellerfassung, Projektzuordnung.
- **BMD-Export:** 1-Klick-Download einer buchungsfertigen CSV-Datei für Steuerberater (BMD NTCS Buchungszeilen).
- **Persistenz:** Volle `localStorage`-Persistenz aller Änderungen + Vorbefüllung mit realistischen Demodaten.

Gib die vollständige, sofort lauffähige `index.html` ohne Auslassungen in einem einzigen Codeblock aus.
```
