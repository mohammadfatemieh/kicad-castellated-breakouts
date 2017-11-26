# Castellated Breakouts for KiCad

Do you own a milling machine that isn't _quite_ precise enough for that
0.5mm-pitch IC you want to use?  Maybe you like to home-etch your PCBs,
but you haven't quite worked out a way of consistently exposing tiny
0.2mm traces?  This repository can help you continue to rapidly prototype
your projects at home by letting PCB board houses handle the
parts of your design that are just a little too difficult to be worth
trying to do at home.

The boards in this repository can be plotted in KiCad and sent off to your
favorite board house (OshPark links are provided below) so you can have
boards for your favorite ICs readily-available for the next time you'd
like to use them in a design.

## Plotting

You can plot these on your own in KiCad, just make sure that you do *not*
tent vias.  The way castellations are implemented for at least OshPark
involve having vias on the edge of the board, and routing the board
board outline through the center of those vias.  If the vias were
tented, you would not be able to easily solder to them!

## Boards

### QFP64 (0.5mm pitch)

<img align="right" src="https://s3-us-west-2.amazonaws.com/coddingtonbear-public/github/kicad-castellated-breakouts/lqfp_fcu.png" />

<a href="https://oshpark.com/shared_projects/OnER0jUi"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>

* IC Pin Pitch: 0.5mm
* Compatible packages: QFP64 (BQFP64, CQFP64, LQFP64, TQFP64, etc).  No
  center pad.
* Castellation Pitch: 1.27mm
* Board Files: [qfp64_0.5mm](qfp64_0.5mm)

### SSOP8 (0.65mm pitch)

* IC Pin Pitch: 0.65mm
* Compatible packages: SSOP8 (TSSOP8, etc) having a width (including pins)
  smaller than 9mm.  No center pad.
* Castellation Pitch: 1.27mm
* Board Files: [ssop8_0.65mm](ssop8_0.65mm)
