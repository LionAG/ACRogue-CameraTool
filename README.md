# ACRogue-CameraTool

### A free camera mod for Assassin's Creed Rogue

## Requirements
- Ubisoft Connect game version (1.07)
- Mod Loader ([Download Here](https://github.com/LionAG/ScriptEngine/releases/latest))

## Features
- Camera control, also in cutscene (including custom roll, pitch, yaw)
- Built-in individual / panoramic screen capture 
- Save / Restore camera position
- Color correction
- More natural shadow
- Depth of Field
- Time of Day
- World Stop
- Slow Motion
- HUD Toggle
  
## Installation

- Download the loader and extract the archive to the game root folder.
- Run the GUI, click on `Add` and select the `.scrx` file.
- Click on `Run` to start the game.

Some AV software is known to block the program - you may need to add the game directory to the exclusion list.

If you need help feel free to join the chat on [Element](https://matrix.to/#/!fiJSxMURNZlyjalmyA:matrix.org?via=matrix.org)

## Controls

| Key | Description |
| --|-- |
| F1				| Toggle HUD |
| F2				| Toggle world stop |
| F3				| Toggle slow motion  |
| F5				| Reload configuration | 
| F6				| Reset camera to initial position |
| F7				| Store camera position |
| F8				| Restore camera position |
| F9				| Individual capture |
| F10				| Panoramic capture |
||
| Numpad 3			| Time of day forward |
| Numpad 1			| Time of day backward |
| Numpad 0			| Time of day freeze |
||
| Home				| Enable free camera |
| I					| Camera forward |
| K					| Camera backward  |
| J					| Camera left  |
| L					| Camera right |
| Space				| Camera up |
| Control				| Camera down |
| Numpad +			| Increase FOV |
| Numpad -			| Decrease FOV |
||
| End				| Activate rotation |
| Numpad 8			| Pitch up |
| Numpad 2			| Pitch down |
| Numpad 4			| Yaw left |
| Numpad 6			| Yaw right |
| Numpad 7			| Roll left |
| Numpad 9			| Roll right |
| Numpad 5			| Reset rotation to default |

## Color Corrections

| Key | Description |
| --|-- |
|ALT + NUMPAD9  |Increase Hue|
|ALT + NUMPAD7  |Decrease Hue|
|ALT + NUMPAD6  |Increase Saturation|
|ALT + NUMPAD4  |Decrease Saturation|
|ALT + NUMPAD3  |Increase Brightness|
|ALT + NUMPAD1  |Decrease Brightness|
|ALT + NUMPAD8  |Increase Contrast|
|ALT + NUMPAD2  |Decrease Contrast|
|ALT + NUMPAD5  |Reset|

## Custom keybinding

To customise the camera keybinding as well as various other parameters, head to:


`[game_root_directory]\ScriptEngine_Data\RTConfig`.


Configuration is stored in the file named `ACC_CameraTools.ini`.

Via this [LINK](https://cherrytree.at/misc/vk.htm) you can find the the correct key value reference.
</br>

## Notes
* Press F5 to apply changes made to the `ACC_CameraTools.ini` file.
* Keybinding cannot be empty. If you wish to disable a keybind set the value to 0. [eg. *KeyToggleFirstPersonCam = 46*. Change `46` by `0`] 
* Activating the first person view while sailing might result in a crash.
