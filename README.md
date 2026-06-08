> Vous preferez la version Française [*README* français](./README-FR.md) !

# Among Us — Mod Installation Guide (Steam)

## Prerequisites
- Among Us installed via Steam

## 1. Find the game folder

1. Right-click on **Among Us** in Steam
2. Click **Properties** → **Local Files** → **Browse local files**
3. A window opens at: `C:\Program Files (x86)\Steam\steamapps\common\Among Us`

> ⚠️ Some mods are made for an older version of Among Us.
> To downgrade to a previous version:
> 1. Right-click Among Us → Properties
> 2. Go to the **Betas** tab
> 3. Select **public-previous**

<img width="1036" height="735" alt="Capture d&#39;écran 2026-06-07 141430" src="https://github.com/user-attachments/assets/4cc86d8b-67b2-4dc6-969b-324310b3940d" />

## 2. Download a mod

Mods can be found on:
- [GitHub](https://github.com)
- [CurseForge](https://www.curseforge.com/)
- [Gamebanana](https://gamebanana.com/)

## 3. Install the mod

Mods usually come as a `.dll` or `.zip` file.

**If it's a .zip:**
It is generally recommended to first make a backup copy of your Among Us folder located at `C:\Program Files (x86)\Steam\steamapps\common\`, then extract the contents of the zip directly into the Among Us folder.

**If it's a .dll:**
You also need to install **BepInEx** — it is the framework that allows mods to load.

1. Go to [github.com/BepInEx/BepInEx/releases](https://github.com/BepInEx/BepInEx/releases)
2. Download the **BepInEx_x64** version
3. Extract the contents of the .zip directly into the game folder
4. Launch Among Us once so BepInEx generates its configuration files
5. Close the game
6. Place your `.dll` mod file in `BepInEx/plugins/`

## Uninstalling a mod

**If it was a .dll:**
Simply delete the corresponding `.dll` file in `BepInEx/plugins/`.

To fully remove BepInEx, delete the files and folders added to the game root:
- `BepInEx/`
- `doorstop_config.ini`
- `winhttp.dll`

**If it was a .zip:**
Delete the files and folders that were included in the zip.
