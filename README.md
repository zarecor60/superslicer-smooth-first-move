# slic3r-smooth-first-move
A Slic3r post-processing script that joins the initial XY &amp; Z movements, producing a smoother initial move and preventing marks/oozes on the bed.

This **should** work as long as the start_gcode and per-layer gcode don't include any G1 moves

```
usage: join_first_xyz.py [-h] <GCode file>

Join the first XY & Z movements in the GCode output of Slic3r and Slic3r PE,
producing a smoother initial move and preventing marks/oozes on the bed.

positional arguments:
  <GCode file>  the GCode file to process

optional arguments:
  -h, --help    show this help message and exit
```
