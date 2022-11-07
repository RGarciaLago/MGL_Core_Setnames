# [MGL Core Setnames] for the [MiSTer Platform](https://github.com/MiSTer-devel/Main_MiSTer/wiki)
A preset pack of core shortcuts (MGL files) which let you have alternate core configs for cores which support multiple systems or input devices.


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
* You can rename the `<setname>` within the MGL file but any name changes after config files have been created will require manual updating of those config files to match the new name.
* Use your [names.txt file](https://github.com/ThreepwoodLeBrush/Names_MiSTer) to change the name of the MGL core shortcuts so they show up how you prefer; see below for naming examples you can copy & paste.
* You can use [symbolic links](https://www.howtogeek.com/howto/16226/complete-guide-to-symbolic-links-symlinks-on-windows-or-linux/) to avoid file duplication if you wish to keep all games in the original core's folder.



### MGL Cores
These are the MGL files with a `<setname>` cores that support two different platforms.
* Atari2600&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Atari 2600
* GameGear&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Sega Game Gear
* GBC&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Nintendo Game Boy Color
* GBC2P&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Nintendo Game Boy Color [2P]
* SG1000&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Sega SG-1000
* SuperGrafx&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;NEC PC Engine SuperGrafx
* TurboGrafxCD&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;NEC TurboGrafx-CD
* WSC&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Bandai WonderSwan Color

### MGL Cores for Light-gun games
These are the MGL files with a `<setname>` for cores that have light-gun game support.
* Genesis_LightGun&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Sega Genesis [Light-gun]
* MegaCD_LightGun&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Sega CD [Light-gun]
* NES_LightGun&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Nintendo NES [Light-gun]
* SNES_LightGun&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Nintendo Super NES [Light-gun]
* SMS_LightGun&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Sega Master System [Light-gun]
* PSX_LightGun&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Sony PlayStation [Light-gun]

### MGL Cores for vertical games
These are the MGL files with a `<setname>` for cores that have vertically oriented games.
* AtariLynx_Vertical&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Atari Lynx [Vertical]
* WonderSwan_Vertical&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Bandai WonderSwan [Vertical]
* WSC_Vertical&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;Bandai WonderSwan Color [Vertical]


## More Resources
For more extensions and utilities to improve your MiSTer: https://github.com/wizzomafizzo/mrext

Thanks to [Wizzo](https://github.com/wizzomafizzo) for the idea to create a repository and [theypsilon](https://github.com/theypsilon) for the custom database!
