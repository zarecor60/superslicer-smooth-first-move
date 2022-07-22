# slic3r-smooth-first-move
A Slic3r post-processing script that joins the initial XY &amp; Z movements, producing a smoother initial move and preventing marks/oozes on the bed.

This should work regardless of your custom gcodes!

```
usage: join_first_xyz.py [-h] <GCode file>

Join the first XY & Z movements in the GCode output of Slic3r and Slic3r PE,
producing a smoother initial move and preventing marks/oozes on the bed.

positional arguments:
  <GCode file>  the GCode file to process

optional arguments:
  -h, --help    show this help message and exit
```

Feel free to suggest changes as you find them! 
