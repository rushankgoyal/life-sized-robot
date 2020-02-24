# life-sized-robot
Code for the Arduino life-sized robot I created. The robot can talk, move its hands, and cut a cake with a knife:

Materials Required:
a) 2 9g servo motors
b) MicroSD card
c) MicroSD card reader
d) Speaker with a wire
e) DC jack for the speaker
f) Jumper wires
g) 2 Arduinos
h) Tape & Glue
i) Cake to cut ;)

Functions Performed:
1. Move hands -> The two 9g servo motors are connected to the main Arduino
2. Talk -> The SD card stores .wav file, the SD card reader module reads the card & plays the file, and the speaker for the audio, all connected to the main Arduino (The speaker is connected through a jack to the Arduino)
3. Cut a cake -> This is kind of a trick, since the knife is not actually on the robot's hand, but instead is glued to a separate box with a separate Arduino controlling it, and it is just placed in front of the robot so as to give the illusion of cutting cake
