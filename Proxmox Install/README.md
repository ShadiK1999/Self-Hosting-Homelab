# Installing Proxmox

Proxmox will be the hypervisor for this home server. This OS will help to run all the virtual machines and containers needed for the service I want to this homelab to provide my network. 

## Requirements

- System with a network connection
- Flash drive with at least 5GB storage
- Program to turn the flash disk into a bootable drive
    - Rufus for Windows
    - BalenaEtcher for MacOS
- System to install Proxmox on

## Equipment used in this Project

- M3 MacBook Pro
- BalenaEtcher 
- 32GB flash drive
- ThinkCentre M910q

## Downloading Proxmox ISO

1. Open the Proxmox website and navigate to the downloads
2. Under "Latest Releases", select the "Proxmox VE ISO Installer". This will download the ISO file for us to flash onto the portable drive later.



## Flashing the Portable Drive

1. Open the program for creating bootable drives, since I am using MacOS that would be BalenaEtcher
2. Select the ISO file and the target flash drive
```
Be careful what you choose as your target drive as the selected drive will be completely wiped!
```
3. Select "Flash" and wait for the for drive to be formatted
