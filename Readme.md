# sense-im

A Small wrapper on top of [gm](https://github.com/aheckmann/gm), adding the follwing helpers:

- fit(width,heigh): Fits the image within the given width & heigth
- square(): Inteligently crops the image into a square

Use like gm:

    si = require 'sense-im'
    
    si('path/to/source.jpg')
      .fit(100,100)
      .square()
      .write('path/to/dest.jpg')

##Installation

    $ npm install sense-im

##Run the tests

    $ cake test
