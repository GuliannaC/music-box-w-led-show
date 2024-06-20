Break down of code:
I began by creating all my variables 
Each note had to be defined I also added a library that had different tones and pitches in it 
Then I created a variable for each melody array and tempo
Each song had its own set note pattern
Following the note pattern was the tempo that needed to be played for the song to sound correct 
After each song and tempo was set up I had to create a variable for the size of the song
Next I added the IRremote library inorder to use the remote to work with the arduino board
After I set up all the inputs that would be working with the remote 
I created a pin for the remote, the red LED, blue LED, green LED, and the buzzer
Next I set up everything for the interrupt 
I used the #define to define all my inputs for the other LEDs and button that caused the interpret 
Next I created my void setup 
I started by making outputs for everything that would go with the remote
I made the red, blue, and green LEDs all outputs
I also made the buzzer and output
Then I made outputs for everything that was going to happen in the interrupt 
I made each LED in the interrupt an output 
I made the button a input pullup 
Next I created a void called blink1 for the interrupt to run
This helped create the button to become the interrupt 
Next I set up my void loop
I started by created everything for the interrupt
I made it so that the LEDs will run in a chain then if the button is pressed all the LEDs will turn on
Next I created everything for the buttons on the remote
Each button on the remote had to be created with a switch and case
After creating the switch and case I was able to input my song 
I made the song play and to turn off after all the notes are done
I also added some LEDs to turn on and off when a specific song was played 
A switch and case had to be made for each different button which contained a different song in each that turned on different LEDs
