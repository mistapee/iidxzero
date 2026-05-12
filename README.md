# iidxzero

!quick update - they're made and being sent out - firmware used is GP2040-CE which is the aim every time really, the target price all together should be around 20 quid (that's GBP). I'll be testing the config backup in the next few days before uploading it, but the webconfig is reachable with the available keys as they are, I then set my buttons to be b1-b4 L1, R1, L2 S1 and S2, although that's mostly arbitrary it's the order GP2040-CE does it. i will also break down how the GPIO are used for setting up the key LEDs n the Add-Ons section, the 2 RGB LEDS and the rotary encoder settings - i set the encoder to act as Dpad up and down but there are other options, you should also set a reset time (in ms)  so it doesn't hold in whatever direction last pushed.

it's the brilliance of community efforts that give us so many opportunities, and i hope that by fulfilling a request i can further bring others in to making accessibility fun and rewarding.

To go with the PCBs you'll need 2x 5050 RGB, a PEC16 4015f encoder, 2x 0603 0.01uf capacitors for the encoder, 8x 0603 220o resistors (one for each key LED and one for the RGB line), 2x 4.5x4.5mm(5-7mm tall) tactile switches for s1 and s2, 7x keyboard switches (linear) and 7x 1.5u key caps. The turntable i made out of resin, you can get creative, it is basically a 60mm diameter encoder knob, but the resin has a good weight to it.


made by request but to my conditions of robustness - no folding or whatever. very cheap. can we agree the turntable is a gimmick?

<img width="4000" height="3000" alt="20260416_150300" src="https://github.com/user-attachments/assets/607eb55d-1c74-4e41-8e42-79d9e710dd9a" />

i was asked to make an iidx controller, tbh 5 key was enough for me and i had just services a bunch of ps1 era beatmania 5 key controllers to feel lovely. i haven't shown anyone my full size iidx project plan cos it's sneaky smart imho

without using 3d printing the scale below arcade keys is keyboard keys, really, not really a quick off-the-shelf middle ground. it's also important to recognise how the game works and how it is played. particularly with 7 keys i should think (i'm not great the game maybe i'm wrong) that a players hands should be focused over the keys - the turntable is an elaborate up/down and you wouldn't position yourself as you would at an actual turntable.

i want to make a micro version with a spring-centering toggle switch instead of the turntable, reachable with the pinky finger, functionally just as good.

i am right now making silicon molds for the turtables to be cast out of resin - i really like the results so far. the rotary encoder is the same used on all other projects which especially in this country is incredibly cheap and a solid unit. this whole controller could travel in your pocket and when you pull it out you just drop the turn table hockey puck on the shaft of the encoder - keeping it fixed risks damage.

<img width="760" height="506" alt="20260425_015308" src="https://github.com/user-attachments/assets/600c2005-d2be-416f-8628-a2d1b0ccd0e9" />


the hole around the encoder is not supposed to line up with the turntable, i usually go from pcbs arriving to getting them out much quicker but i've been busy - AND (NOTE THIS if you use these gerbers) i was doing a big clean up and picked some footprint libraries for Kicad thinking that they were pretty much what I had previously. they're not, so the SMD soldering is less forgiving that i usually go for

no firmware or anything yet, i use my usual RGB test before putting the sandiwche together.
