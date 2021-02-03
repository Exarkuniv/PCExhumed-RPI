# PCExhumed-RPI
Powerslave/Exhumed for Raspberry Pi

![PCExhumed-RPI](https://github.com/Exarkuniv/PCExhumed-RPI/blob/Master/Screenshots/exhumed-2.png)
![PCExhumed-RPI](https://github.com/Exarkuniv/PCExhumed-RPI/blob/Master/Screenshots/powerslave.png)

Thanks to Nuke.YKT source port of Powerslave/Exhumed it is possible to build and install Powerslave/Exhumed 
on Raspberry Pi and RetroPie

This port uses SDL2 dependencies

**Install time:**
It takes about 10 minutes to install

A port of the PC version of Exhumed based on EDuke32

   Copy the following files from the PC retail version of Exhumed or Powerslave (Exhumed preferred), or the Powerslave demo available at http://www.jonof.id.au/build.games/ps. Beta, pre-release or other demo versions not supported.

   STUFF.DAT
   DEMO.VCR
   BOOK.MOV

   Recommended (but optional) - Add the games CD audio tracks as OGG files in the format exhumedXX.ogg or trackXX.ogg (where XX is the track number) to the same folder as pcexhumed.exe. The game includes tracks 02 to 19. These will provide the game with its music soundtrack and add storyline narration by the King Ramses NPC.

   Launch PCExhumed.


**Notes:**
The source port downloads and can be installed from the Experimental section in RetroPie-Setup but is considered experimental since it might has some bugs.

**Disclaimer:** This installation script is provided as is. Im not responsible for anything happening with your Raspberry Pi including corruption of SD card, Hardware damage. 
For support and help you can contact me here or on RetroPie forums.

To install

`wget https://raw.githubusercontent.com/Exarkuniv/PCExhumed-RPI/Master/PCExhumed.sh -P $HOME/RetroPie-Setup/scriptmodules/ports/`
