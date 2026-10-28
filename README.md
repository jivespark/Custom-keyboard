# Custom-keyboard
This is my custom keyboard project. I designed it to be used both at my desk, and when travelling to hackathons. I don't have a good proper mechanical keyboard, and always wanted to build one, so that's part of the reason why I built it. It uses a custom 40% layout that I designed, with portability and ease of use in mind. it has a 4Ux12.75U size layout, with a raspberry PI pico on the side. On the side it also has a USB hub for connecting other periphirals. I built it as my project for week one of the Half Life Hack Club YSWS.

**Technical specifications**  
This keyboard is ran by a Raspberry pi pico RP2040 devboard, which is running RMK firmware. It uses a 12x4 key matrix with 2 empty spots, so 46 keys in total. It has 2 layers, with the second one being accessible with pressing the Fn key. The layouts can be modified by modifying the RMK keyboard.toml file, and recompiling it based on the official docks. For the USB hub part, it has a CH334R chip, with a USB-C port for the computer, and 3 USB ports on the side to connect stuff. The circuit is protected by a fuse, and for the CH334R it also has a 12 Mhz crystal connected to it. I built the main schematics out of what I could find in it's documentation.

**Tutorial credit**  
I built this project with the help of the keyboard tutorial from Hack Club [Keeb](https://keeb.hackclub.com/docs/pcb-design/). I used it as a base for learning how to draw keyboard matrixes, and how to set up my board to be able to properly place the switches. Aside from those, everything else like the layout, the excact wiring, design, CAD, and the firmware was designed fully by me, not copied from the tutorial. I also did  the whole USB hub part on my own of course.

**Images**  
Cad render:  
![CAD](https://github.com/jivespark/Custom-keyboard/blob/main/Images/CAD.png?raw=true)  
PCB:  
![PCB](https://github.com/jivespark/Custom-keyboard/blob/main/Images/PCB.png?raw=true)  
Schematic:  
![schematic](https://github.com/jivespark/Custom-keyboard/blob/main/Images/Schematic.png?raw=true)  
Keymap base layer:  
![keymap](https://github.com/jivespark/Custom-keyboard/blob/main/Images/base-layer.png?raw=true)  
Keymap layer 1:  
![keymap](https://github.com/jivespark/Custom-keyboard/blob/main/Images/layer-1.png?raw=true)  

**BOM**  
| Item                     | Qty | Supplier   | Cost/item | Total Cost | link                                                  |
|--------------------------|-----|------------|-----------|------------|-------------------------------------------------------|
| MX style switches        | 1   | Aliexpress | $13.78    | $13.78     | https://www.aliexpress.com/item/1005007438857419.html |
| Diodes                   | 1   | Aliexpress | $1.91     | $1.91      | https://www.aliexpress.com/item/4001126137167.html    |
| Stabilizers              | 2   | Aliexpress | $0.58     | $1.16      | https://www.aliexpress.com/item/1005007083130095.html |
| Raspberry pi pico        | 1   | Aliexpress | $6.55     | $6.55      | https://www.aliexpress.com/item/1005013004299224.html |
| M3x10 screws             | 1   | Aliexpress | $2.43     | $2.43      | https://www.aliexpress.com/item/4000117933430.html    |
| PCB                      | 1   | JLCPCB     | $17.00    | $17.00     | https://jlcpcb.com/quote                              |
| CH334R chip              | 1   | LCSC       | $0.50     | $0.50      | https://www.lcsc.com/product-detail/C4154405.html     |
| Fuse                     | 1   | LCSC       | $0.58     | $0.58      | https://www.lcsc.com/product-detail/C41367221.html    |
| USB-C receptacle         | 1   | LCSC       | $0.87     | $0.87      | https://www.lcsc.com/product-detail/C165948.html      |
| USB Connector            | 3   | LCSC       | $1.46     | $4.38      | https://www.lcsc.com/product-detail/C5360016.html     |
| 5.1kΩ resistors          | 1   | LCSC       | $0.19     | $0.19      | https://www.lcsc.com/product-detail/C880983.html      |
| Capacitors               | 1   | Aliexpress | $3.12     | $3.12      | https://www.aliexpress.com/item/1005007476892288.html |
| 12 Mhz crystal           | 1   | LCSC       | $0.60     | $0.60      | https://www.lcsc.com/product-detail/C7275087.html     |
| Estimated total shipping | 1   |            |           | $24.86     |                                                       |

