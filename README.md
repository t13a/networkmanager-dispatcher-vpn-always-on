
networkmanager-dispatcher-vpn-always-on
=======================================

About
-----

TODO

Requirements
------------

-  `NetworkManager`

Installation
------------

    # cp vpn-always-on vpn-always-on.conf /etc/NetworkManager/dispatcher.d
    #
    # cd /etc/NetworkManager/dispatcher.d
    # chown root:root vpn-always-on vpn-always-on.conf
    # chmod 755 vpn-always-on vpn-always-on.conf
    #
    # cd /etc/NetworkManager/dispatcher.d/pre-down.d
    # ln -s ../vpn-always-on .
    # ln -s ../vpn-always-on.conf .
