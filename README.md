# Hangman-Game
This Hangman Game was a final project for the ECE 243 (Computer Organization) Course at the University of Toronto. It is designed to run on the DE1-SoC board using the NIOS II Processor. You can also try it out using this online simulator (CPUlator): https://cpulator.01xz.net/?sys=nios-de1soc

# How to Run the Game
1. On CPUlator, change the language from Nios II to C. 

2. Download the Hangman.c file. Then, click File -> Open and open the Hangman.c file.

3. Under Settings, go to "Debugging Checks" and uncheck the box shown in the picture:
![image](https://github.com/user-attachments/assets/bf3425c4-90af-4b08-adfd-e9ee8ba05496)

4. Click on the "Compile and Load" button.

5. Click "Continue".

6. The game will now be displayed on "VGA pixel buffer" under "Devices". To play, scroll further down "Devices", go to "PS/2 Keyboard or Mouse", and click in the field titled "Type here: ".

7. After doing so, the program will now be able to read your keyboard's input. Read below on how to play the game!

(Note: Clicking anywhere else on the screen will cause the game not to be able to read your inputs. If this happens, click into the field again.)

# Instructions 
Press "Space" to enter the game. Players will then choose from three different themes by pressing: 

<1> for the animal theme

<2> for the food theme 

<3> for the instrument theme 

on their keyboards. Players will have 6 attempts to guess a word related to the chosen theme. If they fail to guess the word within these attempts, the correct answer will be displayed. When players reach the end screen, press "Enter" to play the game again. Have fun!
