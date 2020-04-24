# blinky-lite-cam
## env variables
USBDRIVE=/media/usb<br>
USBDRIVEDATA=blinky-lite-cam-data<br>
IMAGESTORAGELOCATION=/home/pi/blinky-lite-cam-data/images<br>
NODEREDSECRET=xxxx<br>

## directories
/home/pi/blinky-lite-cam-data/images/stills<br/>
/home/pi/blinky-lite-cam-data/images/timelapse<br/>
on usb stick there must be a directory blinky-lite-cam-data

## extra installation
sudo apt-get install zip<br/>
sudo apt-get install usbmount<br/>
changing MountFlags=slave to MountFlags=shared at:<br/>
sudo nano /lib/systemd/system/systemd-udevd.service<br/>
