Async-Slumber |build-status| |coverage-status| |docs|
===============================================

Slumber is a Python library that provides a convenient yet powerful
object-oriented interface to ReSTful APIs. It acts as a wrapper around the
excellent aiohttp_ library and abstracts away the handling of URLs, serialization,
and request processing.

.. _aiohttp: http://aiohttp.readthedocs.io/en/stable/

QuickStart
==========

1. Install Slumber::

    $ pip install slumber

2. Install Optional Requirement::

    pip install pyyaml

3. Use Slumber!

Requirements
============

Slumber requires the following modules.

* Python 2.5+
* aiohttp
* pyyaml (If you are using the optional YAML serialization)

.. |build-status| image:: https://travis-ci.org/samgiles/slumber.svg?branch=master
   :target: https://travis-ci.org/samgiles/slumber
   :alt: Build status
.. |coverage-status| image:: https://img.shields.io/coveralls/samgiles/slumber.svg
   :target: https://coveralls.io/r/samgiles/slumber
   :alt: Test coverage percentage
.. |docs| image:: https://readthedocs.org/projects/slumber/badge/?version=latest
   :target: http://slumber.readthedocs.org/
   :alt: Documentation
