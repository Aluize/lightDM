LightDM config from:
/etc/lightdm/lightdm.conf

Change icon:
/var/lib/AccountsService/icons/

Change background:
/usr/share/backgrounds/gnome/

Problem solved:
Xinitrc does not exec wal with LightDM, create .xprofile and put wal -R on it
