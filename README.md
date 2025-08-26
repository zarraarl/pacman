# Pacman AI (University Project)

This repository contains my university **Pacman AI assignments**, based on the classic UC Berkeley CS188 framework.  
Our professor required us to implement and complete **all exercises** from this project.  

## Contents

- **Search algorithms** (DFS, BFS, UCS, A*)  
- **Heuristics** (e.g., Manhattan heuristic)  
- **Pacman framework** with both text and graphical display  
- **Mini-Contest 1**: custom Pacman agents (`myAgents.py`)  

## Requirements

- Python 3.x  
- Tkinter (for GUI, usually pre-installed with Python)  

## How to Run

Run Pacman with different algorithms, for example:

```bash
python3 search/pacman.py -l tinyMaze -p SearchAgent -a fn=dfs
python3 search/pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
python3 search/pacman.py -l mediumMaze -p SearchAgent -a fn=ucs
python3 search/pacman.py -l mediumMaze -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic
```

For the mini-contest:

```bash
python3 minicontest1/game.py
```

## Notes

- The original framework is from **UC Berkeley CS188 AI course**.  
- All exercises were completed as part of university coursework.  
