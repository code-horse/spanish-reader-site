---
layout: bare
title: Spanish Reader — Brugervejledning
lang: da
---

# Spanish Reader — Brugervejledning

> Version: v1.0.0

## Introduktion

Spanish Reader er en browserudvidelse til dig, der lærer spansk. Den tilføjer udtaleannotationer og stavelser til spanske ord på websider og i PDF-filer, med både latinamerikansk og spansk (Spanien) udtale. Der er også et hover-ordbog, text-to-speech og oversættelse — så du lettere kan lære spansk udtale.

---

## Hovedfunktioner

- **Udtale for hele siden** — tilføj udtale til alle spanske ord på siden med ét klik
- **Stavelsesopdeling** — vis opdeling i stavelser med tryk for hvert ord
- **Hover-ordbog** — hold musen over ord for at se definitioner, udtale og en højttalerknap; vælg Dictionary, Tooltip eller Off
- **PDF Reader** — indbygget PDF-læser med udtale, ordbog, oplæsning og oversættelse; drag & drop, URL og automatisk PDF-detektion
- **Latinamerikansk og spansk accent** — skift mellem latinamerikansk (es-419) og spansk (es-ES) udtale
- **Text-to-speech** — klik på højttaleren for at høre udtale i den valgte accent
- **Markering med karaoke-effekt** — markér spansk tekst; en kompakt værktøjslinje vises med oplæsning og oversættelse; ord fremhæves ord for ord under afspilning
- **Oversættelse af markering** — markér tekst og klik for øjeblikkelig oversættelse via Bing Translate eller Google Translate
- **Keyboard shortcuts** — hurtig adgang med tilpasbare genveje

---

## Sådan bruger du udvidelsen

### Trin 1: Installer udvidelsen

Installer **Spanish Reader** fra [Chrome Web Store](https://chromewebstore.google.com/), eller indlæs den lokalt i developer mode.

### Trin 2: Åbn en vilkårlig webside

Besøg en side med spansk indhold.

### Trin 3: Aktivér udtale

Klik på udvidelsens ikon på værktøjslinjen. Slå „Enable Pronunciation“ til, og derefter „Whole Page Mode“ for at annotere alle ord på siden.

### Trin 4: Se udtalen

Hold musen over ord for at se værktøjstip med udtale. Klik på højttalerikonet for at afspille. Når stavelsesopdeling er slået til, vises ordets opbygning (fx „com·pu·ta·do·ra“).

### Trin 5: Læs og oversæt markeret tekst

Markér spansk tekst med musen. En kompakt værktøjslinje vises med to knapper:
- **🔊 Speak** — læser markeringen højt med karaoke-lignende ordfremhævelse
- **🌐 Translate** — viser en indlejret oversættelsesboble under værktøjslinjen

> **Tip:** Klik på udvidelsens ikon for at åbne indstillinger og justere accent, talehastighed, hover mode, translation engine med mere.

---

## Udtale for hele siden

Når udtale for hele siden er slået til, vises udtalen over hvert spansk ord som ruby text.

Udvidelsen justerer automatisk linjehøjde, så annotationerne ikke overlapper teksten.

---

## Stavelsesopdeling

Når „Show syllable breaks“ er aktiveret, vises hvert ord med stavelsesopdeling:

- Stavelser adskilles med et mellempunkt (·)
- Den tryksatte stavelse bestemmes efter spansk udtaleregl
- Ord med skriftlig accent (á, é, í, ó, ú) har altid tryk på den accenterede stavelse

Det hjælper lærende med at forstå:
- hvor trykket ligger ved tale
- hvordan ord brydes ved linjeskift
- den rytmiske struktur i spansk

---

## Hover-ordbog

Udvidelsen har et hover dictionary. I indstillingerne vælger du hover mode:

| Tilstand | Adfærd |
|----------|--------|
| **Dictionary** | Hover viser udtale + definition + højttalerknap |
| **Tooltip** | Hover viser udtale + højttaler (uden definitioner) |
| **Off** | Ingen hover-effekt |

---

## PDF Reader

Spanish Reader har en indbygget PDF Reader, så du kan læse PDF med udtale, ordbog, oplæsning og oversættelse.

### Åbn en PDF

**Metode 1: Fra popup**  
Klik på udvidelsens ikon og derefter „Open PDF Reader“. Træk og slip en PDF eller klik „Choose File“ for en lokal fil. Du kan også indsætte en PDF-URL.

**Metode 2: Kontekstmenu**  
Højreklik på et `.pdf`-link på siden og vælg „Open PDF with Spanish Reader“.

**Metode 3: Automatisk detektion**  
Med „PDF Smart Detection“ i indstillingerne omdirigerer udvidelsen automatisk `.pdf`-URL’er til den indbyggede læser.

### Funktioner i PDF Reader

- **Pronunciation annotations** — al udtalefunktionalitet virker på PDF-tekst
- **Click dictionary** — klik på et ord for at se definitionen
- **Selection toolbar** — markér tekst for oplæsning, oversættelse eller kopi
- **Sidebar** — indholdsfortegnelse og sideminiaturer
- **Search** — søg i PDF’en
- **Themes** — læsetemaer Dark, Light og Sepia
- **Zoom** — flere zoomniveauer inkl. Auto, Page Fit og Page Width

---

## Oversættelse

Markér tekst på siden og brug oversættelsesfunktionen til øjeblikkelige resultater.

**Metode 1: Selection toolbar**  
Markér tekst og klik på oversættelsesknap 🌐.

**Metode 2: Højreklik**  
Markér tekst, højreklik og vælg „Translate Selection“.

**Metode 3: Tastaturgenvej**  
Markér tekst og tryk `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Translation engines:**
- **Bing Translate** (standard) — Microsoft Translator
- **Google Translate** — Google

Begge understøtter **108 target languages**.

---

## Tastaturgenveje

| Genvej | Mac | Handling |
|--------|-----|----------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Slå udtaleannotationer til/fra |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Læs markeret tekst |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Oversæt markeret tekst |

> **Tip:** Tilpas genveje i Chrome under `chrome://extensions/shortcuts`.

---

## Guide til indstillinger

| Indstilling | Beskrivelse |
|-------------|-------------|
| **Enable Pronunciation** | Hovedkontakt for udtaleannotationer |
| **Whole Page Mode** | Viser udtale over alle spanske ord |
| **Accent** | Latinamerikansk eller spansk (Spanien) udtale |
| **Show syllable breaks** | Vis stavelsesopdeling |
| **Hover Mode** | Dictionary (udtale + definitioner + lyd), Tooltip (udtale + lyd) eller Off |
| **Sentence Speech Rate** | Hastighed ved sætningsoplæsning |
| **Translation Engine** | Bing Translate eller Google Translate |
| **Target Language** | Målsprog for oversættelse |
| **PDF Smart Detection** | Omdiriger PDF-URL’er automatisk til den indbyggede læser |

---

## Ofte stillede spørgsmål

**Hvorfor virker det ikke på nogle sider?**  
Af sikkerhedsmæssige årsager kan udvidelser ikke køre på sider som `chrome://`, browserindstillinger eller Chrome Web Store.

**Ingen lyd fra text-to-speech?**  
Tjek systemlydstyrken og at spanske stemmepakker er installeret.

**Oversættelse virker ikke?**  
Oversættelse kræver internet. Hvis Bing Translate fejler, prøv Google Translate i indstillingerne.

---

## Relaterede links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
