PloneEdu demo suite
====================

The idea with this buildout configuration is show install
a Plone latest version with the commons and usefull 
third-party add-ons Plone for education sector.


Features
========

PloneEdu suite includes some Plone products and configurations 
like these:

- 

- 

- 

Development installation
------------------------

To get a basic development installation running follow the steps 
below: ::

    $ git clone git@github.com:plone-ve/ploneedu_demos.suite.git
    $ cd ploneedu_demos.suite
    $ python bootstrap.py
    $ bin/buildout -vvvvvvvvN

CMFBibliographyAT dependency
----------------------------

``CMFBibliographyAT`` requires some utils to Convert between 
bibliographic data formats. Before you need to set up the 
``bibutils`` package. ::

    # aptitude install bibutils

Links
=====

- Github project repository: https://github.com/plone-ve/ploneedu_demos.suite

- Issue tracker: https://github.com/plone-ve/ploneedu_demos.suite/issues

Licensing
=========

This Plone distribution is released under GPL Version 2.

``ploneedu_demos.suite`` is licensed under GNU General Public License, version 2.

.. image:: https://cruel-carlota.pagodabox.com/47108caebd3b96f110cd90b5044b34d6
   :alt: githalytics.com
   :target: http://githalytics.com/plone-ve/ploneedu_demos.suite