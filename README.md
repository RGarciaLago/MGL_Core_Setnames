# [MGL Core Setnames] for the [MiSTer Platform](https://github.com/MiSTer-devel/Main_MiSTer/wiki)
##### ❗ ***Most of these are now part of [MiSTer-devel](https://github.com/MiSTer-devel/Distribution_MiSTer) but this repo will be used to test before being added to Distribution_MiSTer.***
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
* Use your [names.txt file](https://github.com/ThreepwoodLeBrush/Names_MiSTer) to change the name of the MGL files so they show up how you prefer.
* You can use [symbolic links](https://www.howtogeek.com/howto/16226/complete-guide-to-symbolic-links-symlinks-on-windows-or-linux/) to avoid file duplication if you wish to keep all games in the original core's folder.



### MGL Cores
These are MGL files with a `<setname>` for cores that support multiple systems.
* Atari 2600 - *uses "Atari7800" core*
* Game Gear - *uses the "SMS" core*
* Game Boy Color - *uses the "Gameboy" core*
* Game Boy Color 2P - *uses "Gameboy2P" core*
* NeoGeo-CD - *uses "NeoGeo" core*
* NeoGeoMVS - *uses "NeoGeo" core*
* SG-1000 - *uses the "ColecoVision" core*
* SuperGrafx - *uses the "TurboGrafx16" core*
* TurboGrafx-CD - *uses the "TurboGrafx16" core*
* WonderSwan Color - *uses the "WonderSwan" core*

### MGL Cores for Light-gun games
These are MGL files with a `<setname>` for cores that have light-gun game support.
* Atari 7800 (Light-gun)
* Genesis (Light-gun)
* Master System (Light-gun)
* NES (Light-gun)
* PlayStation (Light-gun)
* SEGA CD (Light-gun)
* Super NES (Light-gun)

### MGL Cores for vertical games
These are MGL files with a `<setname>` for cores that support vertically oriented games.
* Atari Lynx (Vertical)
* WonderSwan (Vertical)
* WonderSwan Color (Vertical)

### MGL Cores for enhanced options
These are MGL files with a `<setname>` for cores that support options to push the system past original hardware.
* Game Boy Advance (Enhanced)
* Game Boy Advance (Enhanced) - *uses the new GBA core, see mgl file for where you should place the rbf to avoid duplicate core names.*
* PlayStation (Enhanced)
* PSX_2XCPU - *uses a [custom fork of the PSX core](https://github.com/RobertPeip/PSX_MiSTer/tree/main/releases), see mgl file for where you should place the rbf to avoid duplicate core names.*
* SNES (Enhanced)



## More Resources
Use my [VIDEO_PRESETS_by_Robby](https://github.com/RGarciaLago/VIDEO_PRESETS_by_Robby) to quickly setup a core to look authentically retro. Also available is my [Wallpaper_Collection](https://github.com/RGarciaLago/Wallpaper_Collection) to give you a ton of great backgrounds for the main menu.

Check out [Wizzo](https://github.com/wizzomafizzo)'s amazing set of [MiSTer Extensions](https://github.com/wizzomafizzo/mrext) to improve your MiSTer user experience.

Thanks to Wizzo for the idea to create a repository and [theypsilon](https://github.com/theypsilon) for the custom database!
