# DSA-Word-Puzzle


A **Word Puzzle Game** implemented in **C++** as part of a Data Structures and Algorithms (DSA) final project. It demonstrates the use of core data structures and object-oriented programming.

---

## Features
- Word puzzle gameplay on a grid  
- Dictionary support with hash table lookup  
- Stack for undo/redo moves  
- Grid & GameManager classes for puzzle logic  
- Basic GUI layer (GridGUI) for interaction  

---

## Project Structure
📂 PROJECT_TESTing
┣ 📂 include # Header files (Dictionary.h, Grid.h, HashTable.h, Stack.h, GameManager.h, GridGUI.h)
┣ 📂 src # Source files implementing classes
┣ main.cpp # Entry point
┣ PROJECT_TESTing.cbp # Code::Blocks project file


##Howto Run
```bash
# Clone repo
git clone https://github.com/Mahnoor0000/DSA-Word-Puzzle.git

# Build (example using g++)
g++ main.cpp src/*.cpp -I include -o word_puzzle

# Run
./word_puzzle
Or open PROJECT_TESTing.cbp in Code::Blocks and build/run.

 Concepts Used
Hash Tables for fast dictionary lookup

Stacks for undo/redo

Grid-based puzzle solving

OOP principles in C++

✨ Future Improvements
Better GUI

Scoring system & timer

Multiple levels

Save/load game option
