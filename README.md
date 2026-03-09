This program keeps asking the user to guess a number until the correct number (10) is entered. When the correct number is guessed, it congratulates the user
and stops the game.

<h1>Number Guessing Game</h1>
<p>Try to guess the number between 1 and 20!</p>
This displays the game title and instructions on the web page.

var x = 10;
The program sets 10 as the correct number that the user must guess.

while(true)
This creates an infinite loop, meaning the program keeps asking for a number until the correct number is guessed.

var num = prompt("Enter a number between 1 to 20");
A popup box appears asking the user to enter a number.

if(num == x)
If the entered number equals 10, the user guessed correctly.

alert("Congratulations! You guessed the number correctly.");
if entered number is correct then it will show above message 

or else it will show below message
alert("Wrong guess. Please Try again!");
