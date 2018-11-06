# NS-Merger-Training-Workshop

# Transient Astrophysics
This repository contains all the material needed for the GWsky course held at **Centro Residenziale Universitario di Bertinoro**, 12-16 November 2018 - [NS Merger Training Workshop](https://nsmergerworkshop.wordpress.com/). We provide sample code in Python; you can download the documents and run the code samples in [Jupyter Notebook](http://jupyter.org/). To install Jupyter Notebook see [here](http://jupyter.org/install.html). We work using only **Python 3.x.x**)

**DO not forget your smartphone for a VR section**


# Installation and initialization

We will need to install a few third-party Python packages to run the example code in this tutorial. They are: [healpy](https://healpy.readthedocs.org/en/latest/) for reading the probability sky map files, [mocpy](https://github.com/tboch/mocpy) for parsing and manipulating MOCs, [astropy](http://www.astropy.org/)  package contains key functionality and common tools needed for performing astronomy and astrophysics with Python, [astropy.samp](http://astrofrog-debug.readthedocs.org/en/latest/vo/index.html) is a Python implementation of the SAMP (Simple Application Messaging Protocol) messaging system, [astroquery](https://astroquery.readthedocs.io/en/latest/) for querying astronomical web forms and databases, [scipy](https://www.scipy.org/) and [numpy](http://www.numpy.org/) for scientific computing with Python, the  2D plotting library [matplotlib](https://matplotlib.org/) and [GWsky](https://github.com/ggreco77/GWsky) for tiling a skymap in field of views. The GWsky GUI is written in [TKinter](https://docs.python.org/3/library/tkinter.html), please install and test it.

# Aladin and TOPCAT 
It is important to have installed beforehand in your laptops the VO-tools to be used in the School.

[ALADIN](http://aladin.u-strasbg.fr/). Download the Aladin.jar file and execute it from a terminal typing

                                $ java -Xmx2048m -jar Aladin.jar
          
[TOPCAT](http://www.star.bris.ac.uk/~mbt/topcat/). Download the topcat-full.jar file and execute it from a terminal typing 

                                $ java -jar topcat-full.jar
