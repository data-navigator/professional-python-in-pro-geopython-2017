<section data-background="img/bg_title.jpg">
<h1>Python in ArcGIS Pro</h1>
<br>
<h2>Clinton Dow</h2>
</section>

Introduction {data-background="img/bg_right.jpg"}
============================================================

Today's Presentation {data-background="img/bg_left.jpg"}
--------------------------------------------------------------------

Overview of ArcGIS Pro

 - Why Switch to Pro?
 - Automating ArcGIS Pro
 - Using and creating Packages

Product Engineer - Geoprocessing at Esri California (1 year 8 months) {data-background="img/bg_left.jpg"}
---------------------------------------------------------------------------------------------------------------------
<br>

 - Python

  - ArcPy
  - Conda Integration

 - C#/WPF

  - Python Backstage
  - Charts and Graphs

 - Presentations

  - Dev Summit
  - User Conference
  - PyCon
  - GeoPython
  - AnacondaCon

GIS Developer at Matrix Solutions in Calgary (2 years) {data-background="img/bg_left.jpg"}
------------------------------------------------------------------------------------------------------

 - Civil Engineering/Environmental Consultant Firm
 - Created several dozen custom Geoprocessing tools in Python
 - Customized ArcGIS with Python and C#/WPF

Computer Nerd (30 years) {data-background="img/bg_left.jpg"}
------------------------------------------------------------------------

 - Open Source Development Experience
 - Community Moderation
 - Grown up with the internet and programming

![](img/esri_logo_lrg.png){class="tight"}{data-background="img/bg_right.jpg"}
============================================================

Why ArcGIS Pro? {data-background="img/bg_left.jpg"}
---------------------------------------------------------------

Modern View for ArcGIS:

 - Nearly all active development and new features
 - .Net 4.5 concurrency model
 - Integrated 2D and 3D views
 - Modern Python Experience
   - Supports environments and packages via Conda


ArcGIS Pro {data-background="img/bg_left.jpg"}
---------------------------------------------------------------

