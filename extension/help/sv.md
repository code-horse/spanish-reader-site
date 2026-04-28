---
layout: bare
title: Spanish Reader — Användarguide
lang: sv
---

# Spanish Reader — Användarguide

> Version: v1.0.0

## Introduktion

Spanish Reader är ett webbläsartillägg för dig som lär dig spanska. Det lägger till uttalsanteckningar och stavelseuppdelning för spanska ord på webbsidor och i PDF-filer, med stöd för både latinamerikansk och spansk (Spanien) accent. Det finns också ett hovrande lexikon, text-till-tal och översättning — så att du lättare kan lära dig spanskt uttal.

---

## Huvudfunktioner

- **Whole Page Pronunciation Mode** — lägg till uttal för alla spanska ord på sidan med ett klick
- **Syllable Breaks** — visa stavelseuppdelning med betoning för varje ord
- **Hover Dictionary** — hovra över ett ord för definitioner, uttal och en högtalarknapp; lägen Dictionary, Tooltip eller Off
- **PDF Reader** — inbyggd PDF-läsare med uttal, ordbok, uppläsning och översättning; drag & drop, URL-laddning och automatisk PDF-upptäckt
- **Latinamerikansk och spansk accent** — växla mellan Latin American (es-419) och Spain (es-ES)
- **Text-to-Speech** — klicka på högtalarknappen för uttal som matchar vald accent
- **Selection Speech with Karaoke Effect** — markera spansk text; en kompakt verktygsrad visas med knappar för uppläsning och översättning; uppläsning med ord-för-ord markering i realtid
- **Selection Translation** — markera text och klicka på översätt för direkt översättning via Bing eller Google Translate
- **Keyboard Shortcuts** — snabb åtkomst till kärnfunktioner med anpassningsbara genvägar

---

## Så använder du det

### Steg 1: Installera tillägget

Installera **Spanish Reader** från [Chrome Web Store](https://chromewebstore.google.com/) eller ladda det lokalt i utvecklarläge.

### Steg 2: Öppna en webbsida

Besök en sida med spanskt innehåll.

### Steg 3: Aktivera uttal

Klicka på tilläggsikonen i verktygsfältet. Slå på «Enable Pronunciation», sedan «Whole Page Mode» för att annotera alla ord på sidan.

### Steg 4: Visa uttal

Hovra över ord för uttalsverktygstips. Klicka på högtalarikonen för att lyssna. Stavelseuppdelning visar ordstrukturen (t.ex. «com·pu·ta·do·ra»).

### Steg 5: Läs upp och översätt markerad text

Markera spansk text med musen. En kompakt verktygsrad visas vid markeringen med två knappar:
- **🔊 Speak** — läser den markerade texten med ord-för-ord markering som vid karaoke
- **🌐 Translate** — visar en inbäddad översättningsbubbla under raden

> **Tips:** Klicka på tilläggsikonen för att öppna inställningar och justera accent, talhastighet, hover-läge, översättningsmotor med mera.

---

## Whole Page Pronunciation Mode

När whole page pronunciation-läget är på får varje spanskt ord en uttalsanteckning ovanför med ruby text.

Tillägget justerar automatiskt radhöjden så att anteckningarna inte överlappar texten.

---

## Syllable Breaks

När «Show syllable breaks» är på visar varje ord stavelseuppdelning:

- Stavelsen separeras med en mittpunkt (·)
- Den betonade stavelsen bestäms enligt spanska betoningsregler
- Ord med skriftlig accent (á, é, í, ó, ú) har alltid betoning på den accenterade stavelsen

Det hjälper dig att förstå:
- var du lägger tyngd när du talar
- hur ord bryts över rader
- den rytmiska strukturen i spanska

---

## Hover Dictionary

Tillägget har en hover dictionary. Du väljer hover-läge i inställningarna:

| Läge | Beteende |
|------|----------|
| **Dictionary** | Hover visar uttal + definition + högtalarknapp |
| **Tooltip** | Hover visar uttal + högtalarknapp (inga definitioner) |
| **Off** | Ingen hover-effekt |

---

## PDF Reader

Spanish Reader har en inbyggd PDF Reader så att du kan läsa PDF-dokument med uttalsanteckningar, ordbok, uppläsning och översättning.

### Öppna en PDF

**Metod 1: Från popup**  
Klicka på tilläggsikonen och sedan «Open PDF Reader». Dra och släpp en PDF eller klicka «Choose File» för en lokal fil. Du kan också klistra in en PDF-URL.

**Metod 2: Kontextmeny**  
Högerklicka på en `.pdf`-länk och välj «Open PDF with Spanish Reader».

**Metod 3: Automatisk upptäckt**  
När «PDF Smart Detection» är på i inställningarna omdirigerar tillägget automatiskt `.pdf`-URL:er till den inbyggda läsaren.

### Funktioner i PDF Reader

- **Pronunciation Annotations** — alla uttalsfunktioner fungerar på PDF-text
- **Click Dictionary** — klicka på ett ord för definition
- **Selection Toolbar** — markera text för uppläsning, översättning eller kopiering
- **Sidebar** — innehållsförteckning och sidminiatyrer
- **Search** — sök i PDF:en
- **Themes** — lästeman Dark, Light och Sepia
- **Zoom** — flera zoomnivåer inklusive Auto, Page Fit och Page Width

---

## Translation

Markera text på sidan och använd översättningen för direkta resultat.

**Metod 1: Selection Toolbar**  
Markera text och klicka på 🌐 translate-knappen i raden.

**Metod 2: Högerklicksmeny**  
Markera text, högerklicka och välj «Translate Selection».

**Metod 3: Keyboard Shortcut**  
Markera text och tryck `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Translation Engines:**
- **Bing Translate** (standard) — drivs av Microsoft Translator
- **Google Translate** — drivs av Google

Båda motorerna stöder **108 target languages**.

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | Åtgärd |
|----------|--------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Slå uttalsanteckningar av/på |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Läs upp markerad text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Översätt markerad text |

> **Tips:** Anpassa genvägar i Chrome på `chrome://extensions/shortcuts`.

---

## Settings Guide

| Inställning | Beskrivning |
|-------------|-------------|
| **Enable Pronunciation** | Huvudbrytare för uttalsanteckningar |
| **Whole Page Mode** | Visar uttal ovanför alla spanska ord när den är på |
| **Accent** | Latin American eller Spain |
| **Show syllable breaks** | Visa stavelseuppdelning |
| **Hover Mode** | Dictionary (uttal + definitioner + ljud), Tooltip (uttal + ljud) eller Off |
| **Sentence Speech Rate** | Hastighet för meningsuppläsning |
| **Translation Engine** | Bing Translate eller Google Translate |
| **Target Language** | Målspråk för översättning |
| **PDF Smart Detection** | Omdirigerar PDF-URL:er automatiskt till den inbyggda läsaren |

---

## FAQ

**F: Varför fungerar det inte på vissa sidor?**  
S: Av säkerhetsskäl kan webbläsartillägg inte köras på sidor som `chrome://`, webbläsarinställningar eller Chrome Web Store.

**F: Inget ljud från text-to-speech?**  
S: Kontrollera systemvolymen och att spanska röster är installerade.

**F: Översättning fungerar inte?**  
S: Översättning kräver internet. Om Bing Translate misslyckas, prova Google Translate i inställningarna.

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
