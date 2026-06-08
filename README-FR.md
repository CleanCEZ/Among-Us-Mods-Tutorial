# Among Us — Guide d'installation de mods (Steam)

## Prérequis
- Among Us installé via Steam

## 1. Trouver le dossier

1. Fais un clic droit sur **Among Us** dans Steam
2. Clique sur **Propriétés** puis **Fichiers locaux** puis **Parcourir les fichiers locaux**
3. Une fenêtre s'ouvre avec le dossier du jeu : `C:\Program Files (x86)\Steam\steamapps\common\Among Us`

> ⚠️ Certains mods sont faits pour une version plus ancienne d'Among Us.
> Pour revenir à une version antérieure :
> 1. Clic droit sur Among Us → Propriétés
> 2. Onglet **Bêtas**
> 3. Sélectionner **public-previous**

## 2. Télécharger un mod

Les mods se trouvent sur :
- [GitHub](https://github.com)
- [CurseForge](https://www.curseforge.com/)
- [Gamebanana](https://gamebanana.com/)

## 3. Installer le mod

Les mods se présentent généralement sous forme de fichier `.dll` ou de `.zip`.

**Si c'est un .zip :**
Il est généralement conseillé de créer une copie de son dossier Among Us qui se trouve dans `C:\Program Files (x86)\Steam\steamapps\common\`, puis d'en extraire le contenu dans le dossier de Among Us.

**Si c'est un .dll :**
Il faut aussi installer **BepInEx** — c'est lui qui permet de charger les mods.

1. Va sur [github.com/BepInEx/BepInEx/releases](https://github.com/BepInEx/BepInEx/releases)
2. Télécharge la version **BepInEx_x64**
3. Extrais le contenu du .zip directement dans le dossier du jeu
4. Lance Among Us une première fois pour que BepInEx génère ses fichiers de configuration
5. Ferme le jeu
6. Place ton fichier `.dll` dans `BepInEx/plugins/`

## Désinstaller un mod

**Si c'était un .dll :**
Supprime le fichier `.dll` correspondant dans `BepInEx/plugins/`.

Pour désinstaller complètement BepInEx, supprime les fichiers et dossiers ajoutés à la racine du jeu :
- `BepInEx/`
- `doorstop_config.ini`
- `winhttp.dll`

**Si c'était un `.zip`**
Supprime les fichiers et dossiers qui étaient compris dans celui-ci.
