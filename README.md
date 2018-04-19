#Automatic Fan Control for RPi LibreElec 

this is a fork from: https://github.com/dumbo25/rpi-fan
with some changes to run on LibreElec

How to use SSH on libreelec:
https://wiki.libreelec.tv/accessing_libreelec

Folow the connections on this instructable:
http://www.instructables.com/id/Control-a-Cooling-Fan-on-a-Raspberry-Pi-3/

And use this script.

#Commands
```
cd /storage
wget "https://raw.githubusercontent.com/bigujun/rpi-fan/master/run-fan.py"
nano /storage/.config/autostart.sh
```


Add this line to the file autostart.sh and save it ( press ctrl+O )

```
python /storage/run-fan.py &
```
