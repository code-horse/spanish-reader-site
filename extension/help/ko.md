---
layout: bare
title: Spanish Reader 확장 프로그램 - 사용 가이드
lang: ko
---

# Spanish Reader - 사용 가이드

> Version: v1.0.0

## 소개

Spanish Reader는 스페인어 학습자를 위한 브라우저 확장 프로그램입니다. 웹 페이지와 PDF의 스페인어 단어에 발음 표기와 음절 구분 표시를 추가하며, 라틴 아메리카와 스페인 억양을 모두 지원합니다. 또한 호버 사전, TTS(Text-to-Speech), 번역 기능이 있어 스페인어 발음을 더 쉽게 익힐 수 있습니다.

---

## 주요 기능

- **Whole Page Pronunciation Mode** — 한 번의 클릭으로 페이지의 모든 스페인어 단어에 발음 표기 추가
- **Syllable Breaks** — 모든 단어에 음절 나눔과 강세 표시
- **Hover Dictionary** — 단어에 마우스를 올리면 뜻, 발음, 스피커 버튼 표시; Dictionary, Tooltip 또는 Off 중 선택
- **PDF Reader** — 발음 표기, 사전, 음성, 번역이 있는 내장 PDF 리더; drag & drop, URL 로드, 자동 PDF 감지 지원
- **Latin American & Spain Accents** — 라틴 아메리카(es-419)와 스페인(es-ES) 발음 전환
- **Text-to-Speech** — 스피커 버튼을 눌러 선택한 억양에 맞는 발음 듣기
- **Selection Speech with Karaoke Effect** — 스페인어 텍스트를 선택하면 읽기·번역 버튼이 있는 컴팩트 도구 모음 표시; 재생 시 단어별 실시간 하이라이트
- **Selection Translation** — 텍스트를 선택하고 번역 버튼을 눌러 Bing Translate 또는 Google Translate로 즉시 번역
- **Keyboard Shortcuts** — 사용자 지정 가능한 단축키로 핵심 기능에 빠르게 접근
- **다국어 인터페이스** — 다양한 UI 언어 지원

---

## 사용 방법

### 1단계: 확장 프로그램 설치

