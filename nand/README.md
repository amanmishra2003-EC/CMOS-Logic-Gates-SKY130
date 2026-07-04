# CMOS NAND Gate using SKY130

## Logic

Y = ~(A · B)

## Pull-Up Network

Two PMOS in parallel.

## Pull-Down Network

Two NMOS in series.

## Files

- nand.sch
- nand_schematic.png
- nand_waveform.png

## Schematic

![CMOS NAND Schematic](nand-schematic.png)
![](nand-schematic1-1.png) 
![](nand-schematic2-1.png)
## Simulation

Transient simulation performed using Ngspice with SKY130 TT corner.
![CMOS NAND Waveform](nand-waveform.png)
![](nand-waveform2-1.png)


## Result

The output waveform matches the NAND truth table.