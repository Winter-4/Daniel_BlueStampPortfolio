# 🤖 Gesture Controlled Robot 🤖
My project is a robot controlled by gestures from a bluetooth-connected gauntlet, that moves based on specific movements and directions, such as rotation and forward and backwards movement. One challenge I had was soldering the the pins so that some of them were connected (like the USB port) and some of them were seperate (like the pins on the LED display boards). My biggest takeaway from the project was to solder more carefully and precisely when the pins are pushed fully through, and to bend the pins to keep the pins fully pushed through.


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Daniel J. | Carlmont High School | Mechanical Engineering | Incoming Junior

<p align="center">
  <img src="headshot.JPG" alt="Headshot" height="500" style="border: 3px solid green;">
</p> 



# Final Milestone: 6/24/24

<iframe width="560" height="315" src="https://www.youtube.com/embed/4He3Q5KjJpA?si=w6uD7RK8z6YsOl8N" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="border: 3px solid #c3ff00;"></iframe>


For my third milestone, I attached the top frame to the body of the robot, added a switch to the body, fixed the power disrepencies in the wheels, and started the concept for my glove. My bigget challenge at BSE was resolving an issue regarding an inconsistency in power: by focusing on specific areas that could be problematic, I removed the possibility for error in the motor and energy by changing the battery and constantly checking the voltage. Another issue was pairng to Arduinos together via HC-05 bluetooth modules, and we fixed that by troubleshooting very rigorously. Key topics I have learned in this process include soldering, isolating issues in an engineering process, and how voltage and current function using Ohm's Law. I hope to learn how to analyze code and interpret it into hardware-based actions. 



# Second Milestone: 6/20/24


<iframe width="560" height="315" src="https://www.youtube.com/embed/jv5230nLu1c?si=5IgLsPRPFiSzR8Pm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="border: 3px solid #c3ff00;"></iframe>


For my second milestone, I implemented a bluetooth module that is paired with the main body to take inputs and translate them into motor actions. The bluetooth takes inputs from the accelerometer and gyroscope, being processed by the Arduino Nano R3 on the master module. Then, the information is transferred (via Bluetooth) into the "slave" bluetooth module in order to be processed by an Arduino UNO and then outputted by an L298 motor controller with DC motors. What has surprised me the most was comprehensibility of the input process on the hand-mounted bluetooth module, where the data is printed in the Arduino IDE module. A previous challenge I overcame was the bluetooth connection process: it was surprisingly complex and took a long time to troubleshoot through. Before completing the final milestone, I will fix the consistency of power outage within the motors, as well as fix the battery output so that I do not have to use the power of my computer to power the motors. 

# First Milestone: 6/18/24

<iframe width="560" height="315" src="https://www.youtube.com/embed/eNRlPnJSBbU?si=I9Fve0eyifgYlNAW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="border: 3px solid #c3ff00;"></iframe>


For my first milestone, I have created the main body of the machine, creating the backbone for bluetooth connection. All motors work in coordination with the code inputted into the Arduino, being transported into an L298N Motor Controller. All of this is being powered by a battery case with an On/Off switch. One challenge I ran into was providing enough power for the motors to run. As a result, I used my computer to power the motors when testing, and plan to substitute and test my battery, case, and wiring for further ease of use. 


# Schematics 
<p align="center">
  <img src="https://marobotic.com/wp-content/uploads/2024/02/Arduino-based-Hand-Gesture-Control-Robot-Circuit-Diagram-MArobotics.png" alt="Wiring configuration" style="border: 5px solid; border-image: linear-gradient(to right, yellow, green, blue) 1;">
</p>





# Code



