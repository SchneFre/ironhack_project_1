# ironhack_project_1
The project involves developing a text-based adventure game where players navigate through a haunted mansion filled with puzzles, locked doors, and eerie characters. The objective is to find keys to unlock the main gate and escape before time runs out.

# General info
The escape_the_mansion.py file contains the source code of the command promt version of the game.
The gradio files contain a version with a user interface.
The functionality and gameplay is similar in both files:
The following floorplan is used in the game:
![{40F97F9F-FDDD-4948-8502-134873520420}](https://github.com/user-attachments/assets/2a8b0e4d-52a6-4226-99b6-6e82576c9d75)
# Featurs
- the overall goal is to find the key to the main door and escape the mansion
- the user can inspect the items in the current room and search for the keys to the doors.
- if the user interacts with the doors he can unlock them if the correct key is in the inventory
- if he unlocks a door, he automatically moves to the next room
- in the next room he can search the room again or interact with the doors.
- if the user takes too long to exit the mansion a ghost appears and kills him
- the second time the user enters the hallway, a Zombie appears.
    - the user can either fight the zombie or run away
    - the fight can only be won, if the knifes from the kitchen are in the users inventory
    - the key to the main gate is hidden in the oven
- the Gradio version includes a user-interface and images for each room
# Useage
- excecute the "escape_the_mansion.py" file (i.e. play button in visual Studio Code) or the gr_escape_from_the_mansion.py file.
- the gr_escape_from_the_mansion.py will afterwards open a port and display it in the command promt that can be accessed in the browser
# Requirements
- the images have to be in the same folder as the gradio file (gr_escape_from_the_mansion.py)
- gradio==5.34.2
