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

* MB Application Zip File.
* AWS Account with Free Tier Access .
* Chrome Browser for using lighthouse Extension.
* Demo Website to migrate http://www.mercedes-benz-versicherung.de
* Basic Knowledge of AWS
* IntelliJ or any Framework which support React
* Install Node Js, NPM & React js
* Home Brew
* Docker

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

* JQuery.
* Google Maps.
* UserCentrics.

Migration Steps
----------------
#. Test local run of the application.
  * Unzip the MB application file and open it with Framework which you are using. 
  * install webpack using brew 
  * install babel using brew 
  * npm install --save-dev babel-loader @babel/core @babel/preset-env webpack 
  * npm run build 
  * npm install http-server -g 
  * npm start 
  * npx http-server  
  * You should see the application is started. 
  * You could see the below kind of links to access the application. 
  * Available on: 
    * http://127.0.0.1:9999
    * http://10.0.0.4:9999

Migration Outcome
----------------

Challenges
----------------

References
----------------
