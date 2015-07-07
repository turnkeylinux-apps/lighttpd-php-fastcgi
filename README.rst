Lighttpd PHP FastCGI Configuration - with Adminer
=================================================

`Lighttpd`_ is a web server and load balancer optimized for
speed-critical environments products while remaining
standards-compliant, secure and flexible. It is used by many
high-traffic websites, including Youtube. Lighttpd supports dynamic HTTP
content such as PHP scripts using the FastCGI interface.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Lighttpd configurations:
   
   - Lighttpd configured with FastCGI PHP support.
   - All components installed and maintaiend through the package
     management system.

- TurnKey Web Control panel with links to useful references and
  resources.
- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL, phpMyAdmin: username **root**


.. _Lighttpd: http://www.lighttpd.net
.. _TurnKey Core: http://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org
