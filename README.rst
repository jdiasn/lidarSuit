=============
!!ATTENTION!!
=============

**Archived:** This repository was archived and is not maintained anymore. The lidarSuit project was renamed to lidarwind, please check https://github.com/jdiasn/lidarwind

======================
lidarSuit introduction
======================

.. image:: https://joss.theoj.org/papers/28430a0c6a79e6d1ff33579ff13458f7/status.svg
   :target: https://raw.githubusercontent.com/openjournals/joss-papers/joss.04715/joss.04715/10.21105.joss.04715.pdf

.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.7026548.svg
   :target: https://doi.org/10.5281/zenodo.7026548

.. image:: https://mybinder.org/badge_logo.svg
   :target: https://mybinder.org/v2/gh/jdiasn/lidarSuit/main?labpath=notebooks

.. image:: https://readthedocs.org/projects/lidarsuit/badge/?version=latest
    :target: https://lidarsuit.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. image:: https://img.shields.io/pypi/v/lidarSuit.svg
   :target: https://pypi.python.org/pypi/lidarSuit/

.. image:: https://codecov.io/gh/jdiasn/lidarSuit/branch/main/graph/badge.svg?token=CEZM17YY3I
   :target: https://codecov.io/gh/jdiasn/lidarSuit

lidarSuit is an open-source Python project to retrieve wind speed and direction profiles from Doppler lidar observations from the WindCube-200s, and it was developed to be easy to use. It can retrieve wind profiles from the 6-beam and DBS scanning strategies and allow users to set the signal-to-noise ratio threshold to reduce the noise. It also calculates the Reynolds stress tensor matrix elements from the 6-beam observations.

lidarSuit is a result of an effort to create an environment where it would be flexible and easy to process the observations from the WindCube Doppler lidar. Its development started in 2021 when I had to retrieve wind profiles from the 6-beam observations.

This current version focuses on the WindCube's observations, and the wind retrievals are dedicated to the 6-beam and DBS observations. However, it can be expanded to other Doppler lidar observations and scanning strategies.


-------------
Documentation
-------------

The lidarSuit's documentation is available at https://lidarsuit.readthedocs.io, and an introductory set of rendered notebooks are available at https://nbviewer.org/github/jdiasn/lidarSuit/tree/main/docs/examples/.



.. warning::

    Beware that between versions 0.1.6 and 0.2.0, the package underwent significant refactoring. Now the classes' names
    follow the Pascal case, while module names, functions and attributes follow the snake case. Codes developed using the previous
    version will need revision.



----------
Suggestion
----------

If you want to try using this package without instaling first, you can do it by clicking on the binder badge.
