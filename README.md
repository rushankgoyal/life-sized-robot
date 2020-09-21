# life-sized-robot
I lost the code for the Arduino-based life-sized robot I created :(

The robot can talk, move its hands, and cut a cake with a knife.

Materials Required:

  a) 2 Arduinos

  b) Life-sized cardboard cutout

  c) MicroSD card

  d) MicroSD card reader

  e) Speaker with a wire

  f) DC jack for the speaker

  g) Jumper wires

  h) 2 9g servo motors

  i) Tape & Glue

  j) Cake to cut ;)

Functions Performed:
1. Move hands -> The two 9g servo motors are connected to the main Arduino. The arms of the cutout must be cut out from the body and glued to the servo motors. You might need more powerful motors if 9g ones cannot generate enough force to lift the robot's arms

2. Talk -> The SD card stores .wav file, the SD card reader module reads the card & plays the file, and the speaker for the audio, all connected to the main Arduino (The speaker is connected through a jack to the Arduino)

3. Cut a cake -> This is kind of a trick, since the knife is not actually on the robot's hand, but instead is glued to a separate box with a separate Arduino controlling it, and it is just placed in front of the robot so as to give the illusion of cutting cake
