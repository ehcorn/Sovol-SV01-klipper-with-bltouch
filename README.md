# Sovol-SV01-klipper-with-bltouch
Repository for my backup of my printer configuration files and notes on setting up mainsail os with klipper on my 3D printer.

After searching current repositories on github and finding that none of the configurations quite fit my printer.

my hardware:
- Raspberry pi 3 running mainsail OS
- Sovol SV01 standard 3D printer
- aftermarket BLtouch installed following this tutorial: https://www.youtube.com/watch?v=gH8F8VRKDko
- I do NOT have the silent board, I'm not sure if the pin layout changes or not, but if you do have a silent board you may run into issues.

This config is currently working at the time of thie last update, do submit issues if something's out of date as I'll be actively using this configuration but may not remember to update the gi repository.

based on the main config from [Klipper](https://github.com/Klipper3d/klipper/blob/master/config/printer-sovol-sv01-2020.cfg).
Inspiration taken from [Louis Roussea](https://github.com/louisrousseau/sovol-sv01-pro-klipper-custom-configs) but I found these configs did not work for my printer, many of the pin mappings don't work and my printer doesn't have the same features.
I also found this config from [simon johansson](https://gist.github.com/simonjohansson/863997f73eb39517840470fbcf1d5a35 ) however the options needed don't work in the current version of mainsail OS so I largely had to scrap this config file, though I've followed some of the formatting used.
