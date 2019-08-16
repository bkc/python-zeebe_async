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
.. |docs| image:: https://readthedocs.org/projects/python-zeebe_async/badge/?style=flat
    :target: https://readthedocs.org/projects/python-zeebe_async
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/bkc/python-zeebe_async.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/bkc/python-zeebe_async

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/bkc/python-zeebe_async?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/bkc/python-zeebe_async

.. |requires| image:: https://requires.io/github/bkc/python-zeebe_async/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/bkc/python-zeebe_async/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/bkc/python-zeebe_async/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/bkc/python-zeebe_async

.. |version| image:: https://img.shields.io/pypi/v/zeebe_async.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/zeebe_async

.. |commits-since| image:: https://img.shields.io/github/commits-since/bkc/python-zeebe_async/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/bkc/python-zeebe_async/compare/v0.0.1...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/zeebe_async.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/zeebe_async

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/zeebe_async.svg
    :alt: Supported versions
    :target: https://pypi.org/project/zeebe_async

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/zeebe_async.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/zeebe_async


.. end-badges

Async Zeebe Client

* Free software: Apache Software License 2.0

Installation
============

::

    pip install zeebe_async

Documentation
=============


https://python-zeebe_async.readthedocs.io/


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
