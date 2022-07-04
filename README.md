## dmenu  
  
###
  
#### Requires scripts to be installed

```shell
sudo bash -c "$(curl -q -LSs "https://github.com/dfmgr/installer/raw/main/install.sh")" && sudo dfmgr install installer
```

### Automatic install/update

```shell
dfmgr install dmenu
```

OR

```shell
bash -c "$(curl -q -LSs "https://github.com/dfmgr/dmenu/raw/main/install.sh")"
```
  
requirements:
  
Debian based:

```shell
apt install dmenu
```  

Fedora Based:

```shell
yum install dmenu
```  

Arch Based:

```shell
pacman -S dmenu
```  

MacOS:  

```shell
brew install dmenu
```
  
Manual install:  

  ```shell
APPDIR="$HOME/.local/share/CasjaysDev/dfmgr/dmenu"
mv -fv "$HOME/.config/dmenu" "$HOME/.config/dmenu.bak"
git clone https://github.com/dfmgr/dmenu "$APPDIR"
cp -Rfv "$APPDIR/etc/." "$HOME/.config/dmenu/"
[ -d "$APPDIR/bin" ] && cp -Rfv "$APPDIR/bin/." "$HOME/.local/bin/"
```
  
<p align=center>
   <a href="https://travis-ci.com/github/dfmgr/dmenu" target="_blank" rel="noopener noreferrer">
     <img src="https://travis-ci.com/dfmgr/dmenu.svg?branch=master" alt="Build Status"></a><br />
  <a href="https://wiki.archlinux.org/index.php/dmenu" target="_blank" rel="noopener noreferrer">dmenu wiki</a>  |  
  <a href="dmenu" target="_blank" rel="noopener noreferrer">dmenu site</a>
</p>  
