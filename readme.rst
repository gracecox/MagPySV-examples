Introduction
------------

This repository accompanies the paper "MagPySV: A Python package for processing and denoising geomagnetic observatory data" by Cox et al. (2018), published in *Geochemistry, Geophysics, Geosystems* (https://doi.org/10.1029/2018GC007714). It contains example Jupyter notebooks for the MagPySV software (https://github.com/gracecox/MagPySV, see also the documentation hosted at http://magpysv.readthedocs.io/en/latest/). MagPySV is an open-source Python package designed to provide a consistent, and automated as far as possible, means of generating high resolution SV time series from raw observatory hourly means distributed by the World Data Centre (WDC) for Geomagnetism at the British Geological Survey (BGS), Edinburgh. It uses a second Python package developed by BGS to download data for a given time range and list of observatories.

Example workflows
-----------------

In the accompanying paper, we present two case studies of cleaned data in different geographic regions and discuss their application to geomagnetic jerks: monthly first differences for Europe, and annual differences for northern high latitude regions. The two notebooks in this repository can be used to download the relevant hourly data from BGS and reproduce the figures for these case studies.

To obtain the notebooks, click the green "clone or download" button on this page, select "download zip" from the dropdown menu and save the file to the desired location. Unzip the file and navigate to the resulting folder. To open the notebooks, launch a Jupyter notebook from the folder (e.g. by typing ``jupyter notebook`` into the command line from that directory) and then select the desired notebook from the list that appears in your web browser.

The `Jupyter documentation`_ contains a step-by-step tutorial on installing and running notebooks, and is aimed at new users who have no familiarity with Python.

Note that MagPySV must be installed before using the notebooks, preferably using ``pip`` (see below).

MagPySV installation
--------------------

MagPySV can be installed via the Python Package Index (PyPI) using the command
``pip install magpysv``. This also installs all required dependencies, including the BGS data downloading app. The example Juypyter notebooks  are not included in the PyPI installation and need to be downloaded from this GitHub project page after the software is installed.

Reference
---------

An open access manuscript describing MagPySV, and the examples contained within this repository, is now published in *Geochemistry, Geophysics, Geosystems* (https://doi.org/10.1029/2018GC007714); please cite this if you use the code.

Cox, G. A., Brown, W. J., Billingham, L., & Holme, R. (2018). MagPySV: A Python package for processing and denoising geomagnetic observatory data. Geochemistry, Geophysics, Geosystems, 19, 3347–3363. https://doi.org/10.1029/2018GC007714

.. _Jupyter documentation: https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/.
