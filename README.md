Odoo - Open Source ERP & CRM (formerly OpenERP)
=============================

The main Odoo Apps include an Open Source CRM, Website Builder,
eCommerce, Project Management, Billing & Accounting, Point of Sale,
Human Resources, Marketing, Manufacturing, Purchase Management

Odoo Apps can be used as stand-alone applications, but they also
integrate seamlessly so you get a full-featured Open Source ERP 
when you install several Apps.

This appliance includes all the standard features in `TurnKey Core`_,

- `Odoo`_ v8 installed from upstream GIT source
- Includes all base modules from base install of Odoo
- SSL support out of the box.
- `Adminer`_ administration frontend for PostgreSQL (listening on
  port 12322 - uses SSL).
- Webmin modules for configuring Apache2, PHP and PostgreSQL.


Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH: username **root**
-  PostgreSQL, Adminer: username **postgres**

.. _Odoo: https://github.com/odoo/odoo
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org/
