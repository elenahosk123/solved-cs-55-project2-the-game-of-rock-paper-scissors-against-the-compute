Download Link: https://assignmentchef.com/product/solved-cs-55-project2-the-game-of-rock-paper-scissors-against-the-compute
<br>
Write a program that lets the user play the game of Rock, Paper, Scissors against the computer. The program should work as follows:-

<ol>

 <li>When the program begins, the user enters his or her choice of “rock”, “paper”, or “scissors” at the keyboard using a menu in a function, userChoice, that returns a character.</li>

 <li>Next, there should be a function, computerChoice, that generates the computer’s play. A random number in the range of 1 through 3 is generated. (NOTE:  You’ll have to do some research on how to create random numbers correctly.)  If the number is 1, then the computer has chosen rock. If the number is 2, then the computer has chosen paper. If the number is 3, then the computer has chosen scissors. The computer’s choice is returned as a character.</li>

 <li>After, a function, determineWinner, will determine the winner between the user’s choice vs. the computer’s choice. (NOTE: It will return nothing, but it will take in the user’s choice and the computer’s choice as the two arguments.)  The result is selected according to the following rules:

  <ul>

   <li>If one player chooses rock and the other player chooses scissors, then rock wins. (The rock smashes the scissors.)</li>

   <li>If one player chooses scissors and the other player chooses paper, then scissors wins. (Scissors cuts paper.)</li>

   <li>If one player chooses paper and the other player chooses rock, then paper wins.</li>

  </ul></li>

</ol>

(Paper wraps rock.) o If both players make the same choice, the game ends in a draw and there is no winner.

<ol start="4">

 <li>Finally, after a result is selected, there should be a function, playAgain, in which the player should have the option of playing again. This should return a boolean. Be sure that the program contains at least the four functions mentioned .</li>

</ol>