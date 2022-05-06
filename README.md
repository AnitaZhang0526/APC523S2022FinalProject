# APC523S2022FinalProject

README

This program simulates fluid diffusion through porous media. 3 different boundary conditions and 3 different initial starting spots are possible. Constants and materials parameters can be slightly tweaked as well. Comments throughout the code should explain most of the important functionality. The end output is an animation file, which can be downloaded and viewed with any media player (mp4 file). We recommend using the “rigid” boundary conditions (this is the default) with initial origins “edge”, “center point” or “edge point” and comparing the behavior across the 3 starting spots. 

File Descriptions:

2D_multigrid_diffusion.py
Python file/notebook 

final.sh
Shell script to run the .py 

To run the program, simply ```cd APC523S2022FinalProject``` and then call ```./final.sh```

By changing parameters (g.q in particular) in the function “update force” the forcing terms can be adjusted, and it is worth looking at how forcing affects diffusion as well. 

Feel free to let any of us know if you have any questions.
Anita Zhang (anitazhang@princeton.edu), Christine Blackshaw (cb9072@princeton.edu), Vladislav Sevostianov (vs14@princeton.edu) 

For our project submission, the following files are included:
1) powerpoint
2) pdf write up
3) .py file of the code
4) .ipynb files of the code (in case that is easier to use)
5) .sh shell script to run the .py files
6) this README
7) a couple mp4 videos which show example output
