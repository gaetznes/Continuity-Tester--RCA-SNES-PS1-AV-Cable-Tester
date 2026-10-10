# **Continuity-Tester--RCA-SNES-PS1-AV-Cable-Tester**

Simple Portable Continuity Tester for Testing RCA, SNES Style, PS1 Style AV Cables

Project design is still being tested. The current gerber files are for the board hosted here and first two images shown below. 

The goal is this can fit in a pocket, weigh less than 100grams. Regardless of where you are. At the bench, a flea market, or used store. You want to be able to verify if a AV cable works.
This version will focus on RCA Phono cables, Nintendo SNES N64 NGC and PlayStation PS1 PS2 PS3 AV Cables.
The next one will focus on Din connectors.

Instruction & Led Notes are below. 

<img width="2857" height="2335" alt="6ac6a1dffd31423c6ca3855926f00086" src="https://github.com/user-attachments/assets/3500479f-4128-42c8-b720-c1b0c7e6ae04" />
<img width="2857" height="2335" alt="ba562990975b2dfb5360fdb75c2bb611" src="https://github.com/user-attachments/assets/8d373dfe-0234-4a05-94cf-1c6adc363bc6" />

Previous version tested working, though with layout issues. Plus I used 100ohm resistors and found the green to strong.
<img width="2048" height="1536" alt="dd91cf26-2530-4b87-a052-bc48b03566e9" src="https://github.com/user-attachments/assets/63e04480-aa89-4bcb-9b5b-b3b860154a58" />

Led placement. If you install Leds at "Indicator GND Check", Use the jumper pads next to GND LED By-Pass. 
If not, solder all 3 Jumper pads next to "Indicator GND Check", and place a Led below the GND LED By-Pass.
Due to "Forward Voltage Issues", Don't Use all Green LED's, with the Diodes. To Avoid this issue and consistency, use all Red.
I'm going to play around with more resistor values. See if I can make this work the way I want it to as listed in the parts below. 
Though, currently it's not a high priority. 

# **For Nintendo and PlayStation AV Testing you will need the follow parts**

  -Avaliable from Aliexpress

1q 12mm x 12mm x 5mm Momentary Switch

13q 3mm Leds total (Use all Red, for even brightness and longer battery life)
 - 3 Red (Indvidual GND Check) 
 - 1 Orange (Composite Video) 
 - 9 Green (Everything else)  

11q 2.2k 0805 Resistors

3q rcj-021 for In-put

1q 2032 Battery Holder (BS-3) Builders Choice or Tabbed 2032 Battery

#  **Salvaged Parts**

1q ps1 slim av connector  

#  **Optional Depending on desired functionality**

  -Aliexpress

2q 1n5817 or SS12 Diodes

1q rcj-021 for Out-put 

3q m3 screws : 18mm long for mounting

3q Hex Nuts : 4-5mm long for mounting

I will upload the stl files once i've verified fitment. 

Note: Only Gerber file will be available at this time.

I hope someone finds this helpful little tester


