# polkit-enhance
## rules
### 00-myadmins.rules
Path: /etc/polkit-1/rules.d/  
Description: Make "root" and all member of UNIX-Group "wheel" to admins  
https://wiki.archlinux.org/index.php/Polkit#Administrator_identities

## actions
### org.gentoo.portage.policy
Path: /usr/share/polkit-1/actions/  
Description: Add polkit action for "emerge", "euse" and "etc-update"

### org.gentoo.shell.policy
Path: /usr/share/polkit-1/actions/  
Description: Add polkit action for "bash", for example to use in an profile on KDE Konsole

### org.gentoo.samba.policy
Path: /usr/share/polkit-1/actions/
Description: Add polkit action for "wbinfo", it need root for authenticate user.
