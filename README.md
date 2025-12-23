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

Used my dormant Arduino Uno board for revision 0. The many I/O pins made the hardware easy to design, but later revisions might use a PIC16F for cost efficiency.
I don't have tons of assembly experience, so the software will be done in C for now.
Since I'm using a plastic container, I skipped on heating the FeCl<sub>3</sub> this time. Aluminium seems to be easy to solder/weld, might be used for later revisions.
