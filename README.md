# CS-350
Repository for the CS 350 Thermostat Project
•	Summarize the project and what problem it was solving.
The purpose of the project is to use the LaunchPad’s ambient temperature reading from its sensor and simulate a heating system through the use of the LaunchPad’s buttons and LED. 
The system’s status is then returned on the UART output, so we are able to see the ambient temperature, set point temperature, LED status, and elapsed time. 
The buttons SW2 and SW3 increase or decrease the temperature set point, and when the set point is increased above the ambient temperature, the red LED D10 will turn on. 
If the set point temperature is equal to or below the current ambient temperature, the red LED D10 will be off. 

•	What did you do particularly well?
The code is well commented and modular. I had to adjust throughout the project and that was made easier through modular code and detailed comments. 
The use of error handling also allowed to make note of issues and what actually needed to be addressed. 

•	Where could you improve?
There’s certainly room for further error handling and debugging. I felt that I would run the code, fail, reset the LaunchPad, fail, reset it again, and it would work.
I found that I needed to reset the device multiple times before changing anything in the code to ensure it wasn’t a connection issue between the device and my computer or CCS. 

•	What tools and/or resources are you adding to your support network?
With this project I was introduced to the C language and the Code Composer Studio IDE along with Texas Instruments CC3220x Launch Pad along with the appropriate documentation.
These will prove relevant tools and resources given future embedded systems projects. 

•	What skills from this project will be particularly transferable to other projects 
and/or course work?
This was the longest I have worked with the C language before and my first time you the CCS IDE. 
Managing hardware interfaces like UART2, I2C, and GPIO along with task scheduler implementation will be transferable to future projects, professional or personal. 

•	How did you make this project maintainable, readable, and adaptable?
The project meets the following standards through the use of consistent naming conventions and detailed comments within the code. 
This allowed returning to the project after passed time to be much more approachable. 
The use of modular design also allows for an easier time adding or adjusting a function. 
UART, I2C, and GPIO have their own initialization function. 
