---
layout: bare
title: Spanish Reader — Korisnički priručnik
lang: hr
---

# Spanish Reader — Korisnički priručnik

> Verzija: v1.0.0

## Uvod

Spanish Reader proširenje je za preglednik namijenjeno učenicima španjolskog. Dodaje izgovorne bilješke i oznake dijela slogova španjolskim riječima na web-stranicama i u PDF-ovima, uz podršku za latinoamerički i španjolski (Španjolska) akcent. Uključuje i rječnik pri lebdenju, text-to-speech i prijevod — kako biste lakše učili izgovor španjolskog.

---

## Glavne značajke

- **Način izgovora za cijelu stranicu** — jednim klikom dodajte izgovorne bilješke svim španjolskim riječima na stranici
- **Dijeljenje slogova** — prikažite podjelu slogova s naglaskom za svaku riječ
- **Rječnik pri lebdenju** — zadržite pokazivač iznad riječi da vidite definicije, izgovor i gumb zvučnika; odaberite Dictionary, Tooltip ili Off
- **PDF Reader** — ugrađeni PDF reader s izgovornim bilješkama, rječnikom, govorom i prijevodom; podržava drag & drop, učitavanje s URL-a i automatsko otkrivanje PDF-a
- **Latinoamerički i španjolski akcent** — prebacivanje između latinoameričkog (es-419) i španjolskog (es-ES) izgovora
- **Text-to-speech** — kliknite na zvučnik da čujete izgovor u odabranom akcentu
- **Govor odabira s karaoke efektom** — odaberite španjolski tekst; pojavljuje se kompaktna alatna traka s gumbima za govor i prijevod; reprodukcija ističe riječ po riječ u stvarnom vremenu
- **Prijevod odabira** — odaberite tekst, kliknite prijevod za trenutni prijevod putem Bing Translate ili Google Translate
- **Keyboard shortcuts** — brz pristup glavnim funkcijama putem prilagodljivih prečaca

---

## Korištenje

### Korak 1: Instalirajte proširenje

