
nm-vpn-o-matic
==============

About
-----

TODO

Requirements
------------

-  `NetworkManager`

Installation
------------

    # cp nm-vpn-o-matic* /etc/NetworkManager/dispatcher.d
    # chown root:root /etc/NetworkManager/dispatcher.d/nm-vpn-o-matic*
    # chmod 755 /etc/NetworkManager/dispatcher.d/nm-vpn-o-matic*
    # ln -s ../nm-vpn-o-matic /etc/NetworkManager/dispatcher.d/pre-down.d/nm-vpn-o-matic
    # ln -s ../nm-vpn-o-matic.conf /etc/NetworkManager/dispatcher.d/pre-down.d/nm-vpn-o-matic.conf

License
-------

TODO
