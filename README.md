# Pacmo
A music tample game, which is based on FPGA board.
Press the button on the Keypad of the FPGA board and earn points when you successfully press the right button when objects drop down shown on the board. Win the points.

# Functionality
In our final project, we have designed a music tempo game. The concept of the game is to press the button on the Keypad of the FPGA board and earn points when you successfully press the right button when objects drop down shown on the board. We will demonstrate and describe the details below.

Initially, when the game is programmed onto the board, there would be nothing but a line on the screen of the LCD.

The starting gameview. ![Alt text](/pic/Pacmo_start.jpg)
* The pin in the upper right corner: <br />
This is where the songs are chose and selected.(the two on the leftmost). The rightmost PIN controls to Start or not.
* The LED light in the button: <br />
LED lights up responding to the song you’ve chosen and whether the game has started or not.


When the game starts, different pictures will appear from the top of the LCD screen. There are three different pictures. One is the note of music, another one is a cute mushroom character, and the last one is the PAC-MAN. These three characters are designed to make the game more entertaining and fun. The pattern of their appearance is chosen randomly. They would each fall down from the top of the screen to the line on the below and then disappear. The player should press down the corresponding keys on the keypad in order to earn points in this game. The keys are 0,1,4,and 7. The keys that the players are required to press are relative to the situation of the characters on the LCD screen. If the character is now situated on the leftmost of the screen, then the player should press 1, in order to earn points.

The gaming snapshot. ![Alt text](/pic/Pacmo_gaming.jpg)
* The white keypad in the right: <br />
Where the players should press the key.
* The LCD display:  <br />
The player should press the key 0,1,4,7 when the characters are on the line.

The gaming snapshot. ![Alt text](/pic/Pacmo_point.jpg)
* The the 14-segment display: <br />
Display of the score the players have earned.


# Special Features
- The situations where the characters are shown are randomly picked.
- The pictures of the characters are also randomly picked. Not always the same.
- The amounts of characters that appear in every tempo of the music aren’t the same.
- Two songs for the players to pick.

The above features causes the game to be more diverse and produces excitement and unpredictability to the players and also increase the difficulty of the game, making it much more challenging than normal tempo games.

Also to prevent boredom, we provide two songs for the players to pick, so they wouldn’t get sick of the game too easily.
