isp-plugin-diraccess
====================

Documentation
--------
There is a bug in ISPmanager with scheme where nginx and apache+itk is used. Private directories are not accesible because config files passwd and .htaccess are created with wrong permissions. This plugin fixes the problem.

Installing
----------
> cp -v etc/ispmgr_mod_diraccess_fix.xml /usr/local/ispmgr/etc/

> cp -v addon/diraccess_fix_perms.py /usr/local/ispmgr/addon/

> killall -9 ispmgr

Questions?
----------

If you have questions or problems getting things
working, first try searching wiki.

If all else fails, you can email me and I'll try and respond as
soon as I get a chance.

        -- Andrey V. Scopenco (andrey@scopenco.net)     
