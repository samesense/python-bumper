========
Overview
========

Bump container version

* Free software: MIT license

Installation
============

::

    pip install bumper

You can also install the in-development version with::

    pip install git+ssh://git@python-bumper/samesense/python-bumper.git@master

Documentation
=============


https://python-bumper.readthedocs.io/


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
