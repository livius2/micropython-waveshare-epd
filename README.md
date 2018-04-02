# Waveshare E-Paper Display library for Pycom MicroPython

This library is based on the original Waveshare library for Raspberry Pi, available [here](https://www.waveshare.com/wiki/1.54inch_e-Paper_Module_(B)).

At the moment it supports 1.54" Waveshare two-color E-Paper Display only.

## Features

* Drawing lines (horizontal, vertical and between two arbitrary points)
* Drawing rectangles and circles, both regular and filled
* Drawing images from raw data (`list` or `bytes` object)
* Drawing images from BMP files (Windows-style 1-color bitmap)
* Adjusting screen orientation

## Usage

Consult `main.py` for an example usage.
In order to use fonts, copy them to `epd/lib` directory, or (recommended) freeze them in firmware. See [this blog post](https://kapusta.cc/2018/03/31/epd/) for more info on how to do it.
