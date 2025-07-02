# Extended Video Export (Updated)

This repository is an updated version of **Extended Video Export (EVE)**, adding support for newer GTA V game builds.

Full credit for the original mod goes to **[nightingale](https://www.gta5-mods.com/users/nightingale)**  
Original mod: [Extended Video Export](https://www.gta5-mods.com/scripts/extended-video-export)

A significant amount of time and research went into updating this mod. **Please follow all instructions carefully before requesting support.**
Checkout this forum post for debugging tips: **[CFX - FiveM - How to get EVE working with FiveM](https://forum.cfx.re/t/how-to-use-extended-video-export-eve-fivem/2581771)**  

If you want to add compatibility yourselves you can refer to this guide: **[How to updated your ASI files for FiveM](https://forum.cfx.re/t/how-to-make-a-res-file-and-update-your-asi-files/5090038)**  

---

## Supported GTA V Game Builds:

- ⚠️ 1604 (not tested)
- ⚠️ 2060 (not tested)
- ⚠️ 2189 (not tested)
- ⚠️ 2372 (not tested)
- ⚠️ 2545 (not tested)
- ⚠️ 2612 (not tested)
- ✅ 2699 (confirmed)
- ✅ 2802 (confirmed)
- ✅ 2944 (confirmed)
- ✅ 3258 (confirmed)
- ✅ 3323 (confirmed)
- ✅ 3407 (confirmed)

---

## Installation Guide:

1. **Download and install [Voukoder]([https://github.com/Vouk/voukoder/releases](https://www.voukoder.org/forum/thread/783-downloads-instructions/)).**

2. **Download and install [C++ Runtime](https://aka.ms/vs/17/release/vc_redist.x64.exe).**

3. **Download latest version of [Extended Video Export](https://github.com/MiffedLyric559/EVE-FiveM/releases/latest).**

4. **Locate your `FiveM Application Data` folder.**

5. **Create a `plugins` folder** within the `FiveM Application Data` folder if it doesn't already exist.

6. **Extract the file `ExtendedVideoExport.asi`** into the newly created `plugins` folder.

7. **Extract the `EVE` folder** into the same `plugins` folder.  
   *(You no longer need to place the EVE folder in `data/cache/subprocesses`.)*

8. **Open `ExtendedVideoExport.ini`**, locate the line starting with **`output_folder =`**, and specify your desired output folder path.  
   Example:
   ```ini
   output_folder = C:\eveexports

# ⚠️ Special Instructions for NVE Users:
If you are using NaturalVision Evolved (NVE), follow these additional steps:

1. Complete the standard installation above.
2. Delete the file ReshadeEffectShaderToggler.addon64 from your FiveM plugins folder.
(These instructions are accurate as of March 6, 2025. If compatibility breaks with future NVE updates, please notify me.)
