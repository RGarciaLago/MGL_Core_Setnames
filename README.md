# [MGL Core Setnames] for the [MiSTer Platform](https://github.com/MiSTer-devel/Main_MiSTer/wiki)
##### ❗ ***Some of these are now part of [MiSTer-devel](https://github.com/MiSTer-devel/Distribution_MiSTer) but this repo will be used to test before being added to Distribution_MiSTer.***
A preset pack of core shortcuts (MGL files) which enable alternate configs for cores that support multiple systems or input devices.


## Installation
Download [all mgl files](https://github.com/RGarciaLago/MGL_Core_Setnames/tree/main/_Console) to the `/media/fat/_Console/` folder on your SD card.

### Updates
You can automatically download and get latest with the MiSTer update script and [update_all](https://github.com/theypsilon/Update_All_MiSTer) by adding the following text to `/media/fat/downloader.ini`:
```ini
[RGarciaLago/MGL_Core_Setnames]
db_url = https://raw.githubusercontent.com/RGarciaLago/MGL_Core_Setnames/db/db.json.zip
```


## Usage
Once you've installed the MGL files you can launch them like you would any other core!

Additional notes:
* These core shortcuts are MGL files that use the `<setname>` option.
* MiSTer will treat these core shortcuts as a new core but will need folders named the same as the `<setname>`.
* You can rename the `<setname>` but if you do after the config files are created you'll need to manually rename them to keep the same settings.
* Use your [names.txt file](https://github.com/ThreepwoodLeBrush/Names_MiSTer) to change the name of the MGL files so they show up how you prefer (requires latest [MiSTer unstable](https://github.com/MiSTer-unstable-nightlies/Main_MiSTer/releases/download/unstable-builds/MiSTer_unstable_20221129_14e6d3)).
* You can use [symbolic links](https://www.howtogeek.com/howto/16226/complete-guide-to-symbolic-links-symlinks-on-windows-or-linux/) to avoid file duplication if you wish to keep all games in the original core's folder.



### MGL Cores
These are MGL files with a `<setname>` for cores that support multiple systems.
* Atari 2600 - *uses "Atari7800" core*
* Game Gear - *uses the "SMS" core*
* Game Boy Color - *uses the "Gameboy" core*
* Game Boy Color 2P - *uses "Gameboy2P" core*
* SG-1000 - *uses the "ColecoVision" core*
* SuperGrafx - *uses the "TurboGrafx16" core*
* TurboGrafx-CD - *uses the "TurboGrafx16" core*
* WonderSwan Color - *uses the "WonderSwan" core*

### MGL Cores for Light-gun games
These are MGL files with a `<setname>` for cores that have light-gun game support.
* Genesis (Light-gun)
* SEGA CD (Light-gun)
* NES (Light-gun)
* Super NES (Light-gun)
* Master System (Light-gun)
* PlayStation (Light-gun)

### MGL Cores for vertical games
These are MGL files with a `<setname>` for cores that support vertically oriented games.
* Atari Lynx (Vertical)
* WonderSwan (Vertical)
* WonderSwan Color (Vertical)

### MGL Cores for enhanced options
These are MGL files with a `<setname>` for cores that support options to push the system past original hardware.
* Game Boy Advance (Enhanced)
* PlayStation (Enhanced)



## More Resources
For more extensions and utilities to improve your MiSTer: https://github.com/wizzomafizzo/mrext

Thanks to [Wizzo](https://github.com/wizzomafizzo) for the idea to create a repository and [theypsilon](https://github.com/theypsilon) for the custom database!
