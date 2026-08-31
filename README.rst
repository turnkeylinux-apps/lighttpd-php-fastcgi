Lighttpd PHP FastCGI Configuration - with Adminer
=================================================

`Lighttpd`_ is a web server and load balancer optimized for
speed-critical environments while remaining standards-compliant, secure
and flexible. Lighttpd supports dynamic HTTP content such as PHP scripts
using the FastCGI interface.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Lighttpd configurations:
   
   - Lighttpd configured with FastCGI PHP support.
   - All components installed and maintained through Debian's package
     management system.

- MariaDB (drop-in MySQL replacement).
- TurnKey Web Control panel with links to useful references and
  resources.
- TLS support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses TLS).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL: username **root**
-  Adminer: username **adminer**

.. _Lighttpd: https://www.lighttpd.net
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: https://www.adminer.org
