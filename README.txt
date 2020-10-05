//=============================================\\
|  ___   _   _____   __   ___   _   __  __ ___ 	|
| | __| /_\ / __\ \ / /  / __| /_\ |  \/  | __|	|
| | _| / _ \\__ \\ V /  | (_ |/ _ \| |\/| | _| 	|
| |___/_/ \_\___/ |_|    \___/_/ \_\_|  |_|___|	|
|                                              	|
\\=============================================//

>> Project EasyGame >>

A simple game about two (triangle shape) spaceship fighting each other...
Who will be fated for the victory?

This README list a files and folder contained in this package and provide
some useful information.

=================
Table of Contents
=================

a. Definition
0. About Project
1. Files List
2. How to Play
3. Resources
4. Known Bugs


---------------
a. Definition
---------------

Some word use in this README will have the following definition:
- Project : 	Final project in Practicum for Com. Eng. subject
- Board   : 	Practicum Microcontroller board
- switch  : 	Microcontroller switch

----------------------
0. About This Project
----------------------

This game has been made with Construct 3, Web-base game maker engine,
and hosted by Google Firebase.

You can play the game here:

>> https://cpe-easygame.firebaseapp.com/

The game was built to be played in local, two player together in one device.
No online multiplayer support.

This game is a part of Final project in Practicum for Computer Engineering,
And has been made by

	6010506352	Apiwit Prasittikarnkul
	6110507571	Peeraphat Tontulawat

In Faculty of Computure Engineering, Kasetsart University.

---------------
1. Files List
---------------

> Source Code 	Folder contain hardware code and game materials use in the
		project.

  > html	Folder contain resources such as images, audios and other
		web based files used in the project.

  + z-key.zip,	    Zip file contain V-USB port for Atmel's microcontrollers.
  + slash-key.zip   (See below for more details)

  - EasyGame.c3p    Construct 3 project file. Open it in Construct 3 editor.
		    https://editor.construct.net/

- schematic.png	 Schematic diagram of the board.
- license.txt	 License file for this project.
- README.txt	 This file.

---------------
2. How to Play
---------------

>> Setup the code:	

From usb-ghost folder, run 'usb-ghost.ino' with Arduino IDE, It should also open
all necessary file in Arduino IDE tab. Bootloading and upload the code will set
the board to act as a keyboard button with corresponding zip file name:
	Use slash-key.zip for Player 1 	will set a switch as '/' button
	Use z-key.zip for Player 2	will set a switch as 'z' button

Keyboard:	Using '/' button for Player 1. (Upper side in screen)
		and 'z' button for Player 2. (Lower side in screen)

Board:		Compile the code attached with the project to set the
		board. And use a switch of each board for controlling.

(Both keyboard and switch can be use at the same time)

>> In-game control:

From title screen, Hold both P1 and P2 button (or each board switch)
for a short time to start the game.

Shooting is automatic. Moving is also automate in direction of left and
right. Simply hit a button (or switch) to change direction of spaceship.

Keyboard only:	Press 'Space' button to pause the game
		Press 'Esc' while pause to resume the game

Press both 'z' and '/' button (or board switch) while pause will return
to title screen

(Some of button information can be found in-game)

---------------
3. Resources
---------------

All resources and services that have been used in the project will be
listing here.

About resources' term of use, Please refer to each individual creator's
policies that can be found in each link.

>> Sprites & Animations

2D Explosion Animations | Frame by frame - Sinestesia
> https://opengameart.org/content/2d-explosion-animations-frame-by-frame

Sprite below come with Construct 3 Top-down shooting template
- Triangle spaceship (The player)
- White circle (Used as stars)

Sprite below are made by Apiwit Prasittikarnkul and it should not be used
outside of this project without permission.
- Both side shooting bullet
- Purple sword bullet
- [P] Power-up item
- [+] Green cross (healing item)

>> Audios

M-ART
> http://mart.kitunebi.com/index.html

Purple Planet Music
> https://www.purple-planet.com/top-tracks

ZapSplat
> https://www.zapsplat.com/sound-effect-category/game-sounds

freeSFX
> https://www.freesfx.co.uk/sfx/game

>> Others

Construct 3
> https://www.construct.net/en

Google Firebase
> https://firebase.google.com/

---------------
4. Known Bugs
---------------
Music - Title screen music may not play in the first launch.
Simply click the screen or press a button in keyboard or microcontroller switch
should let the music to play properly.


----------------------- END OF README FILE ---------------------