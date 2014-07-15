# Parallella Cluster Kit

![Four Parallella boards fitted in a PACK-01 case](/images/Completed.jpg)

[PACK-01](http://gndel.ec/PACK-01) is a kit for assembling a cluster of 2 to 4 [Parallella](http://www.parallella.org/) boards and provides:

* Acrylic enclosure with cut-outs for Ethernet, Micro SD, Micro USB and Micro HDMI
* Metal hex spacers for stacking and supplying power to the boards
* Heatsinks for the Epiphany chips
* 80mm 5VDC fan
* Acrylic enclosure
* DC power switch
* High quality 5V 8A mains power supply

Cluster communication interconnect is not provided and it is assumed that Ethernet will be used. Note that neither the Parallella boards nor an Ethernet switch and cables are included.

The PACK-01 kit can be bought from [Ground Electronics](http://groundelectronics.com).

## Repository contents

The case design for PACK-01 is provided in the following formats:

* Adobe Illustrator (source)
* SVG
* PDF
* DXF

It is laser cut from 3mm clear acrylic.

## Bill of materials

In addition to the acrylic parts the PACK-01 kit contains:

| Qty | Item                                   |
| --- | -------------------------------------- |
|  1  | 80x10mm 5VDC fan                       |
|  1  | Pre-crimped/soldered cable assembly    |
|  1  | 20mm 10A rocker switch                 |
|  1  | 3-pin XLR panel male plug              |
|  4  | Hex spacer nickel plated M-F M3x30mm   |
|  12 | Hex spacer nickel plated M-F M3x15mm   |
|  4  | Hex spacer nickel plated F-F M3x20mm   |
|  8  | Cheesehead slotted nylon screw M3x8mm  |
|  2  | Countersunk pozi machine screw M3x10mm |
|  2  | Nyloc nut steel M3                     |
|  28 | Washer steel M3                        |
|  4  | Self-tapping case fan screws M5x12mm   |
|  1  | 5V 8A desktop mains adaptor            |
|  4  | 15x15x8mm heatsink                     |
|  4  | Clear 10mm diameter rubber bumper      |

## Powering boards

J15 must be fitted in order for the Parallella boards to be powered via the metal spacers and their mounting hole pads.

If the jumper is not already fitted, first locate J15.

![J15 open](/images/ParallellaJ15.jpg) 

1. Cut a ~6mm or so piece of solid core hook-up wire and bend this into a U shape, with the two ends around 3mm apart. 

2. Insert this into J15, but note that it may not drop all the way in as there is a Samtec connector directly under one of the pads.

3. Solder the link in place from the top side of the board.

![J15 fitted](/images/ParallellaJ15Fitted.jpg)

## Assembly

1. Remove the protective plastic from the acrylic panels.

2. Lay out the parts.

   ![Parts laid out](/images/LaidOut.jpg)

3. Affix rubber bumpers to the base panel.

   ![Bumpers attached](/images/BumpersAttached.jpg) 

Note that these go on the side opposite from the one which is etched.

4. Fix the switch into the front panel.

   ![Switch fitted](/images/SwitchFitted.jpg)

The front panel has four rectangular slots and a circular cut-out at the bottom. The switch and cut-out are keyed and when looking at the rear of the panel this should be to the left-hand side, with the gold terminal on the rocker switch at the bottom.

5. Fit the XLR plug to the rear panel.

   ![XLR plug fitted](/images/XLRFitted.jpg)

The XLR panel mounted plug should be fitted to the rear panel as shown above, with the long rectangular slot above to the left-hand side, and secured in place with 2x countersunk M3 steel machine screws and 2x nyloc steel nuts.

6. Attach the fan to the right-hand side panel.

   ![Fan attached](/images/FanFitted.jpg) 

Put the panel with the Parallella logo with the etched side facing up, so that the logo is reversed. Place the fan on top with its label facing upwards and wires pointing down. Secure the fan by inserting the M5x12mm screws from the underside.

7. Attach the four 30mm hex spacers to the base panel.

   ![30mm hex spacers fitted](/images/30mmSpacers.jpg)

The four 30mm hex spacers (longest) are secured to the base panel by four M3x8mm nylon screws inserted from the underside. The studs on the spacers should be pointing upwards.

8. Add the first Parallella board.

   ![First board in place](/images/FirstParallella.jpg)

Note the orientation, with the Ethernet jack above the larger rectangle etched onto the base plate, and the Micro SD socket positioned above the smaller rectangle.

9. Connect the power wires.`

   ![Connecting the power wires](/images/XLRBlackRing.jpg)

Bring the rear panel towards the Ethernet jack and route the black wire from the XLR under the board, and then place the crimp ring on the stud nearest TP12. 

Take the crimp ring attached to a red wire and with a female spade connector on the other end — which may already be attached to the switch — and place it on the stud next to the DC barrel connector. 

Take great care and note that if the power connections are reversed permanent damage is likely to occur when power is applied!

Place a single M3 steel washer on each of the two studs opposite.

10. Add four 15mm hex spacers.

   ![Add first set of 15mm spacers](/images/First15mmSpacers.jpg)

Add four 15mm M-F hex spacers and nip tight with a small spanner, but take care not to overtighten.

11. Add second Parallella board.

   ![Add second Parallella board](/images/SecondBoard.jpg)

12. Connect fan wires.

   ![Connect fan wires](/images/ConnectFan.jpg)

Place the right-hand panel and fan assembly to the right of the stack, with the fan label pointing inwards and as shown above. Route the wires from the fan under the bottom board and out of the other side.

Locate the fan crimp rings on the studs, above the power wires, again with red adjacent to the DC barrel connector and black on the stud nearest TP12.

Once again add an M3 steel washer to each of the two studs opposite.

13. Add second set of four 15mm hex spacers.

   ![Add second set of 15mm spacers](/images/Second15mmSpacers.jpg)

14. Add the third Parallella board.

   ![Add the third Parallella](/images/ThirdParallella.jpg)

At this point if you do not have a third board, you must add three M3 steel washers to each stud, so as to maintain the correct height of the stack.

15. Add the fourth board.

   ![Add the fourth board](/images/FourthParallella.jpg)

Again, add three M3 steel washers to each stud if not adding another board.

16. Add the 20mm hex spacers.

   ![Add the 20mm spacers](/images/20mmSpacers.jpg)

17. Connect the switch.

   ![Connect the switch](/images/ConnectSwitch.jpg)

It does not matter which of the red wires is connected to which terminal, as long as it is the two silver coloured terminals (do not connect to the gold coloured one).

Note that the spade connectors may be quite a tight fit.

18. Locate the four side panels in the base plate.

   ![Fit the side panels](/images/FitSidePanels.jpg)

Note that it may be necessary to manoeuvre wires into place before the side panels will locate.

19. Add top plate.

   ![Add the top plate](/images/AddTopPlate.jpg)

Note that the top plate is polarised and will only fit one way round.

20. Secure top plate with four M3x8mm nylon screws.

   ![Secure the top plate](/images/SecureTopPlate.jpg)


## Licence

Parallella Cluster Case is copyright 2014 [AB Open Ltd](http://abopen.com).

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

