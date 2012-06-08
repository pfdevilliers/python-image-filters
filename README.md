python-image-filters
====================

Python script that reads the photoshop curve (.acv) files, extract the polynomials and applies it to an image.

A bit of code that was quickly hacked together for a small project. It supports color images not greyscale.

    Usage:
      python filter.py <path-to-curve-file> <path-to-image-file>

Normal image:

![Image of building](http://github.com/pfdevilliers/python-image-filters/raw/master/images/building.png "Building image")

After curve application:

![Image of building with curve](http://github.com/pfdevilliers/python-image-filters/raw/master/images/building_nasn.png "Building image")