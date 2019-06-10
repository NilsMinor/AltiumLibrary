# AltiumLibrary

AltiumLibrary
├── 3D # 3D Step files used to provide 3D models for pcb footptints
├── db # contains the database libary AltiumDB for resistors and capacitors
├── pcb # contains all footrpint libraries
├── sch # contains all schematic symbol libraries

### Structure

| Name                      | Type | Description                                                |
| ------------------------- | ---: | ---------------------------------------------------------- |
| pcb.PcbLib                |  pcb | main footrpint library                                     |
| crystals.PcbLib           |  pcb | footrpints of crystals used for db library                 |
| diodes.PcbLib             |  pcb | footrpints of diodes used for db library                   |
| passive.PcbLib            |  pcb | footrpints of resistors and capacitors used for db library |
| ---------------           | ---: | ---------------------------------------------------------- |
| battery.SchLib            |  sch |                                                            |
| capacitors.SchLib         |  sch |                                                            |
| connectors.SchLib         |  sch |                                                            |
| diodes.SchLib             |  sch |                                                            |
| fuses.SchLib              |  sch |                                                            |
| ICs.SchLib                |  sch |                                                            |
| inductors.SchLib          |  sch |                                                            |
| mics.SchLib               |  sch |                                                            |
| no-production.SchLib      |  sch |                                                            |
| opto.SchLib               |  sch |                                                            |
| oscillators.SchLib        |  sch |                                                            |
| relays.SchLib             |  sch |                                                            |
| resistors.SchLib          |  sch |                                                            |
| switches.SchLib           |  sch |                                                            |
| test&pcb.SchLib           |  sch |                                                            |
| transistors.SchLib        |  sch |                                                            |
| voltage_regulators.SchLib |  sch |                                                            |
| symbols.SchLib            |  sch |                                                            |
