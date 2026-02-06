# Windows 10 in Termux
Run Windows 10 in Termux

You should have Termux and Termux:X11 installed from F-Droid

>[!WARNING]
>NEVER USE THE GOOGLE PLAY STORE VERSION OF TERMUX AS IF IT IS OUTDATED!!

You should have git installed in Termux
```
pkg install git
```
Install Xfce4:
```
pkg install x11-repo
pkg install termux-x11-nightly
pkg install wget
pkg install tur-repo
pkg install xfce4 xfce4-goodies
pkg install firefox thunderbird abiword gnumeric gnome-font-viewer vlc mpv gimp geany
```
Install Mobox:
```
curl -s -o ~/x https://raw.githubusercontent.com/olegos2/mobox/main/install && . ~/x
```

Now you are installing Windows 10 in Termux!

Forget the installwin10.sh, it is not working

Wget their script
```
wget https://raw.githubusercontent.com/LinuxDroidMaster/Termux-Desktops/main/scripts/termux_native/startxfce4_termux.sh
```

To start the desktop environment, run this
```
bash ~/startxfce4_termux.sh
```

The desktop seemed different, but I recommend to get themes here:
https://github.com/B00merang-Project/Windows-10-Fluent
<br>
https://github.com/B00merang-Project/Windows-10-Fluent-Dark
<br>
https://github.com/B00merang-Artwork/Windows-10
<br>
https://www.gnome-look.org/p/1829490
<br>
https://wallpapercave.com/w/wp5493583
<br>

Enjoy!
