# **Continuity-Tester--RCA-SNES-PS1-AV-Cable-Tester**

Portable Continuity Tester w/ Protection

Mini v1.3.X

Parts, instructions, description below

<img width="1918" height="892" alt="Mini v1 3 x" src="https://github.com/user-attachments/assets/9e7004cc-74eb-4cfd-9e4c-df278eba1ac2" />
<img width="1918" height="892" alt="Mini v1 3 x1" src="https://github.com/user-attachments/assets/91ee9bc2-8cb2-4f98-ba75-e992bfd2ffc0" />

# Description

This device is intended for quick testing of PS1/2/3, Snes/N64/NGC & RCA AV Cables.

Led's are aligned in a column, with clear indicators to what each line is. Ex: Luma, GND, Componsite Video (C.Video)

Depending on your desired configuration. The GND signal can be divided into 3 sperate feeds.

Protection details are listed below, in quality of life features.

# Instructions, namely for the LED placement:

If you install Leds at "Individual.GND Check", Use the jumper pads next to GND LED By-Pass. 
Use a 2.2k Resistor next to GND. If not, solder all 3 Jumper pads next to "Individual.GND Check", 
& place a Led below the GND LED By-Pass, w/ 750r (Not a 2.2k resistor). Otherwise, for consistency use all Red, w/ 750r.

The purpose of this is to verify the GND or shield on each individual RCA cable is intact. 

# Parts
1q 12mm x 12mm x 5mm Momentary Switch

10-13q 3mm Leds total (Use only Red) 

10-11q 750r (Opt. 1q 2.2K): Type 0805 Resistors 

4q rcj-011 (3 for In-Put and 1 for Out-Put)     

1q ps1 slim av connector  

1q 2032 (BS-3) or Tabbed

*Optional Components, with reasons listed below* 

2q MAX40200AUK+T 

1q MCP-111-270, 1q .1uf Ceramic Capacitor, 1q 750r, & 1q 3mm LED

1q Si2301 & 1k to 10k : Type 0805 Resistors 

# Optional quality of life features, for safety & battery life.

They are as followed:

# 1: Low Battery Warning Circuit

Contains a MCP-111-270, .1uf Ceramic Capacitor, 750r Resistor & Modern 3mm Led

When the battery drains down to about 2.63v, the led will light, indicating you should consider replaced the battery

# 2: Back Feeding Protection 

Two MAX40200AUK+T are ideal diodes, to prevent the mistake of inserting a PS1 or Snes AV Cable into the lower Output only RCA port. 

Preventing the signal from back feeding into the device. 

These replaced the 1n5817 or SS12 Diodes, due to the desire to increase the headroom for the Low Battery Warning Circuit. As they consumed to much current. 

# 3: Revere Polarity Protection

The Si2301 and a 1k to 10K resistor are placed between the battery and the momentary switch. 

The idea here is that if a battery is installed in reverse, this will protect the MAX40200, MCP-111 from frying. 

In addition to protecting other components.


# Legacy Files, 

For Legacy reason I'm leaving the following up. 
Though everything works. I've update the design to be more robust in the above version.

Simple Portable Continuity Tester for Testing RCA, SNES Style, PS1 Style AV Cables
Mini 1.2.1 through to 1.2.9. 

1.2.9 is probably the best version, however this version is what led me to discover not all 3mm leds are really 3mm leds and can be larger that 3.2mm round. 
So 1.3.x was designed with this in mind. Plus the added protection for the chance of human error.


Project design is still being tested.

The goal is this can fit in a pocket, weigh less than 100grams. Regardless of where you are. At your bench, a flea market, or used store. You want to be able to verify if a AV cable works.

This version will focus on RCA Phono cables, Nintendo SNES N64 NGC and PlayStation PS1 PS2 PS3 AV Cables.
The next one will focus on Din connectors.

Instruction & Led Notes are below. 

# Mini v1.2.1 / 180 Degree revision

<img width="2857" height="2335" alt="6ac6a1dffd31423c6ca3855926f00086" src="https://github.com/user-attachments/assets/3500479f-4128-42c8-b720-c1b0c7e6ae04" />
<img width="2857" height="2335" alt="ba562990975b2dfb5360fdb75c2bb611" src="https://github.com/user-attachments/assets/8d373dfe-0234-4a05-94cf-1c6adc363bc6" />

# Mini v1.2.3 SMD RCA / 90 Degree revision

<img width="2857" height="2335" alt="5e588613a5493ee4d64b06399005ab2b" src="https://github.com/user-attachments/assets/a83ad5c0-18ba-4256-87c5-ca1fae6b2e57" />

<img width="2857" height="2335" alt="5797944e1af2603203c4059e3795b77b" src="https://github.com/user-attachments/assets/44ff05f1-457d-488c-a949-406165e427c3" />

# Mini v1.2.9 SMT THT Hybrid RCA / 90 Degree revision 

<img width="2857" height="2335" alt="0555b01e0eb3f33450d77647dac2be6d" src="https://github.com/user-attachments/assets/0e5467b1-7ffa-4a5b-a947-5edfbac67f80" />

<img width="2857" height="2335" alt="5a0ba4776f6eee91a193013088d7c63c" src="https://github.com/user-attachments/assets/a7c22336-3927-429f-87c5-a0c57c36f9fd" />

Previous version tested working, though with layout issues. Plus I used 100ohm resistors and found the green to strong.
<img width="2048" height="1536" alt="dd91cf26-2530-4b87-a052-bc48b03566e9" src="https://github.com/user-attachments/assets/63e04480-aa89-4bcb-9b5b-b3b860154a58" />

Led placement. If you install Leds at "Indicator GND Check", Use the jumper pads next to GND LED By-Pass. 
If not, solder all 3 Jumper pads next to "Indicator GND Check", and place a Led below the GND LED By-Pass.
Due to "Forward Voltage Issues", Don't Use all Green LED's, with the Diodes. To Avoid this issue and consistency, use all Red.
I'm going to play around with more resistor values. See if I can make this work the way I want it to as listed in the parts below. 
Though, currently it's not a high priority. 

# **Parts list for Console AV Cable Testing**

  -Avaliable from Aliexpress

1q 12mm x 12mm x 5mm Momentary Switch

11-13q 3mm Leds total (Use all Red, for even brightness and longer battery life)
Testing has lead to the descision that green is not viable to use with 3v 2032. 

11q 2.2k 0805 Resistors

3q rcj-021 / RCJ-011-SMT-TR for In-put

1q 2032 Battery Holder (BS-3) Builders Choice or Tabbed 2032 Battery

#  **Salvaged Parts**

1q ps1 slim av connector  

#  **Optional Depending on desired functionality**

  -Aliexpress

2q 1n5817 or SS12 Diodes

1q rcj-021 / rcj-011 for Out-put 

3q m3 screws : 18mm long for mounting

3q Hex Nuts : 4-5mm long for mounting

# I will upload the stl files once i've verified fitment. 

Note: Only Gerber file will be available at this time.

I hope someone finds this helpful little tester


