# HardwareFinal
 Alannis Davis' Game Hardware Final Repository

 # Brainstorming
- A controller with a D-pad that has lights showing what input
- A controller that vibrates if you are pressing opposite sides of the directionals at the same time. 
- A controller that allows for inputs relating to the keypresses with a light that changes colours based on the inputs applied
- A controller that makes a sound when you make an input, with light for on/off + press
- What should be the directional
- - Buttons
- - Pressure Sensors
- - Potentiometers
- How do we implement the initials?
- - Have initials engraved into the controller
- - Have initials be cut out of the controller
- - A controller that is separated into 2 similar to the Wiimote + nunchuck (but one side = one letter) with a speaker for certain noises
- How do we have a continuous input? 
- - Have a potentiometer edit the sensitivity of the button presses maybe? 
- - Have potentiometers vary the vibration?
- - Have potentiometers vary the sound level?

# Sketch 
<img width="768" alt="HardwareSketch" src="https://github.com/user-attachments/assets/3dc2e75d-e12e-4bed-a532-9e281705de13">
The thought was to make the initials engraved into the controller to avoid issues with lack of space to fit the parts.  Integrate the buttons with the design (having The holes in the A and D be where the keys are placed.  Have 4 buttons.  I did not think of the continuous input yet but I thought that potentially the peizos could go inside to make noise.  


#  Defining
After finishing brainstorming and sketching, I determined that I wanted to make a controller with 4 buttons structured horizontally.  This allows the inputs to be "select, cancel, left, right" or "up down left right" based on the needs.  I also liked the idea of it being structured differently from the conventional controller.  As a rhythm gamer, many games I play only require the 2 aforementioned input structures, interchanging the input structure based on whether you are in the game or in a menu.   
Additionally, I decided to make the piezo speaker sound when there is an input.  The intention of this is to help players have an audio cue to see how on time they are with the music, similar to how hit-sounds work in the game, but this one is in the controller.  This can also help players gauge if there is a delay between their controller input and the game input as the controller audio is triggered on button press while the game input is triggered on the registration of the game. 
**For the game I will choose to make this controller for, I decided to structure it for Friday Night Funkin', a 4-lane rhythm game with a simple 2-directional menu layout.**  Vivid Stasis is another example of a game with these definitions, but I decided to use Friday Night Funkin as it is more popular and has a simpler layout.  


# Electronics
I used Tinker Cad to show off my design. It consists of 4 buttons, a potentiometer, a peizo and a light.  These are controlled by an aurdino. 
![Screenshot 2024-12-05 145152](https://github.com/user-attachments/assets/f1d57909-c985-4ed9-933f-d6043cf34761)


# CAD 
I first translated the sketch into a more refined one in Fusion 360. 
![Screenshot 2024-12-05 130338](https://github.com/user-attachments/assets/9ffaaa46-4186-4814-8ab7-f46c001175ae)
Then I extruded the letters to be defined, creating a top/cover of the controller.  I then created another component for the body.  I used GrabCAD to get parts for the Arduino, keycaps and potentiometer, while I created the buttons out of cylinders.  The case and body holds off of these contents, with holes for the keys, potentiometer dail and power source of the arduino
![Screenshot 2024-12-05 140530](https://github.com/user-attachments/assets/3d315430-eabc-4c3c-bfc8-85f3aa319d29)



# Unity Scene
Unfortunately within the time constraints of the exam, I didn't want to attempt to make a full-on rhythm game.  But to showcase how the controller works I made a demo scene that only uses 4 inputs (these inputs are set to D, F, J, K).  I added UI elements to show how the buttons would work and inform what parts of the controller would be doing in certain parts of the game.  
