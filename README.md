SIMON SAYS

This is a simple text game in the terminal. To run the game, download the files and type make, then ./a.out. 
The rules are just like the classic game of simon says; if Simon says to do it, do it. 
The game becomes more are more difficult as it progresses, opening with the simplest questions and ending with the most difficult.

the organiztion of the code is as follows:
main.c simply runs the begingame function.
The makefile compiles main.c
simonsays.h is an include file and declares all of our functions.
simonsays.c contains all of our code.
It contains the begingame function and fucntions for questions 1-37.
begingame simply starts the game by asking the user if they want to play
each question functon asks the user to perform a task and scans the user input before deciding if the user should move to the next question or not.
the user wins if they answer all 37 questions correctly.
