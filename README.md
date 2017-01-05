# rspi-recipes
A list of recipes for raspberry pi

## SSH
* wake screen 
````
sudo chmod 666 /dev/tty1
echo -ne "\033[9;0]" >/dev/tty1
````
## Usefull links 

* [Clone images](https://computers.tutsplus.com/articles/how-to-clone-raspberry-pi-sd-cards-using-the-command-line-in-os-x--mac-59911)
* [Flash images](https://github.com/hypriot/flash)
* [Custom boot screen](http://blog.fraggod.net/2015/11/28/raspberry-pi-early-boot-splash-logo-screen.html)
