# APC523S2022FinalProject

README

This program simulates fluid diffusion through porous media. 3 different boundary conditions and 3 different initial starting spots are possible. Constants and materials parameters can be slightly tweaked as well. Comments throughout the code should explain most of the important functionality. The end output is an animation file, which can be downloaded and viewed with any media player (mp4 file). We recommend using the “rigid” boundary conditions (this is the default) with initial origins “edge”, “center point” or “edge point” and comparing the behavior across the 3 starting spots. 

File Descriptions:

2D_multigrid_diffusion.py
Python file/notebook 

Final.sh
Shell script to run the .py 

By changing parameters (g.q in particular) in the function “update force” the forcing terms can be adjusted, and it is worth looking at how forcing affects diffusion as well. 

Feel free to let any of us know if you have any questions.
Anita Zhang (anitazhang@princeton.edu), Christine Blackshaw (cb9072@princeton.edu), Vladislav Sevostianov (vs14@princeton.edu) 
