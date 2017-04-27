Harnessing the Power of Python in ArcGIS using the Conda Distribution
=====================================================================

### Shaun Walbridge & Clinton Dow
### Esri UC 2017

**[View the Slides](https://4326.us/esri/conda-uc/)**

**[
Download High Quality Version (PDF, 4MB)
](https://4326.us/esri/conda-uc/uc-2017-conda-arcgis-demo-full.pdf)**

Description
-----------

Python has a rich ecosystem of packages you can use in your own code,
but installation used to be complex. ArcGIS Pro 1.4 includes an enhanced 
Python experience, allowing you to install conda packages through a User 
Interface. This allows you to easily install libraries into your Python 
environment, and distribute that code to others. ArcGIS Pro 2.0 will include
environment support in the User Interface and package creation features will
be included in 2.1 and beyond. We will explore conda, the User Interface and
demonstrate the workflow of packaging a Python script tool on the command 
line, then installing it and running it in ArcGIS Pro. Join us and learn to 
bend Python to your will.

Building
--------

 - From `slides/`, run `make` to rebuild the slide deck from the included 
 slides.md file. Requires [Pandoc](http://johnmacfarlane.net/pandoc/).
 - Check links with `make check`, requires 
 [LinkChecker](https://pypi.python.org/pypi/LinkChecker).
 - Generate handout version with `make pdf`. Requires XeTeX and pandoc.
 - Generate high-quality PDF with `make fullpdf`. Requires 
 [decktape.js](https://github.com/astefanutti/decktape)
