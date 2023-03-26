# Home-Secturity-System-
A Device That Sends Notifications and Photos to the User via Telegram When It Detects Fire, Gas Leakage or Motion inside the House

notes:
1) this project is basically a copy of this project
i advice you to check out this page if you want to build this project https://www.hackster.io/make2explore/home-security-system-using-esp32-cam-and-telegram-app-dce4f8
2) i have ignored the door sensors and the flash light because i wanted everything to fit inside a box properly 
3) reach out to @make2explore on telegram if you have any questions about the project 
4) it is importatnt to add line 160 and 165 in my code if you have the problem of pictures being sent out of sequence 

tips:
1) i used 1M ohm resistors instead of level shifter in the circuit to drop down the voltage from 5v to 3v (its simpler and cheaper) 
2) if the fire sensor keeps on sending alerts then consider using a NOT gate 
3) i used 2 Li-ion batteries (3.7V 2000mA) connected on series and a (8.4V 2S 7.4V Lithium Battery Protection 5A BMS Protection Board) and (9v EU Plug Adapter) to power up the entire project however you can power up the project by the FTDI you are using to code the esp32 cam
4) talk to your electronics professor if things seem confusing 
