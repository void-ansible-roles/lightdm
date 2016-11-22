lightdm
=======


What is does this role do?
--------------------------

This role installs and enables the lightdm display manager.  To use this role you need to install at least one graphical environment.


Meta
----

Files Managed:
  * /usr/share/ligthdm/lightdm.conf.d/
  * /var/service/lightdm

Defaults Provided:
  * None

Variables Required:
  * None

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * [xorg](https://github.com/void-ansible-roles/xorg)
  * [dbus](https://github.com/void-ansible-roles/dbus)
