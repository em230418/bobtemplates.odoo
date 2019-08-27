bobtemplates.itpp.odoo
=================

``bobtemplates.itpp.odoo`` is a set of `mr.bob
<https://mrbob.readthedocs.io/en/latest/>`_
templates to use when developing Odoo addons.

It provides the following templates:

  * ``addon``: an addon skeletton, with optional OCA README and icon

In future:

  * ``model``: an Odoo model with accompanying form, tree, action, menu,
    demo data and ACL
  * ``test``: a test class
  * ``wizard``: a wizard with transient model, view and action

Install
~~~~~~~

  .. code:: shell

    pip install git+https://github.com/it-projects-llc/bobtemplates.odoo.git@master

Usage
~~~~~~~~~~~~~~~~~~~~~~~

* To create addon-template in current directory (interactive):

  .. code:: shell

    mrbob bobtemplates.itpp.odoo:addon

* To create addon-template in current directory (non-interactive):

  .. code:: shell

    mrbob bobtemplates.itpp.odoo:addon -n

* To create addon-template in "/path/to/directory"-folder (non-interactive):

  .. code:: shell

    mrbob -O /path/to/directory" bobtemplates.itpp.odoo:addon -n

Useful links
~~~~~~~~~~~~

* mr.bob readthedocs: https://mrbob.readthedocs.io/en/latest/index.html
* pypi page: https://pypi.python.org/pypi/bobtemplates.odoo
* code repository: https://github.com/acsone/bobtemplates.odoo
* report issues at: https://github.com/acsone/bobtemplates.odoo/issues

Credits
~~~~~~~

Author:

  * Stéphane Bidoul (`ACSONE <http://acsone.eu/>`_)

Inspired by https://github.com/plone/bobtemplates.plone.

Contributors:

  * Adrien Peiffer (`ACSONE <http://acsone.eu/>`_)
  * Olivier Laurent (`ACSONE <http://acsone.eu/>`_)
  * Mohamed Cherkaoui
  * Thomas Binsfeld (`ACSONE <http://acsone.eu/>`_)
  * Anvar Kildebekov (`IT-Projects LLC <https://it-projects.info/team/fedoranvar>`__)

Maintainer
----------

.. image:: https://www.acsone.eu/logo.png
   :alt: ACSONE SA/NV
   :target: http://www.acsone.eu

This module is maintained by ACSONE SA/NV.
