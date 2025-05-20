# CassettePi

Retro-style MP3 player powered by a RaspberryPi 3a+ aand a 16x2 LCD display 
**CassettePI** is a personal project inspired by classic portable cassette players 
it runs on a RaspberryPI , uses physicalbuttons and LCD screen , and plays MP3 files from a local storage

-----

## Features 

-play MP3 file from /home/pi/music
-physical button control :
 -**play/stop**
-display track info on 16x2 I2c LCD 
-Retro feel and design 

----

## Hardware equipments

-Raspberry pi 3a+
-16x2 I2c LCD display
-Audio output -( jack or usb audio )-
-1 gpio push buttons 
-power source (e.g. power bank )

-----

## Instalation
this project runs on **volumio** , a lightweight music player operating system for RaspberryPI

To use Python for lcd and button control on top of volumio you need to :
1 enable SSH on volumio and connect your RaspberryPI via Terminal or puTTY application 

2 Install required python packages 
'''bash
sudo apt update
sudo apt install python3 python3-pip
python3-rpi.gpio python3-smbus
pip3 install pygame
