Plain Server Client Quick Start
===============================

Rapid Framework consists of two different types of servers, Master and Client. Rapid Framework runs micro web servers
on each machine. The communication therefore, is TCP across each machine. We will discuss each servers' responsibilities
and structures in the follow Quick Start tutorial. This tutorial is to allow you to quickly spin up the master and client
without a lot of architecture. For a more robust build out, please see the UWSGIServerClient Quick Start.

Master Server
-------------

The Master server is quite easy to bring up.

    rapid

By default, the master server will listen on port 5000. It will also configure and write to a SQLite database.

Client Server
-------------

The Client server is quite easy to bring up as well.

    rapid -c

There are initial defaults that should just work without any configuration. For further configuration, please see the
:ref:`Configuration` section.