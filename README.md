 # Timex-computer-2068-gray-bug
An small circuit for correction of the sinclair gray bug on timex computer 2068.

this as 3 inputs from the RGB signal another one from the bright sinal, also needs 5v from the board and ground.
very easy to solder, even if this uses very small IC's, just solder one pin in one side, then in the other with lots of flux pass with the solder iron, the bridges are removed by capilarity. then repeat in the other side, removing any bridge.

where to solder for the RGB (no need to connect the right color to the right pin... they need to be all off for this to work, so you could connect G to B or R to B not really matter),you solder at this side of this resistors...
![1](https://github.com/zambujal/Timex-computer-2068-gray-bug/assets/47646777/d8f5c338-bfe9-40ed-81af-51a2ab73dcb7)

Then you should disconnect this resistor here leaving the other side connected. the signal for the bright pin on the pcb will be from the A arrow (you must dissolder the resistor here, and it's the place to solder for the bright signal) then you solder the out signal to the semi removed resistor (B arrow). What you are doing here is to tap the bright signal from the SCLD, not letting this go to that resistor, before being treated by the PCB...
![AB](https://github.com/zambujal/Timex-computer-2068-gray-bug/assets/47646777/8ccb2efb-a2db-4385-b999-15ca86c303af)

the 5V and the ground you could solder here C and D.
![cd](https://github.com/zambujal/Timex-computer-2068-gray-bug/assets/47646777/991ec666-abf3-4ac6-87b3-16dabfdadcb3)

here the PCB:
![received_910357564050578](https://github.com/zambujal/Timex-computer-2068-gray-bug/assets/47646777/577200b4-e345-4c2c-9b83-037d1eda5594)

here the gerber files for the pcb:
[timex2068 bug.zip](https://github.com/zambujal/Timex-computer-2068-gray-bug/files/11846993/timex2068.bug.zip)

P.S. the bright signal to the edge connector, is still untreated... if you want this treated for say an rgb out card or something, you must disconnect this signal to the edge connector and connecting the "treated" signal.

An video (in portuguese)
https://www.youtube.com/watch?v=giwbNEnFmkI

gerber file to make the pcb and an BOM file for the IC's needed in the files section

António Vitor 23/06/2023

Warranty
No Warranty of the Project. The Issuer makes no express or implied warranty of any kind whatsoever with respect to the Project.

License
GNU General Public License v3.0 T&C applies to this repository content.
