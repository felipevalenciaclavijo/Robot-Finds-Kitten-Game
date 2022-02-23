# Greed

## Getting Started
---
Make sure you have Python 3.8.0 or newer and Raylib Python CFFI 3.7 installed and running on your machine. You can install Raylib Python CFFI by opening a terminal and running the following command.
```
python3 -m pip install raylib
```
After you've installed the required libraries, open a terminal and browse to the project's root folder. Start the program by running the following command.```

python3 greed 
```
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the 
project folder. Select the main module inside the hunter folder and click the "run" icon.
'''

## Project Structure
---
The project files and folders are organized as follows:

root                        (project root folder)
+-- greed                   (source code for game)
  +-- data                  (data files for game)
  +-- game                  (specific game classes)
    +-- casting             (cast folder)
      +-- actor             (Visable object methods)
      +-- artifact          (Returns information for objects in game)
      +-- cast              (list of all "actors" in the game)
    +-- directing           (director folder)
      +-- director          (directs the game)
    +-- services            (services folder)
      +-- keyboard_service  (for sensing where the player is in game)
      +-- video_service     (draws game)
    +-- shared              (shared objects for use in other classes)
      +-- color             (color for actors in game)
      +-- point             (gives the location for actors)
  +-- __main__.py           (entry point for program)
+-- README.md               (general info)
```

## Required Technologies
---
* Python 3.8.0
* Raylib Python CFFI 3.7

## Authors
*Logan Andrus lbandrus@byui.edu
*Keeley Imlah wil11070@byui.edu
*Felipe Valencia fevacla@byui.edu
*Kathryn Thompson thompson21057@byui.edu
*Morgan Luke morganluke@byui.edu

*Team 9 CSE-210 Winter 2022
