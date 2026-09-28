# ImageConverter

**Un convertisseur d'images gratuit pour Windows : glissez vos images et transformez‑les en JPG · PNG · GIF · WEBP · TIFF d'un seul clic.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · Français

> Ce document est une traduction. En cas de différence, la [version coréenne](README.ko.md) fait foi.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-2.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/imageconverter?lang=fr)

![Écran d'ImageConverter](images/imageconverter-en.webp)

## Présentation

Une photo HEIC d'iPhone qui ne s'ouvre pas sur le PC, une série de photos à réduire pour un blog, un PDF à transformer en une image par page — ImageConverter s'en charge.

Glissez des fichiers ou des dossiers dans la fenêtre et cliquez sur le bouton **Convertir en**. C'est tout. Le JPG est enregistré plus léger grâce à MozJPEG et, si vous fixez une taille, l'image y est ajustée en gardant ses proportions. Vous pouvez aussi convertir directement depuis l'Explorateur de fichiers par un clic droit.

Les résultats sont toujours enregistrés comme **nouveaux fichiers**. ImageConverter n'écrase jamais vos originaux ni aucun fichier existant.

## Fonctionnalités

- **Plusieurs à la fois** — Ajoutez plusieurs fichiers ou des dossiers entiers (sous‑dossiers compris) et convertissez‑les en une fois.
- **5 formats de sortie** — JPG · PNG · GIF · WEBP · TIFF.
- **Nombreux formats d'entrée** — JPG, PNG, GIF, BMP, WEBP, TIFF, HEIC, AVIF, PSD, PDF, SVG, TGA, ICO, etc.
- **Des JPG plus légers** — MozJPEG enregistre la même qualité en moins d'octets.
- **Redimensionnement proportionnel** — Fixez seulement la largeur ou la hauteur ; l'autre suit les proportions.
- **PDF → images** — Enregistre chaque page d'un PDF de plusieurs pages comme une image distincte.
- **Reconnu même sans extension** — Le format est lu dans le contenu du fichier, pas dans son nom.
- **Originaux protégés** — Si le nom est déjà pris, le fichier est enregistré sous `photo (1).jpg`.
- **Menu du clic droit de l'Explorateur** — Sous Windows 10 et 11, y compris dans le menu par défaut de Windows 11.
- **7 langues** — Coréen · anglais · japonais · chinois · russe · italien · français. Suit la langue d'affichage de Windows.

## Téléchargement / Installation

| Type | Lien |
|---|---|
| Installateur | [Télécharger](https://down.kilho.net/imageconverter?lang=fr) |
| Portable (ZIP) | [Télécharger](https://down.kilho.net/imageconverter?lang=fr&nosetup) |

Avec l'installateur, ImageConverter s'ouvre dès la fin de l'installation, et l'entrée du menu Démarrer ainsi que le menu du clic droit de l'Explorateur sont ajoutés. Pour la version portable, décompressez le ZIP et lancez `ImageConverter.exe` — gardez le dossier `vendor` à côté de l'exécutable. **Le menu du clic droit de l'Explorateur est fourni avec l'installateur.**

## Utilisation

### Déroulement de base

1. Lancez ImageConverter. **Accueil** affiche une liste de fichiers vide.
2. Glissez dans la liste les images ou dossiers à convertir. Seuls les fichiers dont le format est reconnu sont ajoutés ; la colonne **Type** indique le format d'origine et **Statut** affiche `Prêt`.
3. Dans la case de taille en bas à gauche, choisissez **Original**, **Largeur** ou **Hauteur**. Avec Largeur ou Hauteur, une case de taille (px) apparaît à côté.
4. Vérifiez le format de sortie. Le bouton en bas à droite l'indique, par exemple **Convertir en JPG**. Pour le changer, faites un **clic droit** sur le bouton et choisissez JPG · PNG · GIF · WEBP · TIFF.
5. Cliquez sur le bouton. Une barre de progression apparaît et le statut de chaque fichier passe de `Convertir` à `Succès`.
6. Par défaut, les fichiers convertis sont enregistrés dans le **même dossier que l'original**, sous le même nom avec la nouvelle extension.

### Organisation de l'écran

**Accueil**

| Élément | Rôle |
|---|---|
| Liste des fichiers | **Nom du fichier** · **Type** (format d'origine détecté) · **Statut** (`Prêt` / `Convertir` / `Succès` / `Échec`) |
| Clic droit sur la liste | **Supprimer** · **Tout supprimer** |
| Choix de la taille | **Original** · **Largeur** · **Hauteur** |
| Case de taille | Choisissez une taille courante dans la liste ou tapez un nombre (visible seulement avec Largeur ou Hauteur) |
| Bouton **Convertir en JPG** | Cliquez pour démarrer. Clic droit pour choisir le format de sortie |

**Config**

| Élément | Rôle |
|---|---|
| **Chemin de sortie** | **Dossier de Fichier Original** ou un dossier choisi (par défaut `Bureau\ImageConverter`). Changez‑le avec le bouton `…` |
| **Format** | JPG · PNG · GIF · WEBP · TIFF (le même réglage que le menu du clic droit du bouton) |
| **Qualité** | 40 à 100, 75 par défaut. S'applique aux formats avec perte (JPG · WEBP) |

### Que faire quand…

**Convertir des photos d'iPhone (HEIC) en JPG**
Glissez les fichiers HEIC, ou le dossier qui les contient, dans la liste, laissez le format sur **JPG** et cliquez. Les photos sont enregistrées **à l'endroit** selon la rotation enregistrée par le téléphone : inutile de redresser à la main les photos couchées.

**Dimensionner des photos pour un blog ou une boutique en ligne**
Choisissez **Largeur** dans la case de taille et sélectionnez la largeur voulue, par exemple `1280`. La hauteur suit les proportions, rien n'est déformé. Pour une valeur absente de la liste, tapez simplement le nombre (1 à 30000). Les photos plus étroites que cette largeur y sont aussi amenées.

**Donner la même hauteur à toutes les images, comme des vignettes**
Choisissez **Hauteur** : tous les résultats ont la même hauteur et chaque largeur suit ses propres proportions. Pratique pour aligner sur une ligne un mélange de photos en paysage et en portrait.

**Alléger des fichiers pour les envoyer par e‑mail ou messagerie**
Avec **JPG**, MozJPEG enregistre la même qualité dans un fichier plus petit. Pour aller plus loin, baissez **Config → Qualité** vers 60 et réduisez aussi la taille avec **Largeur**. L'enregistrement en **WEBP** donne généralement un fichier plus petit que le JPG.

**Conserver un fond transparent**
Les PNG, SVG et autres images avec transparence la conservent lorsqu'elles sont enregistrées en **PNG** ou **WEBP**. Le JPG ne peut pas contenir de transparence : choisissez PNG ou WEBP pour les logos et les icônes.

**Exporter un logo SVG en PNG à la taille voulue**
Ajoutez le SVG, réglez **Largeur** sur `512` par exemple, et convertissez en **PNG**. Au lieu d'agrandir une petite image, il **redessine l'image à cette taille** : elle reste nette même en grand.

**Transformer un PDF en une image par page**
Ajoutez un PDF et convertissez : chaque page est enregistrée dans un fichier numéroté — `document-001.jpg`, `document-002.jpg` … Avec **Original**, les pages sortent à la taille de l'écran ; avec **Largeur**, elles sont dessinées nettement à cette largeur. Le fond est blanc. Le statut affiche `Succès` une fois toutes les pages enregistrées.

**Changer un GIF animé en WEBP**
Quand le format de sortie est **GIF** ou **WEBP**, toutes les images de l'animation sont conservées. Convertir un GIF animé en WEBP garde le mouvement et réduit la taille. En JPG · PNG · TIFF, seule la première image est enregistrée.

**Enregistrer en WEBP sans aucune perte de qualité**
Montez **Qualité** à **100** et le WEBP est enregistré sans perte. Utile pour garder une copie identique au pixel près, plus petite qu'un PNG.

**Convertir toutes les images d'un dossier**
Glissez un dossier entier : tous ses sous‑dossiers sont parcourus et seules les images sont ajoutées. Les autres fichiers, comme les documents ou les vidéos, sont écartés automatiquement, et un même fichier n'est jamais ajouté deux fois.

**Des fichiers sans extension ou avec la mauvaise**
ImageConverter lit le format dans le **contenu du fichier**, pas dans son nom. Les fichiers sans extension, ou un `.jpg` qui est en réalité un PNG, sont correctement reconnus, et le résultat reçoit la bonne extension.

**Regrouper les résultats dans un seul dossier**
Dans **Config → Chemin de sortie**, choisissez l'option de dossier du bas : tous les résultats y sont placés. Par défaut, c'est `Bureau\ImageConverter`, créé lors de la conversion s'il n'existe pas encore. Choisissez un autre dossier avec le bouton `…`. Pour garder les résultats à côté des originaux, choisissez **Dossier de Fichier Original**.

**Un fichier du même nom existe déjà**
Rien n'est écrasé. Si `photo.jpg` existe, le résultat est enregistré sous `photo (1).jpg`, `photo (2).jpg`, etc. Même en réduisant un JPG en JPG, l'original reste intact.

**Convertir directement depuis l'Explorateur de fichiers**
Sélectionnez une ou plusieurs images dans l'Explorateur, clic droit → **Conversion d'image** → **Convertir en WebP**, **Convertir en PNG** ou **Convertir en JPG**. Une fenêtre s'ouvre avec ces fichiers : choisissez une taille et cliquez sur le bouton.
- Les résultats sont enregistrés dans le **même dossier que les originaux**, et la fenêtre se ferme d'elle‑même une fois terminé.
- Faites un clic droit sur d'autres fichiers et convertissez à nouveau : chacun ouvre sa propre fenêtre, ils peuvent donc tourner en même temps.
- Le menu apparaît quand vous sélectionnez des fichiers JPG · PNG · GIF · BMP · WEBP · TIFF · HEIC · AVIF · PSD · PDF · SVG · TGA.

**Produire les mêmes photos dans plusieurs formats**
La liste reste après la conversion. Faites un clic droit sur le bouton, changez de format et cliquez à nouveau pour obtenir les mêmes fichiers dans un autre format.

**Ranger la liste**
Sélectionnez les lignes à retirer (`Ctrl` · `Shift` pour plusieurs), faites un clic droit sur la liste et choisissez **Supprimer**. Pour tout vider, choisissez **Tout supprimer**. Les lignes sont seulement retirées de la liste ; les fichiers eux‑mêmes ne sont pas supprimés.

**Arrêter en cours de conversion**
Fermez la fenêtre : la question **Arrêter la conversion et quitter ?** s'affiche. Cliquez sur **Oui** : le fichier en cours est terminé, puis le programme se ferme. Les résultats déjà enregistrés restent en place.

## Configuration

Les changements faits dans **Config** et le choix de taille sur l'Accueil sont mémorisés automatiquement pour la fois suivante.

| Élément | Valeur par défaut |
|---|---|
| Format | JPG |
| Taille | Original (Largeur 640 / Hauteur 540) |
| Qualité | 75 |
| Chemin de sortie | Dossier de Fichier Original (dossier choisi par défaut : `Bureau\ImageConverter`) |
| Langue | Langue d'affichage de Windows (anglais si elle n'est pas prise en charge) |

## Configuration requise

- Windows 10 · Windows 11 (64 bits)
- Tout ce qu'il faut pour convertir est inclus — rien d'autre à installer. Aucun droit d'administrateur n'est nécessaire pour exécuter le programme.
- La connexion Internet ne sert qu'aux avis de nouvelle version. Toutes les conversions se font sur votre PC.

## Mises à jour

ImageConverter ne se met **pas** à jour tout seul. Au lancement, il vérifie si une nouvelle version existe et affiche un avis ; en cliquant sur **Oui**, la page de téléchargement s'ouvre et le programme se ferme. Les nouvelles versions sont publiées manuellement après vérification interne et annoncées sur la [page ImageConverter](https://kilho.net/imageconverter). Consultez l'[avis sur la politique de mise à jour](https://en.kilho.net/archives/notice/2940).

**Historique des versions**

| Version | Date | Modifications |
|---|---|---|
| 2.0.0 | 2026-09-22 | Écran renouvelé, tailles choisies dans une liste ou saisies directement, réglages existants conservés après la mise à jour, conversion par clic droit dans l'Explorateur améliorée |
| 1.6.3 | 2026-09-03 | Conversion plus rapide depuis le menu du clic droit de Windows 11, installation des mises à jour améliorée, conversion PDF plus nette et grands documents plus stables, meilleure reconnaissance HEIC · AVIF, fichiers vides écartés de la liste dès l'ajout |
| 1.6.2 | 2026-08-17 | Moteur de conversion PDF amélioré pour une meilleure qualité, fermeture sûre pendant la conversion, protection renforcée des fichiers existants, meilleure prise en charge des noms de fichiers avec caractères spéciaux, liste de fichiers plus rapide |
| 1.6.1 | 2026-07-16 | Conversion JPG et PDF de plusieurs pages plus fiable, meilleure reconnaissance du HEIC et d'autres formats, menu du clic droit de l'Explorateur et réglages plus pratiques |

## Licence

ImageConverter est un **freeware**. Utilisez‑le gratuitement et sans restriction partout — au bureau, à la maison, dans les administrations, à l'école — et redistribuez‑le librement.

## Liens

- Site web : <https://kilho.net/imageconverter>
- Forum : <https://groups.google.com/g/kilhonet>
- X (Twitter) : <https://www.twitter.com/kilhonet>

© KILHO.NET
