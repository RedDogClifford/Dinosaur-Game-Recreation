# Dinosaur-Game-Recreation
Recreated Google's Dinosaur Game using SFML.

Made by RedDogClifford.

## Gameplay of the recreated game

https://youtu.be/x4zw4AwXctA


## Download link for the game only 

https://drive.google.com/drive/folders/1hGBYNhOxN6XGQunfPfULzbwxPyiy21-C?usp=sharing

*.dll files need to be in same file path as .exe.*


## Build

If you did want to build the application on your own device you would need to install SFML-2.5.1 on your system.
Steps can be found on the SFML website.
You would also need to reroute the make file to the path with the SFML library.

Once a successful build is done with the make command,
you will also need to ensure the openal32.dll library is in the same filepath as the executable.
The openal32 library cannot be statically linked unlike the other .dll files that are in the SFML bin.
