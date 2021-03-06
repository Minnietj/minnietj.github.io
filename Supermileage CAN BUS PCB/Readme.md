## Multipurpose CAN BUS PCB
In the 2018/2019 winter session, I have had the privilege of working in UBC's Supermileage team to design a multipurpose PCB to
communicate over the CAN BUS communiaction protocol.\
The purpose of this project was to the wiring complexity on their Urban vehicle and reduce the overall vehicle weight.\
The PCB was designed using the Altium software suite.\
The PCB consists of a MCP2515 CAN controller and CAN tranceiver connected to a Texas Instruments MSP 430 G2553 microcontroller.\
The microcontroller communicates with the CAN controller via SPI communications, and the CAN controller with the tranceiver via UART.\
The primary immediate purpose of this PCB is to interperet CAN BUS signals from the steering wheel to control headlights.
The microcontroller has a total of four GPIO pins attached to opto-isolators and MOSFETs. 
These MOSFETs can then be connected to the headlight circuitry to supply and remove power./
The Microcontroller was programmed using a library provided by github user Spirilis - https://github.com/spirilis/mcp2515/
This project is currently still under development, and is expected to be completed by competition day in May.
![Flowchart](https://github.com/Minnietj/minnietj.github.io/blob/master/Supermileage%20CAN%20BUS%20PCB/Supermileage%20Flowchart.PNG)
![Schematic](https://github.com/Minnietj/minnietj.github.io/blob/master/Supermileage%20CAN%20BUS%20PCB/Schematic.PNG)
