# Set PATH for scripts
```
export PATH=$HOME/.local/bin:$PATH
```
# Installation
```
git clone https://github.com/sajayprakash/dwmblocks
cd dwmblocks
sudo make install
```
# Add dwmblocks to xinitrc
eg: 
```
nitrogen --restore &
picom --config $HOME/.config/picom/picom.conf &
dwmblocks &
exec dwm
```
