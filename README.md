## chromium  
  
an open-source graphical web browser  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/chromium/raw/master/install.sh)"
```
Manual install:
requires:    
```
apt install chromium-browser
```  
```
yum install chromium
```  
```
pacman -S chromium
```  
  
```
mv -fv "$HOME/.config/chromium" "$HOME/.config/chromium.bak"
git clone https://github.com/dfmgr/chromium "$HOME/.config/chromium"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/chromium" target="_blank">chromium wiki</a>  |  
  <a href="https://www.chromium.org/Home" target="_blank">chromium site</a>
</p>  
