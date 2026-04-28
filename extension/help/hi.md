---
layout: bare
title: Spanish Reader — उपयोगकर्ता मार्गदर्शिका
lang: hi
---

# Spanish Reader — उपयोगकर्ता मार्गदर्शिका

> Version: v1.0.0

## परिचय

Spanish Reader स्पेनिश सीखने वालों के लिए एक browser extension है। यह वेब पृष्ठों और PDF पर स्पेनिश शब्दों पर उच्चारण के लिए खास चिह्न और syllable break जोड़ता है, Latin American और Spain दोनों accents का समर्थन करता है। इसमें hover dictionary, text-to-speech और translation भी हैं — जिससे स्पेनिश का उच्चारण आसानी से सीख सकते हैं।

---

## मुख्य सुविधाएँ

- **Whole Page Pronunciation Mode** — एक क्लिक में पृष्ठ पर सभी स्पेनिश शब्दों पर उच्चारण चिह्न
- **Syllable Breaks** — हर शब्द के लिए syllable division और stress marking
- **Hover Dictionary** — शब्द पर mouse ले जाने से definition, उच्चारण और speaker button; Dictionary mode, Tooltip mode या Off चुनें
- **PDF Reader** — अंतर्निहित PDF reader जिसमें उच्चारण, dictionary, speech और translation; drag & drop, URL से खोलना और स्वचालित PDF detection
- **Latin American & Spain Accents** — Latin American (es-419) और Spain (es-ES) उच्चारण के बीच बदलाव
- **Text-to-Speech** — speaker button दबाकर चुने गए accent के अनुसार सुनें
- **Selection Speech with Karaoke Effect** — कोई भी स्पेनिश टेक्स्ट चुनें, छोटा toolbar speak और translate बटनों के साथ दिखे; real-time word-by-word highlighting के साथ speech
- **Selection Translation** — कोई भी टेक्स्ट चुनें, translate बटन से Bing या Google Translate के ज़रिए तुरंत अनुवाद
- **Keyboard Shortcuts** — अनुकूलन योग्य shortcuts से मुख्य सुविधाएँ तुरंत

---

## उपयोग कैसे करें

### चरण 1: Extension स्थापित करें

