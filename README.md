# ISML Project Gallery

A collection of projects I worked on at the Intelligent Sensory Microsystems Laboratory (ISML) at the University of Toronto.

- [Chip-on-board PCB](#chip-on-board-pcb)

- [Amplifier breakout board](#amplifier-breakout-board)
- [Single-ended to differential converter](#single-ended-to-differential-converter)
- [Cuff electrode layout](#cuff-electrode-layout)
- [Probe holder redesign](#probe-holder-redesign)

## Chip-on-Board PCB

I worked on a chip-on-board (COB) PCB for neural interface research. The board provides an interface between the bare die and external test hardware.

![Chip-on-board PCB design](./cob.png)

*The chip-on-board PCB design for the neural interface project.*

## Amplifier Breakout Board

I designed this board from scratch, from schematic capture through PCB layout. It uses four independently controlled 8:1 analog multiplexers to route eight AC-coupled inputs to four outputs.

### Schematic

![Amplifier Breakout Board schematic](https://github.com/user-attachments/assets/73091636-fd67-41a6-a154-9317ca348859)

*Input coupling and bias, channel selection, and output connections.*

### PCB Layout

![Amplifier Breakout Board pcb layout](https://github.com/user-attachments/assets/d950fa45-a952-47fa-bdc6-73008210b970)

*The eight input connectors flank the four multiplexers.*

## Single-Ended to Differential Converter

I completed the final portions of the PCB layout using the existing schematic. The board uses an ADA4945-based stage to convert a single-ended input into a differential output.

### Top-Level Schematic

![Single-Ended to Differential Converter top-level schematic](https://github.com/user-attachments/assets/adf37b87-54c7-49fa-a1e1-693eed67ddd0)

*Supply regulators and the output common-mode reference feed the converter stage.*

### PCB Layout

![Single-Ended to Differential Converter pcb layout](https://github.com/user-attachments/assets/b8a0eafc-e38e-4492-abdb-0fcdbf386e72)

*The layout shows the regulator blocks, converter stage, and signal connectors.*

## Cuff Electrode Layout

![Cuff Electrode Layout](https://github.com/user-attachments/assets/aec78249-76a6-4922-9699-272021bb0048)

*Layout view of the cuff electrode design.*

## Probe Holder Redesign

I designed a modified 3D-printed holder for a lab probe. The photos show the original setup, the revised design, and how it was used at the bench.

### Original setup

![Original probe setup](./OriginalProbe.jpg)

*The original probe setup before the holder was modified.*

### Modified holder

![Modified probe holder](./ModifiedProbe.jpg)

*The revised holder I designed for the probe setup.*

### In use

![Probe setup in use at the bench](./ProbeDuringUSe.jpg)

*The probe and holder in use during a lab setup.*
