---
layout: bare
title: Spanish Reader Extension - User Guide
lang: en
---

# Spanish Reader - User Guide

> Version: v1.0.0

## Introduction

Spanish Reader is a browser extension designed for Spanish learners. It adds pronunciation annotations and syllable break marks to Spanish words on web pages and PDFs, supporting both Latin American and Spain accents. It also includes a hover dictionary, text-to-speech, and translation features — helping you learn Spanish pronunciation more easily.

---

## Main Features

- **Whole Page Pronunciation Mode** — Add pronunciation annotations to all Spanish words on the page with one click
- **Syllable Breaks** — Show syllable division with stress marking for every word
- **Hover Dictionary** — Hover over words to see definitions, pronunciation, and a speaker button; choose between Dictionary mode, Tooltip mode, or Off
- **PDF Reader** — Built-in PDF reader with pronunciation annotations, dictionary, speech, and translation; supports drag & drop, URL loading, and automatic PDF detection
- **Latin American & Spain Accents** — Switch between Latin American (es-419) and Spain (es-ES) pronunciation
- **Text-to-Speech** — Click the speaker button to hear pronunciation matching your selected accent
- **Selection Speech with Karaoke Effect** — Select any Spanish text, a compact toolbar appears with speak and translate buttons; speech plays with real-time word-by-word highlighting
- **Selection Translation** — Select any text, click the translate button to get instant translation via Bing or Google Translate
- **Keyboard Shortcuts** — Quick access to core features via customizable keyboard shortcuts

---

## How to Use

### Step 1: Install the Extension

Install **Spanish Reader** from the [Chrome Web Store](https://chromewebstore.google.com/), or load it locally in developer mode.

### Step 2: Open Any Web Page

Visit any web page containing Spanish content.

### Step 3: Enable Pronunciation

Click the extension icon in your browser toolbar. Toggle "Enable Pronunciation" on, then toggle "Whole Page Mode" to annotate all words on the page.

### Step 4: View Pronunciation

Hover over words to see pronunciation tooltips. Click the speaker icon to hear pronunciation. Syllable breaks show the word structure (e.g., "com·pu·ta·do·ra").

### Step 5: Speak and Translate Selected Text

Select any Spanish text with your mouse. A compact toolbar appears near the selection with two buttons:
- **🔊 Speak** — Reads the selected text aloud with karaoke-style word-by-word highlighting
- **🌐 Translate** — Shows an inline translation bubble below the toolbar

> **Tip:** Click the extension icon to open the settings panel and adjust accent type, speech rate, hover mode, translation engine, and more.

---

## Whole Page Pronunciation Mode

When whole page pronunciation mode is enabled, every Spanish word on the page gets a pronunciation annotation displayed above it using ruby text.

The extension automatically adjusts line height to prevent annotations from overlapping with text.

---

## Syllable Breaks

When "Show syllable breaks" is enabled, each word shows its syllable division:

- Syllables are separated by a middle dot (·)
- The stressed syllable is identified based on Spanish accent rules
- Words with written accents (á, é, í, ó, ú) always have stress on the accented syllable

This helps learners understand:
- Where to place emphasis when speaking
- How words are broken across lines
- The rhythmic structure of Spanish

---

## Hover Dictionary

The extension includes a hover dictionary. You can choose from multiple hover modes in the settings:

| Mode | Behavior |
|------|----------|
| **Dictionary** | Hover shows pronunciation + definition + speaker button |
| **Tooltip** | Hover shows pronunciation + speaker button (no definitions) |
| **Off** | No hover effect |

---

## PDF Reader

Spanish Reader includes a built-in PDF reader that allows you to read PDF documents with pronunciation annotations, dictionary, speech, and translation.

### Opening a PDF

**Method 1: From the Popup**  
Click the extension icon, then click "Open PDF Reader". Drag & drop a PDF file or click "Choose File" to open a local PDF. You can also paste a PDF URL.

**Method 2: Context Menu**  
Right-click any `.pdf` link on a web page and choose "Open PDF with Spanish Reader".

**Method 3: Automatic Detection**  
When "PDF Smart Detection" is enabled in settings, the extension automatically redirects `.pdf` URLs to the built-in reader.

### PDF Reader Features

- **Pronunciation Annotations** — All pronunciation features work on PDF text
- **Click Dictionary** — Click on any word to see its definition
- **Selection Toolbar** — Select text to speak, translate, or copy
- **Sidebar** — Table of contents outline and page thumbnails
- **Search** — Search for text in the PDF
- **Themes** — Dark, Light, and Sepia reading themes
- **Zoom** — Multiple zoom levels including Auto, Page Fit, and Page Width

---

## Translation

Select any text on the page and use the translation feature to get instant translations.

**Method 1: Selection Toolbar**  
Select text, then click the 🌐 translate button in the toolbar.

**Method 2: Right-Click Menu**  
Select text, right-click and choose "Translate Selection".

**Method 3: Keyboard Shortcut**  
Select text and press `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) to translate.

**Translation Engines:**
- **Bing Translate** (default) — Powered by Microsoft Translator
- **Google Translate** — Powered by Google

Both engines support **108 target languages**.

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | Action |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Toggle pronunciation annotations on/off |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Speak selected text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Translate selected text |

> **Tip:** You can customize these shortcuts in Chrome at `chrome://extensions/shortcuts`.

---

## Settings Guide

| Setting | Description |
|---------|-------------|
| **Enable Pronunciation** | Master switch to enable or disable the pronunciation annotation feature |
| **Whole Page Mode** | When enabled, displays pronunciation for all Spanish words above the text |
| **Accent** | Choose between Latin American and Spain pronunciation |
| **Show syllable breaks** | Display syllable division marks for words |
| **Hover Mode** | Choose hover behavior: Dictionary (pronunciation + definitions + audio), Tooltip (pronunciation + audio), or Off |
| **Sentence Speech Rate** | Adjust the speed of sentence reading |
| **Translation Engine** | Choose between Bing Translate and Google Translate |
| **Target Language** | Set the translation target language |
| **PDF Smart Detection** | When enabled, automatically redirects PDF URLs to the built-in reader |

---

## FAQ

**Q: Why doesn't it work on some pages?**  
A: For security reasons, browser extensions cannot run on special pages like `chrome://`, browser settings, or the Chrome Web Store.

**Q: No sound from text-to-speech?**  
A: Please check your system volume settings and ensure Spanish voice packs are installed.

**Q: Translation not working?**  
A: Translation requires an internet connection. If Bing Translate fails, try switching to Google Translate in the settings.

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
