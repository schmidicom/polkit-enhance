polkit-enhance
==============

rules
-----

**00-myadmins.rules**
Path: /etc/polkit-1/rules.d/
Description: Make "root" an all Member of UNIX-Group "adm" to Admins

actions
-------

**org.gentoo.portage.policy**
Path: /usr/share/polkit-1/actions/
Description: Add polkit Action for "emerge", "euse" and "etc-update"
