---
layout: bare
title: Spanish Reader Extension - Guide d'utilisation
lang: fr
---

# Spanish Reader - Guide d'utilisation

> Version : v1.5.1

## Introduction

Spanish Reader est une extension de navigateur conçue pour les apprenants en espagnol. Elle ajoute des annotations de prononciation et des marques de découpage syllabique aux mots espagnols sur les pages web et les PDF, avec prise en charge des accents latino-américain et d'Espagne. Elle inclut aussi un dictionnaire au survol, la synthèse vocale (TTS) et la traduction — pour vous aider à maîtriser plus facilement la prononciation en espagnol.

---

## Fonctionnalités principales

- **Mode prononciation page entière** — Ajoute des annotations de prononciation à tous les mots espagnols de la page en un clic
- **Division syllabique** — Affiche la division syllabique et l'accent pour chaque mot (ex. : « com·pu·ta·do·ra »)
- **Dictionnaire au survol** — Survolez un mot pour voir la définition, la prononciation et le bouton haut-parleur ; choisissez le mode Dictionnaire, Infobulle ou Désactivé
- **Lecteur PDF** — Lecteur PDF intégré avec annotations, dictionnaire, lecture et traduction ; prend en charge le glisser-déposer, le chargement par URL et la détection automatique des PDF
- **Accents latino-américain et espagnol** — Basculez entre la prononciation latino-américaine (es-419) et celle d'Espagne (es-ES)
- **TTS espagnol** — Cliquez sur le bouton haut-parleur pour entendre la prononciation selon l'accent choisi via Chrome TTS
- **Lecture avec karaoké** — Sélectionnez du texte espagnol : une barre d'outils compacte apparaît avec lecture et traduction ; surbrillance mot par mot
- **Traduction de la sélection** — Sélectionnez du texte pour une traduction instantanée via Bing ou Google Traduction
- **Raccourcis clavier** — Accès rapide aux fonctions essentielles
- **Interface multilingue** — Disponible en plusieurs langues

---

## Mode d'emploi

### Étape 1 : Installer l'extension

