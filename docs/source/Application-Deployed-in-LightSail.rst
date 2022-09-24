Application-Deployed-in-LightSail
=====

.. _problem-statement:

Problem-statement
------------

Build and Run the MB Application in LightSail.

#.. code-block:: console

#   (.venv) $ pop install ReadTheDocsDemo

Pre-Requisites
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

Source Website Tech Stack
----------------

Migration Steps
----------------

Migration Outcome
----------------

Challenges
----------------

References
----------------
