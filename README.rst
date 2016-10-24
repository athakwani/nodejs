This dupper template repository is for Node.js + Mongodb.

Node.js
=======

This template install npm & bower packages for your git project.  

.. code-block:: bash

  dupper dup --name=nodejs --template-from=https://github.com/athakwani/nodejs GITURL  
    
Ports
=====

Following ports are opened by default. Additional ports can be opened with -p external_port:interal_port option to dup command.

* 3000 - Default port for project
* 8000 - For node debugger
* 8080 - For Cloud 9 dev environment


Commands
========

This template implements below command interface.

* build - Run npm build

.. code-block:: bash

    Usage:
    dupper exec nodejs build

* start - Run npm start

.. code-block:: bash

    Usage:
    dupper exec nodejs start

* test - Run npm test mean stack

.. code-block:: bash

    Usage:
    dupper exec nodejs stop

* debug - Start node debugger

.. code-block:: bash

    Usage:
    dupper exec nodejs debug

* c9 - Start Cloud 9 SDK
    
.. code-block:: bash

    Usage:
    dupper exec nodejs c9

* heroku-deploy - Deploy on Heroku
    
.. code-block:: bash

    Usage:
    dupper exec nodejs heroku-deploy

* heroku-delete - Delete Heroku app
    
.. code-block:: bash

    Usage:
    dupper exec nodejs heroku-delete
