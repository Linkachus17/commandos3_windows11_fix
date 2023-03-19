# Introduction
This guide will fix Commandos 3 : Destionation Berlin that has:  
1.Glitchy Loading screen  
2.Broken Sniper sniper scope (as well as Enemy sniper scope)

I made this so you don't have to spend lot of time figuring what's wrong with the game being broken in modern machine (because the game is already that broken, 
yes even the HD Remaster still broken in some way), or tried making a Virtual Machine but end up with more problem in the process.

I tried using **dgvoodoo** which seems not working for me because of complicated steps that I don't fully understand.  

<img src="https://github.com/Linkachus17/commandos3_windows11_fix/blob/main/Broken%20Loading.png" width="400" height="400" /> <img src="https://github.com/Linkachus17/commandos3_windows11_fix/blob/main/Broken%20Sniper.png" width="400" height="400" /> 

<img src="https://github.com/Linkachus17/commandos3_windows11_fix/blob/main/Loading.png" width="400" height="400" /> <img src="https://github.com/Linkachus17/commandos3_windows11_fix/blob/main/Sniper.jpg" width="400" height="400" />  
*Running the game with DXWnd fixes the problems*


# Tool you need
DXWnd (https://sourceforge.net/projects/dxwnd/)

# Steps
Asuming you already download the tools you need...  
1.Find commandos3.exe, Right click -> Properties -> Compability tab -> Check **"Reduced color mode = 16-bit (65536) color"**  
<img src="https://github.com/Linkachus17/commandos3_windows11_fix/blob/main/Screenshot%202023-03-20%20043854.png" width="400" height="400" />  

2.Open DXWnd, **drag and drop** commandos3.exe into DXWnd   
<img src="https://github.com/Linkachus17/commandos3_windows11_fix/blob/main/DXWnd%20drag%20and%20drop.gif" width="640" height="360" />

3.From here, you can just simply run the game from DXWnd and leave the settings by default  
4.Enable "Mouse Clipper" in "Mouse" tab in DXWnd to prevent cursor clipping outside the game window


# Problems
**Will not work if you tried to play in native Fullscreen, you're only limited to windowed mode  
Your only option is to set the window size to 1280 x 960, and perhaps play around with the filers in DirectX tab in DXWnd to make it look better  
BG or Borderless Gaming will only stretch it and it'll just look worse for me, unless it's fine for you**
<img src="https://github.com/Linkachus17/commandos3_windows11_fix/blob/main/Screenshot%202023-03-20%20045240.png" width="400" height="400" />  
