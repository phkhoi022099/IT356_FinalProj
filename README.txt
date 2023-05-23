Khoi Pham
IT356 001 Spring 2023

Final Project - 3D Vehicle Simulator

Download the src folder

Extract src.zip

Use CMake on the src folder to get the build/bin folder. 

Open build folder > Run finalProj.sln and build solution of that .sln file

Open bin folder > Run KHOIPHAM_FinalProject.exe



~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~
Hotkeys: 

WASD: Move camera postion. (Forward/Backward/Left/Right).
Q: Rotate the model around x-axis (On/off)
R: Rotate the model around y-axis (On/off)
F: Reset the model back to the original position (Camera position unchanges).
G: Switch gamma correction. 

~~~~~~~~~~~~~~
~~~~~~~~~~~~~~
CODE: 

There are only 2 vehicle models available which are:
	- T90 tank model (default)
	- Harley motorcycle model 

To change between these models change the code in .sln file
line 113~114

***BE CAREFUL WHEN BINDING TEXTURES INTO THE MODEL***
line 95~97

***If you want to use you own model change the line 95 accordingly***

Cubemap:

Skybox: line 216~223 (Default)
Golgate Bridge: line 223~234


