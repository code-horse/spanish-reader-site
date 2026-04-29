---
layout: bare
title: Spanish Reader Extension - User Guide
lang: en
---

# Spanish Reader - User Guide

> Version: v1.0.0

## Introduction

Spanish Reader is a browser extension for learners of Spanish. It adds pronunciation annotations and syllable break marks to Spanish words on web pages and PDFs, supporting both Latin American and Spain accents. It includes a built-in Spanish definitions dictionary, text-to-speech with accent-matched voices, syllable break analysis, and optional translation — helping you learn Spanish pronunciation and vocabulary in context.

---

## Main Features

- **Whole Page Pronunciation Mode** — Add pronunciation annotations to all Spanish words on the page with one click
- **Syllable Breaks** — Show syllable division with stress marking for every word (e.g., "com·pu·ta·do·ra")
- **Hover Dictionary** — Hover over words to see definitions, pronunciation, and a speaker button; choose Dictionary mode, Tooltip mode, or Off
- **PDF Reader** — Built-in PDF reader with pronunciation annotations, dictionary, speech, and translation; drag & drop, URL loading, and PDF smart redirect
- **Latin American & Spain Accents** — Switch between Latin American (es-419) and Spain (es-ES) pronunciation styles
- **Spanish TTS** — Uses Chrome's built-in TTS with accent-matched Spanish voice for words and sentences
- **Selection Speech with Karaoke** — Select Spanish text; a toolbar offers speak and translate; speech highlights words in sync with audio
- **Selection Translation** — Bing or Google Translate for selected text, shown in an inline bubble
- **Keyboard Shortcuts** — Quick access including **Alt+Shift+I** (Mac: **Ctrl+Shift+I**) to toggle annotations
- **Multilingual Interface** — UI available in many languages (see extension settings)

---

## How to Use

### Step 1: Install the Extension

