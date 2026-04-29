---
layout: bare
title: Spanish Reader Extension - Guide d'utilisation
lang: fr
---

# Spanish Reader - Guide d'utilisation

> Version: v1.0.0

## Introduction

Spanish Reader est une extension de navigateur conçue pour les apprenants en espagnol. Elle ajoute des annotations de prononciation et des marques de découpage syllabique aux mots espagnols sur les pages web et les PDF, avec prise en charge des accents latino-américain et d’Espagne. Elle inclut aussi un dictionnaire au survol, la synthèse vocale (TTS) et la traduction — pour vous aider à maîtriser plus facilement la prononciation en espagnol.

---

## Fonctionnalités principales

- **Whole Page Pronunciation Mode** — Ajoute des annotations de prononciation à tous les mots espagnols de la page en un clic
- **Syllable Breaks** — Affiche la division syllabique et l’accent pour chaque mot
- **Hover Dictionary** — Survolez un mot pour voir la définition, la prononciation et le bouton haut-parleur ; choisissez le mode Dictionary, Tooltip ou Off
- **PDF Reader** — Lecteur PDF intégré avec annotations, dictionnaire, lecture et traduction ; prend en charge le glisser-déposer, le chargement par URL et la détection automatique des PDF
- **Latin American & Spain Accents** — Basculez entre la prononciation latino-américaine (es-419) et celle d’Espagne (es-ES)
- **Text-to-Speech** — Cliquez sur le bouton haut-parleur pour entendre la prononciation selon l’accent choisi
- **Selection Speech with Karaoke Effect** — Sélectionnez du texte espagnol : une barre d’outils compacte apparaît avec lecture et traduction ; la lecture met en surbrillance mot par mot en temps réel
- **Selection Translation** — Sélectionnez du texte, cliquez sur traduire pour une traduction instantanée via Bing Translate ou Google Translate
- **Keyboard Shortcuts** — Accès rapide aux fonctions essentielles grâce à des raccourcis clavier personnalisables
- **Interface multilingue** — Disponible en plusieurs langues

---

## Mode d’emploi

### Étape 1 : Installer l’extension

