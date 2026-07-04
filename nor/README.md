# CMOS NOR Gate using SKY130

## Logic

Y = ~(A + B)

## Pull-Up Network

Two PMOS in series.

## Pull-Down Network

Two NMOS in parallel.

## Files

- nor.sch
- nor_schematic.png
- nor_waveform.png

## Schematic

![CMOS NOR Schematic](nor-schematic.png)

![](nor-schematic1-1.png) 
![](nor-schematic2-1.png)

## Simulation

Transient simulation performed using Ngspice with SKY130 TT corner.
![CMOS NOR Waveform](nor-waveform.png)


## Result

The output waveform matches the NOR truth table.