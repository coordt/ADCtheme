===============
Model Reference
===============


Data
====

.. py:data:: MAJOR_VERSION

   The major version.


Exception
=========

.. py:exception:: ExceptionName

   A major exception

Function
========

.. py:function:: format_exception(etype, value, tb[, limit=None])

   Format the exception with a traceback.

   :param etype: exception type
   :param value: exception value
   :param tb: traceback object
   :param limit: maximum number of stack frames to show
   :type limit: integer or None
   :rtype: list of strings


Decorator
=========

.. py:decorator:: removename

   Remove name of the decorated function.

.. py:decorator:: setnewname(name)

   Set name of the decorated function to *name*.

ModelName
=========

.. py:class:: ModelName

   .. py:attribute:: parent

      :py:class:`TreeForeignKey` ``(self)``

      The category's parent category. Leave this blank for an root category.

   .. py:attribute:: name

      **Required** ``CharField(100)``

      The name of the category.

   .. py:attribute:: slug

      **Required** ``SlugField``

      URL-friendly title. It is automatically generated from the title.

   .. py:attribute:: active

      **Required** ``BooleanField`` *default:* ``True``

      Is this item active. If it is inactive, all children are set to inactive as well.

   .. py:method:: format_exception(etype, value, tb[, limit=None])

      Format the exception with a traceback.

      :param etype: exception type
      :param value: exception value
      :param tb: traceback object
      :param limit: maximum number of stack frames to show
      :type limit: integer or None
      :rtype: list of strings

   .. py:staticmethod:: static_format_exception(etype, value, tb[, limit=None])

      Format the exception with a traceback.

      :param etype: exception type
      :param value: exception value
      :param tb: traceback object
      :param limit: maximum number of stack frames to show
      :type limit: integer or None
      :rtype: list of strings

   .. py:classmethod:: class_format_exception(etype, value, tb[, limit=None])

      Format the exception with a traceback.

      :param etype: exception type
      :param value: exception value
      :param tb: traceback object
      :param limit: maximum number of stack frames to show
      :type limit: integer or None
      :rtype: list of strings
