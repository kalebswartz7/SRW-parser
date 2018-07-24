===================
SRW-parser
===================
.. image:: https://travis-ci.com/kalebswartz7/SRW-parser.svg?branch=master
    :target: https://travis-ci.com/kalebswartz7/SRW-parser

Reads in a data file and vizualizes data with image along with interactive horizontal and vertical cuts 

Installation:
-------------
Lightweight installation with only data parsing capabilities - 
::

    pip install SRW-parser
Full installation with graphing capabilities - 
:: 

    pip install "SRW-parser[complete]"

Features:
--------

* User can specify specific data file
::

    SRW-parser -d <file_name>
    
* User can specify if they want the data to be graphed with an interactive plot showing horizontal and vertical cuts 
::

    SRW-parser -d <file_name> -g


Credits:
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
