## Game Of Life
    Game of Life(Popular game/automation created by John CONWAY.)

## Technologies used:
      Clean MVC(Design pattern),Threads(Very intensively + CyclicBarrier for synchronization),Swing(For front end),
      Unit testing(using JUnit)


## Rules for game: 
  1)Any live cell with fewer than two live neighbours dies, as if by underpopulation.
  2)Any live cell with two or three live neighbours lives on to the next generation.  
  3)Any live cell with more than three live neighbours dies, as if by overpopulation.
  4)Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

## Fastest possible implementation of this game.

  There are Threads assigned to each cell, and all cell-threads produce next generation independently.
  Generations are produced lightning fast. // might need rechecking, maybe overusing/overheading  threads.



