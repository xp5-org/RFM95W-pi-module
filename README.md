# RFM95W-pi-module
PCB to connect RFM95W module to ras pi header

have not tested it yet, need to verify things are wired correctly and pinouts are correct

I set this up to be buildable on a single-layer routed or etched (home made) pcb . 

it relies upon jumper bodge wires to complete some of the wiring, otherwise this would be better served by at least 2 layers or 4 layers board.

ras pi zero has two SPI channels, which can allow up to two simutaenous radios/modems in use. 

<br>
<br>

## single radio layout ##
<img width="1492" height="952" alt="image" src="https://github.com/user-attachments/assets/593a1fc3-638c-4c53-a9fd-bb6297cef4b4" />

<br>
<br>

## dual radio layout ##
<img width="1380" height="730" alt="image" src="https://github.com/user-attachments/assets/46cbe9fd-e937-4905-9216-dae4e885a3b4" />

<br>
<br>

# converting kicad gerbers to G-code for CNC
http://flatcam.org/download

need to generate the isolation path (mill the PCB) and then generate the drill instructions (through-holes and vias drills) separately

<img width="1357" height="795" alt="image" src="https://github.com/user-attachments/assets/f237cbba-b03f-42a5-9c2b-3338e0bc1b24" />
