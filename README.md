
# Added 60FPS support for 1080p Thirteen AG patch.
# NB! The creator of this fix is not responsible if something will go wrong during install,or for any issues that arise on your OS/hardware.This fix is distributed under GPL 3.0 license.This tutorial is meant for enthusiasts,tinkerers and gamers who want the the game to work and are not affraid to take the risk of learning some new stuff in the process.
0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support
1. Install DirectX 9 Runtime from MS on Windows 11 it is not included: 
 * https://www.microsoft.com/en-us/download/details.aspx?id=8109
2. Download and extract this github archive. 
3. Copy and paste the contents of Sound Patch folder first into your C:\Program Files (x86)\Steam\steamapps\common\Max Payne
4. Use the sound patch.Convert files by launching MaxBatch.bat and using C and E in the CLI.Exit
5. Launch Game at least once!
6. Copy and paste the rest of the MaxPayne 60 FPS Lock and 1080p Patch folder 6 files: d3d8.dll d3d9.dll d3d9.ini global.ini MaxPayne.WidescreenFix.asi MaxPayne.WidescreenFix.ini into Max Payne folder C:\Program Files (x86)\Steam\steamapps\common\Max Payne

# Max Payne Fix Linux With Thirteen AG Patch and 60 FPS lock

1. Install Mangohud for your distro

2. Download Max Payne Fix Linux from here or from Thirteen AG Repositiory and extract into the game folder:
    
https://thirteenag.github.io/wfp#mp1

4. Go to Steam>Max Payne>Compatibility>General>Launch Options

5. WINEDLLOVERRIDES="d3d8=n,b" MANGOHUD_CONFIG="fps_limit=60,no_display" mangohud %command% -skipstartup

6. If you are on AMD CPU replace rlmfc.dll in Max Payne directory with the one provided here in the FOR AMD CPUs Fix folder in this repo or download it here

https://drive.google.com/file/d/1nPUgYVdj03J1jI0CONMrPit0snFN9P4_/view

6. Enjoy the game

7. At the time of testing the Steam versin of Proton 9.0.1


# Enjoy the game,credit goes to Darkje for the Sound Patch creation and ThirteenAG for the wrapper creation visit his website for more goodies:https://thirteenag.github.io/wfp!
# Thanks goes to silentgameplays for setting it up,testing and configuring the wrapper to be recognized by the game and setiing the FPS limit.
# Enjoy!
# silentgameplays
