---
layout: bare
title: Spanish Reader — Guia d'usuari
lang: ca
---

# Spanish Reader — Guia d'usuari

> Version: v1.0.0

## Introducció

Spanish Reader és una browser extension pensada per a qui aprèn castellà. Afegeix anotacions de pronunciació i marques de divisió sil·làbica a les paraules en castellà de les pàgines web i dels PDF, amb suport per als accents d'Amèrica Llatina i d'Espanya. També inclou hover dictionary, text-to-speech i translation, per aprendre la pronunciació del castellà amb més facilitat.

---

## Funcions principals

- **Whole Page Pronunciation Mode** — Afegeix anotacions de pronunciació a totes les paraules en castellà de la pàgina amb un sol clic
- **Syllable Breaks** — Mostra la divisió sil·làbica i l'accent per a cada paraula
- **Hover Dictionary** — Passeu el cursor per veure definició, pronunciació i botó de speaker; trieu Dictionary mode, Tooltip mode o Off
- **PDF Reader** — PDF reader integrat amb anotacions de pronunciació, dictionary, speech i translation; compatible amb drag & drop, càrrega per URL i detecció automàtica de PDF
- **Latin American & Spain Accents** — Canvieu entre pronunciació Latin American (es-419) i Spain (es-ES)
- **Text-to-Speech** — Cliqueu el botó speaker per escoltar la pronunciació segons l'accent triat
- **Selection Speech with Karaoke Effect** — Seleccioneu text en castellà; apareix una barra d'eines compacta amb els botons speak i translate; la locució es reprodueix amb real-time word-by-word highlighting paraula a paraula
- **Selection Translation** — Seleccioneu text i cliqueu translate per obtenir traducció immediata amb Bing o Google Translate
- **Keyboard Shortcuts** — Accés ràpid a les funcions bàsiques amb keyboard shortcuts personalitzables
- **Interfície multilingüe** — Disponible en diversos idiomes

---

## Com usar-ho

### Pas 1: Instal·lar l'extension

