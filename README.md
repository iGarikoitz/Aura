# AURA

This is a [RetroFE](http://retrofe.nl) layout in which I have put all my dedication for more than two years to make it a reality.

![enter image description here](https://dl.dropbox.com/s/deczn7e8gi312ge/aura%20menu.jpg?dl=0)

![enter image description here](https://dl.dropbox.com/s/caxcgtv527njzfs/aura%20info.jpg?dl=0)

## How to start using it

First download the latest version from this [link](https://github.com/iGarikoitz/Aura/releases). After this, you need to download emulator and get roms to play.

### Retroarch

* Download [RetroArch](https://www.retroarch.com/?page=platforms) and put inside the emulators folder.
* Put **ddonpach.zip** rom inside dodonpachi folder.
* Put **garou.zip** and **neogeo.zip** roms inside garou mark of the wolves folder.
* Put **mslug3.zip** and **neogeo.zip** roms inside metal slug 3 folder.
* Put **pbobblen.zip** and **neogeo.zip** roms inside puzzle bobble folder.

### Mame

* Download [Mame](https://www.mamedev.org/release.html) and put inside the emulators folder.
* You have to change the code from inside the **game.bat** file:
`"../../emulators/mame/mame64.exe" -rompath "../../emulators/mame/roms" "rom name"`
* Put **ddonpach.zip** rom inside mame/roms folder.
* Put **garou.zip** and **neogeo.zip** roms inside mame/roms folder.
* Put **mslug3.zip** and **neogeo.zip** roms inside mame/roms folder.
* Put **pbobblen.zip** and **neogeo.zip** roms inside mame/roms folder.

## How to add my own games.

### Images
When you add a game, you have to include six images in JPG. Why in JPG image format? Because RetroFE works more fluid using JPG compared to PNG.

 1. **Cover** - Resolution: 460 x 690 pixels.
Game artwork with logo.
 2. **Fanart** -  Resolution: 1280 x 720 pixels.
Same Game artwork occupying the entire width.
 3. **Fanart blur** -  Resolution: 1280 x 720 pixels.
Same Fanart image with 15% Gaussian blur.
 4. **Screenshot 1** Resolution: ? x 220 pixels (Depends on the screen ratio).
Title screen. The height has to be 220 pixels.
 5. **Screenshot 2** Resolution: ? x 220 pixels (Depends on the screen ratio).
First gameplay screenshot.. The height has to be 220 pixels.
 6. **Screenshot 3** Resolution: ? x 220 pixels (Depends on the screen ratio).
Second gameplay screenshot.. The height has to be 220 pixels.
