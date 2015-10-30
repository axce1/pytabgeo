Overview
--------

Tabgeo - a special geolocation database to determine country of the user according to his IP-address.
Py2 and Py3 driver for tabgeo.com


Installation
------------

$pip install pytabgeo

or

$ python setup.py install

Usage:
______

Example usage:

    >>> import pytabgeo
    >>> pytabgeo.getCode('8.8.8.8')
    'US'

    $ python3 pytabgeo.py 8.8.8.8
    IP address: 8.8.8.8 
    Country code: US
