Rock Paper Scissor (which is also called Stone Paper Scissor) is a hand game and played between two people, in which each player simultaneously forms one of three shapes. The winner of the game is decided as per the below rules:

Rock vs Paper -> Paper wins.
Rock vs Scissor -> Rock wins.
Paper vs Scissor -> Scissor wins.
In this game, the user will be asked to make choice and according to the choice of user and computer and then the result will be displayed along with the choices of both computer and user.

Approach: Below is the functionality that needed to be implemented in the program:

main() function: 

It consists of the declaration of the variables.
printf() and scanf() functions for displaying the content and taking input from the user. It also contains  two predefined functions:
srand() and rand() which are used to generate random numbers in the range [0, RAND_MAX) and srand() especially will help to generate a random number at each time.
Take modulo of random number generated with 100 to make its range between (0 and 100).
As the range is up to 100 only, the distribution among all the options i.e., stone, paper, and scissors is equal as all of them have an equal probability of coming.
Note: This random number will decide the choice of computer as:

If the number is between 0-33 then the choice will be Stone.
If the number is between 33-66 then the choice will be Paper.
If the number is between 66-100 then the choice will be Scissors.
game() function: This function consists of if-else statements that will compare the choice of user and computer. If the user wins then it will return 1. Otherwise, if the computer wins then it will return 0. If it is a tie, it will return -1.# Rock-Paper-Scissors-in--C-Language
Rock Paper Scissors
