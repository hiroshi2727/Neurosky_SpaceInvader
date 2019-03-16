# Neurosky_SpaceInvader
COGS 189 class project which uses neurosky mindwave headset to play space invader game in python.  
Original code from: https://github.com/leerob/Space_Invaders.  

# Requirements
Windows PC  
Python 2.7.15  
Pygame 1.9.4  
NeuroPy 0.1  
Neurosky Mindwave Headset  

# Set up  
1) Create a conda Python 2.7.15 environment  
2) Download and extract the NeuroPy.zip from: https://github.com/lihas/NeuroPy/tree/master/dist  
3) Extract the zip, and navigate to the directory with the command prompt
4) With your activated Python 2.7.15, run python setup.py install
5) After NeuroPy is installed install pyserial via:
```
pip install pyserial
```
6) Change the variable "PORT 1" in line 17 of spaceinvader.py to your COM or dev location  
7) Run the following code:
```
python spaceinvaders.py
```