Installez **Spanish Reader** depuis le [Chrome Web Store](https://chromewebstore.google.com/), ou chargez-la localement en mode développeur.

### Étape 2 : Ouvrir une page web

Visitez une page contenant du contenu en espagnol.

### Étape 3 : Activer la prononciation

Cliquez sur l'icône de l'extension dans la barre d'outils. Activez **Activer la prononciation**, puis **Mode page entière** pour annoter tous les mots de la page.

### Étape 4 : Consulter la prononciation

Survolez les mots pour voir les infobulles de prononciation. Cliquez sur l'icône haut-parleur pour entendre. La division syllabique montre la structure du mot (ex. : « com·pu·ta·do·ra »).

### Étape 5 : Lire et traduire la sélection

Sélectionnez du texte espagnol à la souris. Une barre d'outils compacte apparaît près de la sélection :
- **Lire** — Lit le texte sélectionné à voix haute avec surbrillance mot par mot façon karaoké
- **Traduire** — Affiche une bulle de traduction sous la barre d'outils

Vous pouvez aussi utiliser le menu contextuel : **Spanish Reader > Lire la sélection** ou **Traduire la sélection**.

> **Astuce :** Cliquez sur l'icône de l'extension pour ouvrir les réglages et ajuster l'accent, la vitesse de lecture, le mode de survol, le moteur de traduction, etc.

---

## Mode prononciation page entière

Lorsque le mode page entière est activé, chaque mot espagnol reçoit une annotation de prononciation au-dessus, via le ruby text. L'extension ajuste automatiquement l'interligne.

---

## Division syllabique

Lorsque **Afficher la division syllabique** est activé, chaque mot affiche sa division syllabique :

- Les syllabes sont séparées par un point médian (·)
- La syllabe accentuée est déterminée selon les règles d'accentuation de l'espagnol
- Les mots avec accent écrit (á, é, í, ó, ú) ont toujours l'accent sur la syllabe marquée

---

## Dictionnaire au survol

L'extension inclut un dictionnaire de **définitions espagnoises** (local, hors ligne). Modes disponibles dans les réglages :

| Mode | Comportement |
|------|----------|
| **Dictionnaire** | Le survol affiche prononciation + définition espagnoise + bouton haut-parleur |
| **Infobulle** | Le survol affiche prononciation + bouton haut-parleur (sans définitions) |
| **Désactivé** | Aucun effet au survol |

> **Astuce :** Les données du dictionnaire se chargent uniquement en mode Dictionnaire.

---

## Lecteur PDF

Spanish Reader inclut un lecteur PDF intégré pour lire des PDF avec annotations, dictionnaire, lecture et traduction.

### Ouvrir un PDF

**Depuis le popup** — Cliquez sur l'icône de l'extension, puis sur **Ouvrir le lecteur PDF**. Glissez-déposez un fichier PDF ou cliquez sur **Choisir un fichier**. Vous pouvez aussi coller une URL de PDF.

**Menu contextuel** — Clic droit sur un lien `.pdf` et choisissez **Ouvrir le PDF avec Spanish Reader**.

**Détection automatique** — Si **Détection intelligente des PDF** est activé, l'extension redirige automatiquement les URL `.pdf` vers le lecteur intégré.

### Fonctions du lecteur PDF

- Annotations de prononciation sur tout le texte
- Dictionnaire par clic sur les mots
- Barre de sélection : lire, traduire ou copier
- Barre latérale : table des matières et vignettes
- Recherche, thèmes (sombre/clair/sépia), zoom

---

## Traduction

Sélectionnez du texte sur la page et utilisez la traduction pour obtenir une traduction instantanée.

**Barre de sélection** — Sélectionnez du texte, puis cliquez sur **Traduire** dans la barre.

**Menu contextuel** — Sélectionnez du texte, clic droit, puis **Traduire la sélection**.

**Raccourci clavier** — Sélectionnez du texte et appuyez sur `Alt+Shift+T` (Mac : `Ctrl+Shift+T`).

**Moteurs de traduction :** Bing (par défaut) et Google Traduction ; de nombreuses langues cibles.

---

## Raccourcis clavier

| Raccourci | Mac | Action |
|----------|-----|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Activer / désactiver les annotations de prononciation |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Lire la sélection |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduire la sélection |

> **Astuce :** Personnalisez ces raccourcis dans Chrome à l'adresse `chrome://extensions/shortcuts`.

---

## Guide des paramètres

| Réglage | Description |
|---------|-------------|
| **Activer la prononciation** | Interrupteur principal pour les annotations de prononciation |
| **Mode page entière** | Affiche la prononciation au-dessus de tous les mots espagnols |
| **Accent** | Choisir la prononciation latino-américaine ou celle d'Espagne |
| **Afficher la division syllabique** | Afficher les marques de division syllabique |
| **Mode de survol** | Dictionnaire (prononciation + définitions + audio), Infobulle (prononciation + audio) ou Désactivé |
| **Vitesse de lecture** | Vitesse de lecture des phrases |
| **Moteur de traduction** | Bing ou Google Traduction |
| **Langue cible** | Langue cible de la traduction |
| **Détection intelligente des PDF** | Redirige automatiquement les URL PDF vers le lecteur intégré |

---

## FAQ

**Q : Pourquoi cela ne fonctionne-t-il pas sur certaines pages ?**  
R : Pour des raisons de sécurité, les extensions ne peuvent pas s'exécuter sur des pages spéciales comme `chrome://`, les réglages du navigateur ou le Chrome Web Store.

**Q : Pas de son pour le TTS ?**  
R : Vérifiez le volume système et assurez-vous que les voix espagnoles sont installées.

**Q : La traduction ne marche pas ?**  
R : La traduction nécessite une connexion Internet. Si Bing échoue, essayez Google Traduction dans les réglages.

**Q : Le dictionnaire fonctionne hors ligne ?**  
R : Oui — définitions et données de prononciation sont locales.

---

## Liens utiles

- [Politique de confidentialité](../privacy-policy)
- [Assistance et commentaires](../support)

---
