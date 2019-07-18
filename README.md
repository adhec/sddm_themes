# IttuSddm themes

A project to animate your login manager

<iframe width="753" height="380" src="https://www.youtube.com/embed/1y0nYQPsREo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen autoplay="1"></iframe>

### Basic configurations

Edit the file  **/usr/share/sddm/themes/ittu/theme.conf** 

```bash
background=components/artwork/background.jpg  #path to file 
blur=true                #true or false, enable blur effect
blurRadius=100           #from 0 to 100, radius of blur 

shape=circle             #circle or rectangle, shape of avatars
avatarTransparent=false  #true or false, draw background 
avatarColor="#f5f5f5"    #background of animations

factorSizeAvatar=0.8     #size of avatars
```
For another theme replace ittu by the name of theme
<span style="color:red"> **- Themes **  </span>  **ittu, ittu_c, ittu_bottom, ittu_bottom_c**

---

### Ittu 

[https://www.opendesktop.org/p/1303587/](https://www.opendesktop.org/p/1303587/)

[![screen](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/ittu_cut.jpg)](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/ittu.jpg)

### Ittu_bottom 

[https://www.opendesktop.org/p/1309044/](https://www.opendesktop.org/p/1309044/)

[![screen](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/ittu_bottom_cut.jpg)](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/ittu_bottom.jpg)

### 1 Installation, for another theme replace ittu by the name of theme

<span style="color:red"> **- Themes **  </span>  **ittu, ittu_c, ittu_bottom, ittu_bottom_c**

Choose: 

#### - From Plasma KDE

Install from Plasma SystemSettings: select ittu or ittu_bottom

```bash
[ SystemSettings > Startup and Shutdown > LoginScreen(SDDM) > GetNew > Search: ittu > Install ]
```

#### - Or download 

Download [here](https://www.opendesktop.org/p/1303587/) the file *ittu.tar.gz*  and run from your terminal

```bash
sudo tar -xvf ~/Downloads/ittu.tar.gz -C /usr/share/sddm/themes
```
for [Ittu_bottom](https://www.pling.com/p/1309044/)  replace **ittu.tar.gz** by **ittu_bottom.tar.gz**

### 2 Usage

Select the theme from the SystemSettings of plasma KDE

SystemSettings  ~> Startup and Shutdown ~> select *ittu* and click on Apply button

### 2.1 Change animation GIF

Use the dolphin [menu service](https://www.pling.com/p/1313714/)

```bash
#Installation
Dolphin > Menu Settings > Configure Dolphin > 
... Services > Search "menu set" > Install "Menu set Login Manager gif" 

# Use
Right click on gif > Action > Set as Login SDDM gif
```

![menu service](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/menu.png)

* All animations from *giphy*

---


### Test our Look & Feel for lock screen and more animations

[PearLight](https://www.pling.com/p/1313727/) and [PearDark](https://www.pling.com/p/1313728/)

Video and more details in https://adhec.github.io/plasma_tweaks/

[![pear](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/pear.png)](https://adhec.github.io/plasma_tweaks/)

### Coffee

Thanks for all the support. If you like what I do,
Share your ❤️ Buy me a ☕

[<img src="https://www.paypalobjects.com/webstatic/en_US/i/buttons/PP_logo_h_100x26.png"  style="width:72px;">](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=V9Q8MK9CKSQW8&source=url)  or  [<img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg">](https://liberapay.com/_adhe_/donate)

Have fun ;)

