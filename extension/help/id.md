---
layout: bare
title: Spanish Reader — Panduan Pengguna
lang: id
---

# Spanish Reader — Panduan Pengguna

> Version: v1.0.0

## Pengantar

Spanish Reader adalah browser extension untuk pembelajar bahasa Spanyol. Extension ini menambahkan anotasi pelafalan dan tanda pemisahan suku kata pada kata-kata bahasa Spanyol di halaman web dan PDF, mendukung aksen Amerika Latin dan Spanyol. Extension ini juga menyertakan hover dictionary, text-to-speech, dan translation — membantu Anda belajar pelafalan bahasa Spanyol dengan lebih mudah.

---

## Fitur Utama

- **Whole Page Pronunciation Mode** — Tambahkan anotasi pelafalan ke semua kata bahasa Spanyol di halaman dengan satu klik
- **Syllable Breaks** — Tampilkan pembagian suku kata dengan penanda aksen untuk setiap kata
- **Hover Dictionary** — Arahkan kursor ke kata untuk melihat definisi, pelafalan, dan tombol speaker; pilih Dictionary mode, Tooltip mode, atau Off
- **PDF Reader** — PDF reader bawaan dengan anotasi pelafalan, dictionary, speech, dan translation; mendukung drag & drop, loading URL, dan deteksi PDF otomatis
- **Latin American & Spain Accents** — Beralih antara pelafalan Latin American (es-419) dan Spain (es-ES)
- **Text-to-Speech** — Klik tombol speaker untuk mendengarkan pelafalan sesuai aksen yang dipilih
- **Selection Speech with Karaoke Effect** — Pilih teks bahasa Spanyol apa pun, toolbar ringkas muncul dengan tombol speak dan translate; audio diputar dengan penyorotan kata per kata secara real-time
- **Selection Translation** — Pilih teks apa pun, klik tombol translate untuk terjemahan instan melalui Bing atau Google Translate
- **Keyboard Shortcuts** — Akses cepat ke fitur inti melalui keyboard shortcuts yang dapat disesuaikan

---

## Cara Menggunakan

### Langkah 1: Instal Extension

