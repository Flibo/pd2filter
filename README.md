# Wolfie's Project Diablo 2 Loot Filters

I have created a Discord so that you can be notified when I update my filter. Take a look [HERE](https://github.com/WolfieeifloW/pd2filter#discord) for more info!

# Table of Contents
1. [Installation](https://github.com/WolfieeifloW/pd2filter#installation)
1. [Loot Filters](https://github.com/WolfieeifloW/pd2filter#loot-filters)
   1. [Detailed](https://github.com/WolfieeifloW/pd2filter#detailed)
   1. [Compact](https://github.com/WolfieeifloW/pd2filter#compact)
   1. [Basic](https://github.com/WolfieeifloW/pd2filter#basic)
   1. [Wolfie](https://github.com/WolfieeifloW/pd2filter#wolfie)
   1. [BTNeandertha1](https://github.com/WolfieeifloW/pd2filter#btneandertha1)
1. [Discord](https://github.com/WolfieeifloW/pd2filter#discord)
1. [Informative Links](https://github.com/WolfieeifloW/pd2filter#informative-links)
1. [Common Issues](https://github.com/WolfieeifloW/pd2filter#common-issues)
1. [Donations](https://github.com/WolfieeifloW/pd2filter#donations)
1. [Disclaimer](https://github.com/WolfieeifloW/pd2filter#disclaimer)

# Installation
Ensure you have opened the PD2 Launcher (as Administrator) and clicked Play. This will update the mod and download all the files you need.
1. Select which filter you want to use from [Loot Filters](https://github.com/WolfieeifloW/pd2filter#loot-filters) section
1. CTRL+Click (will open in a new tab) the link on that filter which will take you to the raw code for that version
1. Copy all of the code (press CTRL+A to select all than CTRL+C to copy)
1. Open your text editor (Notepad, Notepad++, etc) as Administrator (CTRL+click [HERE](https://i.imgur.com/Yy5qyc3.png) for image of how-to)
1. With your text editor open **default.filter** from your ProjectD2 folder
   1. Make sure in Notepad you change the drop-down above the Open button to `All Files (*)` (CTRL+click [HERE](https://i.imgur.com/yjXlWme.png) for image of how-to)
1. Paste the code you copied, overwriting everything in there
1. Go to File -> Save (NOT Save As), overwrite, and then close the file
1. Open Project Diablo 2
1. Once in-game CTRL+click the Settings button (bottom-left corner by default)
1. Change your settings to match the image below
1. Close the Settings window by right-clicking in the title bar (anywhere along the bar that says "Settings")
1. Reload your filter using **Numpad 0**
   1. If you don't have a numpad change `Reload Config:          VK_NUMPAD0` in ProjectDiablo.cfg (in your PD2 folder) to one of these [Virtual Key Codes](https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes)

If it worked a Minor Health Potion should now say *HP1*.

![In-Game Settings](https://i.imgur.com/WFeroFv.png)

# Loot Filters
### [Detailed](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/detailed.filter)
CTRL+click the above link for the raw code.

**Select this version if you are uncomfortable with needing to write your own filter lines.** This version has lines for every single item in the game and is **massively** commented to make it very, very easy to edit to your liking. This is for ease-of-use and very quick editing as you should ideally only ever have to comment or uncomment a line (add or remove //). This version will show and notify a lot of items by default with the idea that you can slowly start to comment out things you don't need. The flip side is that since this filter contains lines for every item you can easily just uncomment a line for things you want to show that aren't currently showing.

### [Compact](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/compact.filter)
CTRL+click the above link for the raw code.

**Select this version if you are comfortable with writing your own filter lines.** This version will contain only the lines that are already uncommented in the Detailed version. This version will still show and notify a lot of items that you can slowly start to comment out but you have to have knowledge of filters to add your own lines for items that are not already in the filter.

### [Basic](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/basic.filter)
CTRL+click the above link for the raw code.

**Select this version if you want a template/base to start from for creating your own filter.** This filters purpose is to help people get a start on building their own filter. No support will be given for this filter, you assume all responsibility for creating and editing it to your liking.

### [Wolfie](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/wolfie.filter)
CTRL+click the above link for the raw code.

**This version is a copy of my own personal filter.** It is semi-strict while still working while leveling. No support will be given for this filter. Only report items that are wrong or items that show as **+++ NO FILTER LINE +++**.

### [BTNeandertha1](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/btneandertha1.filter)
CTRL+click the above link for the raw code.

This is a custom-made version for [BTNeandertha1](https://www.twitch.tv/btneandertha1) which is quite strict. No support will be given for this version.

# Discord
I've created a Discord for my filter so that you can get pinged when there's an update. This allows you to either redownload the filter or you can update just the lines I've changed! Join the server [HERE](https://discord.gg/6bM8AtYGAq)!

# Informative Links
* **Reddit Thread:** <https://www.reddit.com/r/ProjectDiablo2/comments/kokwu0/wolfieeiflows_pd2_filters/>
* **Info for Filter:** <https://github.com/planqi/slashdiablo-maphack/wiki/Advanced-Item-Display>
* **Color Chart:** <https://raw.githubusercontent.com/planqi/slashdiablo-maphack/master/readme_gfx/color_palette.png>
* **Info for Notify:** <https://github.com/planqi/slashdiablo-maphack/wiki/Advanced-Item-Display#marking-items-on-the-map>
* **More Notify Info:** <https://github.com/planqi/slashdiablo-maphack#release-notes-for-bh-maphack-v18>
* **PD2 Item & Skill Codes:** <https://docs.google.com/spreadsheets/d/15_JIFA5Wkx3sGQr_scLZz3l6Q8Ig687yUiz8DttaxtI/edit?usp=sharing>
* **Item Codes:** <http://www.gmstemple.com/Diablo2/itemcodes.html>
* **Skill Codes:** <https://user.xmission.com/~trevin/DiabloIIv1.09_Skills.html>
* **Automods Info:** <https://www.diabloii.net/forums/threads/the-staffmod-grail.740340/>
* **PD2 Wiki:** <https://projectdiablo2.miraheze.org/wiki/Item_Filtering>

# Common Issues
These are the common problems that people seem to run into. Please check each of these before asking for help.
* In-game settings not matching what I have in [Installation](https://github.com/WolfieeifloW/pd2filter#installation)
* Having two PD2 installations and pasting your filter into the wrong one
* Saving the filter file with the wrong name, eg **default.filter.filter**, **default.txt**, or **default.filter.txt**
* Having a PD2 installation inside of a Diablo II folder which is inside another Diablo II folder (folderception!)
* Not saving and closing the filter file after pasting into it

# Donations
I've had several people ask to donate. This is in **no way** required but is in all ways **very much appreciated**. To donate you can use [THIS](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=9JARHKMQ9UU3S&item_name=Project+Diablo+2+Loot+Filter&currency_code=CAD) link to send me money for my work.

# Disclaimer
For all versions of the filter I take no responsibility for any items that are accidentally hidden and/or do not notify. I do try my best to test these filters and ensure they are working properly but there's always room for error.
