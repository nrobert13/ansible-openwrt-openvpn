openwrt-openvpn
==============

configure openvpn aspects of your openwrt system.

Role Variables
--------------

hostname

Dependencies
------------

[openwrt-uci]

Example Playbook
----------------

Requirements
------------

must be kept minimal as this is supposed to run on openwrt embedded
systems. in particular we try get by with plain POSIX shell, using
neither python nor bash in any way. lua could be an option as that
seems to be the openwrt scripting language of choice.

License
-------

BSD

Author Information
------------------

Robert Nemeti, 


[http://wiki.openwrt.org/doc/uci/system]: http://wiki.openwrt.org/doc/uci/system
