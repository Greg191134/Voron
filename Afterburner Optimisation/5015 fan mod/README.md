# 5015 Blower Fan Integration for Voron Afterburner
<img align="right" width=300 src="View overall.png" />

This directory contains files related to a mod to replace the stock 4020 blower of the afterburner by a more powerful 5015 blower. The mod uses the same fan module design as the original so you can easily switch back and forth between the 2 modules when needed. You can use it with the stock air duct. I'm working on optimizing the air duct too but this is still a work in progress

This mod was motivated by a cooling that may be a bit weak with the stock setup when you print PLA with the afterburner

The fan used for this mod is a 50x15 turbine blower from GDSTIME. Fan specs are available on [Gdstime web site](http://gdstime.com/product/?98_493.html). The model I used is the 24V 6000rpm dual ball bearing one which you can be easily find on Aliexpress ([link](https://www.aliexpress.com/item/32841967974.html)). Static head is 1.21 inH2O, maximum flowrate is 5.36CFM. Beware if you prefer to use a Sunon fan : some models do not work well with PWM and you will likely need to adjust the design to fit the fan casing.

The fan will need to be seriously trimed to fit inside the housing so do not hope to reuse it after that :
- Top cover needs to be removed (same as with stock setup)
- The fan "ears" need to be trimmed as well as the latches that attach top and bottom of the casing together
- The fan exit needs to be cut

I cut my fan with a side cutter (cut it by small pieces) and used a file where you need to cut very close to the turbine.

<img width=300 src="Blower casing cut.png" />


