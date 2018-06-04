# 2018-1-OSS-E7

## Wiki
[https://github.com/18-1-SKKU-OSS/2018-1-OSS-E7/wiki](https://github.com/18-1-SKKU-OSS/2018-1-OSS-E7/wiki)

## Static Page
[https://18-1-skku-oss.github.io/2018-1-OSS-E7/](https://18-1-skku-oss.github.io/2018-1-OSS-E7/)

## Project
[https://github.com/vlachoudis/bCNC](https://github.com/vlachoudis/bCNC)

## Members

김민영: operat8990@gmail.com

이수인: dooinee@gmail.com

정진아: jjayd1@naver.com

차호근: chahg0129@naver.com

bCNC
====

GRBL CNC command sender, autoleveler and g-code editor

An advanced fully featured g-code sender for GRBL. bCNC is a cross platform program (Windows, Linux, Mac) written in python. The sender is robust and fast able to work nicely with old or slow hardware like [Rasperry PI](http://www.openbuilds.com/threads/bcnc-and-the-raspberry-pi.3038/) (As it was validated by the GRBL mainter on heavy testing).

![bCNC screenshot](https://raw.githubusercontent.com/vlachoudis/bCNC/doc/Screenshots/bCNC.png)

# Installation
You will need the following packages to run bCNC
- tkinter the graphical toolkit for python
  Depending your python/OS it can either be already installed,
  or under the names tkinter, python-tkinter, python-tk
- pyserial or under the name python-serial, python-pyserial
- Optionally:
- python-imaging-tk: the PIL libraries for autolevel height map
- python-opencv: for webcam streaming on web pendant

Expand the directory or download it from github
and run the bCNC command

# Configuration
You can modify most of the parameters from the "Tools -> Machine"
page. Only the changes/differences from the default configuration
file will be saved in your home directory ${HOME}/.bCNC  or ~/.bCNC

The default configuration is stored on bCNC.ini in the
installation directory.

*PLEASE DO NOT CHANGE THIS ONE*

# Features:
- simple and intuitive interface for small screens
- import/export **g-code** and **dxf** files
- fast g-code sender (works nicely on RPi and old hardware)
- workspace configuration (G54..G59 commands)
- user configurable buttons
- g-code **function evaluation** with run time expansion
- feed override during the running for fine tuning
- Easy probing:
  - simple probing
  - center finder with a probing ring
  - **auto leveling**, Z-probing and auto leveling by altering the g-code during
    sending.
  - height color map display
  - **manual tool change** expansion and automatic tool length probing
  - **canned cycles** expansion
- Various Tools:
  - user configurable database of materials, endmills, stock
  - properties database of materials, stock, end mills etc..
  - basic **CAM** features (profiling, pocketing, cutting, drilling)
  - User g-code plugins:
    - bowl generator
    - finger joint box generator
    - simple spur gear generator
    - spirograph generator
    - surface flatten
    - ...
- G-Code editor and display
    - graphical display of the g-code, and workspace
    - graphically moving and editing g-code
    - reordering code and **rapid motion optimization**
    - moving, rotating, mirroring the g-code
- Web pendant to be used via smart phones

# Disclaimer
  The software is made available "AS IS". It seems quite stable, but it is in
  an early stage of development.  Hence there should be plenty of bugs not yet
  spotted. Please use/try it with care, I don't want to be liable if it causes
  any damage :)

# Stylish Portolio template for Jekyll

A Jekyll implementation of the [Stylish Portfolio](http://startbootstrap.com/template-overviews/stylish-portfolio/) template by [Start Bootstrap](http://startbootstrap.com/).

See the site in action at https://volny.github.io/stylish-portfolio-jekyll/

## To use the Stylish Portfolio template in your project

- Start by adding your info in `_config.yml`
- Add as many address lines as you want. Your address will also be used to show your location on the map.
- For the emdeded map to work you'll need to [get a key from Google Maps Embed API](https://developers.google.com/maps/documentation/embed/?hl=en)
- In `_layouts/front.html` reorder or remove section as you prefer.
