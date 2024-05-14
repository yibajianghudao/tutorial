# Play Mount & Blade: Warband
## Proton Version
I can't run it at any proton version that above 4.11-13.  
So maybe you should select this verison(or more lower).

## DirectX
Now You must select Directx 7 when you start the game or it will not work.  
If you try use Directx 9, you will get this error:
`Error loading postFX shaders make sure you have latest DirectX Return code: -2005530516`  
## Solution
You can use this solution:  
At the Mount & Blade: Warband 's menu(it seems /home/XXX/.local/share/Steam/steamapps/common/MountBlade Warband).  
You can select Manage-Manage-Browse Local File to open this path on the MBW page of steam.  
And you will see a DirectX menu,open it. you will see a file: DXSETUP.exe.   
Install this file can help you resolve the above error.  
### Install DXSETUP.exe
Fisrt, you should install this tool: `protontricks`  and you must install 'yad' or 'zenity' to support his GUI.  
`cd` to the directory of the DXSETUP.exe file.  
run `protontricks-launch ./DXSETUP.exe`  
select `Mount & Blade: Warband` and install according to the instructions.  

Enjoy your game!

