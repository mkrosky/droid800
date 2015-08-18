# Introduction #

This is the on-line manual for the Droid800 Atari 8 bit machine emulator. Droid800 is an Android port, and custom front-end, for the popular <a href='http://atari800.sourceforge.net'>Atari800</a> emulator.

# What is an Emulator? #

In this case, an emulator is an application that allows you to run programs written for Atari 8 bit machines like the Atari 800 on your Android device. Your Android phone doesn't have an 810 disk drive or a cartridge slot (duh!), instead Droid800 plays copies of original Atari programs available in several image formats.

For a more general discussion of emulators and file images, I refer you to the following wikipedia articles on <a href='http://en.wikipedia.org/wiki/Emulator'>emulation</a> and <a href='http://en.wikipedia.org/wiki/ROM_image'>rom images</a>.

# Getting Started #

Droid800 is an _emulator_; before you can do anything with it you need to transfer OS _roms_ and program files to your Android device. It is recommended, but not required, that roms be placed in the "/sdcard/Droid800" directory on your SD card. For directions on how to download Atari roms, skip to the Loading\_Roms section below. .

# Home Screen #

The application opens to the home screen on startup.

![http://droid800.googlecode.com/files/homescreen-portrait.png](http://droid800.googlecode.com/files/homescreen-portrait.png)

The home screen contains the following elements:

  * A vintage Atari scene in the background :-)
  * The name of the OS file
  * The name of the program file to be loaded at startup.
  * A "Load OS" button
  * A "Load File" button
  * A "Clear" button
  * A "Play!" button

There is also a standard Android menu available from the home screen, covered in the Preferences section below.

_Quickstart:_
  * 1) Click the "Load OS" button to browse your storage to find the OS rom to load. The recommended OS file is usually called 'ATARIXL.ROM' and can be found with a google search.
  * 2) Click on the "Load File" button to browse storage for a program file to run at startup. Supported files types include .atr, .cas, .bin.
  * 3) Click the "PLAY!" button to launch the emulator.

# Console and Emulator Controls #

All Atari console controls and some emulator controls are available in the pop-up button panel. The panel can be activated by pressing the Android menu button and then the "control panel" menu item.


| Button	| Function |
|:-------|:---------|
| Reset	 | Atari Reset switch |
| Option	| Atari Option button |
| Select       | Atari Select button |
| Start        | Atari Start button |
| Quit         | Quit the emulator |
| F1           | Bring up the Atari800 menu |
| Escape       | Go back in the Atari800 menu |
| Break        | The Atari "break" key |

# Game Controls #

There are several methods of directional control available:

  * On screen controls: Directional control is performed by using the touch screen - guides are printed on screen.
  * Hardware DPad: If the device has a hardware DPad (example: Original Motorola Droid), it can be used for directional control
  * Accelerometer: Directional control is performed by tilting the device. Note: the accelerometer joystick is at rest when the device is tilted slightly before you
  * Mapped keys: Hardware keys can be mappped for directional control.

## On Screen Controls ##

The screen is divided into 2 areas:

![http://droid2600.googlecode.com/files/onscreencontrols.1.png](http://droid2600.googlecode.com/files/onscreencontrols.1.png)

  * Area 1 contains the on-screen d-pad. A guide is displayed in this area to show the location of the d-pad axis. Touching this section of the screen causes the virtual joystick to be moved in a direction relative to the d-pad axis. This area can be configured to occupy either the left half or the right half of the screen.
  * Area 2 is the trigger area. Touching the screen anywhere in this area causes the trigger button to be pressed. This area can be configured to occupy either the left hand or the right hand part of the screen.
  * Area 3 is reserved for future use.

## Hardware D-Pad ##

Some devices, like the original Motorola Droid, have hardware d-pads. Hardware d-pads are enabled by default and can be used along with any other control.

## Accelerometer ##

The device's accelerometer can be used for directional control, that is - tilting the device produces up movement. Note that when the accelerometer joystick is enabled, the joystick is "at rest" when the device is tilted slightly toward you.

| Atari Joystick | Android Device |
|:---------------|:---------------|
| Left	          | Tilt device left |
| Right          | Tilt device right |
| Up             | Tilt device foreward (away from you) |
| Down	          | Tilt device backwards (toward you) |
| Trigger        | Entire touchscreen |

## Mapped Keys ##

Directional controls and the joystick trigger can be mapped to any available hardware key. See the "Mapping Keys" section for details.

# Preferences #

The preferences screen is accessed by pressing the Android "menu" key while on the home screen.

## System Type ##

Select the type of Atari you want to emulate. The default choice is the 800XL. Your OS rom must match the system type!

## Audio Settings ##

  * Sound: Enable or disable sound output.
  * Max Volume: Limit the volume of the emulator. If the current volume is greater than Max, the volume will be reduced during game play.
  * Sample Rate:

## Display Settings ##

  * Landscape Mode:
  * Stretch to fill Window:
  * Show Speed:
  * Skip Frames: Skip frames in order to maintain full emulation speed. By default the emulator attempts 60 frames per second which is not attainable on most devices. Set the skip rate to 25% or 50% to enable full speed emulation
  * Video System: Choose NTSC or PAL

## Game Controls ##

  * Configure Default Controller: The type of controller that will be active when you start the emulator.
  * Accelerometer: Enalbe or disable the accelerometer joystick
  * On Screen Controls: Enable or disable the on screen controls
  * On Screen Control Layout: Decide where the on screen d-pad will be displayed (Bottom Right, Top Right, Bottom Left, Top Left
  * On Screen Controls Size: Select the size of the on sceen d-pad (smallest, small, medium, or large)

## Key Mapping ##

Game controls can be mapped to an Android physical keyboard. The default mapping is

  * Player 1 Joystick Down -> DPAD Down
  * Player 1 Joystick Up -> DPAD Up
  * Player 1 Joystick Left -> DPAD Left
  * Player 1 Joystick Right -> DPAD Right
  * Player 1 Joystick Trigger -> Left ALT

