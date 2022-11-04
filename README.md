# [MGL Core Setnames] for the [MiSTer Platform](https://github.com/MiSTer-devel/Main_MiSTer/wiki)
These are MGL files that have been setup to provide alternative Core "setnames" so you can have make more than one config for Cores that support multiple platforms. The MiSTer will treat each "setname" as unique so it can have it's own configuration settings applied.


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
* While a "setname" isn't a new core, MiSTer will treat as such and will need folders named the same as the "setname"
* You can use [symbolic links](https://www.howtogeek.com/howto/16226/complete-guide-to-symbolic-links-symlinks-on-windows-or-linux/) to avoid file duplication if you wish to keep all games in the core's folder
* As part of this MGL cores, I've also included "Vertical" and "LightGun" variants of cores to allow for further config customization.
* You can rename the "setname"  but any name changes after config files have been made will require manual updating of those files to match the new name
* Use your `names.txt` file to make name changes so they show up how you prefer; see below for naming examples you can copy & paste.


### MGL Cores
These are the MGL "setname" files that feature two different platforms.
* Atari2600:          Atari 2600
* GameGear:           Sega Game Gear
* GBC:                Nintendo Game Boy Color
* GBC2P:              Nintendo Game Boy Color [2P]
* SG1000:             Sega SG-1000
* WSC:                Bandai WonderSwan Color

### MGL Cores for Light-games
These are the MGL "setname" files for Cores that have light-gun game support.
* Genesis_LightGun:   Sega Genesis [Light-gun]
* MegaCD_LightGun:    Sega CD [Light-gun]
* NES_LightGun:       Nintendo NES [Light-gun]
* SNES_LightGun:      Nintendo Super NES [Light-gun]
* SMS_LightGun:       Sega Master System [Light-gun]
* PSX_LightGun:       Sony PlayStation [Light-gun]

### MGL Cores for vertically oriented games
These are the MGL "setname" files for Cores that allow games to be oriented vertically.
* AtariLynx_Vertical: Atari Lynx [Vertical]
* WonderSwan_Vertical: Bandai WonderSwan [Vertical]
* WSC_Vertical:       Bandai WonderSwan Color [Vertical]


## More Resources
For more extensions and utilities to improve your MiSTer, see [Wizzo](https://github.com/wizzomafizzo)'s list: https://github.com/wizzomafizzo/mrext

Thanks to Wizzo for the idea to create a repository and [theypsilon](https://github.com/theypsilon) for the custom database!
