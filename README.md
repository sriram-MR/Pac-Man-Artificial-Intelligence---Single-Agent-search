# Pac-Man-Artificial-Intelligence---Single-Agent-search
This project was implemented as a part of the Artificial Intelligence course - CSE571. The course was taken in Spring 2020 at ASU.


Below are the command line to implement the code.

run and play the game.

python pacman.py 

For depth first Search -

python pacman.py -l tinyMaze -p SearchAgent
python pacman.py -l mediumMaze -p SearchAgent
python pacman.py -l bigMaze -z .5 -p SearchAgent


For Breadth first search -

python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs
python pacman.py -l mediumDottedMaze -p StayEastSearchAgent
python pacman.py -l mediumScaryMaze -p StayWestSearchAgent


A* sraech

python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic

Corner heuristics problem

python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5


Food Heuristics problem

python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5

Sub-optimal search

python pacman.py -l bigSearch -p ClosestDotSearchAgent -z .5
