# Sound Pad

An instrument with precise rotary encoders for volume and frequency/pitch control.

Will have a custom PCB and a custom case. Will also have keyboard switches akin to a macro pad, so it it multi use. e.g. could be used as an instrument, sound board, synth, macro pad etc.

## Repo layout

All files needed to replicate it can be found in .\hardware. This includes the Gerber, schematic and PCB design files. \images contains images used in the documentation. Aside from the readme, other files are cloned from Half Life.


## PCB Design
Has a fairly simple PCB designed mainly to connect keyboard switches to a microcontroller. Namely a rp2040 zero.

### Schematic

A fairly simple schematic so could be wired by hand. but would need some way to attach the switches.

![Schematic](images/Schematic.png)

### PCB Render

PCB is under 100mm x 100mm so qualifies for the JLCPCB $4 prototype discount

![PCB render](images/PCB_render.png)

## Case

Is a compact single piece case. Holds a 2 row set of 4 keyboard switches, and has a slooed upper shelf/plate for two rotary encoders and a screen.

![Case render](images/Case.png)

## Code

Will likely configure with something like vial or qmk to output midi signals, so it is an "instrument". But has skeleton platformio pin defs in main.cpp.

## BOM

Will total less than $100 for 2 pads. 1 for each hand - theyll just be duplicates.

| Item | Qty | Supplier | Cost/item | Total Cost | link |
|---|---|---:|---|---:|---:|---|
| Keyboard Switches | 1 | AliExpress | $9.06 | $9.06 | [link](https://www.aliexpress.com/item/1005006376024657.html?mp=1&pdp_npi=6%40dis%21USD%21USD+9.06%21USD+8.52%21%21USD+8.52%21%21%21%402103842a17925616571435669e0f55%2112000036949493875%21ct%21GB%218513385029%21%211%210%21) |
| Keycaps | 2 | AliExpress | $4.22 | $8.44 | [link](https://www.aliexpress.com/item/1005009364428646.html?mp=1&pdp_npi=6%40dis%21USD%21USD+4.22%21USD+4.22%21%21USD+4.22%21%21%21%400b0fe08917925617141713066e0ef9%2112000048873877393%21ct%21GB%218513385029%21%211%210%21) |
| 2pcs encoder knobs | 2 | AliExpress | $3.42 | $6.84 | [link](https://www.aliexpress.com/item/1005006063377230.html?mp=1&pdp_npi=6%40dis%21USD%21USD+3.42%21USD+3.42%21%21USD+3.42%21%21%21%400b0fe08917925617141713066e0ef9%2112000060167208476%21ct%21GB%218513385029%21%212%210%21&pdp_ext_f=%7B%22cart2PdpParams%22%3A%7B%22pdpBusinessMode%22%3A%22retail%22%7D%7D) |
| 5pcs ec11 | 1 | AliExpress | $2.83 | $2.83 | [link](https://www.aliexpress.com/item/10000056483250.html?mp=1&pdp_npi=6%40dis%21USD%21USD+2.83%21USD+2.83%21%21USD+2.83%21%21%21%400b0fe08917925617600973704e0ef9%2112000046133170765%21ct%21GB%218513385029%21%211%210%21) |
| Screen | 3 | AliExpress | $1.84 | $5.52 | [link](https://www.aliexpress.com/item/32709141534.html?mp=1&pdp_npi=6%40dis%21USD%21USD+1.84%21USD+1.84%21%21USD+1.84%21%21%21%400b0fe08917925617600973704e0ef9%2112000015830115736%21ct%21GB%218513385029%21%213%210%21) |
| Gluer | 1 | AliExpress | $13.39 | $13.39 | [link](https://www.aliexpress.com/item/1005010440447447.html?mp=1&pdp_npi=6%40dis%21USD%21USD+26.78%21USD+13.39%21%21USD+13.39%21%21%21%400b0fe08917925617141713066e0ef9%2112000052419932648%21ct%21GB%218513385029%21%211%210%21) |
| 3pcs rp2040 zero | 1 | AliExpress | $8.03 | $8.03 | [link](https://www.aliexpress.com/item/1005012511141182.html?mp=1&pdp_npi=6%40dis%21USD%21USD+8.03%21USD+8.03%21%21USD+8.03%21%21%21%400b0fe08917925617600973704e0ef9%2112000058603728665%21ct%21GB%218513385029%21%211%210%21) |
| Speaker | 1 | AliExpress | $8.77 | $8.77 | [link](https://www.aliexpress.com/item/1005006807962595.html?mp=1&pdp_npi=6%40dis%21USD%21USD+8.73%21USD+4.37%21%21USD+4.37%21%21%21%400b0fe08917925617141713066e0ef9%2112000038372782445%21ct%21GB%218513385029%21%211%210%21) |
| UK plug | 1 | AliExpress | $4.38 | $4.38 | [link](https://www.aliexpress.com/item/1005006808365132.html?mp=1&pdp_npi=6%40dis%21USD%21USD+4.38%21USD+4.38%21%21USD+4.38%21%21%21%400b0fe08917925617141713066e0ef9%2112000060848436181%21ct%21GB%218513385029%21%211%210%21) |
| 5pcs PCB | 1 | JLCPCB | $4.00 | $4.00 | [link](https://jlcpcb.com) |
| Case | 2 | JLC3DP | $8.53 | $17.06 | [link](https://jlc3dp.com) |
| Estimated total shipping | 1 |  |  | $10.00 |  |


Will be slightly different cart screenshots due to coupons etc. But will be roughly $98.32
