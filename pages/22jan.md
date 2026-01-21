# 22 January 2026 

# Servo

Simulation done using Tinkercad, as access to IM Lab is quite limited for now. But if assembled in class, it should work. 

How the machine operates is pretty simple, I connected a servo motor to pin 11 and power, then in the Arduino, I created a loop to move 120 degrees (originally 180) with pos variable to store the rotation as a "counter". It gets incremented every loop until it reaches 120, then it gets decremented until 0, which does the loop again. 

![Servo Motor GIF](https://i.imgur.com/7FDJLzP.gif)