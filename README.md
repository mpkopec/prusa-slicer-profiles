# Prusa Slicer profiles

This repo contains Prusa Slicer profiles for MK3S+ derived from the ones 
generated with the config.

## Warning

This is a work in progress repo, use at your own risk!

## Naming scheme

```
lh**_per*_top*_bot*_ew**_inf**_fill****__ef**_seam****.ini
```

* `lh` --- layer height, given in hundreds of milimeters, e.g. 020 is 0.20mm,
* `per` --- number of perimeters,
* `top` --- number of top solid layers,
* `bot` --- number of bottom solid layers,
* `ew` --- extrusion width, analogically to `lh`,
* `inf` --- infill, given in percent, e.g. 50 means 50% infill,
* `fill` --- infill pattern,
* `ef` --- elephant foot compensation value, analogically to `lh`,
* `seam` --- seam position.
