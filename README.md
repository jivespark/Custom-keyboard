<img width="709" height="236" alt="image" src="https://github.com/user-attachments/assets/2d5b569e-41c3-4b3b-a141-f1ceebd530a2" /><img width="709" height="236" alt="image" src="https://github.com/user-attachments/assets/49dbe7d4-ae02-428b-8ee1-f21148e99507" /># Custom-keyboard
This is my custom keyboard project. I designed it to be used both at my desk, and when travelling to hackathons. I don't have a good proper mechanical keyboard, and always wanted to build one, so that's part of the reason why I built it. It uses a custom 40% layout that I designed, with portability and ease of use in mind. it has a 4Ux12.75U size layout, with a raspberry PI pico on the side. I built it as my project for week one of the Half Life Hack Club YSWS.

**Technical specifications**  
This keyboard is ran by a Raspberry pi pico RP2040 devboard, which is running RMK firmware. It uses a 12x4 key matrix with 2 empty spots, so 46 keys in total. It has 2 layers, with the second one being accessible with pressing the Fn key. The layouts can be modified by modifying the RMK keyboard.toml file, and recompiling it based on the official docks.

**Assembly instructions**  
Once you have all the parts, first solder the diodes onto the PCB, based on the PCB drawing, and the silkscreen. Then solder the switches on, also based on the drawing(and the holes). Then snap the 2 stabilizers in place, and solder the pico on too. The next step is to put all the keycaps on, I'd recommend using the keymap image as reference.After that, the only thing left is to srcew on the feet. The recommended screw size for the feet is an M3x10, and for the pico cover it's M3x20. After screwing everything on you are done with the assembly! Now the only thing left is to flash the firmware onto the pico. The one you'll need to flash will be the Custom_keyboard.uf2 file, and once that's on the pico it should work correctly.

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

**BOM**
