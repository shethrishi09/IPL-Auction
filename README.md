#IPL Auction Simulator (Python)
This is a Python project for simulating the Indian Premier League (IPL) player auction. It's a command-line application that demonstrates file I/O and data management for a simulated auction environment.

📌 Features
Manage the auction process for players.

Manage team budgets and track spending.

Track player status (Available, Sold, Unsold).

Display detailed reports for each team's squad.

Data is persistently stored in text files.

🛠️ Technologies Used
Python 3

File I/O (for reading/writing to .txt files)

🗂️ Data Structures Used
List → to store the records of available, sold, and unsold players, and the list of teams.

Dictionary → to represent the details of each player and team with key-value pairs.

Classes & Objects (OOP) → to structure the application logic, separating file handling (File class) from auction operations (IPL class).

🚀 How to Run
Follow these steps to run the project:

Setup Files

Ensure all project files (main.py, availablePlayers.txt, soldPlayer.txt, UnsoldPlayers.txt, Teams.txt) are in the same directory.

Open Your Terminal

Open a command prompt, PowerShell, or any other terminal on your computer.

Navigate to Project Directory

Use the cd command to navigate to the folder where you saved the files.

Bash
cd path/to/your/project/folder
Run the Project

Start the application using the python command:

Bash
python main.py
📖 Notes
The text files act as a simple database; ensure they are present and correctly formatted before running the application.

This project is created for educational purposes to demonstrate Python concepts like OOP, file handling, and data structures.