[Chrome Web Store](https://chromewebstore.google.com/) से **Spanish Reader** स्थापित करें, या developer mode में स्थानीय रूप से लोड करें।

### चरण 2: कोई भी वेब पृष्ठ खोलें

वह वेब पृष्ठ खोलें जिसमें स्पेनिश सामग्री हो।

### चरण 3: उच्चारण चालू करें

ब्राउज़र toolbar में extension आइकन पर क्लिक करें। "Enable Pronunciation" चालू करें, फिर "Whole Page Mode" चालू करें ताकि पृष्ठ पर सभी शब्दों पर चिह्न हों।

### चरण 4: उच्चारण देखें

शब्दों पर hover करके tooltip देखें। speaker आइकन से सुनें। Syllable breaks शब्द की संरचना दिखाते हैं (जैसे "com·pu·ta·do·ra")।

### चरण 5: चुने हुए टेक्स्ट को बोलें और अनुवाद करें

माउस से स्पेनिश टेक्स्ट चुनें। चयन के पास छोटा toolbar दो बटनों के साथ दिखेगा:
- **🔊 Speak** — चयनित टेक्स्ट को karaoke-शैली word-by-word highlighting के साथ पढ़ता है
- **🌐 Translate** — toolbar के नीचे inline अनुवाद bubble दिखाता है

> **Tip:** extension आइकन से settings panel खोलकर accent, speech rate, hover mode, translation engine आदि बदलें।

---

## Whole Page Pronunciation Mode

जब whole page pronunciation mode चालू हो, पृष्ठ पर हर स्पेनिश शब्द के ऊपर ruby text से उच्चारण चिह्न दिखता है।

Extension line height स्वतः समायोजित करता है ताकि चिह्न टेक्स्ट से न टकराएँ।

---

## Syllable Breaks

जब "Show syllable breaks" चालू हो, हर शब्द syllable division दिखाता है:

- Syllables middle dot (·) से अलग
- Stressed syllable स्पेनिश accent नियमों से तय
- लिखित accent (á, é, í, ó, ú) वाले शब्दों में हमेशा उसी syllable पर ज़ोर

इससे सीखने में मदद मिलती है:
- बोलते समय ज़ोर कहाँ रखें
- शब्द lines के बीच कैसे टूटते हैं
- स्पेनिश की लय और संरचना

---

## Hover Dictionary

Extension में hover dictionary है। settings में कई hover mode:

| Mode | व्यवहार |
|------|----------|
| **Dictionary** | Hover पर उच्चारण + definition + speaker button |
| **Tooltip** | Hover पर उच्चारण + speaker button (बिना definitions) |
| **Off** | कोई hover प्रभाव नहीं |

---

## PDF Reader

Spanish Reader में अंतर्निहित PDF reader है जिससे PDF में उच्चारण, dictionary, speech और translation के साथ पढ़ सकते हैं।

### PDF खोलना

**विधि 1: Popup से**  
extension आइकन पर क्लिक करें, फिर "Open PDF Reader" पर क्लिक करें। PDF drag & drop करें या "Choose File" से स्थानीय PDF खोलें। PDF URL भी paste कर सकते हैं।

**विधि 2: Context Menu**  
वेब पृष्ठ पर `.pdf` लिंक पर right-click करें और "Open PDF with Spanish Reader" चुनें।

**विधि 3: Automatic Detection**  
settings में "PDF Smart Detection" चालू होने पर extension `.pdf` URLs को अंतर्निहित reader पर स्वतः redirect करता है।

### PDF Reader सुविधाएँ

- **Pronunciation Annotations** — PDF टेक्स्ट पर सभी उच्चारण सुविधाएँ
- **Click Dictionary** — किसी भी शब्द पर क्लिक कर definition देखें
- **Selection Toolbar** — टेक्स्ट चुनकर speak, translate या copy
- **Sidebar** — विषयसूची outline और page thumbnails
- **Search** — PDF में टेक्स्ट खोज
- **Themes** — Dark, Light और Sepia
- **Zoom** — Auto, Page Fit और Page Width सहित कई स्तर

---

## Translation

पृष्ठ पर कोई भी टेक्स्ट चुनकर translation से तुरंत अनुवाद पाएँ।

**विधि 1: Selection Toolbar**  
टेक्स्ट चुनें, toolbar में 🌐 translate बटन दबाएँ।

**विधि 2: Right-Click Menu**  
टेक्स्ट चुनें, right-click करें और "Translate Selection" चुनें।

**विधि 3: Keyboard Shortcut**  
टेक्स्ट चुनें और `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) दबाएँ।

**Translation Engines:**
- **Bing Translate** (default) — Microsoft Translator
- **Google Translate** — Google

दोनों **108 target languages** समर्थित करते हैं।

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | क्रिया |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | pronunciation annotations चालू/बंद |
| `Alt+Shift+S` | `Ctrl+Shift+S` | चयनित टेक्स्ट बोलें |
| `Alt+Shift+T` | `Ctrl+Shift+T` | चयनित टेक्स्ट अनुवाद |

> **Tip:** Chrome में `chrome://extensions/shortcuts` पर जाकर इन shortcuts को बदल सकते हैं।

---

## Settings Guide

| Setting | विवरण |
|---------|--------|
| **Enable Pronunciation** | pronunciation annotation सुविधा का मुख्य switch |
| **Whole Page Mode** | चालू होने पर सभी स्पेनिश शब्दों के ऊपर उच्चारण |
| **Accent** | Latin American या Spain उच्चारण |
| **Show syllable breaks** | syllable division चिह्न |
| **Hover Mode** | Hover व्यवहार: Dictionary (उच्चारण + definitions + audio), Tooltip (उच्चारण + audio), या Off |
| **Sentence Speech Rate** | वाक्य पढ़ने की गति |
| **Translation Engine** | Bing Translate या Google Translate |
| **Target Language** | अनुवाद की लक्ष्य भाषा |
| **PDF Smart Detection** | चालू होने पर PDF URLs अंतर्निहित reader पर redirect |

---

## FAQ

**प्र: कुछ पृष्ठों पर यह क्यों काम नहीं करता?**  
उ: सुरक्षा कारणों से browser extension `chrome://`, browser settings या Chrome Web Store जैसे विशेष पृष्ठों पर नहीं चल सकता।

**प्र: text-to-speech से आवाज़ नहीं आती?**  
उ: सिस्टम वॉल्यूम जाँचें और Spanish voice packs स्थापित हों, यह सुनिश्चित करें।

**प्र: translation काम नहीं कर रहा?**  
उ: translation के लिए internet ज़रूरी है। अगर Bing Translate विफल हो तो settings में Google Translate आज़माएँ।

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
