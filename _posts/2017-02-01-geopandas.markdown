# Introduction to GeoPandas and related vector geospatial processing with FOSS Python

This [Maptime Meetup workshop](https://www.meetup.com/MaptimeSEA/) is adapted from materials prepared for the [University of Washington GeoHack week event](https://geohackweek.github.io), Nov 14-18, 2016. We'll be using [those materials ("Vector Data Processing using Python Tools")](https://geohackweek.github.io/vector/) directly in some cases, as is.

## Python Preparations

This workshop will rely on **conda** to set up the required Python 2.7 environment and packages. [See here](https://github.com/MaptimeSEA/geopandas-tutorial-maptime/blob/master/install-conda.md) for details on how to get set up. All demonstration will be done on [Jupyter notebooks](http://jupyter.org). The `geopandasenv` Python conda environment you will create includes Jupyter.

## Materials and Lessons

We'll follow the "lessons" used in the [UW GeoHack tutorial](https://geohackweek.github.io/vector/), jumping back and forth from those materials to the updated Jupyter notebooks. All materials can be [downloaded from here](https://github.com/MaptimeSEA/geopandas-tutorial-maptime) so you can run the code on your computer. These include [GIS data files](https://github.com/MaptimeSEA/geopandas-tutorial-maptime/tree/master/data) and the [two Jupyter notebooks](https://github.com/MaptimeSEA/geopandas-tutorial-maptime/tree/master/notebooks).

1. [**Geospatial Concepts.**](https://geohackweek.github.io/vector/02-geospatial-concepts/) What is 'vector' geospatial data all about?
2. [**Encodings, Formats and Libraries.**](https://geohackweek.github.io/vector/03-encodings-libraries/) What are the common ways to encode vector geospatial data in Python, and how much is borrowed from broader encoding standards?
3. **GeoPandas Introduction.** What is GeoPandas? What functionality and advantages does GeoPandas offer over other Python geospatial tools? What geospatial storage, analytical and plotting capabilities does it include? What is its relationship to Pandas? [Download the Jupyter notebook](https://github.com/MaptimeSEA/geopandas-tutorial-maptime/blob/master/notebooks/geopandas_intro.ipynb) to run it locally, or view it [statically but nicely rendered on nbviewer](http://nbviewer.jupyter.org/github/MaptimeSEA/geopandas-tutorial-maptime/blob/master/notebooks/geopandas_intro.ipynb). The original materials with extra formatting and PostGIS content (and original notebook) can be [found here](https://geohackweek.github.io/vector/04-geopandas-intro/) on the UW GeoHack web site.
4. **GeoPandas Advanced Topics.** What additional capabilities does GeoPandas provide, including data access, plotting and analysis? How does it integrate with other common Python tools? How do GeoPandas data objects integrate with analyses of raster data over vector geospatial features? [Download the Jupyter notebook](https://github.com/MaptimeSEA/geopandas-tutorial-maptime/blob/master/notebooks/geopandas_advanced.ipynb) to run it locally, or view it [statically but nicely rendered on nbviewer](http://nbviewer.jupyter.org/github/MaptimeSEA/geopandas-tutorial-maptime/blob/master/notebooks/geopandas_advanced.ipynb). The original materials with extra formatting and PostGIS content (and original notebook) can be [found here](https://geohackweek.github.io/vector/06-geopandas-advanced/) on the UW GeoHack web site.

For lessons 1 and 2 we'll go directly to the GeoHack tutorial site.
