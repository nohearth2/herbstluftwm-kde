# herbstluftwm-kde
If you are looking to run  herbstluftwm  with kde  this bring  herbstluftwm to KDE 
Xorg only 

my systeam 
Arch linux - arcolinux 
KDE Plasma 5
Kerbstulftwm 


other note Think like D-menu work along with the kde menu 
keybinding in kerbstluftwm work with in kde  more testing is need for keybinds 
 the config file im useing is the from acro-linux for kerbstluftwm  and kde  you might need to change the file path for othe Linux distor   


this just a X-seeseon that let you  use both kerbstluftwm  and kde togther 

place the new X-seeson filre in /usr/share/xsessions 

you can download the github file and cp in your /usr/share/xsessions 
by useing  cp your  download fiel path to /usr/share/xsessions  
 
 

Note there has been no change to config file  that come with from herbstluftwm for 


this still need testing i think config file herstilftwn can be change ![2021-08-02_20-05](https://user-images.githubusercontent.com/5195657/127941745-f0bfb052-a633-4431-8ca4-50a29b9cb2dc.png)

![2021-08-02_20-06](https://user-images.githubusercontent.com/5195657/127941825-8d4b9e04-be74-487b-9d80-c5b2a516a411.png)

think like layout work  just fine 

[Desktop Entry]
Type=XSession
Exec=env KDEWM=/usr/bin/herbstluftwm /usr/bin/startplasma-x11 
TryExec=/usr/bin/startplasma-x11
DesktopNames=KDE with herbstluftwm 
Name=Plasma (X11) with herbstluftwm 
 
