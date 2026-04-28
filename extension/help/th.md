---
layout: bare
title: Spanish Reader — คู่มือการใช้งาน
lang: th
---

# Spanish Reader — คู่มือการใช้งาน

> Version: v1.0.0

## บทนำ

Spanish Reader เป็น browser extension สำหรับผู้เรียนภาษาสเปน เพิ่มเสียงอ่านและเครื่องหมายแบ่งพยางค์ให้กับคำภาษาสเปนบนหน้าเว็บและ PDF รองรับ accent ทั้งแบบละตินอเมริกาและสเปน มี hover dictionary, text-to-speech และ translation — ช่วยให้ฝึกการออกเสียงภาษาสเปนได้ง่ายขึ้น

---

## คุณสมบัติหลัก

- **Whole Page Pronunciation Mode** — เพิ่มคำอ่านให้คำภาษาสเปนทั้งหน้าในคลิกเดียว
- **Syllable Breaks** — แสดงการแบ่งพยางค์พร้อมระบุความเค้นของทุกคำ
- **Hover Dictionary** — เลื่อนเมาส์เหนือคำเพื่อดูคำอธิบาย การออกเสียง และปุ่ม speaker เลือกได้ระหว่าง Dictionary mode, Tooltip mode หรือ Off
- **PDF Reader** — ตัวอ่าน PDF ในตัวพร้อมคำอ่าน dictionary การอ่านออกเสียงและ translation รองรับ drag & drop โหลดจาก URL และการตรวจจับ PDF อัตโนมัติ
- **Latin American & Spain Accents** — สลับระหว่างการออกเสียง Latin American (es-419) และ Spain (es-ES)
- **Text-to-Speech** — คลิกปุ่ม speaker เพื่อฟังการออกเสียงตาม accent ที่เลือก
- **Selection Speech with Karaoke Effect** — เลือกข้อความภาษาสเปน แถบเครื่องมือเล็กจะปรากฏพร้อมปุ่ม speak และ translate เสียงเล่นพร้อมไฮไลต์ทีละคำแบบเรียลไทม์
- **Selection Translation** — เลือกข้อความใดก็ได้ คลิกปุ่ม translate เพื่อแปลทันทีผ่าน Bing หรือ Google Translate
- **Keyboard Shortcuts** — เข้าถึงคุณสมบัติหลักได้เร็วผ่าน keyboard shortcuts ที่ปรับได้

---

## วิธีใช้

### ขั้นตอนที่ 1: ติดตั้ง Extension

