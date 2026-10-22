# Custom-keyboard
This is my custom keyboard project. I designed it to be used both at my desk, and when travelling to hackathons. I don't have a good proper mechanical keyboard, and always wanted to build one, so that's part of the reason why I built it. It uses a custom 40% layout that I designed, with portability and ease of use in mind. it has a 4Ux12.75U size layout, with a raspberry PI pico on the side. On the side it also has a USB hub for connecting other periphirals. I built it as my project for week one of the Half Life Hack Club YSWS.

**Technical specifications**  
This keyboard is ran by a Raspberry pi pico RP2040 devboard, which is running RMK firmware. It uses a 12x4 key matrix with 2 empty spots, so 46 keys in total. It has 2 layers, with the second one being accessible with pressing the Fn key. The layouts can be modified by modifying the RMK keyboard.toml file, and recompiling it based on the official docks. For the USB hub part, it has a CH334R chip, with a USB-C port for the computer, and 3 USB ports on the side to connect stuff. The circuit is protected by a fuse, and for the CH334R it also has a 12 Mhz crystal connected to it. I built the main schematics out of what I could find in it's documentation.

**Tutorial credit**  
I built this project with the help of the keyboard tutorial from Hack Club [Keeb](https://keeb.hackclub.com/docs/pcb-design/). I used it as a base for learning how to draw keyboard matrixes, and how to set up my board to be able to properly place the switches. Aside from those, everything else like the layout, the excact wiring, design, CAD, and the firmware was designed fully by me, not copied from the tutorial. I also did  the whole USB hub part on my own of course.

**Images**  
Cad render:  
![CAD](https://github.com/jivespark/Custom-keyboard/blob/main/Images/CAD.png?raw=true)  
Schematic:  
![schematic](https://github.com/jivespark/Custom-keyboard/blob/main/Images/Schematic.png?raw=true)  
PCB:  
![PCB](https://github.com/jivespark/Custom-keyboard/blob/main/Images/PCB.png?raw=true)  
Keymap base layer:  
![keymap](https://github.com/jivespark/Custom-keyboard/blob/main/Images/base-layer.png?raw=true)  
Keymap layer 1:  
![keymap](https://github.com/jivespark/Custom-keyboard/blob/main/Images/layer-1.png?raw=true)  
