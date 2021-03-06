﻿== History of changes for WinPython 2.7.4.0 ==

The following changes were made to WinPython distribution since version 2.7.3.3.

=== Internals ===

The following changes were made to WinPython tools (`winpython` Python package), including WPPM, WPCP and the distribution generation script (`make.py` and its dependencies):
  * utils: added `set_env` and `get_env` functions (will be useful to fix Issue 35)
  * Register WinPython distribution:
    * Added "Edit with Spyder" to context menu entries (requires Spyder 2.2+)
    * Added "unregistration" process (WinPython Control Panel: new "Unregister distribution..." entry in "Advanced" menu)
  * Issue 19: Disable 'settings' folder (%HOME% redirection) by renaming/deleting the directory
  * WinPython control panel (Issue 29): removed embedded Python (Spyder) console
  * Batch scripts: removed unnecessary "cd %WINPYDIR%" (this became unnecessary)
  * Fixed 'register_python.bat' scripts following changes in command line options (these changes were made in revision 9a62581ae693)
  * py3compat: fixed ImportError on non Windows plaforms due to winreg/_winreg

=== Tools ===

Upgraded packages:

  * [http://tortoisehg.bitbucket.org TortoiseHg] 2.6 → 2.7.2 (Set of graphical tools and a shell extension for the Mercurial distributed revision control system)

=== Python packages ===

New packages:

  * [http://abel.ee.ucla.edu/cvxopt cvxopt] 1.1.5 (Convex optimization library)
  * [https://pypi.python.org/pypi/PySide PySide] 1.1.2 (Python binding of the cross-platform GUI toolkit Qt)
  * [http://pypi.python.org/pypi/simplejson simplejson] 3.1.3 (Simple, fast, extensible JSON (JavaScript Object Notation) encoder/decoder)
  * [http://pypi.python.org/pypi/pip pip] 1.3.1 (A tool for installing and managing Python packages)
  * [http://pypi.python.org/pypi/networkx networkx] 1.7 (Python package for creating and manipulating graphs and networks)
  * [http://pypi.python.org/pypi/mahotas mahotas] 0.9.8 (Computer Vision library)
  * [http://www.vpython.org VPython] 5.74 (A free, open-source module for producing real-time 3D scenes with Python)
  * [http://pypi.python.org/pypi/Pillow Pillow] 2.0.0 (Python Imaging Library (fork))

Upgraded packages:

  * [http://www.cython.org Cython] 0.17.4 → 0.19 (Cython is a language that makes writing C extensions for the Python language as easy as Python)
  * [http://pypi.python.org/pypi/distribute distribute] 0.6.33 → 0.6.36 (Download, build, install, upgrade, and uninstall Python packages - easily)
  * [http://pyvisa.sourceforge.net PyVISA] 1.3 → 1.4 (Control all kinds of measurement equipment through various busses (GPIB, RS232, USB))
  * [http://code.google.com/p/numexpr numexpr] 2.0.1 → 2.1 (Fast evaluation of array expressions elementwise by using a vector-based virtual machine)
  * [http://www.pytables.org tables] 2.4.0 → 3.0.0b1 (Package based on HDF5 library for managing hierarchical datasets (extremely large amounts of data))
  * [http://www.reportlab.org reportlab] 2.6 → 2.7 (The PDF generation library)
  * [http://pypi.python.org/pypi/Scidoc Scidoc] 1.6.2.1 → 1.7.1 (Scidoc installs scientific libraries documentation (NumPy, SciPy, ...))
  * [http://www.python.org/ Python] 2.7.3 → 2.7.4 (Python programming language with standard library)
  * [http://pypi.python.org/pypi/pandas pandas] 0.10.1 → 0.11.0 (Powerful data structures for data analysis, time series and statistics)
  * [http://pypi.python.org/pypi/pyzmq pyzmq] 2.2.0.1 → 13.1.0 (Lightweight and super-fast messaging based on ZeroMQ library (required for IPython Qt console))
  * [http://pypi.python.org/pypi/xlwt xlwt] 0.7.4 → 0.7.5 (Create spreadsheet files compatible with Microsoft Excel 97/2000/XP/2003 files, OpenOffice.org Calc, and Gnumeric)
  * [http://numpy.scipy.org/ numpy-MKL] 1.6.2 → 1.7.1 (NumPy: multidimensional array processing for numbers, strings, records and objects (SciPy's core module))
  * [http://pypi.python.org/pypi/scikit-image scikit-image] 0.7.2 → 0.8.1 (Image processing toolbox for SciPy)
  * [http://matplotlib.sourceforge.net matplotlib] 1.2.0 → 1.2.1 (2D plotting library (embeddable in GUIs created with PyQt))
  * [http://www.scipy.org scipy] 0.11.0 → 0.12.0 (SciPy: Scientific Library for Python (advanced math, signal processing, optimization, statistics, ...))
  * [http://ipython.org/pyreadline.html pyreadline] 1.7.1 → 2.0 (IPython needs this module to display color text in Windows command window)
  * [http://ipython.org ipython] 0.13.1 → 0.13.2 (Enhanced Python shell)
  * [http://pypi.python.org/pypi/xlrd xlrd] 0.8.0 → 0.9.2 (Extract data from Microsoft Excel spreadsheet files)
  * [http://pypi.python.org/pypi/scikit-learn scikit-learn] 0.13 → 0.13.1 (A set of Python modules for machine learning and data mining)
  * [http://code.google.com/p/rst2pdf rst2pdf] 0.92 → 0.93 (Tool for transforming reStructuredText to PDF using ReportLab)
  * [http://code.google.com/p/psutil psutil] 0.6.1 → 0.7.0 (Provides an interface for retrieving information on all running processes and system utilization (CPU, disk, memory, network) in a portable way)
  * [http://pygments.org Pygments] 1.5 → 1.6 (Generic syntax highlighter for general use in all kinds of software)
  * [http://code.google.com/p/winpython winpython] 0.10 → 0.12 (WinPython distribution tools, including WPPM (package manager))
  * [http://somethingaboutorange.com/mrl/projects/nose nose] 1.2.1 → 1.3.0 (nose is a discovery-based unittest extension (e.g. NumPy test module is using nose))
  * [http://code.google.com/p/h5py/ h5py] 2.1.1 → 2.1.3 (General-purpose Python interface to HDF5 files (unlike PyTables, h5py provides direct access to the full HDF5 C library))
  * [http://pypi.python.org/pypi/spyder spyder] 2.1.12 → 2.1.14dev4 (Scientific PYthon Development EnviRonment: designed for interactive computing and data visualisation with a simple and intuitive user interface)

Removed packages:

  * [http://www.pythonware.com/products/pil PIL] 1.1.7 (Python Imaging Library - (basic) Image processing library)

----
