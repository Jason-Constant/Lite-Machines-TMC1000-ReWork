# Lite-Machines-TMC1000-ReWork
This project is designed as a step by step process to work around the proprietary hardware and software that has been out of date for years, on the Lite Machines TMC1000 CNC
machine. This project will allow you to build an updated the controller module for the CNC machine with modern hardware (Raspberry Pi / Planet CNC Controller) and modern software
(PlanetCNC).

This project was created by the teachers and students at Nashua High School South in the Manufacturing class. The problem came apparent that there were many CNC machines not being
used, or non functional around the classroom. The students decided to tackle the problem and get the machines running and useful for the next years classes. The following is 
work
done from the students and teachers and has been documented as open-source instructions to try and help anyone with building the TMC1000 CNC machine, as well as many like it.

All of the parts used in the project can be found with the parts list excel file, or with google sheets at:
https://docs.google.com/spreadsheets/d/1oB2_8kQT0YI9Jluc7MAbP1K0-m6zmKGLGUpFqq22EpM/edit?usp=sharing
Some of the optional parts in the list include parts that were reused from the old components, but knowing that some may not want to take apart the old machines, the parts we 
reused are included in the list.

Step 1: This project was designed to be run off of a RaspberryPi 4 Model B (8GB), as well as the free operating system Raspbian. To download Raspbian follow RaspberryPi's 
official download tutorial at: https://www.raspberrypi.org/documentation/installation/installing-images/

Step 2: If you choose the optional TouchScreen Display, connect the display to the RaspberryPi. Else connect the RPI to a touchscreen display, or any display as well as a 
keyboard and mouse.

Steps 1 and 2 can be bypassed if you decide to use a desktop computer to run Plant CNC.

Step 3: After setting up the RPI (RaspberryPI) with raspbian access the internet and download and start up the Planet CNC software at: https://planet-cnc.com/software/ or by 
searching "Planet CNC Software"

Step 4: Connect the Planet CNC MK3/4 controller Via usb

Step 5: Purchase and activate the Planet CNC License in order to use and controller with the hardware.

Step 6: Now that we have the software setup and activated, we will start working on the hardware and wiring things to work. Using the "Hardware Manuals" folder 
set your subdivision and current settings on the stepper driver, based off of the stepper motors you are using.

Step 7: Using the wiring diagrams in the "Wiring Diagrams" folder we can now wire the board to the stepper motor drivers (more information on the drivers can be found in the 
"Hardware Manuals" folder used in the previous step).

Step 8: Using the wiring diagrams previously used, as well as the "DB15 DB9 Wiring" folder, wire the stepper motor drivers to the DB connectors. This will allow for the box to 
be "plug and play" to the CNC machine.

Step 9: Now that the stepper motors are wired up, we can work on the spindle. Fortunately the spindle wires directly from the board to the three connector "wall outlet" style 
plug.

Step 10: Wow that everything is wired up, double check that the wiring is correct, then wire the power to the MK3/4 and using the Planet CNC Software so we can start controlling 
the CNC Machine.

Step 11: Copy over the settings in the "Software Settings" folder to the Planet CNC Software and test to make sure the machine runs. There will be an STL file provided in order 
for you to calibrate your machine.

Step 12: To calibrate your machine use the instructions given by Planet CNC at: https://planet-cnc.com/how-to-setup-cnc/

CREDITS

Contributors:
        Teacher - John Finocchiaro
        Student - Jason Constant
        Student - Benjamin Currier
        
Software/Hardware Companies:
        Planet CNC - https://planet-cnc.com/
        Raspberry Pi - https://www.raspberrypi.org/