Install **Spanish Reader** from the [Chrome Web Store](https://chromewebstore.google.com/), or load it locally in developer mode.

### Step 2: Open Any Web Page

Visit any page with Spanish text you want to study.

### Step 3: Enable Pronunciation

Click the extension icon. Turn on **Enable Pronunciation**, then **Whole Page Mode** if you want annotations above every word.

### Step 4: Read Pronunciation and Definitions

Hover over words to see tooltips with pronunciation. Click the speaker icon to hear it spoken in your selected accent. When syllable breaks are enabled, you'll see word structure (e.g., "com·pu·ta·do·ra").

### Step 5: Speak and Translate Selection

Select Spanish text. A small toolbar offers **Speak** and **Translate**. You can also use the right-click menu: **Spanish Reader > Speak Selection** or **Translate Selection**.

> **Tip:** Open the extension popup to adjust accent, hover mode, speech rate, translation engine, PDF smart detection, and more.

---

## Whole Page Pronunciation Mode

With whole-page mode on, Spanish words on the page get pronunciation in ruby-style placement above the text.

The extension automatically adjusts line height so annotations stay readable and don't overlap with surrounding text. Font size scales for longer annotations.

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

The extension ships with a **Spanish definitions** dictionary (bundled locally, offline). Modes in settings:

| Mode | Behavior |
|------|----------|
| **Dictionary** | Pronunciation + Spanish definition + speaker button |
| **Tooltip** | Pronunciation + speaker button (no full definition panel) |
| **Off** | No hover popover |

In **Dictionary** mode you see: the headword, pronunciation, speak button, and definition text from the bundled data.

> **Tip:** Dictionary data loads when Dictionary mode is active and can unload when you switch modes to save memory.

---

## PDF Reader

Open PDFs with the same pronunciation, dictionary, speech, and translation features as on the web.

### Opening a PDF

**From the popup** — **Open PDF Reader** → drop a file or **Choose File**, or paste a URL.

**Context menu** — Right-click a `.pdf` link → **Open PDF with Spanish Reader**.

**Smart detection** — With **PDF Smart Detection** on, many `.pdf` URLs open in the built-in reader. If Chrome's viewer takes over, you may get a notice to open in Spanish Reader.

### PDF features

- Whole-page and per-word pronunciation; click-to-lookup in the reader where hover is not ideal
- Selection toolbar: speak, translate, copy
- Sidebar: outline and thumbnails; search; dark / light / sepia; zoom; keyboard navigation

---

## Selection Speech & Karaoke

**Toolbar** — Select Spanish text → **Speak** on the selection toolbar. Words highlight in step with TTS (karaoke) when the browser supports word boundaries; otherwise a timing fallback is used.

**Context menu** — **Spanish Reader > Speak Selection** after selection.

**Shortcut** — `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

> **Note:** For best quality, install OS-level **Spanish** voices; the extension requests a Spanish voice matching your selected accent via Chrome TTS.

---

## Translation

**Toolbar** — Select text → **Translate**; result appears in a bubble with copy.

**Context menu** — **Spanish Reader > Translate Selection**.

**Shortcut** — `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Engines:** Bing (default) and Google; many target languages. Translation needs the internet; only **selected** text is sent, when **you** trigger translate.

---

## Keyboard Shortcuts

| Shortcut | Mac | Action |
|----------|-----|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Toggle pronunciation annotations on/off |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Speak selected text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Translate selected text |

> Customize at `chrome://extensions/shortcuts` if your build differs.

---

## Settings Guide

| Setting | Description |
|---------|-------------|
| **Enable Pronunciation** | Master switch for pronunciation annotations on pages |
| **Whole Page Mode** | Show pronunciation above all Spanish words |
| **Accent** | Choose between Latin American and Spain pronunciation |
| **Show syllable breaks** | Display syllable division marks with stress indicators |
| **Hover Mode** | Dictionary / Tooltip / Off |
| **Sentence Speech Rate** | Speed for reading sentences (word-level TTS may use a fixed rate) |
| **Translation Engine** | Bing or Google |
| **Target Language** | Translation target (often auto from the browser) |
| **PDF Smart Detection** | Redirect `.pdf` URLs to the built-in reader; notifications when a PDF is detected |

Additional notes:

- **First visit:** After install, open the popup once to confirm defaults; refresh open tabs if annotations do not appear until reload.
- **Performance:** On very long articles, whole-page mode processes more text; use Tooltip-only mode if the page feels heavy.
- **Reading order:** For subtitles or multi-column pages, the extension follows the DOM; unusual layouts may need zoom or reader mode in the host site.

---

## Tips for Spanish learners

1. **Start with one paragraph** — Enable whole-page mode on a short news article before turning it on for an entire long page.
2. **Pair pronunciation with audio** — Click the speaker on new vocabulary; the extension uses a voice matching your selected accent (Latin American or Spain).
3. **Syllable breaks** — Pay attention to where the stress falls; Spanish has consistent rules, and the stressed syllable is always marked.
4. **PDF study** — Import lesson PDFs via **Open PDF Reader** so annotations stay consistent with web reading.
5. **Accent comparison** — Try switching between Latin American and Spain accents to hear how pronunciation differs (e.g., "c" before "e/i", "z", "ll").
6. **Privacy** — Dictionary and pronunciation never leave your device; use translation only when you are comfortable sending that exact selection to Microsoft or Google.

---

## FAQ

**Q: Why not on some pages?**  
A: Extensions cannot inject into `chrome://`, `edge://`, the Web Store, and similar internal pages.

**Q: Annotations are not showing after enabling.**  
A: Try refreshing the page. If the page was loaded before the extension was enabled, it may need a refresh.

**Q: No TTS sound?**  
A: Check volume and **Spanish** voice packs. The extension requests a Spanish voice; install Spanish voices in the OS or browser if needed.

**Q: Layout with whole-page mode?**  
A: Line height increases slightly; disable whole-page and use tooltips if you prefer a minimal layout.

**Q: Translation fails?**  
A: Network required; try switching engine; corporate firewalls may block APIs.

**Q: Open a PDF?**  
A: Popup **Open PDF Reader**, context menu on `.pdf` links, or **PDF Smart Detection**.

**Q: Dictionary offline?**  
A: Yes — Spanish definitions and pronunciation data are local; no network for lookups.

**Q: Is data sent for pronunciation?**  
A: No — pronunciation and dictionary runs **on device**. Only **optional** translation sends **your selected** text to Bing/Google when you use it.

**Q: Can I use the extension on social networks and forums?**  
A: Yes on normal `https` pages. Dynamic infinite feeds may need scrolling to load more content before toggling whole-page mode.

**Q: Support contact?**  
A: [2008-horse@163.com](mailto:2008-horse@163.com) for feedback and issues (see [Support page](../support)).

---

## Glossary (quick reference)

| Term | Meaning in this guide |
|------|------------------------|
| **IPA** | International Phonetic Alphabet — symbols representing Spanish sounds |
| **Syllable break** | Division of a word into its syllable components (shown with ·) |
| **Stress** | The emphasized syllable in a word, determined by Spanish accent rules |
| **Accent (regional)** | Latin American or Spain pronunciation variant |
| **Tilde** | Written accent mark (á, é, í, ó, ú) indicating stress position |
| **TTS** | Text-to-speech — the system that reads text aloud |

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
