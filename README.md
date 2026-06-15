# rb-patches
 
Lightweight patches to vanilla RB games that add small quality-of-life improvements

**NOTE: The "strum limit" is left *intact* on all of these on XBOX ONLY. The PS3 versions do not have strum limits**

</br>

# 📥 Downloads

| Xbox 360 | PlayStation 3 |
| --- | ----------- |
| 📥 [RB1 Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/RB1-Patch-Xbox.zip) | 📥 [RB1 Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/RB1-Patch-PS3.zip)  |
| 📥 [RB2 Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/RB2-Patch-Xbox.zip) | 📥 [RB2 Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/RB2-Patch-PS3.zip)  |
| 📥 [TBRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/TBRB-Patch-Xbox.zip) | 📥 [TBRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/TBRB-Patch-PS3.zip) 📥 [PS3 Disc Patch (Required)](https://github.com/hmxmilohax/rb-patches/raw/main/tbrb/dependencies/TBRB-PS3DiscPatch.zip)* |
| 📥 [GDRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/GDRB-Patch-Xbox.zip) | 📥 [GDRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/GDRB-Patch-PS3.zip)** |
| 📥 [LRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/LRB-Patch-Xbox.zip) | 📥 [LRB Patch](https://nightly.link/hmxmilohax/rb-patches/workflows/build/main/LRB-Patch-PS3.zip) |

</br>

> These install exactly the same as the *Deluxe* mods, as usual make sure you back up each game's `default.xex`
>
> *If you already had RB2DX installed on PS3/RPCS3, you need to delete `dev_hdd0/game/BLUS30147/PARAM.SFO` or else it will tell you that you have a newer version installed
>
> **Due to technical reasons, TBRB on PS3 requires a separate "Disc Patch", extract that and overwrite the files where your base game is installed
>
> ***For GDRB on PS3, extract and overwrite the files where your base game is installed 

> Please keep in mind this project does not aim to add new features or be "ultimate" or "definitive", but rather to enhance the vanilla experience
>
> If you're looking for a more feature-complete option for RB2, check out [Rock Band 2 Deluxe](https://rb2dx.milohax.org/) instead

</br>

# 📥 RPCS3 Recommended Settings

| Recommended | Minimum |
| --- | ----------- |
| 📥 [All Games](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_all.zip) | 📥 [All Games](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_all.zip) |
| 📥 [RB1](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_rb1.zip) | 📥 [RB1](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_rb1.zip) |
| 📥 [RB2](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_rb2.zip) | 📥 [RB2](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_rb2.zip) |
| 📥 [TBRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_tbrb.zip) | 📥 [TBRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_tbrb.zip) |
| 📥 [GDRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_gdrb.zip) | 📥 [GDRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_gdrb.zip) |
| 📥 [LRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/recommended_lrb.zip) | 📥 [LRB](https://github.com/hmxmilohax/rb-patches/raw/main/_custom_configs/minimum_lrb.zip) |

</br>

> To use these, click on the settings you want to download then extract the ZIP archives in the folder where you extracted RPCS3. It should combine folders automatically if you did it right.
>
> "All Games" includes custom configurations for every game listed here.
>
> In the GIF example below, the “Recommended” requirements settings archive (recommended.zip) was downloaded and its contents were moved into RPCS3’s folder.

</br>

![image](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/quickconf.gif)

</br>

## Patches Applied:

### All:

- Faster boot time
- Faster scrolling
- 1ms calibration increment
- Volume sliders can be muted completely
- Additional practice speeds
- SELECT button restarts current practice section
- Video Overscan enabled by default
- Default difficulty is Expert

### RB1:

- Adjustable options via external `config.dta` file:
	- Track Speed
	- Sync Difficulty Speeds
	- Venue FPS
	- Black Background
	- Performance Mode
	- Autoplay (disables saving, online)
	- Vsync
	- Instrument Slots
- Vocal practice mode
- Allow one player in Band Quickplay and Band World Tour

### RB2:

> Please keep in mind this project does not aim to add new features or be "ultimate" or "definitive", but rather to enhance the vanilla experience.
>
> If you're looking for a better option for the casual fan, check out [Rock Band 2 Deluxe](https://rb2dx.milohax.org/) instead.
- Adjustable options via external `config.dta` file:
	- Most modifiers
	- Track Speed
	- Sync Difficulty Speeds
	- Venue FPS
	- Vsync
	- Instrument Slots
- Vocal practice mode
- Expanded career from [Rock Band 2 Deluxe](https://rb2dx.milohax.org/)
- Leaving mid-gig does not make you lose fans
- All prefabs available
- No Fail Mode can be used without penalty
- Unlock All Songs can be used online
- Main Menu is 60FPS on Xbox 360 (previously PS3 only)
- Menus on PS3 use the full vsync rate everywhere
- DLC loading doesn't interrupt menu usage
- Loading tips and other locale from future games

### TBRB:

- Vsync disabled on RPCS3
- "Super Speed" (Breakneck Speed) in Practice mode and Drum Trainer

### GDRB:

- Vsync disabled on RPCS3
- "Super Speed" (Breakneck Speed) in Practice mode and Drum Trainer
- DIY stems for "Chump" and "Longview" re-done with modern technology [by dirk](https://github.com/dirkNlerxst/dirks-rb3-customs/tree/main/MOGG%20Replacements)
- Main Menu is 60FPS on Xbox 360 (previously PS3 only)

### LRB:

- Adjustable options via external `config.dta` file:
	- Track Speed
	- Sync Difficulty Speeds
	- Venue FPS
	- Vsync
	- Instrument Slots
- Songs of any rating can be played
- UGC songs can be played (RBN, customs)
- Any region DLC can be loaded
- All prefabs available
- All Rock Shop items unlocked
- Holiday DLC minifigures
- Vocal practice mode
- Compatible with the PS3 EU 1.0 debug build via patchcreator
