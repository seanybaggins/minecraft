# minecraft
Instructions for getting modded minecraft up and running on clients and connecting to the server.

## First Time Installation
1. Buy minecraft java edition from the [offical minecraft website](https://www.minecraft.net/en-us/get-minecraft).
2. Get [MultiMC](https://multimc.org/). This is the program that will manage minecraft and its mods.
3. Unzip the MultiMC file and run the MultiMC.exe.
    > Note: you may get a warning from windows saying the developer is unknown. This is fine. Windows is just being overly causous about running code that is not from a well known
    > company. If you have any concerns about running MultiMC, you can inspect the source code yourself [here](https://github.com/MultiMC/Launcher/).
4. Right click and press `Create instance`.
5. Download the modpack I have prepared [here](https://drive.google.com/file/d/1LOYQ7dOCvzth2o5nGEifUxKkbj2FhPkl/view?usp=sharing).
    > Note: This modpack is originally from FTB academy. I decided to fork it so we have the abilitly to add and remove mods in the future.
5. In MultiMC, select `Import from zip` and navigate to the zip file you just downloaded.
4. Go to `Setting->Java` and increase your maximum memory allocation. I have mine set to `5120 MB`.
6. Double click on the newly added icon to run the game.
7. Reach out to Sean to get the ip address of the server and to have him add you to the server whitelist.

## Updating your list of installed mods
If the minecraft server gets updated so that mod(s) can be added or removed, you must ensure that your client is running all of the mods with the same version number as the server.
Follow one of the following methods to garuntee your client is using the same list of mods as the server. 

### Option 1: Replacing the `configs`, `defaultconfigs`, `kubejs`, and `mods` directories.
1. Make a backup.
    - In MultiMC, go to the main page and right click on the icon you use to launch the game.
    - Press `Instance Folder`.
    - Navigate up one directory to `FTB Academy 1.16 1.3.0`.
    - Select and then Right click on the `FTB Academy 1.16 1.3.0` directory and press `Send to`->`Compress zip folder`.
2. Navigate back to the `Instance Folder`->`minecraft` directory.
3. Download and unzip the most up to data list of the packages [here](https://drive.google.com/file/d/1LOYQ7dOCvzth2o5nGEifUxKkbj2FhPkl/view?usp=sharing)
4. Copy and paste the `configs`, `defaultconfigs`, `kubejs`, and `mods` directories into the `Instance Folder`->`minecraft`.
> Note: You should get a popup from windows asking you to overwrite these directories of the same name. Select `Replace the files in the destination`
> to continue.
5. Launch the game as you would normally and get back to making awesome things.

### Option 2: Follow the First Time Installation Instructions (not prefered)
If you go this route, your map waypoints and any other infomation that minecraft stores on the client will be lost.

## Patronage
The current cost of hosting the server on creeperhost is $35/month. If you play regularly and are enjoying yourself, please consider helping me with the
monthly server costs by supporting me on patreon [here](https://www.patreon.com/seanybaggins).