# CS230
 
# Project 1: Hey That's My Fish!

The goal of this project is to implement the game Hey, that’s my Fish! using the C programming language. The game will be interactive and played between a human user and an AI (artificial intelligence). The focus of this project is primarily on exercising an introductory understanding of the C programming language including basic data types, looping and conditional constructs, arrays, iteration, basic I/O, formatted output, and functions.  This semester, all projects are individual work (not done in groups), unlike the challenges and labs!

Traditionally, Hey’ that my Fish! game is a 2-4 player game in which the players first choose a color of penguins and then take turns moving one of his/her penguins in a straight line as far as he/she wishes, as long as there is a continuous line of vacant hexagons between the penguin's starting and destination hexagons. The hexagons have 1-3 points and will be collected when the player's penguin moves out from it. The objective of the game is to collect the most points in the game to win. Please see the Wikipedia entry for more details. In your implementation you will use P (for Player) and A (for AI) characters in place of the colors. In this project, you only need to implement this game for two players and each only has 1 penguin to play in this game. Please use ‘P’ as player’s penguin and ‘A’ to represent the AI’s penguin. Also, we change hexagons to octagon.

# Project 2a: Debugging wtih GDB

 in this project you will use gdb, the standard debugger for the C programming language, to change the execution flow of a program without altering the program’s source code. You will attempt to assign values in order to get past the "locked doors" in the code. 
 
 # Project 2b: Bits and Bytes
 
 This project assignment will help you understand: how to compile C programs, information representation, and bitwise operators. You should complete all the exercises below using a text editor of your choice. Make sure you follow the instructions exactly. The actual code you write is fairly short; however, the details are quite precise. Programming errors often result from slight differences that are hard to detect. So be careful and understand exactly what the exercises are asking you to do.
 
 # Project 3: Binary Bomb
 
 In this project you are provided a binary compiled for a 32-bit IA32 Linux environment. You are not provided the C source code for the compiled binary. The binary bomb consists of five phases that you must defuse - or the bomb will explode. When you run the bomb it will wait for input from the command line.

The binary bomb can be defused by providing the proper input for each of the five phases. To defuse a single phase you must type in one or more single letters or positive decimal numbers, separated by spaces, and hit enter. If the input is acceptable for that phase the bomb will not explode. If you provide incorrect input the bomb will explode and the program will exit. You may type up to 5 letters (uppercase or lowercase) or numbers on each line to defuse each phase. Here is a successful defusing of a bomb:

$ ./binary_bomb tdr
phase-1: 4
OK
phase-2: x y z d
OK
phase-3: 9 45
OK
phase-4: v
OK
phase-5: y 3
OK
Input that you provide comes after phase-n: where n is the phase number. Each of the above input lines correspond to a sequence of characters or positive integers that can be used to defuse each phase. That is, 4 corresponds to phase 1, x y z d corresponds to phase 2, etc. Your goal is to successfully provide the proper sequence of characters or numbers for each phase to defuse the bomb and save the world!
 
 # Project 4: Cache 
 
 This assignment will help you understand the impact that cache memories have on performance of your C programs. It requires you to implement several functions within the context of a program that simulates the behavior of a cache memory. The functions you need to implement focus on different areas that we have most recently studied. In particular:

Allocation and Linked Lists: You are to implement functions that require you to allocate the proper data structures to implement the cache simulator. You will also be required to manipulate a linked list. Knowledge from previous assignments will help here!

Bit Extraction: You are to implement functions that extract bits from an address to index into the cache correctly to determine if you have a hit or a miss, etc.

LRU: You are to implement the core of the least recently used algorithm to determine which cache line to evict when a particular set is full.
