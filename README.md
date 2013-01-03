Instructions of compiling:

1-cd to src of the project  

2- type : "javac Game/Main.java" to compile  

3- type : "java Game.Main" to run the program.


Instructions of playing:
1- you are the white pieces
2- type in the piece you would like to move (w1, w2.. ) followed by the command
you would like the piece to execute. for example: ( w1 moveRight)
3- available commands are: moveRight, moveLeft, captureRight, captureLeft

Explanation:
The core of the program, which is the minimax algorithm, exists in the Tree class.
here is a short explanation.
1-Main : the class with the main method.
2-Board: the board of the game containing instances of Spot class.
3-Spot: the spots of in a board.
4- Move: contains the algorithms which decides wether to make a move or not.
5- Capture: contains the algorithms which decideds wether to make a capture or not.
6- MoveGenerator: populates the game minimax tree with board scenarios.
        Note: I have commented some lines in this class. If you wish to see the board scenarios, please uncomment those lines.
7- Tree: contains the minimax algorithm.



References: The minimax algorithm, along with getMove algorithm, are modified version
of Tim Hibal's Code. source: http://tim.hibal.org/blog/?p=92


