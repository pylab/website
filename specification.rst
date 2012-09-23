The Pylab specification
=======================

Python Distributions promoting themselves as providing Pylab should meet the
requirements listed below.

This specification is versioned, so it can be updated. The current version is
**Pylab 2.0**.

Components
----------

- Python (2.x >= 2.6 or 3.x >= 3.2)
- Numpy (>= 1.5)
- Scipy (>= 0.10)
- Matplotlib (>= 1.1)
- IPython (>= 0.12)
- SymPy          Versions still to be determined.
- pandas
- StatsModels
- scikits-learn
- scikits-image
- PyTables
- NetworkX

.. note::

  At the time of writing, some of the packages listed above are not yet
  Python 3 compatible, so it is not possible to meet this specification using
  Python 3. We hope that this will be fixed soon.

Other requirements
------------------

After installation, entering ``ipython`` in a terminal/command prompt should
start IPython, and it should be possible to import any of the packages specified
above. Distributions are welcome to also provide other shortcuts, menu entries,
and interfaces such as IDEs.

The user should be able to install arbitrary extra Python packages into the
distribution.
