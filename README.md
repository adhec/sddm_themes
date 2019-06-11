# IttuSddm themes

A project to animate your login manager

<iframe width="753" height="380" src="https://www.youtube.com/embed/1y0nYQPsREo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen autoplay="1"></iframe>

### Ittu https://www.opendesktop.org/p/1303587/

[![screen](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/ittu_bottom_cut.jpg)](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/ittu_bottom.jpg)

### Ittu_bottom https://www.opendesktop.org/p/1309044/

[![screen](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/ittu_cut.jpg)](https://git.opendesktop.org/adhe/ittusddm/raw/master/images/ittu.jpg)

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

Search, select (or place) your favorite animation (square shape) in:

```bash
/usr/share/sddm/themes/ittu/components/artwork/gifs/
```

the gif for your user is **USER.gif** where USER is your user name, 

```bash
#Example to use animation 7.gif  
cd /usr/share/sddm/themes/ittu/components/artwork/gifs/
sudo cp 7.gif $(whoami).gif
```



<iframe width="753" height="300" src="https://www.youtube.com/embed/gZd6tnqD3u0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

* All animations from *giphy*

### 3 Customization

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

## 4 Test our Look & Feel

Neve (snow)  look & feel for Plasma

<span style="color:red"> **- Look & Feel **  </span> install from 
[ SystemSettings > Look and Feel > Get New Theme > Search "Neve" > Install  ]

# Coffee

Thanks for all the support :coffee: . If you liked my job please rate the project in opendesktop  (above in the + symbol). Or better yet

send me a coffee :)  from [Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=V9Q8MK9CKSQW8&source=url)

[<img src="https://git.opendesktop.org/adhe/oie/raw/master/images/donate.png"  style="width:150px;">](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=V9Q8MK9CKSQW8&source=url) 

Have fun ;)

## old version

<iframe width="300" height="200" src="https://www.youtube.com/embed/gZd6tnqD3u0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

