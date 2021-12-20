---
---

[HOME](index.md)
[ABOUT](README.md)
[WEB](https://osp4diss.vlsm.org/)
[GITHUB](https://github.com/UI-FASILKOM-OS/osp4diss/)
[TOP](#)
[BOTTOM](#endofpage)
[PREV](index.md)
[NEXT](DebianGuestOnVirtualBox2.md)

# Creating a NEW empty VirtualBox Guest

* You should adjust these following according to your own belief and faith.
  * Name: **DEB10-00-0-64G+64G-EMPTY** (<span style="color:red; font-weight:bold; font-size:larger;">your may choose a different guest name</span>).
  * Processors (Cores): 2 (check your CPU!)
  * Memory = 1024 MB (512MB is OK too!)
  * Storage1 = 64 GB (dynamically allocated)
  * Storage2 = 64 GB (dynamically allocated)
  * SSH: NAT  from host  (127.0.0.1 port 6022) to guest (10.0.2.15 port 22)
  * Jekyll: NAT from host (127.0.0.1 port 5000) to guest (10.0.2.15 port 4000)

<br>
## Click NEW

<img src="pictures/osp21-00.jpg"  width="960">

<br>
* Name = **DEB10-00-0-64G+64G-EMPTY**
  * Type: Linux
  * Version: Debian (64bit)

<img src="pictures/osp21-01.jpg"  width="960">

<br>
* Memory size = <span style="color:red; font-weight:bold; font-size:larger;">1024 MB</span> (But, 512 MB is OK too!)

<img src="pictures/osp21-02.jpg"  width="960">

<br>
* Create a Virtual Hard Disk

<img src="pictures/osp21-03.jpg"  width="960">

<br>
* Hard Disk type: VDI

<img src="pictures/osp21-04.jpg"  width="960">

<br>
* Storage: Dynamically Allocated

<img src="pictures/osp21-05.jpg"  width="960">

<br>
* Storage = 64 GB (dynamically allocated)

<img src="pictures/osp21-06.jpg"  width="960">

<br id="endofpage"><br>

[HOME](index.md)
[ABOUT](README.md)
[WEB](https://osp4diss.vlsm.org/)
[GITHUB](https://github.com/UI-FASILKOM-OS/osp4diss/)
[TOP](#)
[BOTTOM](#endofpage)
[PREV](index.md)
[NEXT](DebianGuestOnVirtualBox2.md)

