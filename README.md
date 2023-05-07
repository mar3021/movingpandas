
<img  width="50%" src="https://movingpandas.github.io/movingpandas/assets/img/logo-wide.svg">



MovingPandas is a Python library for handling movement data based on Pandas, [GeoPandas](https://geopandas.org), and [HoloViz](https://holoviz.org). 

MovingPandas provides trajectory data structures and functions for movement data exploration and analysis.

The official MovingPandas API documentation is hosted on [ReadTheDocs](https://movingpandas.readthedocs.io).

For more information about individual releases, check out the [Changelog](./changelog).


[![Twitter Follow](https://img.shields.io/twitter/follow/MovingPandasOrg)](https://twitter.com/MovingPandasOrg)
[![Mastodon Follow](https://img.shields.io/mastodon/follow/109434720057484377?domain=https%3A%2F%2Ffosstodon.org)](https://fosstodon.org/@movingpandas)

[![docs status](https://readthedocs.org/projects/movingpandas/badge/?version=main)](https://movingpandas.readthedocs.io/en/main/)
[![pyOpenSci](https://camo.githubusercontent.com/63ff31cdb80a06361e53ac2b9ac0d184118ebd0b/68747470733a2f2f74696e7975726c2e636f6d2f7932326e62387570)](https://github.com/pyOpenSci/software-review/issues/18)
[![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/movingpandas.svg)](https://anaconda.org/conda-forge/movingpandas) 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/movingpandas/movingpandas-examples/main) 


## Features

* Easily create trajectories from diverse sources, including CSV files, GIS file formats, (Geo)DataFrames, and OGC Moving Features JSONs (MF-JSON) 
* Find locations for given time stamps and time spans
* Compute movement speed, direction, and sampling intervals
* Detect and extract stops 
* Split trajectories into individual trips
* Clean, simplify, generalize, and aggregate trajectories 
* Create static and interactive visualizations 

![Interactive trajectory visualization using hvplot](https://user-images.githubusercontent.com/590385/137953765-33f9ce1b-037c-4c86-82b2-0620de5ca28f.gif)

![Trajectory cleaning & smoothing](https://user-images.githubusercontent.com/590385/184359439-52eca394-5df6-40b2-a5b3-54543c3ccf34.png)

![Stop detection and splitting](https://user-images.githubusercontent.com/590385/236671475-a37aa046-76d6-48b9-ae6d-d1358a591953.png)


## What's next?

MovingPandas is under active development and there are some exciting features coming up. 
If you’d like to contribute to this project, you’re welcome to head on over to the [Github repo](https://github.com/movingpandas/movingpandas)! 


## Citation information

Please cite [0] when using MovingPandas in your research and reference the appropriate release version. All releases of MovingPandas are listed on [Zenodo](https://doi.org/10.5281/zenodo.3710950) where you will find citation information, including DOIs.  

[0] [Graser, A. (2019). MovingPandas: Efficient Structures for Movement Data in Python. GI_Forum ‒ Journal of Geographic Information Science 2019, 1-2019, 54-68. doi:10.1553/giscience2019_01_s54.](https://www.austriaca.at/rootcollection?arp=0x003aba2b)
