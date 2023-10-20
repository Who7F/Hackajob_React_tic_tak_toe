Hackajob Pathways. Make a tic tac toe in react.
Taking a 'Don't reinvent the wheel' approach. Also I know how to make a tic tak toe game.

1. Find a tic tak toe that I like the look of.
2. Run the game and see what fails.
3. 1st Fail one, no class called 'square'
4. Add className = 'square' to the button in the Square funtion.
5. Run the game.
6. 2nd test passed.
7. 3rd Fail. No reset class
8. Make a new funtion called Reset that take a event handler from game
9. Make an event handler that:- setCurrentMove(0)
10. Add <Reset value = 'Reset' onResetClick={onResetClick} /> to the render of Game
11. Run the game.
12. 4th fail. No Draw text
13. Find the borad status, in Board
14. Add else if with a lambda function to check element are !NULL
15. Clean up
