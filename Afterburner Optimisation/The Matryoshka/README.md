# The Matryoshka

<img width=600 src="The Matryoshka.jpg" />

The Matryoshka is an alternate cooling solution for the Voron afterburner that uses 2 4010 blower fans (like in the pre-afterburner era). 

Main benefit over the 5015 blower fan is better cooling on the rear of the model and higher airflow

This is still a work in progress so things may change and are not optimized yet. Especially the nozzles at the outlet of the fans can certainly be optimized

**Important : the toolhead is wider that the Afterburner, it should not interfere with the ends of the X axis, however it may interfere with your idlers at the front of your bed.** 

Depending on how your printer is buit you may have an area at the front left and right of your bed that spans over couple of millemeter on X and 25 mm on Y that you can't reach. Check that you do not print there and also that you do not go there for a bed leveling routine or a prime line

## Printing and installation

<img width=1000 src="The Matryoshka - CAD views.png" />

Print with the ABS or your choice.

The fan supports are attached with two M3x10 screws each with a brass insert. One insert is on the side of the front fan cover while the other one is on the top of the cooling fan support.

Recommended fans are GDSTIME 4010 24V, 0.1 A, 11000 rpm 4.02CFM, 0.71 inH2O of static pressure. At least it is with these fans that the design was tested 

The wire for the left fan is better routed below the clockwork (so it's easier to install the fans before you put the extruder in place)

On the right side there you have a clip where you can put a zip tie

## Compatibility

The Matryoshka is available for all supported toolheads (Mosquito, E3DV6, Dragon), however it was only tested on a Mellow NF Crazy mosquito clone.

## Cooling improvements

Regarding improvement on cooling, below is a comparison (open the full size images to better see the differences).

<img width=1000 src="Comparison - Front.jpg" />

<img width=1000 src="Comparison - Rear.jpg" />

From left to right
- Stock cooling (GDSTIME 4020 24V 7500 rpm , 4.49 CFM, 0.57 in H2O)
- Long 's (Long V2.349 on Discord) duct (GDSTIME 5015 6000 rpm, 5.36 CFM, 1.21 in H2O)
- My duct (GDSTIME 5015 6000 rpm, 5.36 CFM, 1.21 in H2O integrated in afterburner)
- The Matryoshka (2x GDSTIME 4010 11000 rpm, 4.02 CFM, 0.71 in H2O)

Long's duct is available here : https://fayly.voron.dev/index.php/s/C4SyzrT3S5MazE9

The Benchies are printed with a PLA that requires a hell of cooling (Fiberlogy Fibersilk PLA). A regular PLA could produce a good Benchy with the stock cooling. The advantages of using this hard to cool PLA is that since you get a flawed Benchy you can see the improvements on cooling that are achieved
