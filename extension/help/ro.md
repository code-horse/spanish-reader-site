---
layout: bare
title: Spanish Reader — Ghid de utilizare
lang: ro
---

# Spanish Reader — Ghid de utilizare

> Versiune: v1.0.0

## Introducere

Spanish Reader este o extensie de browser destinată celor care învață spaniola. Adaugă adnotări de pronunție și despărțire în silabe pentru cuvintele spaniole de pe paginile web PDF, cu suport pentru accent latin-american și spaniol (Spania). Include și un dicționar la hover, text-to-speech și traducere — pentru a învăța mai ușor pronunția în spaniolă.

---

## Funcții principale

- **Whole Page Pronunciation Mode** — adaugă pronunții la toate cuvintele spaniole din pagină cu un singur clic
- **Syllable Breaks** — arată despărțirea în silabe cu accentul pentru fiecare cuvânt
- **Hover Dictionary** — treci cu cursorul peste un cuvânt pentru definiții, pronunție și buton de difuzor; moduri: Dictionary, Tooltip sau Off
- **PDF Reader** — cititor PDF integrat cu adnotări de pronunție, dicționar, vorbire și traducere; drag & drop, încărcare URL și detectare automată PDF
- **Accente America Latină și Spania** — comutare între Latin American (es-419) și Spain (es-ES)
- **Text-to-Speech** — clic pe butonul de difuzor pentru a auzi pronunția potrivit accentului ales
- **Selection Speech with Karaoke Effect** — selectează text în spaniolă: apare o bară compactă cu butoane de vorbire și traducere; redarea evidențiază cuvânt cu cuvânt în timp real
- **Selection Translation** — selectează text, clic pe traducere pentru traducere instantanee prin Bing sau Google Translate
- **Keyboard Shortcuts** — acces rapid la funcțiile esențiale prin scurtături personalizabile
- **Interfață multilingvă** — Disponibilă în mai multe limbi

---

## Cum se folosește

### Pasul 1: Instalați extensia

