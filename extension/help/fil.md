---
layout: bare
title: Spanish Reader — Gabay ng Gumagamit
lang: fil
---

# Spanish Reader — Gabay ng Gumagamit

> Bersyon: v1.0.0

## Panimula

Ang Spanish Reader ay isang browser extension para sa mga nag-aaral ng Espanyol. Nagdaragdag ito ng pronunciation annotations at syllable break marks sa mga salitang Espanyol sa web pages at PDFs, na sumusuporta sa Latin American at Spain accents. Kasama rin ang hover dictionary, text-to-speech, at translation — upang mas madaling matuto ng pronunciation ng Espanyol.

---

## Mga pangunahing feature

- **Whole Page Pronunciation Mode** — isang click lang para magdagdag ng pronunciation annotations sa lahat ng salitang Espanyol sa page
- **Syllable Breaks** — ipakita ang paghahati ng pantig at stress marking sa bawat salita
- **Hover Dictionary** — i-hover ang mga salita para makita ang definitions, pronunciation, at speaker button; pumili ng Dictionary mode, Tooltip mode, o Off
- **PDF Reader** — built-in PDF reader na may pronunciation annotations, dictionary, speech, at translation; suportado ang drag & drop, URL loading, at automatic PDF detection
- **Latin American at Spain Accents** — magpalipat-lipat sa pagitan ng Latin American (es-419) at Spain (es-ES) pronunciation
- **Text-to-speech** — i-click ang speaker button para pakinggan ang pronunciation na tumutugma sa napiling accent
- **Selection Speech na may Karaoke Effect** — pumili ng anumang tekstong Espanyol; may compact toolbar na may speak at translate buttons; ang speech ay may real-time word-by-word highlighting
- **Selection Translation** — pumili ng teksto, i-click ang translate button para sa instant translation sa pamamagitan ng Bing o Google Translate
- **Keyboard Shortcuts** — mabilis na access sa core features gamit ang customizable keyboard shortcuts

---

## Paano gamitin

### Hakbang 1: I-install ang extension

