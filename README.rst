=================
django-menu-proxy
=================

Allow you to build different menus and breadcrumbs over objects with differect types on your site.

Installation:
=============

In settings.py:
---------------

1. Add ``menuproxy`` to your ``INSTALLED_APPS``.

2. Set ``MENU_PROXY_SETTINGS`` variable. To learn about how to use it read source code of example project.

Usage:
======

In your templates:
------------------

1. Load ``menuproxy_tags`` templatetag::

    {% load menuproxy_tags %}

2. To show menu use::

    {% show_main_menu <rule> <object> %}

or::

    {% show_full_menu <rule> <object> %}

or::

    {% show_auto_menu <rule> <object> %}

3. To show breadcrumbs use::

    {% show_breadcrumbs <rule> <object> %}

To learn more about usage read source code of example project.
