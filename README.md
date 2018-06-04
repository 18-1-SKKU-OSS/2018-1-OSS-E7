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

# Our Github Page templete: Stylish Portolio template for Jekyll

A Jekyll implementation of the [Stylish Portfolio](http://startbootstrap.com/template-overviews/stylish-portfolio/) template by [Start Bootstrap](http://startbootstrap.com/).

See the site in action at https://volny.github.io/stylish-portfolio-jekyll/

## To use the Stylish Portfolio template in your project

- Start by adding your info in `_config.yml`
- Add as many address lines as you want. Your address will also be used to show your location on the map.
- For the emdeded map to work you'll need to [get a key from Google Maps Embed API](https://developers.google.com/maps/documentation/embed/?hl=en)
- In `_layouts/front.html` reorder or remove section as you prefer.


# Our Theme

## [Start Bootstrap - Agency](https://startbootstrap.com/template-overviews/agency/)

[Agency](https://startbootstrap.com/template-overviews/agency/) is a one page agency portfolio theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). This theme features several content sections, a responsive portfolio grid with hover effects, full page portfolio item modals, a responsive timeline, and a working PHP contact form.

## Preview

[![Agency Preview](https://startbootstrap.com/assets/img/templates/agency.jpg)](https://blackrockdigital.github.io/startbootstrap-agency/)

**[View Live Preview](https://blackrockdigital.github.io/startbootstrap-agency/)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-agency/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-agency.svg)](https://www.npmjs.com/package/startbootstrap-agency)
[![Build Status](https://travis-ci.org/BlackrockDigital/startbootstrap-agency.svg?branch=master)](https://travis-ci.org/BlackrockDigital/startbootstrap-agency)
[![dependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-agency/status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-agency)
[![devDependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-agency/dev-status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-agency?type=dev)

## Download and Installation

To begin using this template, choose one of the following options to get started:
* [Download the latest release on Start Bootstrap](https://startbootstrap.com/template-overviews/agency/)
* Install via npm: `npm i startbootstrap-agency`
* Clone the repo: `git clone https://github.com/BlackrockDigital/startbootstrap-agency.git`
* [Fork, Clone, or Download on GitHub](https://github.com/BlackrockDigital/startbootstrap-agency)

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with the template in your favorite text editor to make changes. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

After installation, run `npm install` and then run `gulp dev` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp sass` compiles SCSS files into CSS
- `gulp minify-css` minifies the compiled CSS file
- `gulp minify-js` minifies the themes JS file
- `gulp copy` copies dependencies from node_modules to the vendor directory

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/BlackrockDigital/startbootstrap-agency/issues) here on GitHub or leave a comment on the [template overview page at Start Bootstrap](http://startbootstrap.com/template-overviews/agency/).

## Custom Builds

You can hire Start Bootstrap to create a custom build of any template, or create something from scratch using Bootstrap. For more information, visit the **[custom design services page](https://startbootstrap.com/bootstrap-design-services/)**.

## About

Start Bootstrap is an open source library of free Bootstrap templates and themes. All of the free templates and themes on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

* https://startbootstrap.com
* https://twitter.com/SBootstrap

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

* http://davidmiller.io
* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2018 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-agency/blob/gh-pages/LICENSE) license.
=======

