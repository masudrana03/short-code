# Flameshot
Everything About Flameshot


## Run to install :

Using Terminal:

```bash
  sudo apt install flameshot
```

### setup
* edit /etc/gdm3/custom.conf

```bash
  sudo nano /etc/gdm3/custom.conf
```
* remove the comment out from WaylandEnable=false.
* than add flameshot to in startup app list
* add to shortcut tin print screen
* command will be : flameshot gui 
* than reboot your system
