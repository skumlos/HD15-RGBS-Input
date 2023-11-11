HD15/VGA Breakout for RGBS sources

This little PCB breaks out RGBS from a HD15/VGA plug, where sync is from the HSync/CSync pin 13.
It was originally designed to fit the Barco ADVM monitors if L77HDEH15SOL2RM8 or similar is used
as the HD15 port, and two 7mm M3 standoffs are used to fasten it to the monitor chassis.

The JP1 is for being able to send sync straight through, or sync can be dealt with just like the
other signals, with a voltage divider and a DC bias capacitor.

Blanking can be from 5V from the VGA port, but it is not normally available in VGA breakout cables.
Instead SW1 can be added, and the voltage it switches can be created with VCC and a voltage divider
consisting of R20 and R21, or VCC directly by closing JP2. All this is not tested as it doesn't fit
the ADVMs, instead auto blanking can be done by other measures.

(2023) Martin Hejnfelt (martin@hejnfelt.com) 
