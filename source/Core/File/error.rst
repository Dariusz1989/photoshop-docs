.. _File.error:

================================================
File.error
================================================

   :ref:`string` **error**


Description
-----------

A string containing a message describing the most recent file system error.

Typically set by the file system, but a script can set it. Setting this value clears any error message and resets the error bit for opened files. Contains the empty string if there is no error.