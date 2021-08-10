### APP Alien Probing Project

Design prompts for this mod are: 
- To provide a bed probing solution of the Tiny-M which requires no modifications to the core parts and no loss of X Y or Z axis travel.

Additional design parameters include: 
- Keep the design envelope unchanged (fit inside panels etc)
- NOT affect overall design beyond adding probe functionality.
- Printed parts must not require supports

The M3x5mm hex screws used on the "captive" MUST be alloy steel and must be either flat head or cap head in order to be magnetically attracted when attaching.

Typically no brim is required for the printed parts...EXCEPT FOR THE SHUTTLE (see print settings below)

![Front Overview](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/front_overview.png)
![Rear Overview](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/rear_overview.png)
![Cross Section A](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/cross%20section%20a.png)
![Cross Section B](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/cross%20section%20b.png)
![Rear](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/rear.png)



#### BOM (US Sources)

#### Hardware	
- 2x M3 Heat Set Nut		[Amazon](https://www.amazon.com/iplusmile-Embedment-Threaded-Printing-Projects/dp/B087NBYF65/ref=sr_1_1?dchild=1&keywords=B087NBYF65&qid=1628628888&sr=8-1)
- 2x M3x6 BHCS		[Amazon](https://www.amazon.com/Button-Socket-Drive-Screws-Stainless/dp/B07QDWFFX3/ref=sr_1_1?dchild=1&keywords=B07QDWFFX3&qid=1628628840&s=industrial&sr=1-1)

- 2x m3x14 SHCS     [Amazon](https://www.amazon.com/iExcell-Stainless-Socket-Screws-Wrench/dp/B089KQV2WV/ref=sr_1_1?dchild=1&keywords=B089KQV2WV&qid=1628629199&s=industrial&sr=1-1)

- 4x m2x10 SHCS self tapping     [Amazon](https://www.amazon.com/Hexagon-Socket-Tapping-Screws-M2x10mm/dp/B00YBMROKC/ref=sr_1_1?dchild=1&keywords=B00YBMROKC&qid=1628628787&s=hi&sr=1-1)

- 3x m4x25 Pen spring   [Amazon](https://www.amazon.com/Customized-Galvanizing-Compression-Diameter4mm-Diameter25mm/dp/B08P8Z1J5S/ref=sr_1_1?dchild=1&keywords=B08P8Z1J5S&qid=1628628962&s=industrial&sr=1-1)

- 2x m3x6 Neodimium pancake magnets [Amazon](https://www.amazon.com/Round-Multi-Use-Magnets-Refrigerator-Project/dp/B07G7ZMGT5/ref=sr_1_1?dchild=1&keywords=B07G7ZMGT5&qid=1628629286&s=home-garden&sr=1-1)

- 1x OMRON D2F-01F (or similar Microswitch SPDT Subminiature) [Amazon](https://www.amazon.com/D2F-01F-Switch-Microswitch-Subminiature-Logitech/dp/B0062WNDLI/ref=sr_1_1?dchild=1&keywords=B0062WNDLI&qid=1628631471&s=electronics&sr=1-1)

### ABS Print Settings

#### If printing all at once:
- 0.2 layer height
- 5 walls 
- 5 top/bottom layers
- 40% infill (cubic)
- moderate print speed
- 0.3 Z-hop
- no supports
- 10 line brim only on shuttle

#### If printing just the shuttle:
- 0.2 layer height
- 3 walls 
- 2 top/bottom layers
- 100% infill (zigzag)
- SLOW print speed (10mm/s or less is good)
- no Z-hop
- no supports
- 10 line brim

### Assembly Guide
- step one
Install the magnets in the "spaceship", strip some wire for connecting to the board, and cut ONE of the pen springs in half.
![Front Overview](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step1.jpg)
- step two
Install your wires goinng from the board to the tool head
![Front Overview](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step2.jpg)
- step three
Install the two cut springs into the spring holes on top of the wires and magnets (optionally solder the wires to the springs)
![Front Overview](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step3.jpg)
- step four
Install the 2x m3 heat set nuts on the bottom holes of the extruder fan and screw the "spaceship" assembly on the tool head
![Front Overview](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step4a.jpg)
![Front Overview](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step4b.jpg)
- step five
Install the Micro switch onto the "captive" making sure the switch pin is in correct alignment with the nozzle (machine right)
![Front Overview](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step5.jpg)
- step six
Cut and strip two small wires which will go from the microswitch to the screw "terminals". Solder each of the wires to the switch terminals marked COM and NC. The terminal post side of the wires can be wrapped around the post screws clockwise, or the wire can go in the screw hole followed by the screw.
![Front Overview](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step6a.jpg)
![Front Overview](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step6b.jpg)