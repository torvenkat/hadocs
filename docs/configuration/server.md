

## Current

My Home Assistant now runs on a dedicated [Home Assistant 'Blue' hardware](https://www.home-assistant.io/blue/) (Not with the fancy blue case).  This helps me focus on integrations and automations, not spending significant time on the upkeep of the server. 

Here are the key specs.

- ODROID-N2+ with 4GB RAM

- eMMC storage with Home Assistant pre-installed

- - Standard Bundle: 64GB eMMC

- RTC backup battery

- Power adapter (12V/2A)

## Older Version

Previously, I repurposed an old Mac Mini (*circa 2014*). 

* Dual-core Intel i5 (Haswell ULT), at 2.7 GHz
* 4 GB RAM
* 1 TB SSD (Samsung SSD 860 QVO)

It runs [Proxmox VE](https://www.proxmox.com/en/proxmox-ve), an open-source Virtualization Platform, on a skeletal Debian.  The Home Assistant runs in a container, with no restrictions on CPU, Memory, or disk space utilization. Along with this I run [WeeWx weather server](http://www.weewx.com/)  on  another. 

