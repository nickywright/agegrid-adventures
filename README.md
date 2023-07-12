# agegrid-adventures

This repository contains various agegrid-related things that can be used for outreach (or just for fun)!

<p align="center">
<img src="https://github.com/nickywright/agegrid-adventures/assets/19943774/f00306f5-6f50-4f68-831c-2924fabace82" width=120% />
</p>

---

A small present-day agegrid globe (1 pg of printing) can be downloaded [here](age_dymaxion_globe_A4.pdf). 

A much more intricate globe (14 pgs of printing) is [here](paperglobe_age_a4.pdf).

See below on details on how these were made.

---

## Data
Most (but not all) of this is based on the latest present-day agegrid from [Seton et al. 2020]((https://doi.org/10.1029/2020GC009214)), that can be downloaded from the EarthByte website [here](https://earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/). 

Palaeo-agegrids are based on the GPlates 2.3 [GeoData](https://www.earthbyte.org/gplates-2-3-software-and-data-sets/).

## How to

- If you have ever wanted to make your own personal present-day agegrid paper globe *almost from scratch*, visit [here](agegrid_printable_globe.ipynb) to see how. 

- If you have ever wanted to make your own personal suite of palaeo-agegrid paper globes (or a cool animation like the one above), visit [here](agegrid-palaeo_printable_globe.ipynb).

### details details

This whole repository relies on a little help from a few of key packages. 
I like to plot everything using [`pygmt`](https://www.pygmt.org/). [`GPlately`](https://github.com/GPlates/gplately) is also handy for plotting reconstruction-y things.

To convert things into a globe for assembling, there are two python-based packages you can use (that I know of). They're also super easy to use:
- If you have a spare few hours and want a slightly more globe-looking thing (and have some heavier weight paper available to print on), [`paper-globe`](https://github.com/joachimesque/paper-globe) easily allows you to make a paper globe!
- Otherwise, [`pydymax`](https://github.com/Teque5/pydymax) allows you to plot using a [dymaxion](https://en.wikipedia.org/wiki/Dymaxion_map) projection, which looks pretty cool, and you can also assemble into a little triangle-faced globe.  
