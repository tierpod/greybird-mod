# Greybird-mod
Light modification of Xubuntu Greybird theme for XFCE4:
* gtk2
* gtk3
* xfwm4
* xfce4-notifyd


## Screenshot
![Screenshot](screenshot.png)

* Squared xfwm4 theme
* Simple scrollbars
* Light panels, tooltips calendar widget
* Try with [evolvere icon theme](http://kde-look.org/content/show.php/Evolvere+Icon+theme?content=164181)


## Installation
Put greybird-mod to your ~/.themes directory

```bash
THEME=greybird-mod
xfconf-query -c xsettings -p /Net/ThemeName -s $THEME
xfconf-query -c xfwm4 -p /general/theme -s $THEME
xfconf-query -c xfce4-notifyd -p /theme -s $THEME
```
