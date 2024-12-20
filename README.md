# Building Centreline Demo

This repository provides a notebook that roughly describes an implementation to replicate the building centreline tool. It relies heavily on the [shapely](https://shapely.readthedocs.io/en/2.0.6/) library, objects of which should interface well with [geopandas](https://geopandas.org/en/stable/index.html).  

As the notebook is intended to demonstrate geometric transformations, it reads from a standalone ```.geojson``` file describing a single polygon in WGS 84, although this can be modified to fit the required data pipelines.  

Included in the repository is a [conda environment file](./environment.yml), and two test cases.  
* [7 Everton Park](./EvertonPark7.geojson)
* [Tanjong Pagar Plaza Commercial Podium](./TanjongPagarPlaza.geojson)