Installez **Spanish Reader** depuis le [Chrome Web Store](https://chromewebstore.google.com/), ou chargez-la localement en mode développeur.

### Étape 2 : Ouvrir une page web

Visitez une page contenant du contenu en espagnol.

### Étape 3 : Activer la prononciation

Cliquez sur l’icône de l’extension dans la barre d’outils. Activez « Enable Pronunciation », puis « Whole Page Mode » pour annoter tous les mots de la page.

### Étape 4 : Consulter la prononciation

Survolez les mots pour voir les infobulles de prononciation. Cliquez sur l’icône haut-parleur pour entendre. Les Syllable Breaks montrent la structure du mot (ex. : « com·pu·ta·do·ra »).

### Étape 5 : Lire et traduire la sélection

Sélectionnez du texte espagnol à la souris. Une barre d’outils compacte apparaît près de la sélection avec deux boutons :
- **🔊 Speak** — Lit le texte sélectionné à voix haute avec surbrillance mot par mot façon karaoké
- **🌐 Translate** — Affiche une bulle de traduction inline sous la barre d’outils

> **Astuce :** Cliquez sur l’icône de l’extension pour ouvrir les réglages et ajuster l’accent, la vitesse de lecture, le mode de survol, le moteur de traduction, etc.

---

## Whole Page Pronunciation Mode

Lorsque le Whole Page Pronunciation Mode est activé, chaque mot espagnol reçoit une annotation de prononciation au-dessus, via le ruby text.

L’extension ajuste automatiquement l’interligne pour éviter que les annotations chevauchent le texte.

---

## Syllable Breaks

Lorsque « Show syllable breaks » est activé, chaque mot affiche sa division syllabique :

- Les syllabes sont séparées par un point médian (·)
- La syllabe accentuée est déterminée selon les règles d’accentuation de l’espagnol
- Les mots avec accent écrit (á, é, í, ó, ú) ont toujours l’accent sur la syllabe marquée

Cela aide les apprenants à comprendre :
- Où placer l’accent à l’oral
- Comment les mots se coupent en fin de ligne
- La structure rythmique de l’espagnol

---

## Hover Dictionary

L’extension inclut un dictionnaire au survol. Plusieurs modes sont disponibles dans les réglages :

| Mode | Comportement |
|------|----------|
| **Dictionary** | Le survol affiche prononciation + définition + bouton haut-parleur |
| **Tooltip** | Le survol affiche prononciation + bouton haut-parleur (sans définitions) |
| **Off** | Aucun effet au survol |

---

## PDF Reader

Spanish Reader inclut un PDF Reader intégré pour lire des PDF avec annotations, dictionnaire, lecture et traduction.

### Ouvrir un PDF

**Méthode 1 : depuis le popup**  
Cliquez sur l’icône de l’extension, puis sur « Open PDF Reader ». Glissez-déposez un fichier PDF ou cliquez sur « Choose File » pour ouvrir un PDF local. Vous pouvez aussi coller une PDF URL.

**Méthode 2 : menu contextuel**  
Clic droit sur un lien `.pdf` et choisissez « Open PDF with Spanish Reader ».

**Méthode 3 : détection automatique**  
Si « PDF Smart Detection » est activé dans les réglages, l’extension redirige automatiquement les URL `.pdf` vers le lecteur intégré.

### Fonctions du PDF Reader

- **Pronunciation Annotations** — Toutes les fonctions de prononciation s’appliquent au texte du PDF
- **Click Dictionary** — Cliquez sur un mot pour voir sa définition
- **Selection Toolbar** — Sélectionnez du texte pour lire, traduire ou copier
- **Sidebar** — Table des matières et vignettes de pages
- **Search** — Recherche de texte dans le PDF
- **Themes** — Thèmes de lecture Dark, Light et Sepia
- **Zoom** — Plusieurs niveaux dont Auto, Page Fit et Page Width

---

## Traduction

Sélectionnez du texte sur la page et utilisez la traduction pour obtenir une traduction instantanée.

**Méthode 1 : barre de sélection**  
Sélectionnez du texte, puis cliquez sur le bouton 🌐 translate dans la barre.

**Méthode 2 : menu contextuel**  
Sélectionnez du texte, clic droit, puis « Translate Selection ».

**Méthode 3 : raccourci clavier**  
Sélectionnez du texte et appuyez sur `Alt+Shift+T` (Mac : `Ctrl+Shift+T`).

**Moteurs de traduction :**
- **Bing Translate** (par défaut) — Via Microsoft Translator
- **Google Translate** — Via Google

Les deux prennent en charge **108** langues cibles.

---

## Raccourcis clavier

| Raccourci | Raccourci (Mac) | Action |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Activer / désactiver les annotations de prononciation |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Lire la sélection |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduire la sélection |

> **Astuce :** Personnalisez ces raccourcis dans Chrome à l’adresse `chrome://extensions/shortcuts`.

---

## Guide des paramètres

| Réglage | Description |
|---------|-------------|
| **Enable Pronunciation** | Interrupteur principal pour activer ou désactiver les annotations de prononciation |
| **Whole Page Mode** | Affiche la prononciation au-dessus de tous les mots espagnols |
| **Accent** | Choisir la prononciation latino-américaine ou celle d’Espagne |
| **Show syllable breaks** | Afficher les marques de division syllabique |
| **Hover Mode** | Comportement au survol : Dictionary (prononciation + définitions + audio), Tooltip (prononciation + audio) ou Off |
| **Sentence Speech Rate** | Vitesse de lecture des phrases |
| **Translation Engine** | Bing Translate ou Google Translate |
| **Target Language** | Langue cible de la traduction |
| **PDF Smart Detection** | Redirige automatiquement les PDF URL vers le lecteur intégré |

---

## FAQ

**Q : Pourquoi cela ne fonctionne-t-il pas sur certaines pages ?**  
R : Pour des raisons de sécurité, les extensions ne peuvent pas s’exécuter sur des pages spéciales comme `chrome://`, les réglages du navigateur ou le Chrome Web Store.

**Q : Pas de son pour le TTS ?**  
R : Vérifiez le volume système et assurez-vous que les voix espagnoles sont installées.

**Q : La traduction ne marche pas ?**  
R : La traduction nécessite une connexion Internet. Si Bing Translate échoue, essayez Google Translate dans les réglages.

---

## Liens utiles

- [Politique de confidentialité](../privacy-policy)
- [Assistance et commentaires](../support)

---
