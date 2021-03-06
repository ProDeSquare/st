# Hamza Mughal's Patch Of St (Suckless Terminal)

![Screenshot](https://prodesquare.com/img/projects/prodesquare-suckless-st-patch.png)
st is a simple terminal implementation for X. Read more about st on [Suckless' website](http://st.suckless.org).

### Highlight on some features
* The background is set transparent. Adjust the transparency by editing `alpha` from `config.h`
* `.Xresources` compatibility
* Basic keybindings

Action | Keybinding
------------ | -------------
Copy | `Alt+c`
Paste | `Alt+v`
Zoom In | `Alt+k`
Zoom Out | `Alt+j`
Scroll | `Mousewheel`

### Arch linux users
Arch linux users can get my patch of ST from the AUR.
```
$ yay -S st-prodesquare-git
```

### Not on arch? Try installing manually
* Clone this repo
* Cd into the directory
* Install

```
$ git clone https://github.com/ProDeSquare/st.git
$ cd st
$ sudo make install
```

### Links
[Portfolio](https://prodesquare.com)
