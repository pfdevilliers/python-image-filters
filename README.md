python-image-filters
====================

Python script that reads the photoshop curve (.acv) files, extract the polynomials and applies it to an image.

A bit of code that was quickly hacked together for a small project. It supports color images not greyscale.

    Usage:
      python filter.py <path-to-curve-file> <path-to-image-file>

Normal image:

![Image of building](https://raw.githubusercontent.com/pfdevilliers/python-image-filters/master/images/building.png "Building image")

After curve application:

![Image of building with curve](https://raw.githubusercontent.com/pfdevilliers/python-image-filters/master/images/building_nasn.png "Building image")