Instal·leu **Spanish Reader** des del [Chrome Web Store](https://chromewebstore.google.com/) o carregueu-la localment en developer mode.

### Pas 2: Obrir qualsevol pàgina web

Visiteu una pàgina amb contingut en castellà.

### Pas 3: Activar la pronunciació

Cliqueu la icona de l'extension a la toolbar del navegador. Activeu "Enable Pronunciation" i després "Whole Page Mode" per anotar totes les paraules.

### Pas 4: Veure la pronunciació

Passeu el cursor sobre les paraules per veure el tooltip de pronunciació. Cliqueu la icona speaker per escoltar. Els Syllable breaks mostren l'estructura (p. ex. "com·pu·ta·do·ra").

### Pas 5: Parlar i traduir el text seleccionat

Seleccioneu text en castellà amb el ratolí. Apareix una barra compacta a prop de la selecció amb dos botons:
- **🔊 Speak** — Llegeix el text seleccionat amb realç tipus karaoke, paraula a paraula
- **🌐 Translate** — Mostra una bombolla de traducció inline sota la barra

> **Tip:** Cliqueu la icona de l'extension per obrir el panell de configuració i ajustar l'accent, speech rate, hover mode, translation engine, etc.

---

## Whole Page Pronunciation Mode

Quan el whole page pronunciation mode està actiu, cada paraula en castellà de la pàgina té una anotació de pronunciació per sobre, amb ruby text.

L'extension ajusta automàticament el line height perquè les anotacions no es superposin al text.

---

## Syllable Breaks

Amb "Show syllable breaks" activat, cada paraula mostra la divisió sil·làbica:

- Les síl·labes es separen amb un middle dot (·)
- La síl·laba tònica es determina segons les regles d'accent del castellà
- Les paraules amb accent escrit (á, é, í, ó, ú) tenen sempre el stress en la síl·laba accentuada

Això ajuda a entendre:
- On posar l'èmfasi en parlar
- Com es parteixen les paraules entre línies
- L'estructura rítmica del castellà

---

## Hover Dictionary

L'extension inclou hover dictionary. A la configuració podeu triar el hover mode:

| Mode | Comportament |
|------|--------------|
| **Dictionary** | En passar el cursor: pronunciació + definition + botó speaker |
| **Tooltip** | Pronunciació + botó speaker (sense definitions) |
| **Off** | Sense efecte hover |

---

## PDF Reader

Spanish Reader inclou un PDF reader integrat per llegir PDF amb anotacions de pronunciació, dictionary, speech i translation.

### Obrir un PDF

**Mètode 1: Des del Popup**  
Cliqueu la icona de l'extension i després "Open PDF Reader". Arrossegueu un PDF o cliqueu "Choose File" per obrir un fitxer local. També podeu enganxar una URL de PDF.

**Mètode 2: Context Menu**  
Cliqueu amb el botó dret en un enllaç `.pdf` i trieu "Open PDF with Spanish Reader".

**Mètode 3: Automatic Detection**  
Si "PDF Smart Detection" és actiu a la configuració, l'extension redirigeix automàticament les URL `.pdf` al reader integrat.

### Funcions del PDF Reader

- **Pronunciation Annotations** — Totes les funcions de pronunciació funcionen sobre el text del PDF
- **Click Dictionary** — Cliqueu una paraula per veure'n la definition
- **Selection Toolbar** — Seleccioneu text per speak, translate o copy
- **Sidebar** — Taula de continguts i miniatures de pàgina (page thumbnails)
- **Search** — Cerca de text dins del PDF
- **Themes** — Temes Dark, Light i Sepia
- **Zoom** — Diversos nivells, incloent Auto, Page Fit i Page Width

---

## Translation

Seleccioneu text a la pàgina i useu translation per obtenir traduccions immediates.

**Mètode 1: Selection Toolbar**  
Seleccioneu text i cliqueu el botó 🌐 translate de la barra.

**Mètode 2: Right-Click Menu**  
Seleccioneu text, botó dret i "Translate Selection".

**Mètode 3: Keyboard Shortcut**  
Seleccioneu text i premeu `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Translation Engines:**
- **Bing Translate** (per defecte) — Microsoft Translator
- **Google Translate** — Google

Ambdues admeten **108 target languages**.

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | Acció |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Activar/desactivar pronunciation annotations |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Parlar el text seleccionat |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduir el text seleccionat |

> **Tip:** Personalitzeu les dreceres a Chrome a `chrome://extensions/shortcuts`.

---

## Settings Guide

| Setting | Descripció |
|---------|------------|
| **Enable Pronunciation** | Interruptor principal de les pronunciation annotations |
| **Whole Page Mode** | Mostra la pronunciació sobre totes les paraules en castellà |
| **Accent** | Trieu pronunciació Latin American o Spain |
| **Show syllable breaks** | Mostra les marques de divisió sil·làbica |
| **Hover Mode** | Comportament hover: Dictionary (pronunciació + definitions + audio), Tooltip (pronunciació + audio) o Off |
| **Sentence Speech Rate** | Velocitat de lectura de frases |
| **Translation Engine** | Bing Translate o Google Translate |
| **Target Language** | Idioma de destinació de la traducció |
| **PDF Smart Detection** | Redirigeix automàticament les URL PDF al reader integrat |

---

## FAQ

**P: Per què no funciona en algunes pàgines?**  
R: Per motius de seguretat, les browser extension no s'executen en pàgines especials com `chrome://`, la configuració del navegador o la Chrome Web Store.

**P: No sona el text-to-speech?**  
R: Comproveu el volum del sistema i que tingueu instal·lats Spanish voice packs.

**P: La translation no funciona?**  
R: Cal connexió a internet. Si Bing Translate falla, proveu Google Translate a la configuració.

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
