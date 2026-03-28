Hospital Night Shift Adventure Game
Technical Documentation

Seil Tekinaeva
Date: 03/28/2026


1. Where the Code Is Hosted
--------------------------------------------------
The code for this project is hosted on GitHub.
GitHub repository link: https://github.com/seilqw/Final-Adventure-Game.git 

A zipped version of the project was also submitted to the course assignment
folder.

2. External Services
--------------------------------------------------
This project does not use any external services.
It does not use a database, website API, or cloud service.

3. Languages and Technologies
--------------------------------------------------
Language used:
- Python 3

Technologies used:
- Python modules
- Class object
- GitHub for hosting

4. System Requirements and Supported Applications
--------------------------------------------------
System requirements:
- Python 3 installed
- A computer that can run Python programs

Supported applications:
- IDLE
- Visual Studio Code
- PyCharm
- Terminal / Command Prompt

Supported operating systems:
- Windows
- macOS
- Linux

5. Coding and Naming Conventions
--------------------------------------------------
The project used simple and clear naming conventions.

Examples:
- main.py starts the game
- chapter1.py to chapter5.py contain each chapter
- player.py contains the Player class

Conventions used:
- file names are always lowercase
- function names are lowercase
- class name begins with a capital letter
- variables use descriptive names such as player, score, and menu_choice
- comments of authorship are included at the top of each file


6. How to Run / Build / Deploy the Program
--------------------------------------------------
This program does not require a build process because it is a Python
text-based game.

To run the program:
1. Make sure all files are in the same folder.
2. Open the folder in IDLE or another Python program.
3. Run main.py.

To run in terminal:
python main.py

To deploy the program for this assignment:
- upload a zipped project folder to the course submission folder
- upload the unzipped files to GitHub

7. Overview of the Architecture
--------------------------------------------------
This game is organized into separate Python files.

Files:
- main.py
- player.py
- chapter1.py
- chapter2.py
- chapter3.py
- chapter4.py
- chapter5.py
- readme.txt

Architecture overview:
- main.py is the main starting file
- player.py contains the Player class object
- chapter1 through chapter5 each contain one part of the Hospital story
- the Player object is passed through each chapter
- the Player class stores the score, selected patient, and ending

This modular structure makes the game easier to read and update

8. How to Start the Program
--------------------------------------------------
To start the game, run main.py.

The program will:
- display the game title
- begin Chapter 1
- move through all 5 chapters
- update the player score
- show a final ending based on the score

The user plays by entering choices in the Python shell or terminal.

9. Class Object Used
--------------------------------------------------
This game uses a class object called Player.

The Player class stores:
- score
- selected patient
- ending

The class object is used to keep game data organized across all chapters.

10. Maintenance Notes
--------------------------------------------------
If the program does not run correctly, check the following:
- all files are in the same folder
- file names match the import statements
- Python 3 is installed
- there are no spelling or indentation errors
- main.py is the file being run

If numbers appear after the game ends in IDLE, that is because the program has
already finished and the user is typing directly into the Python shell.


11. Summary
--------------------------------------------------
Hospital Night Shift Adventure Game is a modular text-based Python adventure
game. The program uses separate chapter files and a Player class object to
manage game progress and final results.
