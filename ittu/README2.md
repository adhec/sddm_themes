# IttuSddm

A project to animate your login manager

[![screen](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/img.png)](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/img02.png)

### Installation 

Install from Plasma SystemSettings: 

```bash
[ SystemSettings > Startup and Shutdown > LoginScreen(SDDM) > GetNew > Search: ittu > Install ]
```


or download the file *ittu.tar.gz*  and run from your terminal

```bash
sudo tar -xvf ~/Downloads/ittu.tar.gz -C /usr/share/sddm/themes
```

### Usage

Select the theme from the SystemSettings of plasma KDE

SystemSettings  ~> Startup and Shutdown ~> select *ittu* and click on Apply button

### Change animation GIF

Search, select (or place) your favorite animation (square shape) in:

```bash
/usr/share/sddm/themes/ittu/components/artwork/gifs/
```

the gif for your user is **$USER.gif** where $USER is your user name, 

```bash
#Example to use animation 7.gif  
cd /usr/share/sddm/themes/ittu/components/artwork/gifs/
sudo cp 7.gif $(whoami).gif
```

* All animations from *giphy*

### Basic configurations

Edit the file  **/usr/share/sddm/themes/ittu/theme.conf** 

```bash
background=components/artwork/background.jpg  #path to file 
blur=true                #true or false, enable blur effect
blurRadius=30            #from 0 to 100, radius of blur 

shape=circle             #circle or rectangle, shape of avatars
avatarTransparent=false  #true or false, draw background 
avatarColor="#dcdcdc"    #background of animations

factorSizeAvatar=0.75    #size of avatars
```



## Test our Look & Feel

Neve (snow)  look & feel for Plasma

<span style="color:red"> **- Look & Feel **  </span> install from 
[ SystemSettings > Look and Feel > Get New Theme > Search "Neve" > Install  ]

[![screen](https://git.opendesktop.org/adhe/focusicons/raw/master/images/light01.png)](https://www.pling.com/p/1304251/)

or Download [here](https://www.pling.com/p/1304251/)


### Coffee

Thanks for all the support :coffee: . If you liked my job please Pling <img src="https://www.opendesktop.org/images/system/pling-btn-hover.png" alt="pling" style="width:28px;" /> the project or/and rate  (above in the + symbol) or/and make a donation [here](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=V9Q8MK9CKSQW8&source=url) [<img src="https://git.opendesktop.org/adhe/oie/raw/master/images/donate.png"  style="width:72px;">](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=V9Q8MK9CKSQW8&source=url) Have fun ;)



