# Maze game
A game where you traverse a generated maze with limited vision

Generation algorithm taken from [aleksandrbazhin/mazegen](https://github.com/aleksandrbazhin/mazegen/blob/master)

### Requirements:
* gnu make
* gcc (gnu c compiler)

### Set up:
1. Clone
2. Compile with "make"

Standard is 20x20 maze but can be changed with commandline arguments

### Running:
    
    ./mazegame [size] -[special_gamemode]
      size:
        size > 2
      special_gamemode:
        idle