![](img/pro_full.png){style="width: 1000px; height=780px; background-color: 
rgba(255, 255, 255, 1);"}

Python Features in ArcGIS Pro UI {data-background="img/bg_right.jpg"}
==================================================================================================

Python Window {data-background="img/bg_left.jpg"}
-------------------------------------------------------------

Quick means of interacting with ArcGIS Pro using Python

 - Good way to practice and test concepts
 - View help documentation for ArcPy functions
 - Import and Export Python Scripts

Interactive Selections

 - Operate on data selected on Map
 - Automatically show result in Map

![](img/python_window.png)

TBX Toolboxes {data-background="img/bg_left.jpg"}
-------------------------------------------------------------

[The original ArcGIS toolbox.](https://geonet.esri.com/blogs/dan_patterson/2016/05/19/toolbox-creation-in-arcgis-pro)

 - Created via the ArcGIS GUI
 - Tool Validation not set in Python script
   - Set via 'Properties' menu of tool in ArcGIS

Python Toolboxes {data-background="img/bg_left.jpg"}
----------------------------------------------------------------

[ArcGIS toolboxes revisited in Python](http://pro.arcgis.com/en/pro-app/arcpy/geoprocessing_and_python/a-quick-tour-of-python-toolboxes.htm)

 - All steps defined in a .pyt file
  - Ease of testing & debugging
 - Validation defined within script
 - Works with Python IDEs
   - Define .pyt as a Python file type in settings
     - Syntax Highlighting
     - Autocomplete

Model Builder {data-background="img/bg_left.jpg"}
-------------------------------------------------------------

[Model Builder](http://pro.arcgis.com/en/pro-app/help/analysis/geoprocessing/modelbuilder/what-is-modelbuilder-.htm)

Allows for visual creation of Geoprocessing tools

 - Consume custom geoprocessing tools
   - Ensure you are setting an output!
 - Export to Python code
 - A good way to introduce scripting concepts

![](img/modelbuilder.png)

Python Packages in ArcGIS Pro {data-background="img/bg_left.jpg"}
-----------------------------------------------------------------------------

Significant effort has been made at Esri to integrate Python package
management and virtual environment support into the ArcGIS Pro
experience.

 - Shipped with default virtual environment
 - In-app user interface
 - Packaging effort for Esri Python code

Conda in ArcGIS Pro {data-background="img/bg_left.jpg"}
-------------------------------------------------------------------

![](img/pro_conda.png){style="width: 1000px; height=780px; background-color: 
rgba(255, 255, 255, 1);"}

Python Packages and Environments {data-background="img/bg_right.jpg"}
================================================================================

Package Management on Windows {data-background="img/bg_left.jpg"}
----------------------------------------------------------------------------

Using pip, wheels, virtualenvs

 - Packaged with distributions of Python
 - Package devs: On OSX and Linux, 'easy' to get the deps! Use a system package manager (e.g. apt, brew, yum)
 - Included Compiler (e.g. clang, gcc).

Virtual Environments {data-background="img/bg_left.jpg"}
--------------------------------------------------------------------

What are Virtual Environments

 - Self-contained instances of Python
 - Seperate from main Python installation
 - Can contain a unique set of packages
 - Useful when working on multiple projects at one time
 - Can be shared between team members

What about Windows? {data-background="img/bg_left.jpg"}
-------------------------------------------------------------------

Windows lacks broadly used package management

 - Only developers have a C compiler on their machine (Typically Visual Studio)
 - Difficult problems for many organizations to reliably solve
   - "Works on my machine but not yours" problem.
   - Supporting users takes up valuable dev time
   - No guarantee that customers will be supported

Enter Conda {data-background="img/bg_right.jpg"}
===========
![](img/continuum_analytics.png){style="width: 400px; height: 200px; 
background-color: rgba(255, 255, 255, 1);"}


Why Conda? {data-background="img/bg_left.jpg"}
----------------------------------------------------------

Scientific Python community identified that there was a gap not being addressed by the core Python infrastructure, limiting their ability to get packages into the hands of users

Industry standard built by people who care about this space &mdash; Continuum Analytics

Handles dependencies for many languages (C, C++, R and of course Python)

Built for Python first, but it really solves a much broader infrastructural issue.

![](img/conda_logo.png){style="width: 400px; height: 150px; background-color: 
rgba(255, 255, 255, 1);"}


Coming Soon {data-background="img/bg_left.jpg"}
-----------------------------------------------------------

Support for custom channels

 - Public Channels
   - Anaconda.org
 - Private Channels
   - Control package distribution, licensing etc.

<br>
Package Creation via UI

 - Currently only available in cmd line
 - Share packages with colleagues and customers

<br>
Additional Support on Server

 - Conda packages and environments fully supported on Enterprise
 - ArcGIS Python API Notebooks served on Enterprise

Using Packages to our Advantage {data-background="img/bg_right.jpg"}
===============================================================================

Open Source Ecosystem {data-background="img/bg_left.jpg"}
----------------------------------------------------------------------------------------------------------------

The Python Ecosystem includes thousands of open-source packages. Saves development time and money.

Esri is using several packages in ArcGIS

   - NumPy
   - SciPy
   - matplotlib
   - Pandas (coming soon)

Open Source Ecosystem {data-background="img/bg_left.jpg"}
----------------------------------------------------------------------------------------------------------------

Automate or Extend your ArcGIS capabilities

   - [Thousands of open-souce Python packages](https://repo.continuum.io/pkgs/)
   - [Conda-Forge community](https://conda-forge.github.io/feedstocks)

Easily package and share your work

   - [Conda-build](https://github.com/conda/conda-build)
   - [Anaconda.org](https://anaconda.org/esri)
   - Host packages on network

Setting up a Development Environment {data-background="img/bg_left.jpg"}
------------------------------------

What can we install?  Not just scientific packages.

   - Documentation
   - Datasets
   - GUI toolkits (PyQt, TKinter)
   - Database Drivers (psycopg2)
   - C++ Libraries (Boost)
   - IDEs
     - [Spyder](https://github.com/spyder-ide/spyder#overview)
     - [Juptyer](https://jupyter.org/)

Setting up a Production Environment {data-background="img/bg_left.jpg"}
-----------------------------------------------------------------------------------

Proven environments that will 'Just work'

   - Solves 'works on my machine' problem
   - Metapackages
    - Packages which only have requirements
   - [Environment.yaml](https://conda.io/docs/using/envs.html#id12)
    - More complex requirements.txt





Packaging Tools the Right Way {data-background="img/bg_right.jpg"}
=============================

Creating a Package {data-background="img/bg_left.jpg"}
------------------------------------------------------------------

Using setuptools and distutils to create a Python Package.

 - setuptools
   - setup
   - pkg_resources
 - distutils
   - Legacy, use setuptools if possible

![](img/pkg.png)

Deploying a Package  {data-background="img/bg_left.jpg"}
------------------------------------------------------------------------------

On a network

 - Point at a network location containing a package

Via a http server

 - All advantages of any http service
   - Authentication
   - Metrics
   - Availability

Anaconda.org


Deploying a Tool as a Service {data-background="img/bg_left.jpg"}
-----------------------------------------------------------------------------

Tools and data sets can be uploaded to ArcGIS Enterprise or ArcGIS
Online as services.

 - Custom GP Tools
 - Datasets
 - Results

Consuming services via the ArcGIS Python API {data-background="img/bg_left.jpg"}
--------------------------------------------------------------------------------------------

The ArcGIS Python API is a cross-platform solution which allows for
users to view, administer and interact with services on ArcGIS
Enterprise or ArcGIS Online.

 - [Sample Notebooks](https://developers.arcgis.com/python/sample-notebooks/)


Thank you!! Questions/Comments?? cdow@esri.com {data-background="img/bg_title.jpg"}
==============================================================================================

