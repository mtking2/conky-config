# Conky Config

This repo is used to house my configuration for conky. I'm constantly tweaking and fiddling with it so hopefully this repo can help keep track of everything.

## Install

  1. Install conky (e.g. Ubuntu): `sudo apt-get install conky`
  2. Clone this repo.
  3. Copy everything in the repo's **conky** folder into `~/.conky` in your home directory.
     - For the weather scripts to work, copy the **1_accuweather** folder into your home directory `~/`
  4. Run `./start.sh`

## Overview

Here is my entire desktop showing all of the conky goodness.

<img src="imgs/screenFetch-2017-02-10_11-06-46.png" width="800">

## Individual Panels

I have created individual conkyrc's for each set of stats I want to display. Here is a breakdown of each panel.

systemrc  
<img src="imgs/system.png" width="40%">  

cpurc  
<img src="imgs/cpu.png" width="40%">  

gpurc  
<img src="imgs/gpu.png" width="40%">

memoryrc  
<img src="imgs/memory.png" width="40%">

diskrc  
<img src="imgs/drives.png" width="40%">

networkrc  
<img src="imgs/network.png" width="40%">

modified *.conkyrc_1_images_wind_2016* from the [accuweather](https://forums.bunsenlabs.org/viewtopic.php?id=189) scripts  
<img src="imgs/weather.png" width="25%">

calrc  
<img src="imgs/calendar.png" width="25%">


syslogrc (Clock with optional logs of `/var/log/syslog` and `dmesg`)  
<img src="imgs/clock.png" width="75%">
