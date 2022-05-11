# Quick setup guide

## Requirements
<a href="https://github.com/Grasscutters/GrassClipper">Grassclipper</a>

<a href="https://anonfiles.com/P0o9defby2/MelonLoader_rar">MelonLoader</a>

### Installation
1) Download the Melonloader files found here on this page.

2) Extract the files from Github and put them in the root directory of Genshin Impact (This is where "*GenshinImpact.exe*" is located, **NOT** "**launcher.exe**".)

3) **DO NOT RUN THE GAME YET** | Or else Melonloader will delete itself.

4) Locate the GrassClipper folder (assuming you are using Grasscutter and opening the game with GrassClipper). In this folder there is another folder called "*scripts*" where you will see many "**.cmd**" files, of which you want to find the one called "*private_server_launch.cmd*".

5) Now right-click it and open it with Notepad or any other note-taking program you use.

6) There you will see a lot of stuff that you don't need to care about. You have to find a line saying this: "*:: Launch game "%GAME_PATH%"*"

7) Now add  "*--melonloader.agfoffline*" to the second line so it looks like this: "*"%GAME_PATH%" --melonloader.agfoffline*"

8) You should now be able to start the game through Grassclipper.

If you run into any problems, add Lantic#6747 or Codecat#2014 on Discord and we will try to get back to you as soon as possible.
