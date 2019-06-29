
# Slowly creating/finding assets to replace the Nintendo assets.

# uMario_Jakowski
uMario C++/SDL2 Game by Łukasz Jakowski

Author: Łukasz Jakowski

WWW: http://lukaszjakowski.pl
Email: jakowskidev@gmail.com

EXE and DLL - Download: http://lukaszjakowski.pl/DL/uMario.zip

YouTube video: https://www.youtube.com/watch?v=jya5He7KFsE


It is my first game made in C++.

Visual Studio 2012
SDL Tutorials which I have used:
http://lazyfoo.net/tutorials/SDL/index.php


My Google Play account: https://play.google.com/store/apps/dev?id=4635849298843013993


## Build Pre-requisites

FreeBSD:

    $ pkg install cmake sdl2 sdl2_image sdl2_mixer

OS X (brew):

    $ brew install cmake sdl2 sdl2_image sdl2_mixer
    
Ubuntu:

    $ sudo apt-get install cmake libsdl2-dev libsdl2-image-dev libsdl2-mixer-dev

## Building and running

    $ make build run

    # or

    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ ./uMario

## Replaced assets

Music/sound
- levelend.wav replaced with "Danish Mega Pony 2a03 OST [1].ogg"  https://opengameart.org/content/danish-mega-pony-2a03-ost
- overworld.wav & overworld-fast.wav, replaced with "Juhani Junkala [Chiptune Adventures] 2. Stage2.wav" 
- lowtime.wav replaced with 2 seconds from "CPU Showdown.mp3" https://opengameart.org/content/4-chiptunes-adventurehttps://opengameart.org/content/cpu-showdown

Images
- fireball_*.bmp replaced with "expl_03_0004.png" https://opengameart.org/content/explosions-0
- firework(0,1,2).bmp replaced with "expl_01_000(4,6,8).png" https://opengameart.org/content/explosions-0