Instal **Spanish Reader** dari [Chrome Web Store](https://chromewebstore.google.com/), atau muat secara lokal dalam developer mode.

### Langkah 2: Buka Halaman Web Mana Pun

Kunjungi halaman web yang berisi konten bahasa Spanyol.

### Langkah 3: Aktifkan Pelafalan

Klik ikon extension di toolbar browser. Aktifkan "Enable Pronunciation", lalu aktifkan "Whole Page Mode" untuk menganotasi semua kata di halaman.

### Langkah 4: Lihat Pelafalan

Arahkan kursor ke kata untuk melihat tooltip pelafalan. Klik ikon speaker untuk mendengar. Syllable breaks menampilkan struktur kata (mis. "com·pu·ta·do·ra").

### Langkah 5: Bicara dan Terjemahkan Teks yang Dipilih

Pilih teks bahasa Spanyol dengan mouse. Toolbar ringkas muncul di dekat seleksi dengan dua tombol:
- **🔊 Speak** — Membaca teks yang dipilih dengan penyorotan kata per kata bergaya karaoke
- **🌐 Translate** — Menampilkan gelembung terjemahan inline di bawah toolbar

> **Tip:** Klik ikon extension untuk membuka panel pengaturan dan sesuaikan jenis aksen, speech rate, hover mode, translation engine, dan lainnya.

---

## Whole Page Pronunciation Mode

Saat whole page pronunciation mode aktif, setiap kata bahasa Spanyol di halaman mendapat anotasi pelafalan di atasnya menggunakan ruby text.

Extension secara otomatis menyesuaikan line height agar anotasi tidak bertumpang tindih dengan teks.

---

## Syllable Breaks

Saat "Show syllable breaks" aktif, setiap kata menampilkan pembagian suku kata:

- Suku kata dipisahkan dengan middle dot (·)
- Suku kata bertekanan ditentukan menurut aturan aksen bahasa Spanyol
- Kata dengan aksen tertulis (á, é, í, ó, ú) selalu bertekanan pada suku kata yang beraksen

Ini membantu pembelajar memahami:
- Di mana menekankan saat berbicara
- Bagaimana kata dipisahkan antar baris
- Struktur ritmis bahasa Spanyol

---

## Hover Dictionary

Extension menyertakan hover dictionary. Anda dapat memilih beberapa hover mode di pengaturan:

| Mode | Perilaku |
|------|----------|
| **Dictionary** | Hover menampilkan pelafalan + definisi + tombol speaker |
| **Tooltip** | Hover menampilkan pelafalan + tombol speaker (tanpa definisi) |
| **Off** | Tidak ada efek hover |

---

## PDF Reader

Spanish Reader menyertakan PDF reader bawaan sehingga Anda dapat membaca dokumen PDF dengan anotasi pelafalan, dictionary, speech, dan translation.

### Membuka PDF

**Metode 1: Dari Popup**  
Klik ikon extension, lalu klik "Open PDF Reader". Seret dan lepas file PDF atau klik "Choose File" untuk membuka PDF lokal. Anda juga dapat menempel URL PDF.

**Metode 2: Context Menu**  
Klik kanan tautan `.pdf` di halaman web dan pilih "Open PDF with Spanish Reader".

**Metode 3: Automatic Detection**  
Saat "PDF Smart Detection" aktif di pengaturan, extension secara otomatis mengalihkan URL `.pdf` ke PDF reader bawaan.

### Fitur PDF Reader

- **Pronunciation Annotations** — Semua fitur pelafalan berfungsi pada teks PDF
- **Click Dictionary** — Klik kata apa pun untuk melihat definisinya
- **Selection Toolbar** — Pilih teks untuk speak, translate, atau copy
- **Sidebar** — Outline daftar isi dan thumbnail halaman
- **Search** — Cari teks di PDF
- **Themes** — Tema baca Dark, Light, dan Sepia
- **Zoom** — Beberapa tingkat zoom termasuk Auto, Page Fit, dan Page Width

---

## Translation

Pilih teks apa pun di halaman dan gunakan translation untuk mendapatkan terjemahan instan.

**Metode 1: Selection Toolbar**  
Pilih teks, lalu klik tombol 🌐 translate di toolbar.

**Metode 2: Right-Click Menu**  
Pilih teks, klik kanan dan pilih "Translate Selection".

**Metode 3: Keyboard Shortcut**  
Pilih teks dan tekan `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) untuk menerjemahkan.

**Translation Engines:**
- **Bing Translate** (default) — Didukung oleh Microsoft Translator
- **Google Translate** — Didukung oleh Google

Keduanya mendukung **108 target languages**.

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | Tindakan |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Aktifkan/nonaktifkan pronunciation annotations |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Ucapkan teks yang dipilih |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Terjemahkan teks yang dipilih |

> **Tip:** Anda dapat menyesuaikan shortcuts ini di Chrome di `chrome://extensions/shortcuts`.

---

## Settings Guide

| Setting | Deskripsi |
|---------|-----------|
| **Enable Pronunciation** | Saklar utama untuk mengaktifkan atau menonaktifkan fitur anotasi pelafalan |
| **Whole Page Mode** | Saat aktif, menampilkan pelafalan untuk semua kata bahasa Spanyol di atas teks |
| **Accent** | Pilih pelafalan Latin American atau Spain |
| **Show syllable breaks** | Tampilkan tanda pembagian suku kata |
| **Hover Mode** | Pilih perilaku hover: Dictionary (pelafalan + definisi + audio), Tooltip (pelafalan + audio), atau Off |
| **Sentence Speech Rate** | Sesuaikan kecepatan pembacaan kalimat |
| **Translation Engine** | Pilih Bing Translate atau Google Translate |
| **Target Language** | Setel bahasa target terjemahan |
| **PDF Smart Detection** | Saat aktif, secara otomatis mengalihkan URL PDF ke PDF reader bawaan |

---

## FAQ

**T: Mengapa tidak berfungsi di beberapa halaman?**  
J: Demi keamanan, browser extension tidak dapat berjalan di halaman khusus seperti `chrome://`, pengaturan browser, atau Chrome Web Store.

**T: Tidak ada suara dari text-to-speech?**  
J: Periksa volume sistem dan pastikan Spanish voice packs terinstal.

**T: Translation tidak berfungsi?**  
J: Translation memerlukan koneksi internet. Jika Bing Translate gagal, coba beralih ke Google Translate di pengaturan.

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
