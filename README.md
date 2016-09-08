# rspi-recipes
A list of recipes for raspberry pi

## SSH
* wake screen 
````
sudo chmod 666 /dev/tty1
echo -ne "\033[9;0]" >/dev/tty1
````
