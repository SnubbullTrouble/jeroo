# Jeroo Maps
These are .jev island maps to be used in Jeroo. To place the jeroo, instantiate a Jeroo isntance and use the starting position listed below for each problem.

## Picking Up Flowers
The problems center around avoiding obstacles and picking up flowers.

### Pick A Flower
The Jeroo starts at position (2, 2), facing East, and the goal is to reach and pick the flower at (3, 3).

### Avoid the Net
The Jeroo starts at (2, 2) and needs to avoid the water at (2, 3) and reach the flower at (2, 4).

### Navigate Water and Nets
The Jeroo starts at (2, 2) and must avoid both water and nets. There is a flower at (4, 1) that it must reach. The Jeroo must hop carefully to avoid obstacles.

### Multiple Jeroos, Multiple Goals
Two Jeroos are in the game, one at (1, 2) and the other at (6, 3). They both need to collect different flowers scattered across the island. The goal is for each Jeroo to pick up the flowers without interfering with each other.

### Pathfinding with Obstacles
The Jeroo starts at (2, 2). It has to navigate through water (w) and avoid nets in order to reach a flower at (4, 4). The challenge here is that the Jeroo will have to use turn() and hop() effectively to maneuver through the map.

### Collecting Multiple Flowers
The Jeroo starts at (4, 3). It needs to collect 3 flowers and avoid water, all while navigating a more complex path. There is water at (1, 1), and the flowers are located at (2, 2), (4, 5), and (5, 2).

### Turn And Avoid Water
The Jeroo starts at (2, 3) and has to turn left and avoid water at (1, 1) and (3, 1). There's a flower at (8, 4) that the Jeroo must pick up. The challenge is more about turning in the right direction to avoid the water and find the flower.

### Flower Maze
A mini-maze where the Jeroo starts at (7, 0) and must navigate around water blocks to reach the flower at (0, 7). This involves multiple turns and planning.

### Flower Row with Obstacles
The jeroo starts at (7,0). Pick up all the flowers along row 7, which are located every other space, while avoiding water and disabling nets. This encourages a loop to move, check for flower/net, take appropriate action, and repeat.

### Zigzag Flower Collector
Collect all flowers placed in a zigzag pattern across the grid. The Jeroo will start at (0,0) and need to move across a row, turn down, reverse direction, and repeat—perfect for using nested loops or toggling directions.

### Obstacle Garden
Start at (7,0)Collect all the flowers scattered in a semi-random pattern while avoiding water and disabling nets. The student must explore the map, possibly backtrack, and optimize their route.

## These problems center around laying flowers in a particular pattern. Maps are provide to show you what the output should look like.

### Plant Flowers in a Line
The Jeroo starts at (2, 2), and its goal is to plant flowers as it moves East.

### Plant A Pattern
Start at (0,0) and move across the map and drop flowers in a checkerboard pattern on the top-left 4x4 grid.

### Plant the Border
Start at (2,2) and drop flowers only along the outer edge of a 5×5 square (from rows 0–4, columns 0–4). The center area should be empty.

### Plant a Diagonal
Start at (0,0) and drop flowers along the main diagonal from (0, 0) to (7, 7).

### X Marks the Border
Start at (0, 0) and drop flowers along both diagonals and the border of an 8×8 grid.