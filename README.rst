========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-softflo-fin-jour/badge/?style=flat
    :target: https://readthedocs.org/projects/python-softflo-fin-jour
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/daveboyd777/python-softflo-fin-jour.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/daveboyd777/python-softflo-fin-jour

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/daveboyd777/python-softflo-fin-jour?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/daveboyd777/python-softflo-fin-jour

.. |requires| image:: https://requires.io/github/daveboyd777/python-softflo-fin-jour/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/daveboyd777/python-softflo-fin-jour/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/daveboyd777/python-softflo-fin-jour/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/daveboyd777/python-softflo-fin-jour

.. |version| image:: https://img.shields.io/pypi/v/fin-jour.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/fin-jour

.. |wheel| image:: https://img.shields.io/pypi/wheel/fin-jour.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/fin-jour

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/fin-jour.svg
    :alt: Supported versions
    :target: https://pypi.org/project/fin-jour

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/fin-jour.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/fin-jour

.. |commits-since| image:: https://img.shields.io/github/commits-since/daveboyd777/python-softflo-fin-jour/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/daveboyd777/python-softflo-fin-jour/compare/v0.1.0...master



.. end-badges

Financial journaling from statements.

* Free software: ISC license

Installation
============

::

    pip install fin-jour

You can also install the in-development version with::

    pip install https://github.com/daveboyd777/python-softflo-fin-jour/archive/master.zip


Documentation
=============


https://python-softflo-fin-jour.readthedocs.io/


Development
===========

To run all the tests run::

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
