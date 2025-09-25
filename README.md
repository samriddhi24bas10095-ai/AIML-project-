# AIML-project-
Vityarthi project for AIML course
CSA2001 - Autonomous Delivery Agent
This project is an implementation of an autonomous delivery agent that navigates a 2D grid city to deliver packages efficiently. It uses various search algorithms to find optimal paths while operating under fuel and time constraints.

Dependencies
Python 3.x

Tkinter (usually included with Python)

How to Run
The project includes a graphical user interface (GUI) for visualization and running simulations.

Clone the repository or download the files.

Ensure your file structure is correct: The maps folder must be in the same directory as the Python script.

Run the script from your terminal:

python aiml_vityarthi.py

(Replace your_script_name.py with the actual name of your Python file).

Using the GUI:

Map: Select the desired map file from the dropdown.

Algorithm: Choose the planning algorithm to use (e.g., astar, bfs).

Run: Executes a single simulation with visualization.

Compare All: Runs all algorithms on all maps and generates a summary report in the information panel. This is useful for gathering experimental data.

Reset: Clears the current simulation.

Grid File Format
The .txt map files use the following character-based format:

S: Agent's starting position.

P / P1: Package pickup location.

G / G1: Package delivery destination.

X: An impassable static obstacle.

1, 3, etc.: A number representing the terrain cost (fuel consumed) to enter that cell.
