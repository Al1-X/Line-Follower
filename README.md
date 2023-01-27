# Introduction to Robotics (2022 - 2023)


Introduction to Robotics laboratory project, taken in the 3rd year at the **Faculty of Mathematics and Computer Science**, University of Bucharest. 

<h2> 🏎️ Line follower </h2>

### 📜 Task Requirements
We assembled the line follower kit that we received from the laboratory. Also, we needed to program it and find the PID values that will help us complete the course in less than 20 seconds. Moreover, we implemented an algorithm for self-calibration, find a name for the robot and if we wanted to we could stylize it in different ways.

Our team name is the same as the line follower's name and it's **Bârlad**. This name derived from a joke made during one of our lectures. 
Our best time during the evaluation was 19.53 seconds.
For styling, we used two blinking LEDs. 

#### Components
The linefollower kit contained:
- chassis
- Arduino Uno Board
- 2 DC motors
- 2 wheels
- L293D driver
- button
- breadboard
- 2 LEDs
- resistors
- wires per logic
- 6 sensors from a QTR-8A sensor bar
- zip ties
- nuts and bolts

#### Description
This is a robot that follows a line using 6 sensors from a QTR-8A sensor bar and a PID algorithm.
It self calibrates and we save the calibration in EEPROM so we do not have to redo the calibration every single time. 
The PID algorithm processes the values from multiple ranges registered by the sensors and passes the new numbers to the motors. The final PID values were empirically found and we also used the I value for bringing some smoothiness for the line follower.

### 🖼️ Pictures of the setup
<details>
 <summary> Top View </summary>
  <img src="https://github.com/AlinaGeo/Line-Follower/blob/main/SetupImages/TopView.jpeg" width="400" height="400" />
</details>
<details>
 <summary> Front View </summary>
  <img src="https://github.com/AlinaGeo/Line-Follower/blob/main/SetupImages/FrontView.jpeg" width="400" height="400" />
</details>
<details>
 <summary> Back View </summary>
  <img src="https://github.com/AlinaGeo/Line-Follower/blob/main/SetupImages/BackView.jpeg" width="400" height="400" />
</details>

### 🎞️ Video presenting the functionality
The video can be found [here](https://youtu.be/gbQHCzN8Bp8).

### 🖥️ Code
You can also check out the code [here](https://github.com/AlinaGeo/Line-Follower/blob/main/linefollower/linefollower.ino).

### 🔗 Don't forget to check out my teammate's repo [here](https://github.com/MadalinaKopacz/LineFollower)! :3

~ Thanks for reading! ❤
