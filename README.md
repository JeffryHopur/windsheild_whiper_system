# windsheild_whiper_system

The objective of this project is to replicate the wiper system.

The wiper stalk will be replaced by the hex pad. The input commands from the Hexpad are processed through the first microcontroller and they are:
●	“1” sets the wipers to Low speed
●	“2” sets the wipers to Medium speed
●	“3” Sets the wipers to High Speed
●	“A” turns on the adaptive wiper system
●	“B” activates the DC motor that will pump the windshield washer fluid
●	“0” will turn off the wiper system

Once the first microcontroller receives the inputs such as hex pad commands and light sensor readings, it processes it and sends it to the second microcontroller to execute output commands. The stepper motor will represent a wiper on the vehicle. The DC motor represents the windshield washer fluid pump. It will turn on for a short duration of time to simulate pumping washer fluid out of the reservoir. The LCD screen will display the input commands from the hex keypad such as “Medium Speed”. RGB lights will display accordingly as per Output section above. 

Schematic
![image](https://github.com/JeffryHopur/windsheild_whiper_system/assets/96551103/8b750349-ba37-4a50-958a-ab889eb2f2bc)

User’s Guide
Hex Keypad
“1” - Turns on wipers at a slow speed
“2” - Turns on wipers at a medium speed
“3” - Turns on wipers at a fast speed
“A” - Turns on adaptive windshield wiper 
“B” is pressed - Washer fluid pump turns on briefly
“0” is pressed - Turns off windshield wiper (interrupt)
