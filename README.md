#arfedora-plymouth-theme
This is plymouth theme for Fedora Linux



#Screenshot

![Alt text](https://raw.githubusercontent.com/yucefsourani/arfedora-plymouth-theme/master/screenshot.png "Screenshot")



##Installing
tested only on Fedora 23 64bit

* Install deps
  * sudo dnf install plymouth-theme-script git

* clone repo
  * cd ~/Downloads && git clone https://github.com/yucefsourani/arfedora-plymouth-theme.git

* copy theme folder to /usr/share/plymouth/themes
  * sudo cp -r  ~/Downloads/arfedora-plymouth-theme /usr/share/plymouth/themes

* set theme
  * sudo plymouth-set-default-theme arfedora-plymouth-theme -R

* rebuild initramfs
  * sudo dracut --force



##Based on

darwin plymouth theme
http://gnome-look.org/content/show.php/Darwin+Plymouth?content=170649


##arfedora blog

http://arfedora.blogspot.com/


##LICENSE

GPL


