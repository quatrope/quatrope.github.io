

**QuatroPe** is an effort to develop high-quality scientific software, by
mentoring people and outreach and mentoring projects.

Many of the QuatroPe tools emerged as independent efforts of
its members and were integrated into the organization in order to maintain and
improve them.

## [Astroalign](https://astroalign.readthedocs.io)

Astroalign is a python module that will try to align two stellar astronomical
images, especially when there is no WCS information available.

It does so by finding similar 3-point asterisms (triangles) in both images and
deducing the affine transformation between them.


[![Build Status](https://travis-ci.com/toros-astro/astroalign.svg?branch=master)](https://travis-ci.com/toros-astro/astroalign)
[![Coverage](https://codecov.io/github/toros-astro/astroalign/coverage.svg?branch=master)](https://codecov.io/github/toros-astro/astroalign)
[![Documentation Status](https://readthedocs.org/projects/astroalign/badge/?version=latest)](http://astroalign.readthedocs.org/en/latest/?badge=latest)
[![Updates](https://pyup.io/repos/github/toros-astro/astroalign/shield.svg)](https://pyup.io/repos/github/toros-astro/astroalign/)
[![Python 3](https://pyup.io/repos/github/toros-astro/astroalign/python-3-shield.svg)](https://pyup.io/repos/github/toros-astro/astroalign/)
[![PyPI](https://img.shields.io/pypi/v/astroalign)](https://pypi.org/project/astroalign/)
[![ascl:1906.001](https://img.shields.io/badge/ascl-1906.001-blue.svg?colorB=262255)](http://ascl.net/1906.001)

---

## [Properimage](https://properimage.readthedocs.io)

Properimage is an implementation of the algorithms described in Zackay & Ofek 2017
papers, "How to coadd images" [1](https://iopscience.iop.org/article/10.3847/1538-4357/836/2/187/meta) [2](https://iopscience.iop.org/article/10.3847/1538-4357/836/2/188).

- It performs PSF estimation using Karhunen-Loeve expansion, which is based on Lauer 2002 work.
- It performs statistical proper coadd of several images.
- It performs proper-subtraction of images.

[![Build Status](https://travis-ci.com/quatrope/ProperImage.svg?branch=master)](https://travis-ci.com/quatrope/ProperImage)
[![codecov](https://codecov.io/gh/quatrope/ProperImage/branch/master/graph/badge.svg)](https://codecov.io/gh/quatrope/ProperImage)
[![Documentation Status](https://readthedocs.org/projects/properimage/badge/?version=latest)](http://properimage.readthedocs.io/en/latest/?badge=latest)
[![License](https://img.shields.io/pypi/l/properimage?color=blue)](https://tldrlegal.com/license/bsd-3-clause-license-(revised))
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://badge.fury.io/py/properimage)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/ambv/black)

---

## [Carpyncho](https://carpyncho.github.io/)

Carpyncho, is a catalog browser that we hope will be reutilized to search for and
characterize time variable data of the ~PiB size [VVV/VVVx](https://vvvsurvey.org/)
survey. Is being developed for the detection and classification of periodic
variables. For this purpose the stacked pawprint data from the VDFS CASU v >= 1.3
catalogs have been crossed matched with the VDFS CASU v1.3 tile catalogs into a
Parquet files.
The Carpyncho infrastructure [https://carpyncho.gihub.io](https://carpyncho.gihub.io) is being developed entirely in Python.

Also, a companion Python library is developed to access the same dataset as a [Pandas DataFrame](https://pandas.pydata.org/).

[![Build Status](https://travis-ci.org/carpyncho/carpyncho-py.svg?branch=master)](https://travis-ci.org/carpyncho/carpyncho-py)
[![Python 3](https://img.shields.io/badge/python-3.7+-blue.svg)](https://badge.fury.io/py/carpyncho)
[![BSD-3](https://img.shields.io/badge/License-BSD3-blue.svg)](https://www.tldrlegal.com/l/bsd3)
[![Documentation Status](https://readthedocs.org/projects/carpyncho-py/badge/?version=latest)](https://carpyncho-py.readthedocs.io/en/latest/?badge=latest)
[![PyPI](https://img.shields.io/pypi/v/carpyncho)](https://pypi.org/project/carpyncho/)
[![ascl:2005.007](https://img.shields.io/badge/ascl-2005.007-blue.svg?colorB=262255)](http://ascl.net/2005.007)

---

[More Projects](/projects)