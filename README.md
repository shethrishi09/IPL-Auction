# IPL Auction Simulator (Python + Text Files)

This project is a **Python-based IPL Auction Simulator** that uses **text files** as a simple database. It demonstrates the use of core Python concepts like **Object-Oriented Programming (OOP)** and **file I/O** for managing a simulated auction environment.

---

## 📌 Features
- Manage the **auction process** for players.
- Manage **team budgets** and track spending.
- Track player status (**Available**, **Sold**, **Unsold**).
- Text files (`.txt`) included to act as a database with sample data.
- Console-based interaction for simplicity.

---

## 🛠️ Technologies Used
- **Python 3**
- **Text Files (.txt)** for data storage
- **Standard Library Modules**

---

## 🚀 How to Run

Follow these steps to run the project:

1. **Setup Files**
   -   Ensure all project files (`main.py`, `availablePlayers.txt`, `soldPlayer.txt`, `UnsoldPlayers.txt`, `Teams.txt`) are in the same directory.

2. **Open Your Terminal**
   -   Open a command prompt, PowerShell, or any other terminal on your computer.

3. **Navigate to the Project Directory**
   -   Use the `cd` command to navigate to the folder where you saved the files.
      ```bash
      cd path/to/your/project/folder
      ```

4. **Run the Project**
   -   Start the application by running `main.py`:
      ```bash
      python main.py
      ```

---

## 📖 Notes
- **Data Files**: `Teams.txt`, `availablePlayers.txt`, `soldPlayer.txt`, `UnsoldPlayers.txt`.
- `main.py` → main entry point of the project.
- `IPL` class → handles auction logic and data management.
- `File` class → handles reading from and writing to the text files.
