=================
Installing Cuckoo
=================

Proceed with download and installation.

Create a user
=============

Even if you obviously can run Cuckoo with your current user, creating a dedicated
one is always a good practice.

Create a new user::

    $ sudo adduser cuckoo

Make sure the new user belongs to the "vboxusers" group (or the group you used to
run VirtualBox)::

    $ sudo useradd -G vboxusers cuckoo

Download Cuckoo
===============

You can get your copy of Cuckoo from the `official website`_ or from our
`git repository`_.

Please notice that the archives to be downloaded from the website are core
releases, while the version on git has to be considered an **under
development** stage, therefore possibly unstable and not yet fully documented.

.. _official website: http://www.cuckoobox.org
.. _git repository: https://github.com/cuckoobox/cuckoo

Install it
==========

Extract or checkout your copy of Cuckoo to a path of your choice and you're
ready to go ;-).

