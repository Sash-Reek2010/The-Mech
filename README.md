# The Mech
A 100% mechanical keyboard with the Raspberry Pi Pico as its brains! It features 104 Akko V3 Matcha Green keyswitches with 3D printed keycaps and Durock Smokey Screw-In stabilizers. The PCB itself is housed inside a 3D printed case which is held down by M4 screws. 
<img width="1414" height="2000" alt="main zine" src="https://github.com/user-attachments/assets/caae3f3d-815f-433f-a4f8-b690f9f74fe6 " />

## Why a keyboard?
I recently started learning Fusion and my laptop couln't run it AT ALL so I borrowed my dad's pc. That's when I first encoutered the worst keyboard of my life. I got so used to the laptop keyboard that normal detached ones feel extremely off to me. So to combat that I decided to make a mechanical keyboard! Plus I've never dealt with firmware and KMK is supposed to be really really easy and beginner friendly. And the main reason is that I'm really bad at soldering, so this should help me improve that too. (104 switches is a lot of pins to solder T-T)
<img width="1920" height="736" alt="zine 2" src="https://github.com/user-attachments/assets/baeabc7e-3b9d-43b6-a9f5-1d38fb1637ee" />

## Layout
I'm used to the numpad in my laptop so I decided to choose a 100% layout. I'd say its pretty rare to find a 100% these days!
<img width="1234" height="370" alt="keyboard-layout" src="https://github.com/user-attachments/assets/0963bf3e-3aa4-40ff-9380-37ed6b4138cd" />

# The Main 
This includes all the hardware stuff that went into the making of this project. 

## Schematic
The schematic for this project was made in KiCAD. The 26 GPIO pins were barely enough for the switch matrix but it did the job. 
<img width="1237" height="546" alt="image" src="https://github.com/user-attachments/assets/3893a15b-39af-45f4-b3e0-d43f7b7ae560" />
<img width="591" height="751" alt="image" src="https://github.com/user-attachments/assets/21e2ced6-9f36-474f-8faa-61755ffa7318" />

## The PCB
 The PCB for this project was made in KiCAD again! Most of the footprints used are from the internet but some are slightly edited to fit my project.
 <img width="1406" height="455" alt="image" src="https://github.com/user-attachments/assets/3c2e06d4-67d7-4ea5-8338-74a3b1587f88" />
 <img width="1403" height="465" alt="image" src="https://github.com/user-attachments/assets/037c4dd2-9307-408e-a58d-c2fcc093dc52" />
 <img width="1410" height="469" alt="image" src="https://github.com/user-attachments/assets/f4bce634-91fd-4c07-8a73-4e4a6cf1b64b" />
 
## PCB Render 
<img width="1463" height="687" alt="image" src="https://github.com/user-attachments/assets/de8938fa-1f36-40d3-9cdb-123ee0b89978" />

## Case
I made the case in Fusion 360! It is also split into parts which can be printed with a build volume of less than 180mm. 
<img width="1920" height="736" alt="case 1" src="https://github.com/user-attachments/assets/32b0fca5-c83a-4c04-b887-c1bdff6fba4a" />
<img width="1920" height="736" alt="case 2" src="https://github.com/user-attachments/assets/8e81d409-6e9a-4574-a154-a91c6e7b3fd7" />

## BOM
The full BOM is in the repo files as a csv. The shortened version without links and cost is as follows.
Total cost ~ 65-80 USD depending on location and cost of PCB fab.
| Component | Description | Units |
| :---------------- | :------: | ----: |
| Akko V3 Matcha Green | Keyswitches | 104 |
| Durock Smokey Screw-In Stabilizers | Stabilizers |  7 |
| Raspberry Pi Pico | Microcontroller | 1 |
| M4 Screws 45mm | Screws for mounting | 10 |
| Keeb PCB | PCB | 1 |

# Final Thoughts

## Challenges
I learnt way too much through this project. I got to know what a diode was and also switch matrices. I learnt to make my own keycaps and also how to use the Raspberry Pi Pico. But at the same time I faced a lot of trouble along the way. The most notable would be making the case for this. I spent a long time export svg files from KiCAD and using the Keyboard Layout Editor to get a sketch that I could just extrude and mae a case. But in the end I had to just manually draw the sketch for the best fit. I also had some problems with stabilizers and their mounting holes. This was one of the first things I made for this project!
<img width="617" height="324" alt="KEEB!" src="https://github.com/user-attachments/assets/0dc94d1f-4cad-4af0-8dca-fa81beb3083b" />

## Thanks for reading! Hope you have fun with the build :3 -Sashreek!
