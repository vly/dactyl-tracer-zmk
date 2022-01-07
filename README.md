# Dactyl Tracer with ZMK

A wireless build of [mjohn](https://github.com/mjohns)'s excellent [Dactyl Tracer](https://github.com/mjohns/tracer) using ZMK firmware.

## Hardware 

The following is the hardware used for this build:

- Dactyl tracer case prints (used generic PLA+)
- [Deep-dish case plates](https://github.com/vly/dactyl-tracer-zmk/tree/master/things) to allow space for battery and height of the switches
- nice!nano v2 controllers x2
- Alps SKCC green switches x44
- Single switch PCBs x44
- 1100mAh LiPo battery x2
- Omron B3F1072N switches for bootloading x2
- USB-c extension cables x2
- m3 brass heat-sunk threads and m3 10mm bolts

Optional components

- Micro Losi connectors for connecting rows and columns to the controllers
- Montana Gold paint: Yosemite for the case
- Rustolium 2x ultra cover white primer

## Fluff

Goal for this build was a compact, portable and quiet board to take on work trips where I wouldn't annoy others with the regular clicky soundtrack.
Having used a [34-key keyboard](https://github.com/sanderboer/chonkybois) for a few months already as a daily driver at home, the Tracer fit the brief to a t.

For the switches and keycaps, I had a 50-odd alps skcc green linears sourced from broken Canon AP350 typewriter. The dimensions are the same footprint as MX (14x14), however with a notable height diff. After a light clean, the result is a relaxed and buttery smooth travel with a minor tactile bump prior to bottoming out. Given actuation is fairly early, typing is a very light and easy experience.

To accomodate the clearance issues with the skcc switches, I did a quick and dirty deep-dish-esk case plate which worked out well. Perhaps could've made it a tad thicker but it works as is.

For the wiring up of the switches, I shamelessly pilfered [cy384](https://github.com/cy384)'s alps mount single pcb design with minor changes. Essentially, the alps Amoeba equiv. They really make light work of doing wireup of full matrix in confined cases such as this.

Nice!nano controllers are a pleasure to work with, and running time on a single charge is >3 months. 

Total project material cost was approximately $150 AUD with the controllers accounting for half of that.
