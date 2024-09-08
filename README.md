## Go Ban Game

Go Ban Game is a Python-based implementation of the classic board game Go, designed to showcase the concept of mutual exclusion in operating systems. The project demonstrates how to prevent multiple users from accessing shared resources simultaneously, helping to avoid deadlock scenarios.

**Features**

*Mutual Exclusion:* Demonstrates an OS concept where multiple players cannot make moves at the same time, preventing deadlocks and ensuring orderly turn-based gameplay.
*Interactive Game Board:* Players can place stones, form groups, and capture opponents' stones.
*Visual Feedback:* Real-time graphical representation of the Go board and pieces, enhancing user interaction.

**Project Structure**

*Game Logic (go.py):*
This file contains the core game logic, including: Stone placement, Group management, Enforcement of Go game rules.
*Graphical User Interface (main.py):*
This module handles the user interface, including: Drawing the game board and stones, Managing player interactions and moves. 

These components work together to deliver a fully functional Go game experience, allowing players to engage in strategic gameplay while appreciating the underlying systems concept.

**Requirements**

Python 3.x
Tkinter (for GUI)

**How to Execute**

Clone this repository.
Ensure Python 3.x is installed on your system.
Install Tkinter (if not already installed).
Run the following command to start the game:
bash
Copy code
python main.py

**Operating Systems Concept**

The game also highlights the mutual exclusion principle in operating systems. In this context, mutual exclusion ensures that only one player can make a move at a time, mimicking the restriction of access to shared resources. This concept prevents race conditions and ensures a smooth game flow without deadlocks.


**Screenshot** 
![Screenshot 2024-06-19 175822](https://github.com/manvithapula/GoBan-Game/assets/113161233/db03b5eb-765a-4e61-ac92-a8c5c7734788)

![Screenshot 2024-06-19 175848](https://github.com/manvithapula/GoBan-Game/assets/113161233/f2a08f93-81c8-4a44-8ba7-042cfeca9800)

