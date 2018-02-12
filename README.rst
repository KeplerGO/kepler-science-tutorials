====================================================
Welcome to kepler-science-tutorials's documentation!
====================================================

**kepler-science-tutorials** are a set of easy to follow tutorials for doing science with Kepler and K2 data. They are in the form of jupyter notebooks, which can be exported as pdfs and slides for you to use offline and with your team. They are split into broad categories for specific areas such as exoplanets_ and supernovae_.

.. _exoplanets: link
.. _supernovae: link

These tutorials require you to have Python installed to run. If you do not have a version of Python installed we recommend you use Anaconda, which will also install most of the package dependencies for these tutorials. You can find information on installing python with Anaconda on your machine here_.

.. _here: https://conda.io/docs/user-guide/install/index.html

Running these tutorials will require at least the following

* Python: 2.7, 3.5, 3.6 or later.
* lightkurve_
* astropy_ 1.3 or later.
* numpy: 1.11.3 or later.
* scipy: 0.17 or later.
* matplotlib: 1.5.3 or later.

.. _astropy: http://www.astropy.org/
.. _lightkurve: http://lightkurve.keplerscience.org/

You can install all these dependencies using pip_ by typing the following command into your terminal for Linux and OSX, or into the `Anaconda Prompt`__ for windows::

  $ pip install lightkurve astropy numpy scipy matplotlib

.. __: https://conda.io/docs/user-guide/install/windows.html) for windows
.. _pip: https://pip.pypa.io/en/stable/user_guide/

Some of these notebooks are direct copies of notebooks from **lightkurve**, **PyKE** and other topics. (Such as basic tutorials on opening files and querying MAST.)

**************
Acknowledgment
**************

**kepler-science-tutorials** is a community project supported by the
`Kepler/K2 Guest Observer Office <https://keplerscience.arc.nasa.gov>`_.
The code development happens `on GitHub <https://github.com/KeplerGO/kepler-science-tutorials>`_.
