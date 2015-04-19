CS 101 : 2014 - 2015
Team Number :	389
Team Members :	14D070026 - Vikram Bhosale (Group Leader)
			14D070025 - Ashwin Wagh
			140070005 - Aditya Jain
			140070035 - Abhimanyu

Project Title:	Speed Modulated Bot via Colour Signals

Behaviour:

1. The Bot follows white line till it encounters a junction
2. On encountering a junction it moves 9 cm to the front and analyses the flag
3. If the path is forbidden it keeps searching for alternate paths
4. Red Flags - Forbidden Path, Blue Flags - Favourable Path, Black Flag - Favourable Path With Speed Toggling

Software Required:

1.Atmel Studio 6 - to compile and create the hex file to load on the FIREBIRD. Link: http://www.atmel.com/System/BaseForm.aspx?target=tcm:26-65530
2.AVR Bootloader - to bootload the hex file on the FIREBIRD. Link: http://www.nex-robotics.com/images/downloads/M2560_FBV_14MHz_115200_UART2_PE7.zip

Installation Instructions:

1. Download AVR Bootloader. Link: http://www.nex-robotics.com/resources/avr-bootloader.html
2. Alternate download from Google Drive of E-YRC. Link: tinyurl.com/robottutorials
3. Open \source\Speed Modulated Bot.atsln in Atmel Studio and Build the code
4. Burn \source\Speed Modulated Bot\Debug\Speed Modulated Bot.hex Code into the Bot With AVR bootloader
5. Configure Black colour by holding the black flag in front of the colour sensor for approximately 1 second

Youtube Video Links:

1. https://youtu.be/X127enR_vak
2. https://youtu.be/ZYe5OLtl0pQ
 
GitHub Link

https://github.com/Adityajain97/Speed-Modulated-Bot/tree/94aa6808317f5c6a520e63f13d3b7ca640051426

Code Contribution:

1. Vikram Bhosale & Aditya Jain - White line and junction code
2. Abhimanyu & Ashwin Wagh - Colour sensor code