## chromium  
  
an open-source graphical web browser  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/chromium/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install chromium-browser
```  

Fedora Based:

```shell
yum install chromium
```  

Arch Based:

```shell
pacman -S chromium
```  

MacOS:  

```shell
brew install chromium
```
  
```shell
mv -fv "$HOME/.config/chromium" "$HOME/.config/chromium.bak"
git clone https://github.com/dfmgr/chromium "$HOME/.config/chromium"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/chromium" target="_blank" rel="noopener noreferrer">chromium wiki</a>  |  
  <a href="https://www.chromium.org/Home" target="_blank" rel="noopener noreferrer">chromium site</a>
</p>  
