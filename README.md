# Extended Video Export (Updated)

This repository is an updated version of **Extended Video Export (EVE)**, adding support for newer GTA V game builds.

Full credit for the original mod goes to **[nightingale](https://www.gta5-mods.com/users/nightingale)**  
Original mod: [Extended Video Export](https://www.gta5-mods.com/scripts/extended-video-export)

A significant amount of time and research went into updating this mod. **Please follow all instructions carefully before requesting support.**

---

## Supported GTA V Game Builds:

- ⚠️ 1604 (not tested)
- ⚠️ 2060 (not tested)
- ⚠️ 2189 (not tested)
- ⚠️ 2372 (not tested)
- ⚠️ 2545 (not tested)
- ⚠️ 2612 (not tested)
- ✅ 2699
- ✅ 2802
- ✅ 2944
- ✅ 3258
- ⚠️ 3323 (not tested)
- ⚠️ 3407 (not tested)

---

## Installation Guide:

1. **Download and install [Voukoder](https://github.com/Vouk/voukoder/releases).**

2. **Download and install [C++ Runtime](https://aka.ms/vs/17/release/vc_redist.x64.exe).**

3. **Download version 0.5.2 of [Extended Video Export](https://www.gta5-mods.com/scripts/extended-video-export).**

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
