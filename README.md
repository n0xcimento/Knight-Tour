# Knight's Tour
Question 7.22 from Paul Deitel and Harvey Deitel. 2017. C++ How to Program. 10th Edition.

"(Knight’s Tour) One of the more interesting puzzlers for chess buffs is the Knight’s Tour problem. The question is this: Can the chess piece called the knight move around an empty chess-board and touch each of the 64 squares once and only once? We study this intriguing problem in depth in this exercise.
The knight makes L-shaped moves (over two in one direction then over one in a perpendicular direction). Thus, from a square in the middle of an empty chessboard, the knight can make eight different moves (numbered 0 through 7) as shown in Fig. 7.25."

![Fig. 7.25 The eight possible moves of the knight.](https://i.imgur.com/mQxjT6Y.png)

* "Write a version of the Knight’s Tour program which, when encountering a tie between two or more squares, decides what square to choose by looking ahead to those squares reachable from the “tied” squares. Your program should move to the square for which the next move would arrive at a square with the lowest accessibility number."

To run the program:
    `g++ -o knight-tour knight-tour.cpp`
    `./knight-tour`