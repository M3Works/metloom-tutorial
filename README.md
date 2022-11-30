# Metloom Tutorial
A collection of jupyter notebooks with metloom examples

## Metloom
Metloom (Location Oriented Observed Meteorology)
is a python package containing a collection of classes that
allow for standardized retrieval of station data from multiple 
data sources. The codeset for metloom can be found on 
[github](https://github.com/M3Works/metloom) and the
documentation can be found on [readthedocs](https://metloom.readthedocs.io).
Metloom is available for install through
[pypi](https://pypi.org/project/metloom/).

The installation, testing, and development instructions can be
found on github or readthedocs. 

## Requirements
Metloom has been tested on mac and linux and requires python >=3.7

## Setup
This repository is designed to walk through some examples of
how metloom may be leveraged for a variety of use cases. The 
notebooks are best run using jupyter notebook which can be installed
with `pip install notebook` and run from the command line with
`jupyter notebook` as explained [here](https://jupyter.org/install).

## Outline
 * Install and import
 * PointData and Variables
 * Daily Data and return dataframes
 * Searching for points
    * buffer
    * point metadata
    * point iterator
 * Data from multiple points
 * Saving data
 * Plotting data
 * Extending classes
 * mesowest
