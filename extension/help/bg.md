---
layout: bare
title: Spanish Reader — Ръководство за потребителя
lang: bg
---

# Spanish Reader — Ръководство за потребителя

> Version: v1.0.0

## Въведение

Spanish Reader е browser extension за изучаващи испански. Добавя анотации за произношение и маркери за сричково деление върху испански думи в уеб страници и PDF, с поддръжка на латиноамерикански и испански (на полуострова) акценти. Включва още hover dictionary, text-to-speech и translation — за по-лесно усвояване на испанското произношение.

---

## Основни възможности

- **Whole Page Pronunciation Mode** — С едно кликване добавя анотации за произношение към всички испански думи на страницата
- **Syllable Breaks** — Показва деление на срички и подчертаване на ударението за всяка дума
- **Hover Dictionary** — Задръжте курсора върху дума, за да видите дефиниция, произношение и speaker button; избирайте между Dictionary mode, Tooltip mode или Off
- **PDF Reader** — Вграден PDF reader с анотации за произношение, dictionary, speech и translation; поддържа drag & drop, зареждане по URL и автоматично разпознаване на PDF
- **Latin American & Spain Accents** — Превключване между произношение Latin American (es-419) и Spain (es-ES)
- **Text-to-Speech** — Кликнете speaker button, за да чуете произношението според избирания accent
- **Selection Speech with Karaoke Effect** — Маркирайте испански текст; появява се компактен toolbar с бутони speak и translate; речта се възпроизвежда с real-time word-by-word highlighting
- **Selection Translation** — Маркирайте текст, кликнете translate за моментален превод чрез Bing или Google Translate
- **Keyboard Shortcuts** — Бърз достъп до основните функции чрез настройваеми keyboard shortcuts
- **Многоезичен интерфейс** — Наличен на много езици

---

## Как да ползвате

### Стъпка 1: Инсталиране на extension

Инсталирайте **Spanish Reader** от [Chrome Web Store](https://chromewebstore.google.com/) или заредете локално в developer mode.

### Стъпка 2: Отворете уеб страница

Посетете страница с испанско съдържание.

### Стъпка 3: Включете произношението

Кликнете иконата на extension в toolbar на браузъра. Включете "Enable Pronunciation", после "Whole Page Mode", за да анотирате всички думи на страницата.

### Стъпка 4: Прегледайте произношението

Задържете курсора върху думи за tooltip с произношение. Кликнете speaker icon, за да чуете. Syllable breaks показват структурата на думата (напр. "com·pu·ta·do·ra").

### Стъпка 5: Четене и превод на маркиран текст

Маркирайте испански текст с мишката. Компактен toolbar се появява до селекцията с два бутона:
- **🔊 Speak** — Чете маркирания текст на глас с karaoke-style word-by-word highlighting
- **🌐 Translate** — Показва inline bubble с превод под toolbar

> **Tip:** Кликнете иконата на extension за panel с настройки: тип accent, speech rate, hover mode, translation engine и др.

---

## Whole Page Pronunciation Mode

Когато whole page pronunciation mode е включен, всяка испанска дума на страницата получава анотация за произношение над нея чрез ruby text.

Extension автоматично настройва line height, за да не се припокриват анотации с текста.

---

## Syllable Breaks

При включено "Show syllable breaks" всяка дума показва деление на срички:

- Сричките са разделени с middle dot (·)
- Ударената сричка се определя по правилата за accent в испанския
- Думи с писмено ударение (á, é, í, ó, ú) винаги имат ударение върху ударената сричка

Това помага на учащите да разберат:
- Къде да поставят ударението при говорене
- Как думите се разделят между редовете
- Ритмичната структура на испанския

---

## Hover Dictionary

Extension включва hover dictionary. В настройките можете да изберете hover mode:

| Mode | Поведение |
|------|----------|
| **Dictionary** | При hover: произношение + definition + speaker button |
| **Tooltip** | При hover: произношение + speaker button (без definitions) |
| **Off** | Без hover ефект |

---

## PDF Reader

Spanish Reader включва вграден PDF reader за четене на PDF с анотации за произношение, dictionary, speech и translation.

### Отваряне на PDF

**Метод 1: От Popup**  
Кликнете иконата на extension, после "Open PDF Reader". Пуснете PDF с drag & drop или използвайте "Choose File" за локален файл. Можете да поставите и URL на PDF.

**Метод 2: Context Menu**  
Десен бутон върху `.pdf` връзка на страницата и изберете "Open PDF with Spanish Reader".

**Метод 3: Automatic Detection**  
При включен "PDF Smart Detection" в настройките extension автоматично пренасочва `.pdf` URL към вградения reader.

### Функции на PDF Reader

- **Pronunciation Annotations** — Всички функции за произношение работят върху PDF текст
- **Click Dictionary** — Клик върху дума за definition
- **Selection Toolbar** — Маркирайте текст за speak, translate или copy
- **Sidebar** — Outline на съдържанието и page thumbnails
- **Search** — Търсене в PDF
- **Themes** — Теми Dark, Light и Sepia
- **Zoom** — Нива включително Auto, Page Fit и Page Width

---

## Translation

Маркирайте текст на страницата и ползвайте translation за моментален превод.

**Метод 1: Selection Toolbar**  
Маркирайте текст, кликнете бутона 🌐 translate в toolbar.

**Метод 2: Right-Click Menu**  
Маркирайте текст, десен бутон и "Translate Selection".

**Метод 3: Keyboard Shortcut**  
Маркирайте текст и натиснете `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Translation Engines:**
- **Bing Translate** (default) — Microsoft Translator
- **Google Translate** — Google

И двете поддържат **108 target languages**.

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | Действие |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Включване/изключване на pronunciation annotations |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Озвучаване на маркирания текст |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Превод на маркирания текст |

> **Tip:** Персонализирайте shortcuts в Chrome на `chrome://extensions/shortcuts`.

---

## Settings Guide

| Setting | Описание |
|---------|----------|
| **Enable Pronunciation** | Главен превключвател за pronunciation annotations |
| **Whole Page Mode** | При включване показва произношение над всички испански думи |
| **Accent** | Избор между Latin American и Spain произношение |
| **Show syllable breaks** | Показване на маркери за деление на срички |
| **Hover Mode** | Поведение при hover: Dictionary (произношение + definitions + audio), Tooltip (произношение + audio) или Off |
| **Sentence Speech Rate** | Скорост на четене на изречения |
| **Translation Engine** | Bing Translate или Google Translate |
| **Target Language** | Език на превода |
| **PDF Smart Detection** | При включване автоматично пренасочва PDF URL към вградения reader |

---

## FAQ

**В: Защо не работи на някои страници?**  
О: От съображения за сигурност browser extension не работи на специални страници като `chrome://`, настройки на браузъра или Chrome Web Store.

**В: Няма звук от text-to-speech?**  
О: Проверете системния volume и инсталирани Spanish voice packs.

**В: Translation не работи?**  
О: Нужна е internet връзка. Ако Bing Translate отказва, опитайте Google Translate в настройките.

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
