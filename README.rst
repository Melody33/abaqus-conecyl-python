Introduction
============

This repository has been incorporated as part of the
`desicos repository <https://github.com/saullocastro/desicos>`_.

DESICOS is an European Project studying the Knock-Down Factors used in the
Space Industry for te design of cylindrical and conical structures
(rocket science...).

www.desicos.eu

This repository contains the plug-ins used along the project for the studies
comparing geometric imperfections, load imperfections, stochastic analysis and
so on.


0. Download
-----------

::

    $ git clone git://github.com/saullocastro/desicos.git


1. Documentation and usage
--------------------------

1.1 Abaqus plug-ins
-------------------

The user-friendly way to use the plug-in is through the graphic interface.
Just execute the file `START_GUI.bat`.
You need Abaqus to be executable by the command line `abaqus cae`
for this to work.

You can access all and more fuctionalities from the Python IDE in Abaqus::

    >>> from desicos.abaqus.conecyl import ConeCyl
    >>> cc = ConeCyl()
    >>> cc.fromDB('huehne_2008_z07')
    >>> cc.create_model()

See more examples of how to access the Python functionalities in the folder
`desicos.abaqus.studies`.

3. Licensing
------------

The new BSD License (`see the LICENSE file for details 
<https://raw.github.com/saullocastro/abaqus-conecyl-python/master/LICENSE/>`_)
covers all files in the compmech repository unless stated otherwise.

