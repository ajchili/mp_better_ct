# mp_better_ct
A Call of Duty Black Ops mod aimed at introducing better features to the Combat Training mode.


### getting started (development)
_This pertains to both development of this mod as well as other mods_

The basic requirements for development are listed below:
* [Call of Duty: Black Ops](http://store.steampowered.com/app/42700/Call_of_Duty_Black_Ops/) I recommend the steam version as it comes with the mod tools, if you get the game other ways you **need** to get the mod tools as well
* [MohaaScriptEditor](https://github.com/ajchili/mp_better_ct/blob/master/MohaaScriptEditor.exe) Originally recommended [here](http://www.moddb.com/mods/ultimate-combat-training/downloads/uct-v154) by [wcp75](http://www.moddb.com/members/wcp75), I use it because it works
* A text editor, I use [Notepad++](https://notepad-plus-plus.org/)

How to get started with the mod
1. Install Black Ops and the mod tools
2. Open the mod tools
3. Run the converter ![](https://github.com/ajchili/mp_better_ct/blob/master/images/convert.png)
4. Create a mod **or** load mp_better_cp
    * Creating a mod
      1. Click 'Tools' in the menubar
      2. Click 'New mod...' in the drop down menu
      3. Name your mod, **if it is for multiplayer you MUST include "mp_" before the title of your mod**
    * Loading mp_better_cp
      1. Download or fork the repo
      2. Place the repo inside of "GAME_INSTALL_DIR/mods/mp_better_ct"
          * As an example, my directory looks like "E:\SteamLibrary\steamapps\common\Call of Duty Black Ops\mods\mp_better_ct"
          * A mod folder may not be created, if the folder is not there you can just make it
      3. Select "mp_better_ct" from the drop down menu ![](https://github.com/ajchili/mp_better_ct/blob/master/images/select_mod.png)
5. Building a mod
    * Check "Link FastFile" and "Build IWD"
    * Make sure mod is not loaded in Black Ops
    * Press "Build Mod" ![](https://github.com/ajchili/mp_better_ct/blob/master/images/build.png)
    * Re-launch or load another mod
    * Load mod in Black Ops
6. Adding new files to a mod
    * Ensure [MohaaScriptEditor](https://github.com/ajchili/mp_better_ct/blob/master/MohaaScriptEditor.exe) is downloaded
    * Open MohaaScriptEditor
    * Press "File" ![](https://github.com/ajchili/mp_better_ct/blob/master/images/file.png)
    * Press "Open" ![](https://github.com/ajchili/mp_better_ct/blob/master/images/open.png)
    * Select "[mod.csv](https://github.com/ajchili/mp_better_ct/blob/master/mod.csv)" from the mod folder
    * Add file as "FILE_TYLE,FILE_LOCATION"
        * The only file types that I know of are _(if there are more, make an issue and they will be added here)_:
            * fx
            * material
            * menufile
            * rawfile
            * weapon
7. Copy and edit files
    * Find a file which you want to make changes to, this should be a file that was previously added in step 6
        * Files can be found inside of the raw folder which has been added to you game directory
    * Copy the file, then put it inside the mod folder, making sure to preserve its directory
        * As an example, the "raw/ui_mp/main.menu" file inside the main folder would become "mods/mp_better_cp/ui_mp/main.menu"
    * Make changes as desired
    * Re-build the mod, refer to step 5
