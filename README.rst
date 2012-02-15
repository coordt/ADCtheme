==============
How To Install
==============

Install in Sphinx
-----------------

Copy this directory into the ``sphinx/themes`` directory where Sphinx is installed. For example, a standard install of sphinx on Mac OS X is at ``/Library/Python/2.6/site-packages/``

Install Somewhere Else
----------------------

If you want to install this theme somewhere else, you will have to modify the ``conf.py`` file. ::

    templates_path = ['/absolute/path/to/dir/','relative/path/']

Install Directly in Your Documentation
--------------------------------------

If you want to include the files directly in the documentation, so another person can build your documentation, it is easy.

 1. Copy over everything in the ``static`` directory into the ``_static`` directory of your documentation's source folder.

 2. Copy the ``layout.html`` file into the ``_templates`` directory of your documentation's source folder.

 3. Alter your ``conf.py`` ::

        html_theme = 'basic'
        html_style = 'adctheme.css'

    instead of ``'ADCtheme'``.


Making Sphinx Use the Theme
---------------------------

If you aren't installing the files directly into your documentation, edit the ``conf.py`` file and make the following setting: ::

    html_theme = 'ADCtheme'

Screen Shots
------------

.. image:: https://github.com/coordt/ADCtheme/raw/master/static/scrn1.png

.. image:: https://github.com/coordt/ADCtheme/raw/master/static/scrn2.png

To Do
-----

 * Gotta get the javascript working so the Table of Contents is hide-able.
 * Probably lots of css cleanup.