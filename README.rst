======
hoodex
======


.. image:: https://img.shields.io/pypi/v/hoodex.svg
        :target: https://pypi.python.org/pypi/hoodex

.. image:: https://img.shields.io/travis/Ratxi/hoodex.svg
        :target: https://travis-ci.org/Ratxi/hoodex

.. image:: https://readthedocs.org/projects/hoodex/badge/?version=latest
        :target: https://hoodex.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status




Hoodex checks your plex instance and get the url of the latest uploaded content


* Free software: Apache Software License 2.0
* Documentation: https://hoodex.readthedocs.io.

Install
-------

Install using pip from pypi:

.. code-block:: sh

  pip install hoodex


Config
------

You can create a config.ini file with the following content:
.. code-block:: ini

  [hoodex]
  PlexUserName = your_user
  PlexPassword = your_password
  PlexServer = your_server
  PlexLibraries = Movies,TV


Features
--------

- Connect to your Plex Server and get the last added elements of a list of libraries

