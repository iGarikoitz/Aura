
# AURA

This is a [RetroFE](http://retrofe.nl) layout in which I have put all my dedication for more than two years to make it a reality.

![enter image description here](https://dl.dropbox.com/s/deczn7e8gi312ge/aura%20menu.jpg?dl=0)

![enter image description here](https://dl.dropbox.com/s/caxcgtv527njzfs/aura%20info.jpg?dl=0)

## How to start using it

First download the latest version from this [link](https://github.com/iGarikoitz/Aura/releases). After this, you need to download **emulator** and get **ROMs** to play.

### Emulators

For arcade games **RetroArch** is used with the core `final burn alpha` by default. You can also use **MAME** if you prefer.

* **Arcade (Using RetroArch)**

	1. [Download](https://www.retroarch.com/?page=platforms) and put inside the emulators folder.
	2. Open RetroArch and go to: `Online Updater/core updater/` and select `Arcade (FB Alpha)` to download de core.

* **Arcade (Using MAME)**

	1. [Download](https://www.mamedev.org/release.html) and put inside the emulators folder.
	2. In each game you want to use **MAME** you need to Find `settings.conf` inside the game folder. In `launcher` in launcher, you have to replace `final burn alpha` with `mame` same as in the code below:

	~~~
 	list.path            = collections/%ITEM_COLLECTION_NAME%
	list.extensions      = zip
	launcher             = mame
	media.system_artwork = collections/%ITEM_COLLECTION_NAME%/
	~~~

### ROMs

* Put **ddonpach.zip** rom inside `dodonpachi` folder.
* Put **garou.zip** and **neogeo.zip** roms inside `garou mark of the wolves` folder.
* Put **mslug3.zip** and **neogeo.zip** roms inside `metal slug 3` folder.
* Put **pbobblen.zip** and **neogeo.zip** roms inside `puzzle bobble` folder.
* Put **sfiii3.zip** and **neogeo.zip** roms inside `street fighter 3 3rd strike` folder.

## How to add my own games.

### Images

When you add a game, you have to include six images in JPG. Why in JPG image format? Because RetroFE works more fluid using JPG compared to PNG.

  *  **Cover** (460 x 690 pixels) Game artwork with logo.
  *  **Fanart** 1280 x 720 pixels) Same Game artwork occupying the entire width.
  *  **Fanart blur** (1280 x 720 pixels) Same Fanart image with 15% Gaussian blur.
  *  **Screenshot 1** (? x 220 pixels) (Depends on the screen ratio). Title screen. The height has to be 220 pixels.
  *  **Screenshot 2** (? x 220 pixels) (Depends on the screen ratio). First gameplay screenshot. The height has to be 220 pixels.
  *  **Screenshot 3** (? x 220 pixels) (Depends on the screen ratio). Second gameplay screenshot. The height has to be 220 pixels.
