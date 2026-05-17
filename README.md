# iidxzero

17th May 2026 - Guide for setting up with GP2040-CE firmware uploaded, plus 3D print files for a gasket and a case - the gasket is in place of washers between the PCBs, it is specifically 3mm and any washers I got just weren't. By going between the 2 PCBs we add a fair bit of strength to the top plate. It's a bit different here as we are not using hotswap sockets, so we don't have screw holes and the plate and PCB are fixed with the keys are soldered in.

The case has the same dimensions as the PCB so it will be difficult to insert the controller if you print it as it is - either sand the inside to allow enough gap for it to slide in, or slightly scale up the print. I used 100.2% and it has been perfect for all the controllers - the controller slides in easy and stays in, but I know from experience this might need tweaking for your own printer.

The only thing missing is a turntable, a 60mm diameter rotary encoder knob. You can find these in 3D print file archives, but I can not find them to purchase which I would rather do. I've got several different prototypes made and will update when I have achieved some clarity.

<img width="1600" height="1200" alt="s-l16001" src="https://github.com/user-attachments/assets/237d428c-0c23-4b22-be7d-cafe9b781368" />

<img width="1600" height="1200" alt="s-l1600" src="https://github.com/user-attachments/assets/a8a5e52d-cd80-4092-aa9f-1a33912c5287" />

!10th May 2026 - they're made and being sent out - firmware used is GP2040-CE which is the aim every time really, the target price all together should be around 20 quid (that's GBP). I'll be testing the config backup in the next few days before uploading it, but the webconfig is reachable with the available keys as they are, I then set my buttons to be b1-b4 L1, R1, L2 S1 and S2, although that's mostly arbitrary it's the order GP2040-CE does it. i will also break down how the GPIO are used for setting up the key LEDs n the Add-Ons section, the 2 RGB LEDS and the rotary encoder settings - i set the encoder to act as Dpad up and down but there are other options, you should also set a reset time (in ms)  so it doesn't hold in whatever direction last pushed.

it's the brilliance of community efforts that give us so many opportunities, and i hope that by fulfilling a request i can further bring others in to making accessibility fun and rewarding.

To go with the PCBs you'll need 2x 5050 RGB, a PEC16 4015f encoder, 2x 0603 0.01uf capacitors for the encoder, 8x 0603 220o resistors (one for each key LED and one for the RGB line), 2x 4.5x4.5mm(5-7mm tall) tactile switches for s1 and s2, 7x keyboard switches (linear) and 7x 1.5u key caps. The turntable i made out of resin, you can get creative, it is basically a 60mm diameter encoder knob, but the resin has a good weight to it.


made by request but to my conditions of robustness - no folding or whatever. very cheap. can we agree the turntable is a gimmick?

<img width="4000" height="3000" alt="20260416_150300" src="https://github.com/user-attachments/assets/607eb55d-1c74-4e41-8e42-79d9e710dd9a" />
