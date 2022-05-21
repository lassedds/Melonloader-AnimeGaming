# Quick setup guide

# Disclaimer

This program injects code into the running game. More than that, the game has kernel access to your pc while running so if the developer wanted to, in a future update they could easily detect this software and ban you for using it.

**TLDR**: You will probably get banned when using this.

## Requirements
<a href="https://github.com/Grasscutters/GrassClipper">Grassclipper</a>

<a href="https://anonfiles.com/P0o9defby2/MelonLoader_rar">MelonLoader</a>

For MelonLoader to work, you must be an administrator in Windows, otherwise it will not work!
To verify this, simply press the Windows key and type CMD. This will bring up a program called Command Prompt, or the equivalent in your language, and you should see an option on the side called "Run as administrator".

### Installation
1) Download the Melonloader files found <a href="https://anonfiles.com/P0o9defby2/MelonLoader_rar">here</a> on this page.

2) Extract the files and put them in the root directory of Genshin Impact (This is where `GenshinImpact.exe` is located, **NOT** "**launcher.exe**".)

3) **DO NOT RUN THE GAME YET** | Or else Melonloader will delete itself.

4) Locate the GrassClipper folder (assuming you are using Grasscutter and opening the game with GrassClipper). In this folder there is another folder called `scripts` where you will see many "**.cmd**" files, of which you want to find the one called "*private_server_launch.cmd*".

5) Now right-click it and open it with Notepad or any other note-taking program you use.

6) There you will see a lot of stuff that you don't need to care about. You have to find a line saying this: <nobr>`:: Launch game "%GAME_PATH%"`</nobr>

7) Now add  `--melonloader.agfoffline` to the second line so it looks like this:
8) `%GAME_PATH%" --melonloader.agfoffline`
9) You should now be able to start the game through Grassclipper.

If you run into any problems, add Lantic#6747 or Codecat#2014 on Discord and we will try to get back to you as soon as possible.
