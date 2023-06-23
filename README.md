# Timex-computer-2068-gray-bug
An small circuit for correction of the sinclair gray bug on timex computer 2068.

this as 3 inputs from the RGB signal another one from the bright sinal, also needs 5v from the board and ground.
very easy to solder, even if this uses very small IC's, just solder one pin in one side, then in the other with lots of flux pass with the solder iron, the bridges are removed by capilarity. then repeat in the other side, removing any bridge.

where to solder for the RGB (no need to connect the right color to the right pin... they need to be all off for this to work, so you could connect G to B or R to B not really matter),you solder at this side of this resistors...
![1](https://github.com/zambujal/Timex-computer-2068-gray-bug/assets/47646777/5a928f2d-2641-46da-8248-e5547746a16e)
Then you should disconnect this resistor here leaving the other side connected. the signal for the bright pin on the pcb will be from the A arrow (you must dissolder the resistor here, and it's the place to solder for the bright signal) then you solder the out signal to the semi removed resistor (B arrow). What you are doing here is to tap the bright signal from the SCLD, not letting this go to that resistor, before being treated by the PCB...![Screenshot_20230623-104848](https://github.com/zambujal/Timex-computer-2068-gray-bug/assets/47646777/ea09cd60-ef28-4aca-a557-63ef808e2b5e) 

the 5V and the ground you could solder here C and D.
![Screenshot_20230623-104903](https://github.com/zambujal/Timex-computer-2068-gray-bug/assets/47646777/b86ef3ad-3748-40b6-b382-10ef6b8e9763)


here the PCB:
![received_910357564050578](https://github.com/zambujal/Timex-computer-2068-gray-bug/assets/47646777/577200b4-e345-4c2c-9b83-037d1eda5594)


