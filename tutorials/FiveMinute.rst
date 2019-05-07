Five Minute Tutorial
====================

This tutorial should get you up and running in five minutes.
Hopefully it will be quick.

Getting Started
---------------
We highly recommend that you run rapid within a virtual environment.
To do this, please install whichever version of Python, 2.7 or 3.x,
onto your machine.

- Install Virtualenv
.. code-block:: sh
   :1:

   pip install virtualenv

- Create virtualenv
.. code-block:: sh
   :1:

   virtualenv venv

- Activate virtualenv
.. code-block:: sh
   :1:

   . /venv/bin/activate

- Install Rapid-framework
.. code-block:: sh
   :1:

   pip install rapid-framework

- Create a configuration
.. code-block:: sh
   :1:

   rapid --create-config master > master.cfg

- Bring the Server up
.. code-block:: sh
   :1:

   rapid -f master.cfg

- Configure the Server to run files

  - Add a Pipeline

  - Add a vcs (connect pipeline to the vcs)
- Point Github to the Server `http://<server>/api/github/webhooks`

Enjoy!
