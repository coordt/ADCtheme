=====================
Sphinx specific stuff
=====================

note
====

.. note::

   This function is not suitable for sending spam e-mails.

warning
=======

.. warning::

   This function causes radioactive leaks and kills puppies.

versionadded
============

.. versionadded:: 2.5
   The *spam* parameter.

versionchanged
==============

.. versionchanged:: 2.6
   Now sends all spam back to sender.

deprecated
==========

.. deprecated:: 3.1
   Use :func:`spam` instead.

seealso
=======

.. seealso::

   Module :py:mod:`zipfile`
      Documentation of the :py:mod:`zipfile` standard module.

   `GNU tar manual, Basic Tar Format <http://link>`_
      Documentation for tar archive files, including GNU tar extensions.

rubric
======

.. rubric:: Rubric title

centered
========

.. centered:: LICENSE AGREEMENT

hlist
=====

.. hlist::
   :columns: 3

   * A list of
   * short items
   * that should be
   * displayed
   * horizontally

glossary
========

.. glossary::

   environment
      A structure where information about all documents under the root is
      saved, and used for cross-referencing.  The environment is pickled
      after the parsing stage, so that successive runs only need to read
      and parse new and changed documents.

   source directory
      The directory which, including its subdirectories, contains all
      source files for one Sphinx project.

productionlist
==============

.. productionlist::
   try_stmt: try1_stmt | try2_stmt
   try1_stmt: "try" ":" `suite`
            : ("except" [`expression` ["," `target`]] ":" `suite`)+
            : ["else" ":" `suite`]
            : ["finally" ":" `suite`]
   try2_stmt: "try" ":" `suite`
            : "finally" ":" `suite`

code-block
==========

.. code-block:: python
   :emphasize-lines: 3,5

   def some_function():
       interesting = False
       print 'This line is highlighted.'
       print 'This one is not...'
       print '...but this one is.'

abbr
====

Example: :abbr:`LIFO (last-in, first-out)`.

command
=======

The name of an OS-level command, such as :command:`rm` or :command:`rm -Rf /`

dfn
===

Mark the defining instance of a :dfn:`term` in the text. (No index entries are generated.)

guilabel
========

An accelerator key for the GUI label can be included using an ampersand; this will be stripped and displayed underlined in the output (example: :guilabel:`&Cancel`)

kbd
===

the same sequence should be marked as :kbd:`Control-x Control-f`


mailheader
==========

example: :mailheader:`Content-Type`

manpage
=======

A reference to a Unix manual page including the section, e.g. :manpage:`ls(1)`.

menuselection
=============

For example, to mark the selection “Start > Programs”, use this markup: :menuselection:`Start --> Programs`


sectionauthor
=============

.. sectionauthor:: Guido van Rossum <guido@python.org>