[Chrome Web Store](https://chromewebstore.google.com/)에서 **Spanish Reader**를 설치하거나, 개발자 모드로 로컬에서 로드합니다.

### 2단계: 웹 페이지 열기

스페인어 콘텐츠가 있는 웹 페이지를 방문합니다.

### 3단계: 발음 켜기

브라우저 도구 모음의 확장 프로그램 아이콘을 클릭합니다. "Enable Pronunciation"을 켠 다음 "Whole Page Mode"를 켜 페이지의 모든 단어에 표기합니다.

### 4단계: 발음 보기

단어에 마우스를 올리면 발음 툴팁이 표시됩니다. 스피커 아이콘을 클릭하면 발음을 들을 수 있습니다. 음절 구분은 단어 구조를 보여 줍니다(예: "com·pu·ta·do·ra").

### 5단계: 선택한 텍스트 읽기 및 번역

마우스로 스페인어 텍스트를 선택합니다. 선택 영역 근처에 두 개의 버튼이 있는 작은 도구 모음이 나타납니다.
- **🔊 Speak** — 노래방 스타일로 단어별 하이라이트와 함께 선택 텍스트를 소리 내어 읽음
- **🌐 Translate** — 도구 모음 아래에 인라인 번역 말풍선 표시

> **팁:** 확장 프로그램 아이콘을 클릭해 설정 패널을 열고 억양 유형, 읽기 속도, 호버 모드, 번역 엔진 등을 조정할 수 있습니다.

---

## Whole Page Pronunciation Mode

Whole Page Pronunciation Mode가 켜지면 페이지의 모든 스페인어 단어 위에 ruby text로 발음 표기가 표시됩니다.

확장 프로그램은 표기가 본문과 겹치지 않도록 줄 간격을 자동으로 조정합니다.

---

## Syllable Breaks

"Show syllable breaks"가 켜지면 각 단어의 음절 나눔이 표시됩니다.

- 음절은 가운뎃점(·)으로 구분됩니다
- 강세 음절은 스페인어 강세 규칙에 따라 결정됩니다
- 악센트 기호가 있는 단어(á, é, í, ó, ú)는 항상 해당 음절에 강세가 있습니다

학습자가 다음을 이해하는 데 도움이 됩니다.
- 말할 때 어디에 강세를 둘지
- 줄 바꿈 시 단어가 어떻게 나뉘는지
- 스페인어의 리듬 구조

---

## Hover Dictionary

확장 프로그램에는 호버 사전이 있습니다. 설정에서 여러 호버 모드를 선택할 수 있습니다.

| 모드 | 동작 |
|------|----------|
| **Dictionary** | 호버 시 발음 + 정의 + 스피커 버튼 표시 |
| **Tooltip** | 호버 시 발음 + 스피커 버튼 표시(정의 없음) |
| **Off** | 호버 효과 없음 |

---

## PDF Reader

Spanish Reader에는 발음 표기, 사전, 음성, 번역으로 PDF 문서를 읽을 수 있는 내장 PDF Reader가 있습니다.

### PDF 열기

**방법 1: 팝업에서**  
확장 프로그램 아이콘을 클릭한 뒤 "Open PDF Reader"를 클릭합니다. PDF 파일을 drag & drop하거나 "Choose File"을 눌러 로컬 PDF를 엽니다. PDF URL을 붙여넣을 수도 있습니다.

**방법 2: 상황에 맞는 메뉴**  
웹 페이지의 `.pdf` 링크를 우클릭하고 "Open PDF with Spanish Reader"를 선택합니다.

**방법 3: 자동 감지**  
설정에서 "PDF Smart Detection"이 켜져 있으면 확장 프로그램이 `.pdf` URL을 내장 리더로 자동 리디렉션합니다.

### PDF Reader 기능

- **Pronunciation Annotations** — 모든 발음 기능이 PDF 텍스트에서 동작
- **Click Dictionary** — 단어를 클릭해 정의 확인
- **Selection Toolbar** — 텍스트를 선택해 읽기, 번역 또는 복사
- **Sidebar** — 목차 개요 및 페이지 썸네일
- **Search** — PDF에서 텍스트 검색
- **Themes** — Dark, Light, Sepia 읽기 테마
- **Zoom** — Auto, Page Fit, Page Width를 포함한 여러 배율

---

## 번역

페이지에서 텍스트를 선택하고 번역 기능을 사용하면 즉시 번역을 받을 수 있습니다.

**방법 1: 선택 도구 모음**  
텍스트를 선택한 뒤 도구 모음의 🌐 translate 버튼을 클릭합니다.

**방법 2: 우클릭 메뉴**  
텍스트를 선택하고 우클릭한 뒤 "Translate Selection"을 선택합니다.

**방법 3: 키보드 단축키**  
텍스트를 선택하고 `Alt+Shift+T`를 누릅니다(Mac: `Ctrl+Shift+T`).

**번역 엔진:**
- **Bing Translate**(기본) — Microsoft Translator 제공
- **Google Translate** — Google 제공

두 엔진 모두 **108**개 대상 언어를 지원합니다.

---

## 키보드 단축키

| 단축키 | Mac Shortcut | 동작 |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | 발음 표기 켜기/끄기 |
| `Alt+Shift+S` | `Ctrl+Shift+S` | 선택한 텍스트 읽기 |
| `Alt+Shift+T` | `Ctrl+Shift+T` | 선택한 텍스트 번역 |

> **팁:** Chrome의 `chrome://extensions/shortcuts`에서 이 단축키를 사용자 지정할 수 있습니다.

---

## 설정 안내

| 설정 | 설명 |
|---------|-------------|
| **Enable Pronunciation** | 발음 표기 기능을 켜거나 끄는 마스터 스위치 |
| **Whole Page Mode** | 켜면 모든 스페인어 단어 위에 발음 표시 |
| **Accent** | 라틴 아메리카 또는 스페인 발음 선택 |
| **Show syllable breaks** | 단어의 음절 구분 표시 |
| **Hover Mode** | 호버 동작 선택: Dictionary(발음 + 정의 + 오디오), Tooltip(발음 + 오디오), Off |
| **Sentence Speech Rate** | 문장 읽기 속도 조절 |
| **Translation Engine** | Bing Translate 또는 Google Translate 선택 |
| **Target Language** | 번역 대상 언어 설정 |
| **PDF Smart Detection** | 켜면 PDF URL을 내장 리더로 자동 리디렉션 |

---

## 자주 묻는 질문

**질문: 일부 페이지에서 동작하지 않는 이유는 무엇인가요?**  
답변: 보안상의 이유로 브라우저 확장 프로그램은 `chrome://`, 브라우저 설정, Chrome Web Store 같은 특수 페이지에서는 실행할 수 없습니다.

**질문: TTS에 소리가 나지 않나요?**  
답변: 시스템 음량 설정을 확인하고 스페인어 음성 팩이 설치되어 있는지 확인하세요.

**질문: 번역이 작동하지 않나요?**  
답변: 번역에는 인터넷 연결이 필요합니다. Bing Translate가 실패하면 설정에서 Google Translate로 바꿔 보세요.

---

## 관련 링크

- [개인정보처리방침](../privacy-policy)
- [지원 및 피드백](../support)

---
