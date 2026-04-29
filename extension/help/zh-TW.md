---
layout: bare
title: Spanish Reader 擴充功能 - 使用手冊
lang: zh-TW
---

# Spanish Reader - 使用手冊

> Version: v1.0.0

## 簡介

Spanish Reader 是專為西班牙語學習者設計的瀏覽器擴充功能。它會在網頁與 PDF 上的西班牙語單字旁加入發音標註與音節切分標記，支援拉丁美洲與西班牙口音。另內建懸浮字典、文字轉語音（TTS）與翻譯功能，協助你更輕鬆地學習西班牙語發音。

---

## 主要功能

- **Whole Page Pronunciation Mode** — 一鍵為頁面上所有西班牙語單字加上發音標註
- **Syllable Breaks** — 顯示每個單字的音節劃分與重音標示
- **Hover Dictionary** — 將滑鼠懸停在單字上可查看釋義、發音與喇叭按鈕；可在 Dictionary、Tooltip 或 Off 模式間選擇
- **PDF Reader** — 內建 PDF 閱讀器，具發音標註、字典、朗讀與翻譯；支援拖放、以 URL 載入與自動 PDF 偵測
- **Latin American & Spain Accents** — 在拉丁美洲（es-419）與西班牙（es-ES）發音之間切換
- **Text-to-Speech** — 點選喇叭按鈕，可依所選口音聽取發音
- **Selection Speech with Karaoke Effect** — 選取任何西班牙語文字後會出現精簡工具列（朗讀與翻譯按鈕）；朗讀時會即時逐字高亮
- **Selection Translation** — 選取任何文字後點翻譯按鈕，可透過 Bing Translate 或 Google Translate 即時翻譯
- **Keyboard Shortcuts** — 透過可自訂的快速鍵快速使用核心功能
- **多語言介面** — 支援多種介面語言

---

## 使用方式

### 步驟 1：安裝擴充功能

