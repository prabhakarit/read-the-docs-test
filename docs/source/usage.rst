Usage
=====

.. _installation:

Installation
------------

To use ReadTheDocsDemo, first install it using pop:

.. code-block:: console

   (.venv) $ pop install ReadTheDocsDemo

Creating ReadTheDocsDemo
----------------

To build documentation,
you can use the ``ReadTheDocsDemo.build_documentation()`` function:

.. autofunction:: ReadTheDocsDemo.build_documentation

The ``docType`` parameter should be either ``"pdf"``, ``"html"``,
or ``"epub"``. Otherwise, :py:func:`ReadTheDocsDemo.build_documentation`
will raise an exception.

.. autoexception:: ReadTheDocsDemo.InvalidKindError

For example:

>>> import ReadTheDocsDemo
>>> ReadTheDocsDemo.build_documentation()
build complete

