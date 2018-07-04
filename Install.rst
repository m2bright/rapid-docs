Installing Rapid Framework
==========================

Installing from source
----------------------

To build uWSGI you need Python.  We recommend that you install the package under
a python virtualenv.

To install the full package:

.. code-block:: sh

   pip install rapid-framework

To install the Master specific packages:

.. code-block:: sh

   pip install rapid-framework[master]

To install the Client specific packages:

.. code-block:: sh

   pip install rapid-framework[client]


Configuration
-------------

To run Rapid, you will need a configuration file. You can create that file by
running:

.. code-block:: sh

   rapid --generate-config

For further information, look at :doc:`Configuration`