Instalați **Spanish Reader** din [Chrome Web Store](https://chromewebstore.google.com/) sau încărcați-o local în modul dezvoltator.

### Pasul 2: Deschideți o pagină web

Accesați orice pagină care conține conținut în spaniolă.

### Pasul 3: Activați pronunția

Faceți clic pe pictograma extensiei din bara de instrumente. Activați „Enable Pronunciation”, apoi „Whole Page Mode” pentru a adnota toate cuvintele din pagină.

### Pasul 4: Vizualizați pronunția

Treceti cu cursorul peste cuvinte pentru tooltip-uri de pronunție. Faceți clic pe pictograma difuzorului pentru a asculta. Despărțirea în silabe arată structura cuvântului (ex.: „com·pu·ta·do·ra”).

### Pasul 5: Vorbiți și traduceți textul selectat

Selectați text în spaniolă cu mouse-ul. Lângă selecție apare o bară compactă cu două butoane:
- **🔊 Speak** — citește textul selectat cu evidențiere cuvânt cu cuvânt în stil karaoke
- **🌐 Translate** — afișează un balon de traducere inline sub bară

> **Sfat:** Faceți clic pe pictograma extensiei pentru a deschide setările și a regla accentul, viteza vocii, modul hover, motorul de traducere etc.

---

## Whole Page Pronunciation Mode

Când modul whole page pronunciation este activat, fiecare cuvânt spaniol primește o adnotare de pronunție deasupra, folosind ruby text.

Extensia ajustează automat înălțimea rândului pentru ca adnotările să nu se suprapună peste text.

---

## Syllable Breaks

Când „Show syllable breaks” este activat, fiecare cuvânt arată despărțirea în silabe:

- Silabele sunt separate printr-un punct median (·)
- Silaba accentuată este determinată după regulile de accent din spaniolă
- Cuvintele cu accent grafic (á, é, í, ó, ú) au mereu accentul pe silaba accentuată grafic

Acest lucru ajută la:
- unde pui accentul când vorbești
- cum se împart cuvintele la sfârșitul rândului
- structura ritmică a spaniolei

---

## Hover Dictionary

Extensia include un hover dictionary. Puteți alege modul hover în setări:

| Mod | Comportament |
|-----|----------------|
| **Dictionary** | Hover: pronunție + definiție + buton difuzor |
| **Tooltip** | Hover: pronunție + buton difuzor (fără definiții) |
| **Off** | Fără efect la hover |

---

## PDF Reader

Spanish Reader include un PDF Reader integrat pentru citirea documentelor PDF cu adnotări de pronunție, dicționar, vorbire și traducere.

### Deschiderea unui PDF

**Metoda 1: Din popup**  
Faceți clic pe pictograma extensiei, apoi pe „Open PDF Reader”. Trageți un fișier PDF (drag & drop) sau faceți clic pe „Choose File” pentru PDF local. Puteți lipi și un URL PDF.

**Metoda 2: Meniu contextual**  
Click dreapta pe un link `.pdf` și alegeți „Open PDF with Spanish Reader”.

**Metoda 3: Detectare automată**  
Cu „PDF Smart Detection” activ în setări, extensia redirecționează automat URL-urile `.pdf` către cititorul integrat.

### Funcții PDF Reader

- **Pronunciation Annotations** — toate funcțiile de pronunție pe textul PDF
- **Click Dictionary** — clic pe un cuvânt pentru definiție
- **Selection Toolbar** — selectați text pentru vorbire, traducere sau copiere
- **Sidebar** — cuprins și miniaturi pagini
- **Search** — căutare în PDF
- **Themes** — teme de citire Dark, Light și Sepia
- **Zoom** — nivele de zoom inclusiv Auto, Page Fit și Page Width

---

## Translation

Selectați text pe pagină și folosiți traducerea pentru rezultate instantanee.

**Metoda 1: Selection Toolbar**  
Selectați text, apoi butonul 🌐 translate din bară.

**Metoda 2: Meniu click dreapta**  
Selectați text, click dreapta și „Translate Selection”.

**Metoda 3: Keyboard Shortcut**  
Selectați text și apăsați `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Translation Engines:**
- **Bing Translate** (implicit) — Microsoft Translator
- **Google Translate** — Google

Ambele motoare suportă **108 target languages**.

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | Acțiune |
|----------|--------------|---------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Comutare adnotări pronunție |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Vorbește textul selectat |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduce textul selectat |

> **Sfat:** Personalizați scurtăturile în Chrome la `chrome://extensions/shortcuts`.

---

## Settings Guide

| Setare | Descriere |
|--------|-----------|
| **Enable Pronunciation** | Comutator principal pentru adnotările de pronunție |
| **Whole Page Mode** | Afișează pronunția deasupra tuturor cuvintelor spaniole |
| **Accent** | Latin American sau Spain |
| **Show syllable breaks** | Afișează despărțirea în silabe |
| **Hover Mode** | Dictionary (pronunție + definiții + audio), Tooltip (pronunție + audio) sau Off |
| **Sentence Speech Rate** | Viteza citirii propozițiilor |
| **Translation Engine** | Bing Translate sau Google Translate |
| **Target Language** | Limba țintă pentru traducere |
| **PDF Smart Detection** | Redirecționare automată a URL-urilor PDF către cititorul integrat |

---

## FAQ

**Î: De ce nu funcționează pe unele pagini?**  
R: Din motive de securitate, extensiile nu rulează pe pagini speciale precum `chrome://`, setările browserului sau Chrome Web Store.

**Î: Nu se aude text-to-speech?**  
R: Verificați volumul sistemului și că sun instalate pachetele de voce în spaniolă.

**Î: Traducerea nu merge?**  
R: Traducerea necesită internet. Dacă Bing Translate eșuează, încercați Google Translate în setări.

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
