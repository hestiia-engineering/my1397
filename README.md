# my1397
Dev board for BM1397 chips (only !) from Bitmain 

THIS BOARD IS DESIGNED FOR FOLKS THAT HAVE AN EXTENSIVE KNOWLEDGE OF ELECTRONICS, BITCOIN HASHBOARDS AND BM1397 CHIPS. THESE BOARDS HAVE CURRENTLY NO OVERVOLTAGE OR OVERCURRENT PROTECTION, USE IT AT YOUR OWN RISK !!!

---

## Features

- Plug and play hashing with BM1397 chip with no soldering or TIM management thanks to custom socket (IYKYK)
- One "Master" board support chaining of multiple "slave" boards, accepting parrallel and series chaining (look for characteristics for details)
- Interface with UART and NRST line (see pin diagram), no controller on board ! (see basic instructions below for fast setup using external controller, modified CGminer and FTDI cable)


## Characteristics

- 80% to 90% Hashing efficiency until 400Mhz with the current thermal management solution. Hashing efficiency can drop abruptly going higher frequencies.
- Chaining of boards has been tested with success on 2pN configurations (Pairs of N series of chips)

---

## Pin Diagram
TBD

## Electrical specs
TBD

## Basic instructions
First you need to prepare the "Master" board.

## Roadmap
(informative, could be done next week or never ....)
- Die temp sensor acquisition (TEMP_N and TEMP_P) communicating in I2C.


## More on Hestiia-engineering

We're dreaming about a new way to heat our homes, going grom scratch to reinvent products and make them robust, innovative, aesthetic and eco-friendly.  


## Devs

Coumba Ndiaye for the PCB design.
Thomas Chainiau for the thermal related mechanical parts.

## Disclaimer

This design is is proposed to the community AS IS, WITH NO GUARENTEE OF ANY SORT

