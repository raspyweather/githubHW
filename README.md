#  Github Calendar in Hardware
This is a very basic try to bring github's calendar to hardware. Who wouldn't like to get up and look at the glorious contribution history of the path?

![just an image from githubs documentation](https://help.github.com/assets/images/help/profile/contributions_graph.png)

(not my calendar btw ☺)

# introduction
Since I'm a student, manufacturing cost need to be low, why I decided to use three 10cm x 10cm pcbs and solder all components by hand. Because it is cheaper using one mutli-purpose board than two specific pcb designs, I decided to do so, not assemblying unnecessary components on these boards. 

## first/main pcb
All parts assembled 
- WeMos D1 mini (KiCad files used from https://github.com/jerome-labidurie/d1_mini_kicad)
- 2x [TPIC6B595N](http://www.ti.com/lit/ds/symlink/tpic6b595.pdf)
- [TLC5940](http://www.ti.com/lit/ds/symlink/tlc5940.pdf)
- *some* leds
- 4x Buttons
- 1x Poti

![pcb layout](https://cdn.rawgit.com/raspyweather/githubHW/86964fc3/githubHW-brd.svg)

## following two pcbs
- TLC5940
- *some* leds

## Total Circuit (connected ones)
only TLC5940 and leds assembled.
![total scheme](https://cdn.rawgit.com/raspyweather/githubHW/86964fc3/totalCircuit/githubHW.svg)
