# StealthGame
C++ Stealth Game from Udemy tutorial

# Play
You can play in splitscreen form opening the game in the Unreal Engine using the `FPSGame.uproject` file.

## Multiplayer
To play in multiplayer, you need to package the game.
  - Go in the Engine
  - File > Package Project > Windows > Windows 64bit
  - Save the package in the folder of your choice
  - Zip the folder `WindowsNoEditor` and send it to your friend
  - Run the game by clicking on `FPSGame.exe`
  - In the game, open the console by clicking on the `~` key
  - write `open FirstPersonExampleMap?listen`: this will make you the host
  - your friend can now run the game
  - In his game, he needs to write `open yourIpAdress:7777` in the console
     - :warning: the port 7777 needs to be forwarded in your router for this to run if you don't play in the same network.
  - Enjoy! :tada:
