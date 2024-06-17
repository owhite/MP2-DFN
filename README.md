# **MP2-DFN** 
A motor controller board based on the NVMTSC4D3N15MC with a DFN footprint. 

## Version 0.2

Thanks to badgineer for extensive review of the circuit. 

Punchlist:
+ Removed some TVSs
+ Removed one of the Vsensing circuits
+ Improved busbars for assembly
+ Heatsink for assembly
+ Updated bulk mlccs to 250v rating
+ Inverted 12v DC-DC
+ Inverted 5v DC-DC

The project hosted here absolutely would not have been possible without the intellectual work of the MP2-ESC, and the team that contributed to development of that ESC. 

## Version 0.3
Previous version works great. The only change has been to extend the VBAT connectors.


**Attribution for the MP2-DFN must always include acknowledgement of badgineer's original [MP2-ESC](https://github.com/badgineer/MP2-ESC).** 

It should also be noted that in comparison to the MP2-ESC, this ESC is larger, more expensive, and completely untested. However, it is expected to still run with the [STM32F405 pill](https://github.com/davidmolony/F405_pill), and be fully compatible with David Molony's [MESC Firmware](https://github.com/davidmolony/MESC_Firmware). 
