# Altair 8800B Display/Control PCB
This is a reproduction of the Altair 8800B Display/Control PCB, with some cleanup and reorganization of trace routing and pad placement. The 8800B’s D/C PCB, much like the original 8800’s front panel PCB, is the primary form of I/O for a stock machine: the LEDs for indicating the data/address/control signals and switches for setting the address and inputting data as well as controlling the CPU are to be found on this PCB. Unlike the original 8800, which drove the LEDs directly off the system bus, the 8800B D/C PCB buffers all signals and uses a 1702 EPROM (or just “PROM” as it would have originally been called) to pass control instructions off to the CPU.

This version of the D/C PCB is not a true 1:1 reproduction (just like the 8800B CPU and Interface cards), but strives to maintain a closely similar layout and trace routing to try to ensure that the hidden “feature” of the Altair remained present: the ability to generate EMI off the D/C board in such a fashion that music can be generated and received via an AM radio at very close proximity.

This design is presently untested and I am awaiting a set to be fabricated. Once I have tested this card in my 8800B, I will update this disclaimer to indicate as much. Until this disclaimer is updated and/or removed, this PCB is to be strictly treated as experimental only. User beware – these project and fabrication files are provided with absolutely zero guarantees.
For the accompanying CPU, Interface, and 1702-to-2716/32 adapter boards, please see the following repositories:

[Altair 8800B CPU Card](https://github.com/warmech/altair-8800b-cpu-card)
[Altair 8800B Interface Card](https://github.com/warmech/altair-8800b-interface-card)
[Altair 8800B Display/Control PCB](https://github.com/warmech/altair-8800b-display-control-pcb)

![](/images/altair-8800b-display-control-pcb-front.png)
