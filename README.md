ploneedu_demos.suite
====================

Features
--------

PloneEdu suite includes some Plone products and configurations like these:


Development installation
------------------------

To get a basic development installation running follow the steps below: ::

    $ git clone git@github.com:plone-ve/ploneedu_demos.suite.git
    $ cd ploneedu_demos.suite
    $ python bootstrap.py
    $ bin/buildout -vvvvvvvvN

CMFBibliographyAT dependency
----------------------------

``CMFBibliographyAT`` requires some utils to Convert between bibliographic data formats. Before you need to set up the ``bibutils`` package. ::

    # aptitude install bibutils