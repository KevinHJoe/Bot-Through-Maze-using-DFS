# Bot-Through-Maze-using-DFS
My bot finds it's way through a maze using a simple depth first search algorithm

The maze does not have any weighted edges, so it finds it's way by searching one path. If a path leads down a dead end, it will back track to where it started toward that path. The bot will continue to backtrack all dead ends until it reaches the end. A stack will hold the coordinates of the fastest route to ensure the bot will be able to use again if need be.
