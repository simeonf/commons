.. documentation master file, created by
   docbird
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

twitter.commons Python Docs
===========================

`twitter.commons <https://github.com/twitter/commons>`_ contains common
libraries in use at Twitter for Python and the JVM. 

These pages document the Python side of things (the code found
`src/python/twitter/common`). `twitter.commons` uses `Pants <http://pantsbuild.github.io/>`_ as its
build system. If you've never used pants be sure to read the `Pants Tutorial
<http://pantsbuild.github.io/first_tutorial.html>`_ and complete the `Pants/Python tutorial
<http://pantsbuild.github.io/python-readme.html>`_.

.. py:module:: twitter.common

`twitter.common` contains an :ref:`twitter.common.app` class you
should use for your applications. The app structure includes the idea
of a module and `twitter.common` comes with a variety of pre-built
modules you can include in your application.

.. toctree::
   :maxdepth: 2

   app
   module

`twitter.common` also contains various libraries that may be useful in writing your application or service.

.. toctree::
   :maxdepth: 2
   
   collections
   concurrent
   confluence
   contextutil
   dirutil
   filesystem
   git
   lang
   log
   metrics
   net
   python
   quantity
   reviewboard
   rpc
   string
   zookeeper
   styleguide
   
   

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