ติดตั้ง **Spanish Reader** จาก [Chrome Web Store](https://chromewebstore.google.com/) หรือโหลดในเครื่องใน developer mode

### ขั้นตอนที่ 2: เปิดหน้าเว็บ

เปิดหน้าเว็บที่มีเนื้อหาภาษาสเปน

### ขั้นตอนที่ 3: เปิดการออกเสียง

คลิกไอคอน extension ในแถบเครื่องมือเบราว์เซอร์ เปิด "Enable Pronunciation" แล้วเปิด "Whole Page Mode" เพื่อใส่คำอ่านให้ทุกคำบนหน้า

### ขั้นตอนที่ 4: ดูการออกเสียง

เลื่อนเมาส์เหนือคำเพื่อดู tooltip การออกเสียง คลิกไอคอน speaker เพื่อฟัง Syllable breaks แสดงโครงคำ (เช่น "com·pu·ta·do·ra")

### ขั้นตอนที่ 5: อ่านและแปลข้อความที่เลือก

เลือกข้อความภาษาสเปนด้วยเมาส์ แถบเครื่องมือเล็กจะปรากฏใกล้การเลือกพร้อมสองปุ่ม:
- **🔊 Speak** — อ่านข้อความที่เลือกออกเสียงพร้อมไฮไลต์ทีละคำแบบ karaoke
- **🌐 Translate** — แสดงฟองแปลใต้แถบเครื่องมือ

> **Tip:** คลิกไอคอน extension เพื่อเปิดแผงการตั้งค่าและปรับประเภท accent, speech rate, hover mode, translation engine และอื่นๆ

---

## Whole Page Pronunciation Mode

เมื่อเปิด whole page pronunciation mode คำภาษาสเปนทุกคำบนหน้าจะมีคำอ่านแสดงเหนือคำโดยใช้ ruby text

Extension ปรับ line height อัตโนมัติเพื่อไม่ให้คำอ่านทับข้อความ

---

## Syllable Breaks

เมื่อเปิด "Show syllable breaks" แต่ละคำจะแสดงการแบ่งพยางค์:

- พยางค์คั่นด้วย middle dot (·)
- พยางค์ที่เน้นเสียงระบุตามกฎ stress ของภาษาสเปน
- คำที่มีเครื่องหมายเน้นเสียง (á, é, í, ó, ú) จะเน้นที่พยางค์ที่มีเครื่องหมายเสมอ

ช่วยผู้เรียนเข้าใจ:
- เน้นตรงไหนเมื่อพูด
- คำแบ่งข้ามบรรทัดอย่างไร
- จังหวะและโครงสร้างของภาษาสเปน

---

## Hover Dictionary

Extension มี hover dictionary เลือก hover mode ในการตั้งค่าได้หลายแบบ:

| Mode | พฤติกรรม |
|------|----------|
| **Dictionary** | เมื่อ hover แสดงการออกเสียง + คำจำกัดความ + ปุ่ม speaker |
| **Tooltip** | เมื่อ hover แสดงการออกเสียง + ปุ่ม speaker (ไม่มีคำจำกัดความ) |
| **Off** | ไม่มีเอฟเฟกต์เมื่อ hover |

---

## PDF Reader

Spanish Reader มี PDF Reader ในตัวให้อ่านเอกสาร PDF พร้อมคำอ่าน dictionary การอ่านออกเสียงและ translation

### เปิด PDF

**วิธีที่ 1: จาก Popup**  
คลิกไอคอน extension แล้วคลิก "Open PDF Reader" ลากไฟล์ PDF มาวางหรือคลิก "Choose File" เพื่อเปิด PDF ในเครื่อง หรือวาง URL ของ PDF

**วิธีที่ 2: Context Menu**  
คลิกขวาที่ลิงก์ `.pdf` บนหน้าเว็บแล้วเลือก "Open PDF with Spanish Reader"

**วิธีที่ 3: Automatic Detection**  
เมื่อเปิด "PDF Smart Detection" ในการตั้งค่า extension จะ redirect URL ที่เป็น `.pdf` ไปยัง PDF Reader ในตัวโดยอัตโนมัติ

### คุณสมบัติของ PDF Reader

- **Pronunciation Annotations** — คุณสมบัติการออกเสียงทำงานกับข้อความใน PDF
- **Click Dictionary** — คลิกคำใดก็ได้เพื่อดูคำจำกัดความ
- **Selection Toolbar** — เลือกข้อความเพื่อ speak, translate หรือ copy
- **Sidebar** — สารบัญและ thumbnail หน้า
- **Search** — ค้นหาข้อความใน PDF
- **Themes** — Dark, Light และ Sepia
- **Zoom** — หลายระดับรวมถึง Auto, Page Fit และ Page Width

---

## Translation

เลือกข้อความบนหน้าแล้วใช้ translation เพื่อแปลทันที

**วิธีที่ 1: Selection Toolbar**  
เลือกข้อความแล้วคลิกปุ่ม 🌐 translate ในแถบเครื่องมือ

**วิธีที่ 2: Right-Click Menu**  
เลือกข้อความ คลิกขวาแล้วเลือก "Translate Selection"

**วิธีที่ 3: Keyboard Shortcut**  
เลือกข้อความแล้วกด `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) เพื่อแปล

**Translation Engines:**
- **Bing Translate** (default) — ใช้ Microsoft Translator
- **Google Translate** — ใช้ Google

ทั้งสองรองรับ **108 target languages**

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | การกระทำ |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | เปิด/ปิด pronunciation annotations |
| `Alt+Shift+S` | `Ctrl+Shift+S` | อ่านข้อความที่เลือกออกเสียง |
| `Alt+Shift+T` | `Ctrl+Shift+T` | แปลข้อความที่เลือก |

> **Tip:** ปรับ shortcuts เหล่านี้ใน Chrome ที่ `chrome://extensions/shortcuts`

---

## Settings Guide

| Setting | คำอธิบาย |
|---------|---------|
| **Enable Pronunciation** | สวิตช์หลักเปิด/ปิดคุณสมบัติ pronunciation annotations |
| **Whole Page Mode** | เมื่อเปิด แสดงคำอ่านเหนือคำภาษาสเปนทุกคำ |
| **Accent** | เลือก Latin American หรือ Spain pronunciation |
| **Show syllable breaks** | แสดงเครื่องหมายแบ่งพยางค์ |
| **Hover Mode** | พฤติกรรมเมื่อ hover: Dictionary (การออกเสียง + คำจำกัดความ + audio), Tooltip (การออกเสียง + audio) หรือ Off |
| **Sentence Speech Rate** | ปรับความเร็วการอ่านประโยค |
| **Translation Engine** | เลือก Bing Translate หรือ Google Translate |
| **Target Language** | ตั้งภาษาปลายทางสำหรับการแปล |
| **PDF Smart Detection** | เมื่อเปิด redirect URL PDF ไป PDF Reader ในตัวโดยอัตโนมัติ |

---

## FAQ

**ถาม: ทำไมบางหน้าใช้งานไม่ได้?**  
ตอบ: เหตุผลด้านความปลอดภัย browser extension ทำงานบนหน้าพิเศษเช่น `chrome://` browser settings หรือ Chrome Web Store ไม่ได้

**ถาม: text-to-speech ไม่มีเสียง?**  
ตอบ: ตรวจสอบระดับเสียงระบบและติดตั้ง Spanish voice packs

**ถาม: translation ใช้ไม่ได้?**  
ตอบ: ต้องเชื่อมต่ออินเทอร์เน็ต หาก Bing Translate ล้มเหลว ลองสลับเป็น Google Translate ในการตั้งค่า

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
