# polkit-enhance
## rules
### 10-admin.rules
Path: /etc/polkit-1/rules.d/
Description: Make "root" and all member of UNIX-Group "wheel" to admins
https://wiki.gentoo.org/wiki/Polkit#Rules
https://wiki.archlinux.org/index.php/Polkit#Administrator_identities

## actions
### org.gentoo.portage.policy
Path: /usr/share/polkit-1/actions/  
Description: Add polkit action for "emerge", "euse" and "etc-update"

### org.gentoo.shell.policy
Path: /usr/share/polkit-1/actions/  
Description: Add polkit action for a root-Shell.

### org.gentoo.samba.policy
Path: /usr/share/polkit-1/actions/  
Description: Add polkit action for Samba-Tools that need root.

### org.gentoo.netdev.policy
Path: /usr/share/polkit-1/actions/  
Description: Add polkit action for Network-Tools that need root.
