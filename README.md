<div align="center">
  <h1>THE GUIDE</h1>
</div>

> ## **DISCLAIMER**, methods mentioned below **ONLY FOR WORK 2.6**.
>
> This program injects code into the running game. More than that, the game has kernel access to your pc while running so if the developer wanted to, in a future update they could easily detect this software and ban you for using it.
>
> **TLDR**: You **WILL GET BANNED** if you use this on Official Servers.

# Requirements :

> <a href="https://anonfiles.com/P0o9defby2/MelonLoader_rar">MelonLoader</a>  
> <a href="https://github.com/Grasscutters/GrassClipper/releases/tag/v0.9.10">GrassClipper</a> _(optional and only for **Method #2**)_

For MelonLoader to work, your current user account must be an "Administrator Account" in Windows, otherwise it **WILL NOT WORK!**  
To verify this, try launching CMD(or any program) as an administrator and you should be able to launch it instead of being asked for an administrator password.  
Also, if you aren't using an "Administrator Account", how'd you even play _the anime game_ in the first place?

# Installation :

### Method #1 (without GrassClipper)

1. Extract the files and put them in the root directory of Genshin Impact (This is where `GenshinImpact.exe` is located, **NOT** "**launcher.exe**".)

2. **DO NOT RUN THE GAME YET** | Or else Melonloader will delete itself.
3. In the above mentioned root directory, create a new file named `start.bat`.
4. Now with a text editor(eg. notepad), open/edit the file(`start.bat`) add the following lines in it:
   > `.\GenshinImpact.exe --melonloader.agfoffline`  
5. Save and close the editor.
6. **ALWAYS** launch the game by Double-Clicking the `start.bat` file.
7. Once again, if you launch the game using the `GenshinImpact.exe` executable or by any other means while using **Method #1**, Or else Melonloader will delete itself.

### Method #2 (using GrassClipper)<sup>_[optional]_</sup>

1. Follow **Method #1** until step 2.

2. Locate the GrassClipper folder (assuming you are using Grasscutter and opening the game with GrassClipper). In this folder there is another folder called `scripts` where you will see many "**.cmd**" files, of which you want to find the one called "_private_server_launch.cmd_".
3. Now right-click it and open it with Notepad or any other note-taking program you use.
4. There you will see a lot of stuff that you don't need to care about. You have to find a line saying this: `"%GAME_PATH%"`
5. Now add `--melonloader.agfoffline` to the same line as `"%GAME_PATH%"` so it looks like this:
   > `%GAME_PATH%" --melonloader.agfoffline`  
6. You should now be able to start the game through Grassclipper.

<br>_If you run into any problems, add Lantic#6747 or Codecat#2014 on Discord and we will try to get back to you as soon as possible._
