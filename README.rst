Roowifi
=======

Roowifi is a module for issuing commands to and collecting data from Roomba robots via the RooWifi_ wifi-to-serial device.

Don't let your Roomba go unhacked!

Usage:
------

.. code-block:: bash

    $ python roowifi.py -h

It may also be imported directly, thus:

.. code-block:: pycon

    >>> import roowifi
    >>> roomba = Roomba('12.34.56.78')
    >>> roomba.clean()
    ...

Contribute:
-----------

#. It would be cool to expose more of the `iRobot SCI`_
#. Roomba discovery on the network, but without nasty dependencies
#. It would be super cool to give an option to host a connection the robots connect directly to, perhaps using twisted.

.. _RooWifi: http://roowifi.com
.. _iRobot SCI: http://www.irobot.com/images/consumer/hacker/Roomba_SCI_Spec_Manual.pdf
