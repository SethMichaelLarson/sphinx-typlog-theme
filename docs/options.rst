.. _options:

Options
=======

There are some options for you to configure the theme in ``conf.py``::

    html_theme_options = {}

logo
----

Put a logo file in your docs ``_static`` folder, e.g. the filename is
``logo.png``::

    html_theme_options = {
        'logo': 'logo.png'
    }

With logo configured, there will be a logo image on sidebar.

logo_name
---------

You can hide the name under your logo image with::

    html_theme_options = {
        'logo_name': 'false'
    }

description
-----------

Add a description under your logo and logo_name::

    html_theme_options = {
        'description': 'Your project description'
    }

color
-----

Add a theme color, it will be shown as the hover color for links etc::

    html_theme_options = {
        'color': '#E8371A'
    }

github
------

Configure your GitHub repo with ``github_user`` and ``github_repo``::

    html_theme_options = {
        'github_user': 'lepture',
        'github_repo': 'mistune'
    }

Remember to include the ``github.html`` template::

    html_sidebars = {
        '**': [
            'github.html',
            ...
        ]
    }

analytics_id
------------

Track your site with Google Analytics::

    html_theme_options = {
        'analytics_id': 'UA-xxx'
    }
