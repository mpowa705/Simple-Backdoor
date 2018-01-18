# Simple-Backdoor
CPSC 526 - Assignment 2 
Gregory Muchka 10153582
Matthew Powaschuck 30022573
Both in tutorial T04

File(s) that were written for this assignment: backdoor.c
To run the program first compile ussing the command: gcc backdoor.c 
										followed by: ./a.out [port number]

On a seperate terminal window, you can run ncat localhost [port number] to connect with the backdoor.
After connecting a password is required, if it is correct you are free to use the program, 
otherwise if the password is not correct then the session ends. Password is: valar morghulis

The current supported commands are: pwd, cd, ls, cp, mv, rm, cat, snap, diff, logout, off, who, and ps,
although, through the pipe some others may work as well but we are not actively checking input for them.
