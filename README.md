# Generate .gct files from Gecko Codes (GameCube/Wii)
I was searching for how to generate a .gct on Windows since geckocodes.org shut down, but it turns out it's a very simple format: some prefix bytes, then the raw bytes from the cheats, then some suffix bytes. The prefix and suffix are always the same (regardless of the cheats/game), and the bytes from the cheats are equivalent to the hex value displayed for the cheat.<br>
[Try it here](https://shytyger.blogspot.com/2023/02/gecko-codes-to-gct-file-gamecube-wii.html)<br>
Or download and open **gctFromGecko.html**

# Instructions
**1.** Click on the top bar "open txtcode.txt" and select the file containing the cheats (cheats at the end of this readme)<br>
*Note: if the cheats don't display properly, try checking the box "Force uppercase when opening file" and opening the txt file again*<br>
**2.** Click on the cheats you want. Green means selected & active, blue means inactive.<br>
**3.** Click "Save as .gct" and save them to the appropriate directory that your Wii will load them

# Where to Save .gct
Using USB Loader GX: **sd:/codes/**<br>
Using Configurable USB Loader: **sd:/usb-loader/codes/** *but Cfg USB Loader can generate its own cheats. Just putting the .txt file into sd:/usb-loader/codes/ and selecting cheats & saving is more convenient than this webapp*<br>
Using Nintendont: **usb:/codes/**

# Cheat Backups and Finding Game ID from Title
(I didn't compile these lists, I found them on various websites. Just backing them up here for convenience.)<br>
**wiitdb game IDs.txt** - a list of Wii & GameCube games by their ID, so you can search for the title ID knowing your game's name (wii/gc title list downloaded from gametdb.com)<br>
**wii codes.zip** - collection of gecko cheats for Wii posted by The Real Jdbye at https://gbatemp.net/threads/download-the-whole-cheat-code-data-base-for-wii-gc.518107/post-8283816<br>
**gamecube codes.zip** - collection of gecko cheats for GameCube (to be used through Nintendont on Wii) posted by Hero Q8 at https://gbatemp.net/threads/all-cheats-text-for-usb-loader-and-nintendont.373990/

Happy cheating~