Instalirajte **Spanish Reader** iz [Chrome Web Store](https://chromewebstore.google.com/) ili ga lokalno učitajte u developer mode.

### Korak 2: Otvorite bilo koju web-stranicu

Posjetite stranicu sa španjolskim sadržajem.

### Korak 3: Uključite izgovor

Kliknite ikonu proširenja na alatnoj traci. Uključite „Enable Pronunciation“, zatim „Whole Page Mode“ da označite sve riječi na stranici.

### Korak 4: Pregledajte izgovor

Lebdite iznad riječi da vidite savjete s izgovorom. Kliknite ikonu zvučnika za reprodukciju. Kod uključenog dijeljenja slogova vidi se struktura riječi (npr. „com·pu·ta·do·ra“).

### Korak 5: Govorite i prevodite odabrani tekst

Mišem odaberite španjolski tekst. Pojavljuje se kompaktna alatna traka s dva gumba:
- **🔊 Speak** — čita odabrani tekst naglas s naglašavanjem riječi u karaoke stilu
- **🌐 Translate** — prikazuje ugrađenu oblačić prijevoda ispod alatne trake

> **Savjet:** Kliknite ikonu proširenja da otvorite postavke i prilagodite vrstu akcenta, brzinu govora, hover mode, translation engine i dr.

---

## Način izgovora za cijelu stranicu

Kad je uključen cjelostranični izgovor, svaka španjolska riječ ima izgovornu bilješku iznad sebe pomoću ruby text.

Proširenje automatski prilagođava visinu retka kako se bilješke ne bi preklapale s tekstom.

---

## Dijeljenje slogova

Kad je uključeno „Show syllable breaks“, svaka riječ pokazuje podjelu na slogove:

- Slogovi su odvojeni srednjom točkom (·)
- Naglašeni slog određuje se prema pravilima naglaska u španjolskom
- Riječi s pismenim naglaskom (á, é, í, ó, ú) uvijek imaju naglasak na tom slogu

To pomaže učenicima razumjeti:
- gdje staviti naglasak pri govoru
- kako se riječi lome na kraju redaka
- ritmičku strukturu španjolskog

---

## Rječnik pri lebdenju

Proširenje uključuje hover dictionary. U postavkama birate hover mode:

| Način | Ponašanje |
|-------|-----------|
| **Dictionary** | Lebdenje: izgovor + definicija + gumb zvučnika |
| **Tooltip** | Lebdenje: izgovor + zvučnik (bez definicija) |
| **Off** | Nema hover efekta |

---

## PDF Reader

Spanish Reader uključuje ugrađeni PDF reader za čitanje PDF-ova s izgovornim bilješkama, rječnikom, govorom i prijevodom.

### Otvaranje PDF-a

**Način 1: Iz skočnog prozora**  
Kliknite ikonu proširenja, zatim „Open PDF Reader“. Povucite i ispustite PDF ili kliknite „Choose File“ za lokalnu datoteku. Možete zalijepiti i URL PDF-a.

**Način 2: Kontekstni izbornik**  
Desni klik na `.pdf` vezu na stranici i odaberite „Open PDF with Spanish Reader“.

**Način 3: Automatsko otkrivanje**  
Kad je u postavkama uključeno „PDF Smart Detection“, proširenje automatski preusmjerava `.pdf` URL-ove na ugrađeni reader.

### Značajke PDF Readera

- **Pronunciation annotations** — sve izgovorne funkcije rade na PDF tekstu
- **Click dictionary** — klik na riječ za definiciju
- **Selection toolbar** — odabrani tekst za govor, prijevod ili kopiranje
- **Sidebar** — sadržaj (outline) i minijature stranica
- **Search** — pretraživanje teksta u PDF-u
- **Themes** — teme čitanja Dark, Light i Sepia
- **Zoom** — razine zumiranja uključujući Auto, Page Fit i Page Width

---

## Prijevod

Odaberite bilo koji tekst na stranici i upotrijebite prijevod za trenutne rezultate.

**Način 1: Selection toolbar**  
Odaberite tekst i kliknite gumb prijevoda 🌐.

**Način 2: Desni klik**  
Odaberite tekst, desni klik i „Translate Selection“.

**Način 3: Tipkovnički prečac**  
Odaberite tekst i pritisnite `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Translation engines:**
- **Bing Translate** (zadano) — Microsoft Translator
- **Google Translate** — Google

Oba podržavaju **108 target languages**.

---

## Tipkovni prečaci

| Prečac | Mac | Radnja |
|--------|-----|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Uključi/isključi izgovorne bilješke |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Pročitaj odabrani tekst |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Prevedi odabrani tekst |

> **Savjet:** Prečace prilagodite u Chromeu na `chrome://extensions/shortcuts`.

---

## Vodič kroz postavke

| Postavka | Opis |
|----------|------|
| **Enable Pronunciation** | Glavni prekidač za izgovorne bilješke |
| **Whole Page Mode** | Prikaz izgovora iznad svih španjolskih riječi |
| **Accent** | Latinoamerički ili španjolski (Španjolska) izgovor |
| **Show syllable breaks** | Prikaži oznake dijela slogova |
| **Hover Mode** | Dictionary (izgovor + definicije + audio), Tooltip (izgovor + audio) ili Off |
| **Sentence Speech Rate** | Brzina čitanja rečenica |
| **Translation Engine** | Bing Translate ili Google Translate |
| **Target Language** | Ciljni jezik prijevoda |
| **PDF Smart Detection** | Automatski preusmjeri PDF URL-ove na ugrađeni reader |

---

## Često postavljana pitanja

**Zašto ne radi na nekim stranicama?**  
Iz sigurnosnih razloga proširenja ne mogu raditi na posebnim stranicama poput `chrome://`, postavki preglednika ili Chrome Web Store.

**Nema zvuka iz text-to-speecha?**  
Provjerite glasnoću sustava i instalirane pakete španjolskih glasova.

**Prijevod ne radi?**  
Prijevod zahtijeva internetsku vezu. Ako Bing Translate ne uspije, u postavkama pokušajte Google Translate.

---

## Povezane poveznice

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
