NAME: NIHARIKA SIDDA
Company: CODTECH
ID:CT08DS795
Domain: Embedded systems
Duration: August-September 2024
Mentor:Neela Santhosh Kumar

OVERVIEW OF THE PROJECT:

PROJECT:LED BLINKING WITH ARDUINO

Objective: 

Learn Basic Arduino Programming: Blinking an LED helps beginners understand how to write and upload simple code to control hardware using Arduino.

Understand Digital Output: The project demonstrates how to turn a digital pin on and off, which is essential for controlling other devices like motors, sensors, and displays.

Components Used:

Arduino Board,LED,Resistor (220Ω or 330Ω),Jumper Wires,Breadboard

Procedure:

Set up the Circuit:

Connect the long leg (+) of the LED to pin 13 (or any other digital pin) on the Arduino.
Connect the short leg (-) of the LED to one end of a 220Ω resistor.
Connect the other end of the resistor to the GND pin on the Arduino.

Write the Code:

Open the Arduino IDE on your computer.
Now write the following code:
/LED BLINKING WITH ARDUINO/
// C++ code
//
void setup()
{
  pinMode(8, OUTPUT);
}

void loop()
{
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}

Connect your Arduino to your computer using a USB cable.
Select the correct board and port in the Arduino IDE.
Click the Upload button to transfer the code to the Arduino.
Once uploaded, the LED connected to pin 8 should start blinking on and off every second.

![Screenshot 2024-09-29 104703](https://github.com/user-attachments/assets/7656bba3-aafd-4e46-9d2f-f5cecc224a61)


Key Activities:

Writing and Uploading Code: Create a simple Arduino program (sketch) that uses the digitalWrite() function to turn an LED on and off at set intervals, then upload it to the Arduino board.

Connecting the Circuit: Connect an LED and a resistor to the appropriate pins on the Arduino (typically using a breadboard) to complete the circuit for the LED to blink.

Technologies Used:

Arduino Microcontroller: The Arduino board, a microcontroller platform, processes the code and controls the LED's blinking by sending digital signals.

Embedded C/C++ Programming: The code is written in Arduino's programming language, based on C/C++, to instruct the microcontroller on how to interact with the LED.

Key Insights:

Digital Control Fundamentals: Blinking an LED demonstrates how microcontrollers like Arduino can control hardware through digital outputs, a basic concept for interacting with sensors, actuators, and more.

Timing and Delays: The project highlights the importance of timing in embedded systems, using functions like delay() to control the frequency of actions, which is essential for real-world applications.


