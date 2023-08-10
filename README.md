# Google Pixel Tablet


## Wall Mount

![](pictures/version1.png)


### Parts
7x M3x12mm countersunk. \
7x M3 nuts (<3mm thick). \
16x 12x5x3 cube magnets. \
3x M4 countersunk self-drilling screw.



## Base stand
### Disassembly

1) Rubber feet (E12) is held on with double sided adhesive. A gentle pull releases it.

![](pictures/dissasembly/20230729_000832.jpg)


2) Metal bracket (EW M2-1) is fastened with five Torx T7H screws (color coded magenta).

![](pictures/dissasembly/20230729_000819.jpg)

3) To EW M2-1 is main PCB attached. I assume this is the speaker driver. The 5-pin connector is for the speaker units. The smaller flex cable connects to the daughter PCB that mates with the tablet when it is docked.

![](pictures/dissasembly/20230729_001121.jpg)


4) Four Torx T6H screws (color coded green) fastens the magnetic face plate (TL-A2). The two in the front are easy to reach, however the two in the back are rather hard to reach. It requires a at least 70mm long screw driver (max 7mm) to reach them. The magnets are quite close and they will easily catch the screws at the bottom.

![](pictures/dissasembly/20230729_001110.jpg)


5) Face plate (TL-A2) lifts up.

![](pictures/dissasembly/20230729_005831.jpg)


6) The three main pieces.

![](pictures/dissasembly/20230729_005930.jpg)


### Magnet placements

The back has a total of eight magnet-pairs glued in place. Each pair has a thin metal backplate. I assume this is something that improves the magnetization.

![](pictures/dissasembly/20230729_011425.jpg)

![](pictures/dissasembly/20230729_011338.jpg)

A scan of the plate and a draw up in Freecad gives the exact locations of the magnets relative to the quick-disconnect port.

![](pictures/magnet-placements.png)




## Quick-disconnect connector

Disassembly and probing the connections reveals that the base stand forwards 12VDC to the tablet on the two outer most connector pads. The tablet will charge just fine if provided with 12VDC only.

![](pictures/data-signals/20230730_022716.jpg)

The connector pair in the middle carry data signals. The protocol is still undetermined but it however seem like some sort of differential signalling.

![](pictures/data-signals/20230729_030050.jpg)

