# Board Etching Unit (BEU)

The **BEU** assists in the etching of PCB'S using FeCl<sub>3</sub>, so the operator gets to do more interesting things in the meantime.
BEU aims to achieve the following goals
- [ ] material cost below 50€
- [ ] moving FeCl<sub>3</sub> container
- [ ] FeCl<sub>3</sub> heater
  - [ ] open loop
  - [ ] closed loop control using thermoelement
- [ ] timer
- [ ] speed control

# Revision 0
- [ ] material cost below 50€
- [X] moving FeCl<sub>3</sub> container
- [ ] FeCl<sub>3</sub> heater
  - [ ] open loop
  - [ ] closed loop control using thermoelement
- [x] timer
- [x] speed control

Used my dormant Arduino Uno board for revision 0. A dev board for 20€ is fine for revision 0 but it did screw over the goal of low material cost.
Following revisions might use a PIC, the instruction set seems compact enough for some assembly and I found several primers covering them (IDE: PIKDEV).\
Though the AVR software will be done in C for now.\
Since I'm using a plastic container, I skipped on heating the FeCl<sub>3</sub> this time. Aluminium seems to be easy to solder/weld, might be used for later revisions.\
Closed loop temperature controll could be done using a PT100 or Typ K element, if the casing survives extended exposure to FeCl<sub>3</sub>.\

The board just etches on one side, with the other one facing down. A support beam could hold it up, but the support itself would cover parts of the board too.\
Vertical support on the left and right with 1 mm width could work.
