.. Data Analysis using SunPy documentation master file, created by
   sphinx-quickstart on Tue Oct 29 12:40:22 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Data Analysis using SunPy's documentation!
=====================================================



This page guide you through the steps of installing the required softwares and packages you might need for the upcoming lectures.

Installation instructions for Anaconda and SunPy
################################################


If you already have installe Anaconda distribution then you don't need to go through this. Follow the package installation instructions.

Please download the setup file for Anaconda (Python 3.7 compatible) via this `link <https://repo.anaconda.com/archive/Anaconda3-2019.10-Linux-x86_64.sh>`_.

Make it executable by ``>> chmod +x Anaconda3-2019.10-Linux-x86_64.sh``.

For installing the setup run 
``>> ./Anaconda3-2019.10-Linux-x86_64.sh``. 

You don't require administrative permissions for intalling this. During installation please choose a working directory of your choice.

Once you are done with this step, run the following commands.

``>> conda update conda``

``>> conda install -c conda-forge matplotlib``

``>> conda install -c conda-forge numpy``

``>> conda install -c conda-forge sunpy``

``>> conda install -c anaconda jupyter``

``>> conda update conda``


For launching a new jupyter noteboook run ``>> jupyter notebook``.


At the top-right corner you will find a tab 'New', create a new python3 notebook.


Contents:

.. toctree::
   :maxdepth: 2

   first-example
   

