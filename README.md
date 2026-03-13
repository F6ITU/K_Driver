# K_Driver
Ajax Telamon, 10 to 33 dBm driver to feed LDMOS RF amplifier

![Le driver](https://github.com/F6ITU/K_Relay_Board/blob/main/switch_ant.jpg)


Ajax is a cascade of four OPA2674 op-amps, designed to amplify the signal from a DAC by around 30 dB (between 0 and 10 dBm of power, or 1 to 10 mW). The comfort zone of this amplifier is around half a watt to one watt of power.

The origin of the diagram is lost in the mists of time.

It can be found in the archives of the OpenHPSDR Penelope and Pennylane project, a 1/2 watt exciter (https://openhpsdr.org/wiki/index.php?title=PENELOPE) (following a AD9744ARU DAC).

It is also used in the 14HAM-DK2, an impressive project by F4JGL.  (https://sites.google.com/view/projet-14ham-dk2/les-%C3%A9l%C3%A9ments-du-projet/modules-ampli-hf-%C3%A9mission/module-driver). 

It is used to directly attack a push-pull made of MRF101AN/BN , in other words Kjell LA2NI's OpenHPSDR "MUNIN 100" amplifier (https://github.com/F6ITU/K_Munin100_Fork)

This umpteenth version has no other ambition than to provide exactly the same "service," but in a smaller size, with the PCB measuring only 6.5 x 2.5 cm.

The shielding of the assembly is left to the discretion of each user. 



