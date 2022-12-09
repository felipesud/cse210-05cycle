# Cycle
Cycle is a game where the players try to cut each other off using cycles that leave a trail behind them.

## Getting Started
---
Make sure you have Python 3.8.0 or newer installed and running on your machine. Open a terminal and 
browse to the project's root folder. Start the program by running the following command.
```
python3 jumper 
```
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the 
project folder. Select the main module inside the dice folder and click the "run" button.

## Project Structure
---
The project files and folders are organized as follows:
```
root
├── constants.py
├── game/
│   ├── casting/
│   │   ├── actor.py
│   │   ├── cast.py
│   │   ├── cycle.py
│   │   └── score.py
│   ├── directing/
│   │   └── director.py
│   ├── scripting/
│   │   ├── action.py
│   │   ├── control_actors_action.py
│   │   ├── draw_actors_action.py
│   │   ├── handle_collisions_action.py
│   │   ├── move_actors_action.py
│   │   └── script.py
│   ├── services/
│   │   ├── keyboard_service.py
│   │   └── video_service.py
│   └── shared/
│       ├── color.py
│       └── point.py
├── __main__.py
└── README.md
```

## Required Technologies
---
* Python 3.8.0
* Raylib

## Author
---
* Felipe Belisário