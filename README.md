# tuto-mods-steam

## Prérequis

- Among Us installé via Steam

## 1. Trouver le dossier

1. Fais un clic droit sur **Among Us**
2. Clique sur **Propriétés** puis **Fichiers locaux** puis **Parcourir les fichiers locaux**
3. Une fenêtre s'ouvre avec le dossier du jeu (`C:\Program Files (x86)\Steam\steamapps\common\Among Us`)

⚠️ Certain mods sont fait pour une version plus ancienne d'Among Us.
Pour cela il faut revenir a une version  plus ancienne de Among Us:

1. Clic droit sur Among Us puis Propriétés
2. Onglet Bêtas
3. selectionner "public-previous"

<img width="1036" height="735" alt="Capture d’écran 2026-06-07 141435" src="https://github.com/user-attachments/assets/9352e246-849d-4419-9752-c4052224f968" />

## 2. Télécharger un mod

Les mods se trouvent sur :

- [GitHub](https://github.com)
- [CurseForge](https://www.curseforge.com/)
- [Gamebanana](https://gamebanana.com/)

## Étape 4 — Installer le mod

1. Le mod se présente généralement sous forme de fichier `.dll` ou de `.zip`

⚠️ Si il sagit d'un .zip il est generalemnt conseillé de creer une copie de son dossier "Among US" qui se trouve dans 
(`C:\Program Files (x86)\Steam\steamapps\common\Among Us`)





---

## Étape 5 — Lancer le jeu

1. Lance Among Us normalement via Steam
2. BepInEx charge automatiquement les mods présents dans le dossier `plugins`
3. Si le mod a été détecté, il apparaît généralement dans le menu principal du jeu

---

## Désinstaller un mod

Il suffit de **supprimer le fichier `.dll`** correspondant dans `BepInEx/plugins/`.

Pour désinstaller **complètement BepInEx**, supprime les fichiers et dossiers ajoutés à la racine du jeu (`BepInEx/`, `doorstop_config.ini`, `winhttp.dll`).

---
