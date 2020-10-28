**Almost every program you'll ever need is available in AUR (using `yay`)**


#### AUR package manager
- [yay](https://github.com/Jguer/yay)

##### How to install Yay

In the terminal emulator

```
sudo pacman -S git
cd ~/Downloads
git clone https://aur.archlinux.org/yay-bin.git
cd yay-bin
makepkg -si
```

Also, you need to add this to the end of `pacman.conf` file

```
sudo nvim /etc/pacman.conf
```

```
[archlinuxfr] </br>
SigLevel = Never </br>
Server = http://repo.archlinux.fr/$arch </br>
```

##### Install programs using yay

```
yay 'program_name'
```

#### Install zsh instead of bash and make it default

```
yay zsh
chsh -s $(which zsh)
```

### CLI programs for the terminal
#### For zsh
- [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)

#### Terminal emulator
- [guake](http://guake-project.org/)

#### Terminal multiplexor
- [tmux](https://github.com/tmux/tmux/wiki)

#### Text editor
- vi (present on every linux/unix machine)
- [neovim](https://neovim.io/) (new)
- nano (present on most linux/unix machines)
- [micro](https://micro-editor.github.io/)

#### File manager
- [ranger](https://github.com/ranger/ranger)
- [mc](https://midnight-commander.org/)
- [nnn](https://github.com/jarun/nnn)

#### Video editors
- [GStreamer](https://gstreamer.freedesktop.org/)
- [ffmpeg](https://ffmpeg.org/)

#### Browser
- [w3m](http://w3m.sourceforge.net/)

#### File listers
- ls (present on every linux/unix machine)
- [k](https://github.com/supercrabtree/k)
- [exa](https://github.com/ogham/exa)
- colorls (in yay - ruby-colorls)

#### Changing directory
- cd (present on every linux/unix machine)
- [z](https://github.com/agkozak/zsh-z)

#### System monitoring
- top (by default)
- [gotop](https://github.com/cjbassi/gotop) (my favorite)
- [gtop](https://github.com/aksakalli/gtop)
- [bashtop](https://github.com/aristocratos/bpytop)
- htop

#### Image viewer
- [tiv](https://github.com/stefanhaustein/TerminalImageViewer)

#### Python interpreter
Basic Python interpreter, called CPython (`python3` in the terminal), 
is good enough, but it is not very fast and does not have a lot of features
- IPython - have a beautiful interface with autocomplete
- PyPy - very fast interpreter (about 20-30 times faster)

#### For git management
- [lazygit](https://github.com/jesseduffield/lazygit)

#### For fun
- [cmatrix](https://github.com/abishekvashok/cmatrix)
- sl
- cowsay
- espeak
- hollywood
- [Color-Scripts](https://github.com/stark/Color-Scripts)
- [conky](https://github.com/brndnmtthws/conky)

### Recommended GUI programs

#### [Gnome Extensions](https://extensions.gnome.org/)

#### For photos view
- PhotoQT
- Gnome eye
- gThumb

#### Video player
- VLC
- Mplayer

#### Terminal emulator
- terminology
- termite
- Guake

#### Browsers
- Chromium
- Google chrome
- Firefox

#### Torrent
- QBitTorrent
- Transmission

#### Notepad
- leafpad
- gedit
- neovim-qt

#### Markdown editor
- Boostnote

#### Document viewer
- zathura

#### Screenshot utility
- flameshot

#### Graphical yay alternative 
- pamac-aur

#### 3d modeler
- Blender

#### Photo editors
- Darktable
- GIMP

#### File manager
- nautilus (default in Gnome3)
- total commander
- double commander

#### System monitoring
- [netdata](https://github.com/netdata/netdata)
- cpu-x (IMHO, the best one)

#### Instead of Microsoft Word packet
- Google docs, sheets, impress. Available online on every PC.
- LibreOffice

#### FTP cliente
- Filezilla

#### For astronomy
- Kstars

#### For disks management
- GParted