# Bill of Materials &#40;Main Project&#41;

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino UNO | Inputs code from Arduino IDE app | $25.81 | <a href="https://www.newark.com/arduino/a000066/dev-board-atmega328-arduino-uno/dp/78T1601?COM=ref_hackster&CMP=Hackster-NA-project-94b13d-Jun-24"> Link </a> |
| Arduino Nano R3 | Transports inputs in the hand-mounted bluetooth gauntlet | $23.23 | <a href="https://www.newark.com/arduino/a000005/dev-board-atmega328-arduino-nano/dp/13T9275"> Link </a> |
| Inertial Measurement Unit (IMU) (6 deg of freedom) | What the item is used for | $5.99 | <a href="https://www.amazon.com/dp/B008BOPN40/?tag=octopart00-20"> Link </a> |
| SparkFun Dual H-Bridge motor drivers L298 | Transports actions into the motors using code from the Arduino | $9.99 | <a href="https://www.amazon.com/Stepper-Controller-Arduino-Envistia-Mall/dp/B07NKJFTGM?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1CV2ETGSPQEB3"> Link </a> |
| Solderless Breadboard Half Size | Connects the actions through bluetooth | $4.96 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| HC-05 Bluetooth Module | Provides Bluetooth connection between the car and arm gauntlet | $10.39 | <a href="https://www.amazon.com/HiLetgo-Wireless-Bluetooth-Transceiver-Arduino/dp/B071YJG8DR"> Link </a> |
| Male/Male Jumper Wires | Connects pins on the Solderless Breadboard | $2.10 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Male/Female Jumper Wires | Connects wires in chassis elements | $4.11 | <a href="https://www.newark.com/adafruit/826/wire-gauge-28awg/dp/88W2802?COM=ref_hackster&CMP=Hackster-NA-project-94b13d-Jun-24"> Link </a> | 
| DC Motor, 12V | Rotates the wheels on the robot base based on code input | $14.99 | <a href="https://www.newark.com/multicomp/287-2520/dc-motor-with-180-1-gear-reducer/dp/52Y4441?COM=ref_hackster&CMP=Hackster-NA-project-94b13d-Jun-24"> Link </a> | 
| Pimoroni Maker Essentials - Micro-motors & Grippy Wheels | Wheels for the outputs of the motors to rotate and move | $33.57 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Rocker Switch, SPST | Turns the base of the robot on and off | $4.53 | <a href="https://www.newark.com/mcm/is-ec-rs12513/switch-operation/dp/95Y1410?COM=ref_hackster&CMP=Hackster-NA-project-94b13d-Jun-24"> Link </a> |
| 9V Battery Clip | Connects the battery to the body of the robot | $0.54 | <a href="https://www.newark.com/keystone/233/battery-strap-9v-wire-lead/dp/22C4351?COM=ref_hackster&CMP=Hackster-NA-project-94b13d-Jun-24"> Link </a> |
| 9V Battery (generic) | Powers the body of the robot via the 9V battery clip | $10.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Battery Holder, 18650 x 2 | Holds batteries to substitute as a power source | $9.48 | <a href="https://www.newark.com/keystone/1048/battery-holder-18650-li-ion-2cell/dp/56T2029?COM=ref_hackster&CMP=Hackster-NA-project-e96ead-Jun-24"> Link </a> |

<!--- 
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
--->




# Other Resources/Examples
Here are some of the other resources, examples, and videos I used to create my final project.
- [How to connect “L298N Dual H-Bridge Motor Controller” to “Arduino Uno”](https://www.youtube.com/watch?v=OkHR1BZCcqA)
- [Arduino Based Gesture Controlled Robot Overview]([https://www.youtube.com/watch?v=wZurHScVyAM](https://marobotic.com/2023/12/08/arduino-based-hand-gesture-control-robot/))
- [Arduino Two Way Communication via Bluetooth](https://www.instructables.com/Arduino-Two-Way-Communication-Via-Bluetooth-HC-05/)
  

# Starter Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/gqJXe-XYi_0?si=VRvozP0RvAkL96Hh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="border: 3px solid #ffff00;"></iframe>


For my starter project, I built a handy arcade box with four directional buttons, two side buttons with additional game settings including a firing function for specific games, stop start and pause, and a toggle for music. Also, a score counter and game display are all used neatly with LED display, and a switch and battery case are used to power the arcade machine.


# Bill of Materials &#40;Starter Project&#41;
<!--- Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. -->
<a href="https://www.amazon.com/Electronic-Soldering-Practice-Comfortable-VOGURTIME/dp/B094QRRHC2/ref=sr_1_3?crid=12C0SOV36FG6M&dib=eyJ2IjoiMSJ9.Prj06eg0mzBHrfW8zuFr43Ott4t2wUOVBo8A8bYw0PqFZRlOEmgR5YwhMy7jXrdI2HlBjVttnEyYLz5CP684SzJyHmVMBp25vNna9o8wjV-df55ilTgj0xMy1CiRwkcnu6xqacZ3JUPlq8C3mQJwmEtoeokndNqpwpdkZBQMplM9vg3M-cfB0xM_nXdjeqHQ3bB707ehrzX6Llp-Euu3CTFzF8wgEqhPwo6RCvzbo5M.yyrFg8EXJr9BL5cOgZF551-8cIl91p0MSy8nGiilcpU&dib_tag=se&keywords=arcade%2Bsolder%2Bproject&qid=1717994267&sprefix=arcade%2Bsolder%2Bprojec%2Caps%2C147&sr=8-3&th=1">Amazon Calculator Link</a>

| **Part** | **Note** | **Quantity** |
|:--:|:--:|:--:|:--:|
| Solderless breadboard | Main frame for the build | x1 |
| LED display board | Displays the various games | x2 |
| 5V USB power cable | Possible external modifications to code / debugging | x1 |
| Battery Case | Powers the project | x1 |
| Functional buttons | Controls in-game direction, music, firing, etc | x7 |
| LED score board | Displays current score for each game | x1 |
| Rectangular transparent  frame | Used between the frame to hold the game | x2 |
| Side transparent frame | Pins the two rectangular frames together | x4 | 





