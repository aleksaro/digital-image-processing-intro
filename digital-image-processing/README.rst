===================================
TDT4195 :: Digital Image Processing
===================================

This directory contains information for getting started with the assignments in the digital image processing part of the `NTNU`_ course `TDT4195 - Visual Computing Fundamentals`_.

Assignments can be completed in the programming language of your choice, however, it may be a good idea to select one that support matrix and image processing operations. The computers in the computer lab support `Python`_ and `MATLAB`_.

The following Python packages are installed on the lab computers:

+-----------------+------------------------------------------------------------------------------------+
| Library         | Function                                                                           |
+=================+====================================================================================+
| `NumPy`_        | Adds support for multi-dimensional arrays along with algorithms to operate on them |
+-----------------+------------------------------------------------------------------------------------+
| `Pillow`_       | A PIL (Python Imaging Library) fork                                                |
+-----------------+------------------------------------------------------------------------------------+
| `SciPy`_        | Includes a slew of modules that operate on NumPy arrays                            |
+-----------------+------------------------------------------------------------------------------------+
| `matplotlib`_   | A 2D plotting package                                                              |
+-----------------+------------------------------------------------------------------------------------+
| `scikit-image`_ | A collection of algorithms for image processing                                    |
+-----------------+------------------------------------------------------------------------------------+


Getting started
===============

To get started with the assignments, we have created two introductory guides: one for Python and another for MATLAB. Both guides can be found in the ``getting-started`` subdirectory:

* `Python guide`_
* `MATLAB guide`_

We recommend that you go through the relevant guide before starting with the assignments.


Installation
============

Below are a few different ways to set up your own computer for either Python or MATLAB. Keep in mind that this is not strictly necessary as you can always use the lab computers to do the assignments.


Python
------

There are multiple ways to install Python. This section outlines some options for installing Python on Linux, Windows, and Mac OS X operating systems.

* **[option 1 - *] Anaconda** The easiest way to get quickly started is to install `Anaconda`_. This is a Python distribution that comes with its own virtual environment tool ``conda`` and a slew of the most popular Python packages. Please check out the relevant part of the `Anaconda documentation`_ for how to install it on Linux, Windows, and Mac OS X systems.


* **[option 2 - Windows] WinPython** Take a look at `WinPython`_ if you want a similar, but more portable Python distribution compared to Anaconda on Windows.

* **[option 3 - Linux] Manual installation** If you have access to a terminal with Python and ``pip`` installed, then you can easily create a virtual environment with the packages specified in ``requirements.txt``. To set it up using ``virtualenv``, clone the repository and move into *this* directory using ``cd``:

.. code-block:: bash

  sudo pip install virtualenv        # Make sure virtualenv is installed globally
  virtualenv ~/.tdt4195env           # Create virtual environment in the HOME directory
  source ~/.tdt4195env/bin/activate  # Activate virtual environment
  pip install -r requirements.txt    # Install packages specified in requirements.txt
  # Work on assignment
  deactivate                         # Deactivate virtual environment

You can also install Python using the installer on the `Python`_ website, however, it is more cumbersome to install math heavy packages like NumPy and SciPy this way.


MATLAB
------

MATLAB is *not* a free piece of software and you will need a license to run it. Please have a look at the `Matlab for students`_ page on NTNU Innsida to see how you can install MATLAB and get an academic license. The most important MATLAB Toolbox to install is the `Image Processing Toolbox`_. Without it you will have a rough time with the assignments.


.. Links

.. _NTNU: https://www.ntnu.edu/
.. _TDT4195 - Visual Computing Fundamentals: https://www.ntnu.edu/studies/courses/TDT4195/
.. _Python: https://www.python.org/
.. _MATLAB: https://www.mathworks.com
.. _NumPy: http://www.numpy.org/
.. _Pillow: https://python-pillow.org/
.. _SciPy: https://www.scipy.org/
.. _matplotlib: http://matplotlib.org/
.. _scikit-image: http://scikit-image.org/
.. _Python guide: ./getting-started/getting-started-python.ipynb
.. _MATLAB guide: ./getting-started/getting-started-matlab.rst
.. _Anaconda: https://www.continuum.io/downloads
.. _Anaconda documentation: https://docs.continuum.io/anaconda/install
.. _WinPython: https://winpython.github.io/
.. _Matlab for students: https://innsida.ntnu.no/wiki/-/wiki/English/Matlab+for+students
.. _Image Processing Toolbox: https://www.mathworks.com/products/image/
