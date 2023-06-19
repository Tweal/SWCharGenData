# SWCharGen Custom Data
This is custom data for use with OggDude's SWChargen app. You can find the app (and a probably outdated version of this data) [here](https://drive.google.com/drive/folders/11DWTUo364gf-TVPnZcc_qIsmNFPnI7So?usp=sharing). 

This custom data includes descriptions for all of the talents and careers/specializations as well as most weapons, items, ships, and species. However it does not contain everything, namely it is missing a lot of items and most of the stuff from the final books.

## Usage

To use this data you will need to have launched the app at least once to create the roaming data. Once you have done so you will find a folder called `SWCharGen` in your roaming folder (found by typing `%appdata%` in a file browser).

### For the git inclined:
You can simply clone this repo directly to that file (you will have to clone it with the name `SWCharGen` to ensure it goes into that folder and does not create a subfolder). You could then just `git pull` any updates released.

### For the non git inclined:
You can download a zip of the repo by clicking the green `Code` button at the top and then selecting `Download ZIP`. Once extracted you can simply copy the `DataCustom` file over to the `AppData/Roaming/SWCharGen` folder mentioned above. Replace any conflicts that may arrise. If you have already added your own custom items it should not interfere (unless you named it the same as an existing item) since each item is it's own file.

## Updates
Updates will be infrequent and as my group needs them. I will not respond to requests for new items to be added. If you want to add items fork the repo and add them yourself, it is not hard to use OggDude's provided data editor to do so.