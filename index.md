# 🤖 Gesture Controlled Robot 🤖
My project is a robot controlled by gestures from a bluetooth-connected gauntlet, that moves based on specific movements and directions, such as rotation and forward and backwards movement. One challenge I had was soldering the the pins so that some of them were connected (like the USB port) and some of them were seperate (like the pins on the LED display boards). My biggest takeaway from the project was to solder more carefully and precisely when the pins are pushed fully through, and to bend the pins to keep the pins fully pushed through.


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Daniel J. | Carlmont High School | Mechanical Engineering | Incoming Junior

<!---**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone --->

# First Milestone 🦿

<iframe width="560" height="315" src="https://www.youtube.com/embed/eNRlPnJSBbU?si=I9Fve0eyifgYlNAW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my first milestone, I have created the main body of the machine, creating the backbone for bluetooth connection. All motors work in coordination with the code inputted into the Arduino, being transported into an L298N Motor Controller. All of this is being powered by a battery case with an On/Off switch. One challenge I ran into was providing enough power for the motors to run. As a result, I used my computer to power the motors when testing, and plan to substitute and test my battery, case, and wiring for further ease of use. 

<!---
# Bill of Materials &#40;Main Project&#41;

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino UNO | Inputs code from Arduino IDE app | $25.81 | <a href="https://www.newark.com/arduino/a000066/dev-board-atmega328-arduino-uno/dp/78T1601?COM=ref_hackster&CMP=Hackster-NA-project-94b13d-Jun-24"> Link </a> |
| Arduino Nano R3 | Transports inputs in the hand-mounted bluetooth gauntlet | $23.23 | <a href="https://www.newark.com/arduino/a000005/dev-board-atmega328-arduino-nano/dp/13T9275"> Link </a> |
| Inertial Measurement Unit (IMU) (6 deg of freedom)
 | What the item is used for | $5.99 | <a href="https://www.amazon.com/dp/B008BOPN40/?tag=octopart00-20"> Link </a> |
| SparkFun Dual H-Bridge motor drivers L298 | Transports actions into the motors using code from the Arduino | $9.99 | <a href="https://www.amazon.com/BOJACK-H-Bridge-Controller-Intelligent-Mega2560/dp/B0C5JCF5RS/ref=sr_1_3?crid=3VGUNHF3A1PXX&dib=eyJ2IjoiMSJ9.Uhkp4V4YuMhSQCL0zp7DORZTnVDlTZ_jCoPCZv_PKdrIzY2gw3yF4NPgx-YMXvSPhbT6gfN7i1dEACtqBngQlqzHByRTtDJmhXIVV7SxnENw7GO-GjMoy3nFx04Mt011TtpEXyzXag0sXJH_3p3jeMU2GWRwmXZoNCzrld6p-rB0pnJpQIDvEcgWD81larQPPpcmARbK7EHFQhRZCHvTCN9ZN9wPqJ9K6FSXale2ykM.K4orzSvxNWtp3LtM1ai6V9j0h_jb7ytcMbsZw7oN0os&dib_tag=se&keywords=SparkFun+Dual+H-Bridge+motor+drivers+L298&qid=1718755008&sprefix=sparkfun+dual+h-bridge+motor+drivers+l298%2Caps%2C210&sr=8-3"> Link </a> |
| Solderless Breadboard Half Size | Connects the actions through bluetooth | $4.96 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> | --->

<!---
# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->

# Other Resources/Examples
Here are some of the other resources, examples, and videos I used to create my final project.
- [How to connect “L298N Dual H-Bridge Motor Controller” to “Arduino Uno”](https://www.youtube.com/watch?v=OkHR1BZCcqA)
- [Arduino Based Gesture Controlled Robot Overview]([https://www.youtube.com/watch?v=wZurHScVyAM](https://marobotic.com/2023/12/08/arduino-based-hand-gesture-control-robot/))
  

# Starter Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/gqJXe-XYi_0?si=VRvozP0RvAkL96Hh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

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





