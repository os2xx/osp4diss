---
---

[HOME](index.md)
[ABOUT](README.md)
[WEB](https://osp4diss.vlsm.org/)
[GITHUB](/https://github.com/os2xx/osp4diss)
[TOP](#)
[BOTTOM](#endofpage)
[PREV](DebianISOImage.md)
[NEXT](index.md)

# Installing Debian NetInst (guest) on VirtualBox

<br>
## Default Settings

* You should adjust these following according to your own belief and faith.
  * Hostname: cbkadal
  * Domain: none
  * Root/Pass: root/cbkadal
  * UserName/Account/Pass: Cicak Bin Kadal/cbkadal/cbkadal
  * Disk #1 (16 GB): 1024MB swap and "/" (root partition).
  * Disk #2 (32 GB): 1024MB swap and "/mnt/lfs/" (partition).
  * <span style="color:red; font-weight:bold; font-size:larger;">You 
    might want to enlarge the SWAP size</span>

<br>
## Import an EMPTY VirtualBox Guest

* E.g DEB11-02.ova

### Select and Click Settings

<img src="pictures/OS21-038a.jpg"  width="960">

<br>
### Storage: Controller: SATA

<img src="pictures/OS21-039.jpg"  width="960">

* Adds Optical Drive

<img src="pictures/OS21-040.jpg"  width="960">

<br>
### Add Disk Image

<img src="pictures/OS21-041.jpg"  width="960">

<br>
### Open an ISO Image

* Eg. debian-11.2.0-amd64-netinst.iso
  <span style="color:red; font-weight:bold; font-size:larger;">(Check if this is the latest version!)</span>

<img src="pictures/OS21-042.jpg"  width="960">

<br>
### Eg. Choose: debian-11.2.0-amd64-netinst.iso

* <span style="color:red; font-weight:bold; font-size:larger;">(Check if this is the latest version!)</span>

<img src="pictures/OS21-043.jpg"  width="960">

<br>
### Storage: Storage Devices: OK

<img src="pictures/OS21-044.jpg"  width="960">

<br>
## Starting Guest **DEB11-02**

<img src="pictures/OS21-045.jpg"  width="960">

<br>
### Virtual Box Starts

<img src="pictures/OS21-046.jpg"  width="960">

<br>
### Graphical Install

<img src="pictures/OS21-047.jpg"  width="960">

<br>
### Select A Language: English (or else)

<img src="pictures/OS21-048.jpg"  width="960">

<br>
### Select Your Location: Other (or else)

<img src="pictures/OS21-049.jpg"  width="960">

<br>
### Select Your Location: Asia (or else)

<img src="pictures/OS21-050.jpg"  width="960">

<br>
### Select Your Location: Asia: Indonesia (or whereever)

<img src="pictures/OS21-051.jpg"  width="960">

<br>
### Configure Locales: United States (en_US.UTF-8) (or else)

<img src="pictures/OS21-052.jpg"  width="960">

<br>
### Configure The Keyboard: American English (or else)

<img src="pictures/OS21-053.jpg"  width="960">

<br>
### Load Installer Components From CD

<img src="pictures/OS21-054.jpg"  width="960">

<br>
### Configure The Network

* Hostname: cbkadal

<img src="pictures/osp21-57.jpg"  width="960">

* Domain Name: none

<img src="pictures/osp21-58.jpg"  width="960">

<br>
### Set Up Users And Passwords

* Root Password: cbkadal

<img src="pictures/osp21-59.jpg"  width="960">

* Full Name For The New User: Cicak Bin Kadal

<img src="pictures/osp21-60.jpg"  width="960">

* Username For Your Account: cbkadal

<img src="pictures/osp21-61.jpg"  width="960">

* Choose A Password For The New User: cbkadal

<img src="pictures/osp21-62.jpg"  width="960">

<br>
### Configure The Clock

<img src="pictures/osp21-63.jpg"  width="960">

* Select A City In Your Time Zone: WIB

<img src="pictures/osp21-64.jpg"  width="960">

<br>
### Partitions Disk

<img src="pictures/osp21-65.jpg"  width="960">

* Partition method: Manual

<img src="pictures/osp21-66.jpg"  width="960">

<br>
### Select: SCSI1 (0,0,0) (sda)

<img src="pictures/osp21-67.jpg"  width="960">

* Create A New Partition Table: Yes

<img src="pictures/osp21-68.jpg"  width="960">

<img src="pictures/osp21-69.jpg"  width="960">

* Create A New Partition

<img src="pictures/osp21-70.jpg"  width="960">

* Partition Size: 257 MB
  * <span style="color:red; font-weight:bold; font-size:larger;">
    You might want to consider other SWAP sizes:
    </span>
    * 512MB
    * 1024MB
    * 2048MB

<img src="pictures/osp21-71.jpg"  width="960">

* Partition Type: Primary

<img src="pictures/osp21-72.jpg"  width="960">

* Location: Beginning

<img src="pictures/osp21-73.jpg"  width="960">

* Set Partition As A Swap Area

<img src="pictures/osp21-74.jpg"  width="960">

<img src="pictures/osp21-75.jpg"  width="960">

* Done: Swap Partition

<img src="pictures/osp21-76.jpg"  width="960">

* Second Partitiion

<img src="pictures/osp21-77.jpg"  width="960">

* Create A New Partition

<img src="pictures/osp21-78.jpg"  width="960">

* Partition Size: 68.5 GB

<img src="pictures/osp21-79.jpg"  width="960">

* Partition Type: Primary

<img src="pictures/osp21-80.jpg"  width="960">

* Done Setting Up The Partition

<img src="pictures/osp21-81.jpg"  width="960">

<br>
### Select: SCSI2 (0,0,0) (sdb)

<img src="pictures/osp21-82.jpg"  width="960">

* Create A New Partition Table: Yes

<img src="pictures/osp21-83.jpg"  width="960">


<img src="pictures/osp21-84.jpg"  width="960">

* Create A New Partition

<img src="pictures/osp21-85.jpg"  width="960">

* Partition Size: 257 MB
  * <span style="color:red; font-weight:bold; font-size:larger;">
    You might want to consider other SWAP sizes:
    </span>
    * 512MB
    * 1024MB
    * 2048MB

<img src="pictures/osp21-86.jpg"  width="960">

* Partition Type: Primary

<img src="pictures/osp21-87.jpg"  width="960">

* Location: Beginning

<img src="pictures/osp21-88.jpg"  width="960">

* Set Partition As A Swap Area

<img src="pictures/osp21-90.jpg"  width="960">


<img src="pictures/osp21-91.jpg"  width="960">

* Done: Swap Partition

<img src="pictures/osp21-92.jpg"  width="960">

* Second Partitiion

<img src="pictures/osp21-93.jpg"  width="960">

* Create A New Partition

<img src="pictures/osp21-94.jpg"  width="960">

* Partition Size: 68.5 GB

<img src="pictures/osp21-95.jpg"  width="960">

* Partition Type: Primary

<img src="pictures/osp21-96.jpg"  width="960">

* Change Mounting Point From /home to /lfs

<img src="pictures/osp21-97.jpg"  width="960">

* Select: Enter Manually


<img src="pictures/osp21-98.jpg"  width="960">

* Mounting Point: Linux From Scratch (/lfs)

<img src="pictures/osp21-99.jpg"  width="960">

* Done Setting Up The Partition

<img src="pictures/osp21-A0.jpg"  width="960">

* Finish Partitioning And Write Changes To Disk

<img src="pictures/osp21-A1.jpg"  width="960">

* Write The Changes To Disk: Yes

<img src="pictures/osp21-A2.jpg"  width="960">

<br>
### Partition Disk Process

<img src="pictures/osp21-A3.jpg"  width="960">

<br>
### Installing The Base System

<img src="pictures/osp21-A4.jpg"  width="960">

<br>
### Configuring The Package Manager

* Scan Another CD or DVD: No

<img src="pictures/osp21-A5.jpg"  width="960">

* Debian Archive Mirror Country: Indonesia

<img src="pictures/osp21-A6.jpg"  width="960">

* Debian Archive Mirror: deb.debian.org

<img src="pictures/osp21-A7.jpg"  width="960">

* HTTP proxy: none

<img src="pictures/osp21-A8.jpg"  width="960">

* Configuring APT

<img src="pictures/osp21-A9.jpg"  width="960">

<br>
### Configuring Popularity-Contest: No

<img src="pictures/osp21-B0.jpg"  width="960">

<br>
### Software Selection
* SSH server
* Standart System Utilities

<img src="pictures/osp21-B1.jpg"  width="960">

<br>
### Select And Install Software

<img src="pictures/osp21-B2.jpg"  width="960">

<br>
### Install The GRUB Boot Loader On A Harddisk

* Install the GRUB Boot Loader to the master boor record: YES

<img src="pictures/osp21-B3.jpg"  width="960">

* Enter Device Manually: /dev/sda

<img src="pictures/osp21-B4.jpg"  width="960">

* Installing GRUB Boot Loader

<img src="pictures/osp21-B5.jpg"  width="960">

<br>
### Installation Complete

<img src="pictures/osp21-B6.jpg"  width="960">

<br>
### Rebooting The System

<img src="pictures/osp21-B7.jpg"  width="960">

<br>
### GRUB Loader

<img src="pictures/B-OSP-42.jpg"  width="960">

<br>
### Login 

<img src="pictures/osp21-B8.jpg"  width="960">

```
apt-get update
apt-get dist-upgrade -y;
poweroff
```

<img src="pictures/osp21-B9.jpg"  width="960">

<br>
### Remove SATA Attachment 

* Settings

<img src="pictures/osp21-C0.jpg"  width="960">

* Storage: Controller: SATA: EMPTY

<img src="pictures/osp21-C1.jpg"  width="960">

* Remove Attachment

<img src="pictures/osp21-C2.jpg"  width="960">

<br>
### SETTING: Done

<img src="pictures/osp21-C3.jpg"  width="960">

<br>
## EXPORT Debian Guest:

* In this example: DEB10-00-1-INSTALL
* For Debian 11, the name should be: **DEB11-00-1-INSTALL**

<img src="pictures/osp21-C4.jpg"  width="960">

<img src="pictures/osp21-C5.jpg"  width="960">

<img src="pictures/osp21-C6.jpg"  width="960">


<br>
# DONE

<br id="endofpage"><br>

[HOME](index.md)
[ABOUT](README.md)
[WEB](https://osp4diss.vlsm.org/)
[GITHUB](/https://github.com/os2xx/osp4diss)
[TOP](#)
[BOTTOM](#endofpage)
[PREV](DebianISOImage.md)
[NEXT](index.md)
<br>

