# GameMaker Studio 2 HTML FULLSCREEN
A GameMaker Studio 2 plugin for adding full screen (with respect to aspect ratio) to HTML games [**(Example)**](https://www.newgrounds.com/projects/games/1920316/preview "Example")

Free to use and do whatever you want with it. Credit is appreciated but not necessary.

# How to Import Plugin
Open your GameMaker project and go to Tools > Import Local Package. Select the downloaded .yymps file, Import All, then Import.

If you get an error when importing it you probably downloaded it wrong. Make sure to download it with the download button, not save link as.

# How to Use It
At the very start of your game add this to the create event
```
if (os_browser != browser_not_a_browser && !instance_exists(obj_HTML_FS)) { instance_create_depth(x,y,depth,obj_HTML_FS); }
```
You can now press F to call **HTML_FS_canvas_fullscreen()** which is included in the script **scr_HTML_FS** already. 

# NEWGROUNDS
If you make web games and don't put them on Newgrounds you're a FOOL!
It's the best place for creatives to be!

**GO MAKE GAMES ON NEWGROUNDS RIGHT NOW!**

[![Newgrounds](https://upload.wikimedia.org/wikipedia/en/thumb/8/85/Newgrounds_Tankman_logo.png/220px-Newgrounds_Tankman_logo.png "Newgrounds")](https://www.newgrounds.com/ "Newgrounds")

[https://www.newgrounds.com/](https://www.newgrounds.com/ "https://www.newgrounds.com/")

# Video Tutorial
[![YouTube Link](https://img.youtube.com/vi/9Q5SsT8mO7Q/0.jpg)](https://youtu.be/9Q5SsT8mO7Q)

# Credits
Shoutout to myself for being epic [@plufmot](https://twitter.com/plufmot "@plufmot")

I ripped off the formatting of this from https://github.com/Dungeonation/ngio-gms2-api

Shoutout [@Dungeonation](https://twitter.com/dungeonation "@Dungeonation") and Nick Pasto ([@DetermDungeon](https://twitter.com/DetermDungeon "@DetermDungeon")) for pointing me in the right direction to getting this done.

Shoutout [@Stepford](https://twitter.com/Stepf0rd "@Stepford") for hosting the Newgrounds Mobile Game Jam. My game looking like crap on mobile is what made me finally decide to give this a crack.
