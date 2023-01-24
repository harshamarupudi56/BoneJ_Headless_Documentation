Welcome to BoneJ Headless documentation!
===================================

**BoneJ Headless** BoneJ is a Fiji plugin for calculation of microstructural metrics and bone analysis with unique plugins not available from vendors. The plugins can be automated with simple Fiji macros, but this still requires GUI support. This repository allows for automation of BoneJ without GUI dependence and can allow for quick processing of large datasets, access to Python libraries, and a simple method of parameter sweeping to optimize BoneJ plugins. The Division of Imaging, Diagnostics, and Software Reliability (DIDSR) at the U.S. Food and Drug Administration developed BoneJ Headless a Python wrapper that automates BoneJ without any GUI dependence. This plugin was used on several microCT images and compared to microstructural metrics from other sources. All scripts are written in Python and can only be executed on Linux OS.


Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api

Plugins
==================

Currently supports the following plugins:

* Trabecular Thickness 
* Trabecular Spacing 
* Anisotropy
* Area Volume Fraction
* Connectivity
* Ellipsoid Factor 

Secondary plugins:

* Inter-trabecular Angles
* Surface Area 
* Fractal Dimension
* Skeletonize
* Analyze Skeleton
