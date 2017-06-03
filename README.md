These are the Home Assistant configuration files used in the BRUH3 Home Automation project. Check out the [YouTube Series](https://www.youtube.com/playlist?list=PLgtGAtCt_hGTc_GAEmMhQ_XVs80mZoBIG) if you want to learn more about it! 

# Home Assistant Installation
I'm currently running [Home Assistant](https://home-assistant.io) version __0.45.1__. My preferred installation method is [Hassbian](https://github.com/home-assistant/pi-gen/releases).

After downloading the disk image and writing it to an SD card with [Etcher](https://etcher.io/), I run the following commands in [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) to install the required prerequisites. 

```
sudo hassbian-config install mosquitto
sudo hassbian-config install libcec
sudo hassbian-config install openzwave
sudo hassbian-config install samba
```
I also use [HASSCTL](https://github.com/dale3h/hassctl) which allows for some super simple commandline shortcuts for starting, stoping, and upgrading HA. 

```
hassctl update-hass
hassctl start
hassctl stop
hassctl error
```

# Home Assistant Hardware
* [Raspberry Pi 3](http://geni.us/raspberrypi3)
* [Case](http://geni.us/2rQEgy5)
* [CanaKit 2.5A 5V Power Supply](http://geni.us/2ABPd1D)
* [Samsung Evo+ 64GB SD](http://geni.us/PbZS2oD)
* [Aeotec ZStick](http://geni.us/N2ULv)
* [433 RF RX TX](http://amzn.to/2b5wOS1)


# BRUH3 Flow Diagram 
![BFD](www/BFDv2.png)
