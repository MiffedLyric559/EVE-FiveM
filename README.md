# Extended Video Export (Updated)
![Maintenance](https://img.shields.io/maintenance/yes/2025)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/MiffedLyric559/EVE-FiveM)
![GitHub all releases](https://img.shields.io/github/downloads/MiffedLyric559/EVE-FiveM/total)
![GitHub issues](https://img.shields.io/github/issues/MiffedLyric559/EVE-FiveM)
![GitHub pull requests](https://img.shields.io/github/issues-pr/MiffedLyric559/EVE-FiveM)

This repository provides an updated version of **Extended Video Export (EVE)**, with support for newer GTA V game builds.

> **Original Author**: [nightingale](https://www.gta5-mods.com/users/nightingale)
> **Original Mod**: [Extended Video Export on GTA5-Mods](https://www.gta5-mods.com/scripts/extended-video-export)

A great deal of time and research went into updating this mod.
**Please follow all instructions carefully before requesting support.**

* For debugging tips and troubleshooting, see:
  👉 [How to Use EVE with FiveM – CFX Forum Guide](https://forum.cfx.re/t/how-to-use-extended-video-export-eve-fivem/2581771)

* Want to add support for other versions or mods? Check out:
  👉 [How to Update Your ASI Files for FiveM](https://forum.cfx.re/t/how-to-make-a-res-file-and-update-your-asi-files/5090038)

---

## ✅ Supported GTA V Game Builds

| Build | Status        |
| ----- | ------------- |
| 1604  | ⚠️ Not Tested |
| 2060  | ⚠️ Not Tested |
| 2189  | ⚠️ Not Tested |
| 2372  | ⚠️ Not Tested |
| 2545  | ⚠️ Not Tested |
| 2612  | ⚠️ Not Tested |
| 2699  | ⚠️ Not Tested |
| 2802  | ✅ Tested      |
| 2944  | ⚠️ Not Tested |
| 3258  | ✅ Tested      |
| 3323  | ⚠️ Not Tested |
| 3407  | ⚠️ Not Tested |

---

## 🔧 Installation Guide

1. **Install [Voukoder (Legacy Version)](https://www.mediafire.com/file/btntwuf69c55gag/voukoder.msi/file)**
   ⚠️ The latest *Voukoder Pro* versions do **not** work with EVE. Uninstall any newer version **before** installing this legacy version.

2. **Install [Microsoft Visual C++ Runtime](https://aka.ms/vs/17/release/vc_redist.x64.exe)**

3. **Download the [latest EVE release from this repository](https://github.com/MiffedLyric559/EVE-FiveM/releases/latest)**

4. **Open your `FiveM Application Data` folder**

5. **Create a folder named `plugins`** inside `FiveM Application Data`, if it doesn’t already exist

6. **Extract `ExtendedVideoExport.asi`** into the `plugins` folder

7. **Extract the entire `EVE` folder** into the same `plugins` folder

   > ⛔️ Do **not** place EVE files in `data/cache/subprocesses` or your GTA V directory. Make sure any previous EVE files are removed from those locations.

8. **Open `ExtendedVideoExport.ini`**

   * Locate the line starting with `output_folder =`
   * Set it to your desired export directory. Example:

     ```ini
     output_folder = C:\eveexports
     ```

---

## ⚠️ Note for Cinematic Creators Using MENYOO

Having `Menyoo.asi` in your `FiveM/plugins` folder may cause crashes during export (e.g., stuck on “Preparing Clip” or frozen first frame).
**Fix:**

* Record your scenes with Menyoo enabled
* Then remove `Menyoo.asi` **before** exporting via Rockstar Editor

---

## 🎨 Graphics Pack Compatibility (As of July 20, 2025)

* **QuantV**: *QuantV FiveM – 2025-07-13 build*
* **NVE**: *1.0.285.0 (ReShade Addon Version) – July 2025 Update*

---

## 🎞️ ReShade & ENB Compatibility (As of July 20, 2025)

* **ENB**: Tested with CoreFX's “CoreENB”
  👉 [Get it on Patreon](https://www.patreon.com/c/crxhvrd/home)

* **ReShade**:

  * Tested with ReShade 6.5.1 (Full Addon Support)
  * Also works with the version bundled with NVE
    👉 [Download ReShade 6.5.1](https://reshade.me/downloads/ReShade_Setup_6.5.1_Addon.exe)

---

## 📬 Stay Updated

These instructions are accurate as of **July 20, 2025**.
If future updates break compatibility, please [open an issue](https://github.com/MiffedLyric559/EVE-FiveM/issues) or reach out.

📩 **Contact**:
**Discord** – `MiffedLyric`
