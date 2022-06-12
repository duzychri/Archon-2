<p align="center">
  <img width="432" height="84" src="https://github.com/duzychri/Archon-2/blob/main/images/logo_large.png?raw=true">
</p>

A 2D top-down spaceshooter written in C# using the Monogame framework.

<p align="center">
  <img width="320" height="180" src="https://github.com/duzychri/Archon-2/blob/main/images/screenshot_1.png?raw=true">
  <img width="320" height="180" src="https://github.com/duzychri/Archon-2/blob/main/images/screenshot_2.png?raw=true">
</p>

**[:rocket: Download the newest version here :rocket:](https://github.com/duzychri/Archon-2/releases/latest "Archon 2 Release")**

## Gameplay Features

* Control an agile spaceship
* Fight evil enemies that are attacking
* Challenge a powerful boss
* Change your resolution or play in fullscreen mode
* Listen to the sounds of space combat
* The old javascript version is also there
* There is an options menu
* I think you can go fullscreen too
* The old javascript/html version sucks btw. but you can find it in the releases as well
* There are sounds as well my dude

## Engine Features

The games code contains around 18k lines of code and multiple features were hand-crafted from scratch:

* An optimized collision detection system
* A rendering stack with multiple postprocessing effects (for example: bloom, vignette and chromatic abberation)
* An input system that allows seamless switching from controller to keyboard and mouse
* A user interface layouting system supporting layout groups, images and text
* A sprite and sprite sheet system with a sprite animator allowing for seamless animation switching
* A game settings menu, with options that persist between different application runs
* A game object system with support for components (for example: sprite renderer, collision or sprite animator components)

## Older Versions

A list of release versions (including the old javascript/html version of Archon 1) can be found [here](https://github.com/duzychri/Archon-2/releases "Archon 2 Releases")

:warning: **Note:**
For some of the older versions of the game there's a bug where the game doesn't start or returns an error that an xml file could not be read. This is due to an incompatible settings file.
To fix this issue got to the _AppData/Roaming/Archon 2_ folder and delete the _settings.xml_ file. (To open the _AppData_ folder press `Win + R`, type in `%AppData%` and press enter.)
