========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - |
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-ptvsd-ez/badge/?style=flat
    :target: https://readthedocs.org/projects/python-ptvsd-ez
    :alt: Documentation Status


.. |version| image:: https://img.shields.io/pypi/v/ptvsd-ez.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/ptvsd-ez

.. |commits-since| image:: https://img.shields.io/github/commits-since/nwinocur/python-ptvsd-ez/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/nwinocur/python-ptvsd-ez/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/ptvsd-ez.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/ptvsd-ez

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/ptvsd-ez.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/ptvsd-ez

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/ptvsd-ez.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/ptvsd-ez


.. end-badges

A library for making simple-case usage of the Python Tools Visual Studio Debug server even easier, when you don't need
fine control over all the fiddly options.

* Free software: MIT license

Installation
============

::

    pip install ptvsd-ez

Documentation
=============


https://python-ptvsd-ez.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