從 [Chrome Web Store](https://chromewebstore.google.com/) 安裝 **Spanish Reader**，或以開發人員模式在本機載入。

### 步驟 2：開啟任意網頁

瀏覽包含西班牙語內容的任意網頁。

### 步驟 3：啟用發音

點選瀏覽器工具列中的擴充功能圖示。開啟「Enable Pronunciation」，再開啟「Whole Page Mode」以標註頁面上所有單字。

### 步驟 4：查看發音

將滑鼠懸停在單字上可查看發音提示。點選喇叭圖示可聆聽發音。音節切分會顯示單字結構（例如："com·pu·ta·do·ra"）。

### 步驟 5：朗讀與翻譯選取文字

以滑鼠選取任何西班牙語文字。選取區附近會出現具兩個按鈕的精簡工具列：
- **🔊 Speak** — 以卡拉 OK 式逐字高亮朗讀選取文字
- **🌐 Translate** — 在工具列下方顯示內嵌翻譯氣泡

> **提示：** 點選擴充功能圖示可開啟設定面板，調整口音類型、朗讀速度、懸浮模式、翻譯引擎等。

---

## Whole Page Pronunciation Mode

啟用 Whole Page Pronunciation Mode 時，頁面上每個西班牙語單字上方會以 ruby text 顯示發音標註。

擴充功能會自動調整行高，避免標註與正文重疊。

---

## Syllable Breaks

啟用「Show syllable breaks」時，每個單字會顯示音節劃分：

- 音節之間以中點（·）分隔
- 重音音節依西班牙語重音規則判定
- 帶有書寫重音符號的單字（á、é、í、ó、ú）重音永遠在該音節

有助於學習者了解：
- 說話時重音應落在何處
- 單字在換行時如何斷開
- 西班牙語的節奏結構

---

## Hover Dictionary

擴充功能內建懸浮字典。可在設定中選擇多種懸浮模式：

| 模式 | 效果 |
|------|----------|
| **Dictionary** | 懸停顯示發音 + 釋義 + 喇叭按鈕 |
| **Tooltip** | 懸停顯示發音 + 喇叭按鈕（無釋義） |
| **Off** | 無懸停效果 |

---

## PDF Reader

Spanish Reader 內建 PDF Reader，可在具發音標註、字典、朗讀與翻譯的情況下閱讀 PDF。

### 開啟 PDF

**方式 1：從 Pop-up**  
點選擴充功能圖示，再點選「Open PDF Reader」。拖放 PDF 檔案或點選「Choose File」開啟本機 PDF。亦可貼上 PDF URL。

**方式 2：情境選單**  
在網頁上對 `.pdf` 連結右鍵，選擇「Open PDF with Spanish Reader」。

**方式 3：自動偵測**  
在設定中啟用「PDF Smart Detection」時，擴充功能會自動將 `.pdf` URL 重新導向內建閱讀器。

### PDF Reader 功能

- **Pronunciation Annotations** — 所有發音功能皆適用於 PDF 文字
- **Click Dictionary** — 點選任意單字查看釋義
- **Selection Toolbar** — 選取文字以朗讀、翻譯或複製
- **Sidebar** — 目錄大綱與頁面縮圖
- **Search** — 在 PDF 中搜尋文字
- **Themes** — Dark、Light 與 Sepia 閱讀主題
- **Zoom** — 多種縮放層級，含 Auto、Page Fit、Page Width

---

## 翻譯

選取頁面上任意文字並使用翻譯功能即可取得即時翻譯。

**方式 1：選取工具列**  
選取文字後，點選工具列上的 🌐 translate 按鈕。

**方式 2：右鍵選單**  
選取文字後右鍵，選擇「Translate Selection」。

**方式 3：鍵盤快速鍵**  
選取文字後按下 `Alt+Shift+T`（Mac：`Ctrl+Shift+T`）翻譯。

**翻譯引擎：**
- **Bing Translate**（預設）— 由 Microsoft Translator 提供
- **Google Translate** — 由 Google 提供

兩種引擎皆支援 **108** 種目標語言。

---

## 鍵盤快速鍵

| 快速鍵 | Mac Shortcut | 功能 |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | 開啟／關閉發音標註 |
| `Alt+Shift+S` | `Ctrl+Shift+S` | 朗讀選取文字 |
| `Alt+Shift+T` | `Ctrl+Shift+T` | 翻譯選取文字 |

> **提示：** 可在 Chrome 的 `chrome://extensions/shortcuts` 自訂這些快速鍵。

---

## 設定說明

| 設定 | 說明 |
|---------|-------------|
| **Enable Pronunciation** | 開啟或關閉發音標註功能的主開關 |
| **Whole Page Mode** | 啟用時，在所有西班牙語單字上方顯示發音 |
| **Accent** | 選擇拉丁美洲或西班牙發音 |
| **Show syllable breaks** | 顯示單字的音節切分標記 |
| **Hover Mode** | 選擇懸停行為：Dictionary（發音 + 釋義 + 音訊）、Tooltip（發音 + 音訊）或 Off |
| **Sentence Speech Rate** | 調整句子朗讀速度 |
| **Translation Engine** | 選擇 Bing Translate 或 Google Translate |
| **Target Language** | 設定翻譯目標語言 |
| **PDF Smart Detection** | 啟用時，自動將 PDF URL 重新導向內建閱讀器 |

---

## 常見問題

**問：為什麼某些頁面無法使用？**  
答：基於安全考量，瀏覽器擴充功能無法在 `chrome://`、瀏覽器設定或 Chrome Web Store 等特殊頁面執行。

**問：文字轉語音沒有聲音？**  
答：請檢查系統音量設定，並確認已安裝西班牙語語音套件。

**問：翻譯無法使用？**  
答：翻譯需要網路連線。若 Bing Translate 失敗，請在設定中改試 Google Translate。

---

## 相關連結

- [隱私權政策](../privacy-policy)
- [支援與意見回饋](../support)

---