I-install ang **Spanish Reader** mula sa [Chrome Web Store](https://chromewebstore.google.com/), o i-load ito nang lokal sa developer mode.

### Hakbang 2: Buksan ang anumang web page

Bisitahin ang anumang page na may Espanyol na nilalaman.

### Hakbang 3: Paganahin ang pronunciation

I-click ang icon ng extension sa toolbar. I-on ang „Enable Pronunciation“, pagkatapos i-on ang „Whole Page Mode“ para i-annotate ang lahat ng salita sa page.

### Hakbang 4: Tingnan ang pronunciation

I-hover ang mga salita para makita ang pronunciation tooltips. I-click ang speaker icon para marinig ang audio. Ang syllable breaks ay ipinapakita ang istruktura ng salita (hal., „com·pu·ta·do·ra“).

### Hakbang 5: Magsalita at magsalin ng napiling teksto

Pumili ng tekstong Espanyol gamit ang mouse. May compact toolbar malapit sa selection na may dalawang button:
- **🔊 Speak** — binabasa ang napiling teksto nang malakas na may karaoke-style na word-by-word highlighting
- **🌐 Translate** — nagpapakita ng inline translation bubble sa ilalim ng toolbar

> **Tip:** I-click ang icon ng extension para buksan ang settings panel at ayusin ang accent type, speech rate, hover mode, translation engine, at iba pa.

---

## Whole Page Pronunciation Mode

Kapag naka-on ang whole page pronunciation mode, ang bawat salitang Espanyol sa page ay may pronunciation annotation sa ibabaw gamit ang ruby text.

Awtomatiko nitong inaayos ang line height para hindi mag-overlap ang annotations sa teksto.

---

## Syllable Breaks

Kapag naka-on ang „Show syllable breaks“, ang bawat salita ay nagpapakita ng paghahati ng pantig:

- Ang mga pantig ay pinaghihiwalay ng middle dot (·)
- Tinutukoy ang stressed syllable batay sa Spanish accent rules
- Ang mga salitang may written accents (á, é, í, ó, ú) ay laging may stress sa accented syllable

Tumutulong ito sa mga learner na maintindihan:
- saan maglagay ng diin kapag nagsasalita
- paano nahahati ang mga salita sa dulo ng linya
- ang rhythmic structure ng Espanyol

---

## Hover Dictionary

May kasamang hover dictionary ang extension. Maaari kang pumili ng iba’t ibang hover modes sa settings:

| Mode | Kilos |
|------|--------|
| **Dictionary** | Ang hover ay nagpapakita ng pronunciation + definition + speaker button |
| **Tooltip** | Ang hover ay nagpapakita ng pronunciation + speaker button (walang definitions) |
| **Off** | Walang hover effect |

---

## PDF Reader

Kasama sa Spanish Reader ang built-in PDF reader na nagpapahintulot basahin ang mga PDF na may pronunciation annotations, dictionary, speech, at translation.

### Pagbukas ng PDF

**Paraan 1: Mula sa popup**  
I-click ang icon ng extension, pagkatapos i-click ang „Open PDF Reader“. I-drag & drop ang PDF file o i-click ang „Choose File“ para buksan ang lokal na PDF. Maaari ring i-paste ang PDF URL.

**Paraan 2: Context menu**  
I-right-click ang anumang `.pdf` link sa page at piliin ang „Open PDF with Spanish Reader“.

**Paraan 3: Automatic detection**  
Kapag naka-on ang „PDF Smart Detection“ sa settings, awtomatikong ini-redirect ng extension ang `.pdf` URLs papunta sa built-in reader.

### Mga feature ng PDF Reader

- **Pronunciation annotations** — gumagana ang lahat ng pronunciation features sa PDF text
- **Click dictionary** — i-click ang anumang salita para makita ang definition
- **Selection toolbar** — pumili ng teksto para magsalita, magsalin, o kopyahin
- **Sidebar** — table of contents outline at page thumbnails
- **Search** — maghanap ng teksto sa PDF
- **Themes** — Dark, Light, at Sepia reading themes
- **Zoom** — maraming zoom levels kasama ang Auto, Page Fit, at Page Width

---

## Translation

Pumili ng anumang teksto sa page at gamitin ang translation feature para sa instant translations.

**Paraan 1: Selection toolbar**  
Pumili ng teksto, pagkatapos i-click ang 🌐 translate button sa toolbar.

**Paraan 2: Right-click menu**  
Pumili ng teksto, i-right-click at piliin ang „Translate Selection“.

**Paraan 3: Keyboard shortcut**  
Pumili ng teksto at pindutin ang `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Translation engines:**
- **Bing Translate** (default) — pinapagana ng Microsoft Translator
- **Google Translate** — pinapagana ng Google

Sinusuportahan ng pareho ang **108 target languages**.

---

## Keyboard Shortcuts

| Shortcut | Mac shortcut | Aksyon |
|----------|--------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | I-toggle on/off ang pronunciation annotations |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Magsalita ng napiling teksto |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Isalin ang napiling teksto |

> **Tip:** Maaari mong i-customize ang mga shortcuts sa Chrome sa `chrome://extensions/shortcuts`.

---

## Gabay sa settings

| Setting | Paglalarawan |
|---------|--------------|
| **Enable Pronunciation** | Master switch para paganahin o huwag paganahin ang pronunciation annotation feature |
| **Whole Page Mode** | Kapag naka-on, ipinapakita ang pronunciation sa lahat ng salitang Espanyol sa ibabaw ng teksto |
| **Accent** | Pumili sa Latin American at Spain pronunciation |
| **Show syllable breaks** | Ipakita ang syllable division marks sa mga salita |
| **Hover Mode** | Pumili ng hover behavior: Dictionary (pronunciation + definitions + audio), Tooltip (pronunciation + audio), o Off |
| **Sentence Speech Rate** | Ayusin ang bilis ng pagbasa ng pangungusap |
| **Translation Engine** | Pumili sa Bing Translate at Google Translate |
| **Target Language** | Itakda ang target language ng translation |
| **PDF Smart Detection** | Kapag naka-on, awtomatikong ini-redirect ang PDF URLs sa built-in reader |

---

## Mga madalas na itanong

**B: Bakit hindi ito gumagana sa ilang pages?**  
S: Dahil sa seguridad, hindi maaaring tumakbo ang mga browser extension sa mga espesyal na page tulad ng `chrome://`, browser settings, o Chrome Web Store.

**B: Walang tunog mula sa text-to-speech?**  
S: Pakitingnan ang volume ng sistema at siguraduhing naka-install ang Spanish voice packs.

**B: Hindi gumagana ang translation?**  
S: Kailangan ng internet connection ang translation. Kung nabigo ang Bing Translate, subukan ang Google Translate sa settings.

---

## Kaugnay na mga link

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
