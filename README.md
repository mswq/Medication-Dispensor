# Medication-Dispensor
This project focuses on the development of a medication dispenser designed to reduce medication errors in hospitals and among informal caregivers. The device leverages STM32 microcontrollers and STM32CubeIDE to automate the dispensing process, ensuring that medications are administered accurately and on time. By addressing common issues such as the complexity of managing multiple medications, time pressures, and the risk of miscommunication, the dispenser helps minimize errors caused by losing or misplacing pills or administering them at the wrong time. Through precise PWM control, UART communication, and custom 3D-printed mechanical components, this device offers a reliable solution to improve medication management for both healthcare professionals and caregivers.

## Electric Design Graphic
<img src="https://github.com/user-attachments/assets/c5c711d2-d3c6-4ecf-878f-5de753af2b7b" width="400" height="500">

## Overview
<img src="https://github.com/user-attachments/assets/258735e3-cf90-4673-b73b-7fc53ff7215c" width="500" height="550">
<img src="https://github.com/user-attachments/assets/38fa8226-2f30-42b5-837f-44cf1c188df0" width="500" height="600">

## Installation Manual
# 1. Introductionn
This manual is meant for use by licensed medical professionals, technicians, and formal and informal caregivers. It details how to safely and correctly install the medication dispensing device. 

# 2. Safety Precautions
This device is only intended to be used with the included power supply (5V)  

This device must be placed on a flat, secure surface  

This device dispenses medication, keep out of reach of children, pets and other dependent individuals at risk  

Do not exceed the maximum capacity for each medicine compartment (do not allow compartments to overflow, leave at least 1cm of room between the lid and medication)  

 

# 3. Assembly 
Unpackage and place device on a flat, stable and secure surface, (for example, a table or counter) 

Ensure that the microcontroller is correctly placed below the device, and that all wires to both motors are correctly connected 

Store the device in a dry environment (note: make sure that the device is stored at a temperature most appropriate for the medication being dispensed), and place the lid securely on top of the cylindrical container  

# 4. Initial Setup and Testing  

Place the second microcontroller one meter away from the main device 

Place a minimal amount of medication in each compartment (for testing purposes)  

Turn both microcontrollers on and plug the device into its power source  

Set the desired amount of medication to be dispensed per compartment using the provided breadboard and buttons (Compartment 1, Compartment 2, Compartment 3, Compartment 4, Compartment 5, Count Button, Enter Button, Reset Button)  

Note: See user manual for more detailed instructions  

Wait to observe the medication being dispensed  

 # 4. Maintenance 

Clean the dispenser and its compartments regularly using a dry or slightly damp cloth to avoid dust buildup 

Thoroughly clean before switching medications in each compartment 

Periodically check to make sure the motor, microcontrollers and buttons continue to work properly 

 # 5. Troubleshooting 

If the dispenser servo is unable to move each compartment, or is unable to open the hatch to dispense medication, or both: 

Check to make sure its servos are fully functional (wiring is fully connected, path of servo is unobstructed, and it is correctly being powered)  

Unplug the device and attempt to reset it  

If the dispenser is not receiving input from the buttons to determine the number of pills being dispensed 

Check to make sure all buttons are securely wired and fully connected 

Attempt to reset the inputs on the device using the Reset Button  

Unplug/turn off the device and attempt to reset it  


