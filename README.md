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

Couple of notes:
* While a "setname" isn't a new core, MiSTer will treat as such and will need folders named the same as the "setname"
* You can use [symbolic links](https://www.howtogeek.com/howto/16226/complete-guide-to-symbolic-links-symlinks-on-windows-or-linux/) to avoid file duplication if you wish to keep all games in the core's folder
* You can rename the "setname"  but any name changes after config files have been made will require manual updating of those files to match the new name

### MGL Cores
* Game Boy Color - using the Game Boy core
* to be filled out


## More Resources
For more extensions and utilities to improve your MiSTer, see [Wizzo](https://github.com/wizzomafizzo)'s list: https://github.com/wizzomafizzo/mrext

Thanks to [theypsilon](https://github.com/theypsilon) for the custom database!
