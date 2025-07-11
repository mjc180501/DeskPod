---
title: "DeskPod"
author: "Megan Campbell"
description: "An electronic spinning Podmoro timer for my desk with display powered by an Arduino Nano."
created_at: "2024-06-27"
---

Total time = 5 hours and 30 minutes

June 27: (30 min)
I made the schematic for my design. It has two battery sources, one 9V and one 5V. I have an OLED-120064D and a servo connected to three buttons (one for start, one for reset, and one for stop). Everything is wired to the arduino nano. The 9V is for the nano and the 5V is for the servo. 

I learned the difference between SPI and I2C. SPI is good for constant streams of changing data, but I2C is better for slower communication over two wires, but it is much easier to wire. 

(45 minutes)
I also started on the CAD. I got all of the different electrical components and started putting them together in one file and arranging them as I think I will on the actual design. I might use a breadboard though, as that would be much easier to design around to get the components to fit. I will have to see. 
<img width="516" alt="Screenshot 2025-06-27 at 10 43 14 PM" src="https://github.com/user-attachments/assets/b7ed06e5-4aba-49c2-8318-27db807afc1f" />
<img width="483" alt="Screenshot 2025-06-27 at 11 42 52 PM" src="https://github.com/user-attachments/assets/45baac54-bc55-40be-856b-8ff5cfd2890e" />

June 28 (2 hours)
I completed the rest of the CAD design for the bottom, the surrounding case with incriptions for the buttons, and the top piece that will spin around on the servo. 

I am researching code to figure out how I can do the servo with the nano. 
<img width="502" alt="Screenshot 2025-06-28 at 1 10 41 PM" src="https://github.com/user-attachments/assets/740a003d-0a88-4078-8386-f4ebd317f61c" />

(2 hours)

I finished writing all of the Arduino code. I had to code the OLED to blink text indicating the phase and I also had to write the code to control state switching, as well as the code to control the gradual movement of the servo, which varies according to what phase the machine is in. This took a while but since I have some familiarity with the Arduino language it wasn't a hopeless endeavor. I wrote all of the code in the Arduino IDE but I copy and pasted it into a txt format to make it easier to read. 

I didn't know that you couldn't move the servo 360 degrees, so I had to adjust it to work for 180 degrees. Also, after doing research for the code I started poking around in the OLED datasheet and figured out that I have to connect the VSS and VCOMPH and VLSS to various resistors and capacitors with external connections between these pins. 

<img width="1440" alt="Screenshot 2025-06-28 at 9 50 00 PM" src="https://github.com/user-attachments/assets/5d160cb6-9e6c-46d4-92ef-ea4273c3726f" />

<img width="603" alt="Screenshot 2025-06-28 at 9 49 00 PM" src="https://github.com/user-attachments/assets/806fd6eb-c2bf-4d97-8a91-a3074fe10910" />

I thought I finished this, but then I remembered that I have to add funcitonality for the 3 push buttons. Oops. I updated the code to account for all three of the buttons. 

July 8: (15 minutes)

I added the links on the BOM with the costs. 
