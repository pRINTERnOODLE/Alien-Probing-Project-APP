### APP Alien Probing Project

Design prompts for this mod are: 
- To provide a bed probing solution for he Tiny-M which requires no modifications to the core parts and no loss of X Y or Z axis travel.

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
- 2x M3 Roll In Tee Nut [Amazon](https://www.amazon.com/Boeray-Spring-Aluminum-Profile-20x20mm/dp/B075SY9Y96/ref=sr_1_1?dchild=1&keywords=B075SY9Y96&qid=1628637163&s=hi&sr=1-1)
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
- 10 line 
- modereate cooling

### Assembly & Physical Install Guide

- step one

Install the magnets in the "spaceship", strip some wire for connecting to the main control board, and cut ONE of the pen springs in half.

![inatall magnets](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step1.jpg)

- step two

Install your wires going from the main board to the tool head

![install wires](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step2.jpg)

- step three

Install the two cut springs into the spring holes on top of the wires and magnets (optionally solder the wires to the springs)

![install springs](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step3.jpg)

- step four

Install the 2x m3 heat set nuts on the bottom holes of the extruder fan and screw the "spaceship" assembly on the tool head and terminate your probe wires to your main board.

![install het set nuts](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step4a.jpg)

![install spaceship](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step4b.jpg)

- step five

Install the Micro switch onto the "captive" making sure the switch pin is in correct alignment with the nozzle (machine right)

![install switch](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step5.jpg)

- step six

Cut and strip two small wires which will go from the microswitch to the screw "terminals". Solder each of the wires to the switch terminals marked COM and NC. The terminal post side of the wires can be wrapped around the post screws clockwise, or the wire can go in the screw hole followed by the screw.

![install wires](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step6a.jpg)

![install more wires](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step6b.jpg)

![install all the wires](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step6c.jpg)

- step seven

Install the two remaining m4x25 pen springs

![install the main springs](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step7.jpeg)

- step eight

Install the shuttle onto the shuttle spring

![install the shuttle](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step8a.jpeg)

![really install the shuttle](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step8b.jpeg)

![there you go...installed](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step8c.jpeg)

- step nine

Thread both of the the self tapping screws all the way into the torsion spring arm and keep going untill they're stripped out and loose enough that they can wiggle a little.
Now back one of the screws almost all the way out and install the torsion spring arm onto the torsion spring one screw at a time.

![strip those screws](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step9a.jpeg)

![install install install](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step9b.jpeg)

- step ten

Assemble the "captive" into the "home planet" and make sure the locking mechanism works to retain the captive. Now, WITH THE "CAPTIVE" LOCKED IN, adjust the torsion spring arm screws until there's very little room between the "torsion spring arm" and the "home planet"...do not bottom out this adjustment or binding and failure will result.
Lock and unlock the shuttle a few times and loosen off the torsion spring arm screws as needed for proper operation.

![put it all on the machine](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step10a.jpeg)

![yes we're close now](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step10b.jpeg)

- step eleven

With the "captive" installed and locked in place loosly attach the entire "home planet" assembly to the right front upright 2020 extrusion low enough that the tool head will miss it when moved forward.

With the power to the printer off, move the tool head forward and to the right so you can line up the "home planet" as you screw it on. The best alignment is when the "captive" screws just kiss the plastic of the "spaceship" as the tool head is moved forward...this alignment should "lift" the captive slightly and lock it in place on the tool head when properly set up. Leveling the "captive" screws can help this alignment (screw them in or out relative to eachother). 

With the power still off, unlock the captive by sliding the "shuttle" to the right and slowly move the tool head in and out of the docking possition checking for smoth operation. The "captive" should not get bumped off or hang up on the way in or out...adjust as needed.

![check alignment](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step11a.jpeg)

![check agian](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step11b.jpeg)

![check and adjust till it looks good](https://github.com/pRINTERnOODLE/Alien-Probing-Project-APP/blob/main/images/step11c.jpeg)


### Firmware Setup

1. REMOVE THE "CAPTIVE" probe switch from the "home planet" and grab a pen and paper.

2. power on

3. home x y z

4. move bed down 20mm or more

5. manually command the tool head toward the front right corner (x130 y20 ish for a standard 150mm Tiny-M)

6. move the tool head write down the coordinate where the edge of the "spaceship" and the edge of the "shuttle" line up in X (mine is X150)

7. write down the coordinate where the edge of the "spaceship" and the edge of the "shuttle" line up in Y (mine is Y5)

8. now write down the same Y coordinate PLUS 12mm (mine is Y17 )

9. from the point in step 7, move the tool head ONE MM at a time in X+ (right) untill the shuttle is locked open. Write this absolute coordinate down (mine is X153 Y5).

10. move the tool head back about 4mm in X- (to the left) and place the "captive" probe switch into the "home planet" under the tool head...the probe should click in place under the tool head firmly onto the magnets (mine is X148.5 Y2). Write this coordinate down.

11. move the tool head and attached probe in -Y (forward) and write down where the probe makes contact with the "home planet" (mine is X148.5 Y1)

12. move the tool head and probe in Y+ (to the back) about 20mm (my coordinate for this is X149 Y25) observing the "captive" for smooth operation. Move it back and forth a few times. Adjust the tool head in X if needed untill you can move the probe in and out of the home planet along Y withot binding or shifting the "captive". Some fiddling with the "home planet" might be needed here to get it just right.

13. move the tool head and probe into the "home planet" (coordinate from step 10)

14. now move the tool head in -X (to the left) 10mm. This is the detachment coordinate (mine is X138.5 Y2). The probe should detach and remain home. If successful move on to step 15. If you hear a thump and or the probe flies out...move the "home planet" down very slightly until disengagement is smooth and recheck step 12. 

15. now that you can move to the detachment coordinate and smoothly detach the probe, move the tool head in Y+ (back) 10mm and write this coordinate down (mine is Y11).

16. move the tool head in X+ (to the right) to the X coordinate in step 9 (mine is X153)

17. lock the "captive" in place by moving the tool head 1mm at a time in -Y (forward) untill the shuttle clicks and locks the captive in place (mine is X153 Y7).


#### RRF Example
Now two custom macros can be written


;load.g

; called to load the APP

G90                     ;   absolute moves

G1 X150 Y17 F99999      ;   coordinate from step 6 and 8

G1 Y5 F2000             ;   coordinate from step 7


G1 X153                 ;   coordinate from step 9

G1 X148.5               ;   coordinate from step 10

G1 Y2                   ;   coordinate from step 11

G1 Y17                  ;   coordinate from step 8
 

;unload.g 

; called to unload the APP

G90                     ;   absolute moves

G1 X148.5 Y17 F99999    ;   coordinate from step 6 and 8

G1 Y1 F2000             ;   coordinate from step 11   

G1 X138.5               ;   coordinate from step 14

G1 Y11                  ;   coordinate from step 15

G1 X153                 ;   coordinate from step 16

G1 Y7                   ;   coordinate from step 17
 


