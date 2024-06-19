# HiFiPi
A little 3D printed frame for a Raspberry Pi 5 based HiFi system

## Description

A self-contained unit capable of playing High Fidelity audio

## Design Requirements

- The device should be one integrated unit, not a bunch of loose components (except for possibly the DAC, see below)
- Easy to tinker with
- Touch screen
- knowbs, buttons, switches, LEDs, etc.
- The device should be modular

## Bill Of Materials

###### All components locally sourced in NL, from either [TinyTronics](https://www.tinytronics.nl/) or [Kiwi Electronics](https://www.kiwi-electronics.com/nl/home/) or [Amazon](https://www.amazon.nl/)

### Single Board Computer

- Any [Raspberry Pi 5](https://www.kiwi-electronics.com/nl/raspberry-pi-boards-behuizingen-uitbreidingen-en-accessoires-59/raspberry-pi-boards-363?ff1=32), although the 2GB version is NOT recommended
- An [active cooler](https://www.kiwi-electronics.com/nl/raspberry-pi-boards-behuizingen-uitbreidingen-en-accessoires-59/raspberry-pi-koeling-419)
- A [power supply](https://www.kiwi-electronics.com/nl/raspberry-pi-boards-behuizingen-uitbreidingen-en-accessoires-59/stroomvoorzieningen-voor-de-raspberry-pi-192?ff1=32)

### Storage

#### Basic

- Any SD card of 32GB or more

#### Advanced (recommended)

- An NVMe SSD (500GB or more)
- A [PCIe to NVMe HAT](https://www.kiwi-electronics.com/nl/raspberry-pi-boards-behuizingen-uitbreidingen-en-accessoires-59/raspberry-pi-opslag-422?ff1=32), either top or bottom mounted (I chose top for easy accessibility)

### Display

Here the possibilities are endless, I would recommend at least a 7" display with capacitive touch. Make sure that it has mounts for the Raspberry Pi. I ended up getting [this one](https://www.amazon.nl/dp/B0CGNH5G68?psc=1&ref=ppx_yo2ov_dt_b_product_details) from Amazon

### Audio

This another of those "whatever floats your boat" options thing, [here](https://www.kiwi-electronics.com/nl/raspberry-pi-boards-behuizingen-uitbreidingen-en-accessoires-59/raspberry-pi-hats-uitbreidingen-144/raspberry-pi-audio-addons-hats-202) you will find a whole range of DACs, with prices starting at €24.- going al the way to €220.-

Another option is an external DAC, with an even more bewildering price range. [Here](https://www.hifistudio79.nl/product-categorie/stereo/dac-usb-1/) you can find a good assortment. A good source for DAC reviews can be found [here](https://www.audiosciencereview.com/forum/index.php?pages/Reviews/)

### Software

There are three main dedicated HiFi contenders, see [here](http://techroadtrip.com/audio-software/volumio-vs-moode-vs-picoreplayer/) for a comparison

- I am currently using [Volumio](https://volumio.com/get-started/), which has an active and very friendly [community](https://community.volumio.com/).
  One disadvantage is that you need a premium subscription to unlock all the extra bells and whistles
- [Moode](https://moodeaudio.org/) is a good alternative (actually a fork of the original Volumio)
- [piCorePlayer](https://www.picoreplayer.org/) is also an excellent option, although the initial setup is less intuitive than the others
- [Hifiberry-os](https://github.com/hifiberry/hifiberry-os) is another interesting one, especially for Hifiberry DAC owners
- As the Pi5 is a pretty capable little computer, you could also install Raspberry Pi OS, Ubuntu or any other ARM64 OS and go from there
- Last but not least, [LibreElec](https://libreelec.tv/) (a dedicated [KODI](https://kodi.tv/) distro) is very capable and adds some interesting video streaming options and other bells and whistels through its extensive Add-on ecosystem

### Miscellanea

- The buttons are recycled MX keys
- TinyTronics has a nice [rotary encoder](https://www.tinytronics.nl/nl/schakelaars/manuele-schakelaars/rotary-encoders/rotary-encoder-module)
- They also have a nice selection of small 1.3"128x64 I2C [OLED displays](https://www.tinytronics.nl/nl/displays/oled)

- You will probably need a variety of spacers, flat cables and screws, these are readily available at either Amazon or Tinytronics
