---
---

[HOME](index.md)
[ABOUT](README.md)
[WEB](https://os2xx.github.io/osp4diss/)
[GITHUB](https://github.com/os2xx/osp4diss/)
[TOP](#)
[BOTTOM](#endofpage)

<br id="idx00"><br>
Welcome to the Operating System Programming for DISS site.
The following is a step-by-step guide to set up a Virtual Debian Guest on VirtualBox.

<br id="idx00a">
# Table of Contents

* [Introduction](#idx00)
* [VirtualBox Guest Preparation](#idx00b)
* [Import/Rename/Export/Delete a Virtual Guest](#idx01)
* [Installing a VirtualBox Debian Guest (ISO File)](#idx02)
* [<span style="color:red;font-weight:bold;">Troubleshooting</span>](#idx02a)
* [Running a VirtualBox Debian Guest](#idx03)
* [Dress Up Your Virtual Guest](#idx04)
* [PULL from / PUSH to GitHub](#idx05)
* Weekly Assignments
  * [Operating Systems](AOS.md)
  * [System Programming](ASP.md)
* [More Links](#idx06)

<br id="idx00b">
# VirtualBox Guest Preparation

It would be best if you had a hypervisor, i.e., VirtualBox.
It can be installed on Intel's processors of Windows 10, macOS, or Linux.
Using a Download Manager might help for a less reliable internet connection.
For Windows 10, you also need to install PUTTY and WINSCP.

* [FDM: Free Download Manager (Optional)](InstallFDM.md)
* [Downloading and Installing VirtualBox](InstallVirtualBox.md)
* [Downloading and Installing PUTTY and WINSCP](SSHGuest.md)
* [More On Intel based MacOS](https://fxdros.github.io/virtualbox-on-macos/)
  --- managed by FXDROS, since 2021.

<br id="idx01">
# Import/Export/Delete a Virtual Guest

* [EXPORTing OVA](DebianGuestExportOva.md) -- e.g. DEB11-00.ova
* [RENAMing OVA](DebianGuestExportOva1.md) -- e.g. rename DEB11-00 to DEB11-01
* [IMPORTing a VirtualBox Guest with a different Name](DebianGuestImportOva.md)
* [DELETING Debian VirtualBox Guest(s)](DebianGuestDeleteOva.md)

<br id="idx02">
# Installing a VirtualBox Debian Guest (ISO File)

* [VirtualBox: NEW EMPTY Guest with 16GB + 32 GB disks](DebianGuestOnVirtualBox1.md) (E.g. DEB11-00)
* [EXPORTing OVA](DebianGuestExportOva.md) -- e.g. DEB11-00.ova
* [RENAMing OVA](DebianGuestExportOva1.md) -- e.g. rename DEB11-00 to DEB11-01
* [VirtualBox: General](DebianGuestOnVirtualBox2.md)
* [VirtualBox: System](DebianGuestOnVirtualBox3.md)
* [VirtualBox: Display](DebianGuestOnVirtualBox4.md)
* [VirtualBox: Storage](DebianGuestOnVirtualBox5.md)
* [VirtualBox: Audio](DebianGuestOnVirtualBox6.md)
* [VirtualBox: Network](DebianGuestOnVirtualBox7.md)
* [EXPORTing OVA](DebianGuestExportOva2.md) -- e.g. DEB11-01.ova
* [RENAMing OVA](DebianGuestExportOva3.md) -- e.g. rename DEB11-01 to DEB11-02
* [Downloading Debian ISO Image](DebianISOImage.md)
* [Installing Debian Netinst Guest on VirtualBox](InstallDebianNetinst.md)
* [EXPORTing OVA](DebianGuestExportOva4.md) -- e.g. DEB11-02.ova

<br id="idx02a">
# <span style="color:red;font-weight:bold;">Troubleshooting</span>
* [DNS Failure](osp-117.md)
* [MacBook (Intel based)](https://fxdros.github.io/virtualbox-on-macos/)
* [Windows 10: SFC and DISM mantras](https://rahmatm.samik-ibrahim.vlsm.org/2021/07/windows-10-sfc-and-dism-mantras.html)
* [Windows 10: Simple Troubleshooting Tools](https://rahmatm.samik-ibrahim.vlsm.org/2021/10/four-simple-windows-troubleshooting.html)
* [VirtualBox: SWAP File On Main Filesystem](osp-125.md)
* [VirtualBox: To Shrink and Clean the VDI Files](osp-126.md)

<br id="idx03">
# Running a VirtualBox Debian Guest

* [Startup a VirtualBox Guest](osp-002-startup.md)
* [Login from a Console](osp-002-login.md)
* [Shutdown a VirtualBox Guest](osp-002-shutdown.md)
* [Login with PUTTY](osp-002-putty.md)
* [Login with SSH](osp-002-ssh.md)
* [WINSCP](osp-002-winscp.md)
* [SCP](osp-002-scp.md)
* The ATM Way, GSGS and Read:
  * [Study some Command Lines, Editor, Regular Expression (regex), and String Processing](Welcome2GNULinux.md)
  * [More links about Operating Systems](osp-115.md)
* [EXPORT](#idx01) your Virtual Guest to an OVA file. Estimated OVA size 355 MB.

<br id="idx04">
# Dress Up Your Virtual Guest

* [PASTE: passing “NEW LINE” or not?](osp-116.md)
* [DNS Server TEST](osp-118.md)
* [Update Your Debian Guest](osp-102.md)
* [Adding Debian Packages](osp-103.md)
* [Adding UserName](osp-104.md) -- E.g. "dummy" and "CicakBinKadal"
* [Rename Hostname](osp-105.md)
* [.bash_profile](osp-106.md)
* [.vimrc](osp-107.md)
* [.bash_aliases](osp-108.md)
* [SUPERUSER](osp-109.md)
* [RENAME](DebianGuestExportOva1.md) and [EXPORT](DebianGuestExportOva.md).
  E.g., "OSP221.ova".  Estimated OVA size 747 MB.

<br id="idx05">
# PULL from / PUSH to GitHub.com

* [SSH: Generating public/private rsa key pair](osp-110.md)
* [SSH: Put a Public Key at GitHub.com](osp-111.md)
* [GIT: .gitconfig](osp-112.md)
* [GIT: cloning from GitHub.com](osp-113.md)
* [mylog: Updating add commit push](osp-114.md)
* [The 4 GIT MANTRAS: (pull), add, commit, push](osp-119.md)
* [EXPORT](#idx01) your Virtual Guest to an OVA file. Estimated OVA size 645 MB.

<br id="idx06">
# More Links

* [C-lib: Long Options with getopt_long()](osp-122.md)
* [GNU autoconf example: A Small Hello World](osp-123.md)
* [GNUPG: How to symmetrically encrypt and decrypt a file](osp-121.md)
* [GNUPG: Kleopatra (Windows 10)](CBKadal3.md)
* [FUSE Demo and Links](osp-120.md)
* [LFS: Kernotex's Linux From Scratch 11.1 Highlights](osp-124.md)
* [Linux: Making and encrypting a tarball](osp-001.md)
* [Linux: TOP (was Table Of Processes)](osp-101.md)
* [OS Log Codes](ETC/logCodes.txt)
* [OS/SP Public Key](ETC/rmspubkey.txt)
* [X11 for Windows 10](osp-003.md)
* [VirtualBox: How To Shrink and Clean VDI File](https://lfs.vlsm.org/LFS-02-5.html)

<br>
<hr>
<br id="endofpage"><br>

[HOME](index.md)
[ABOUT](README.md)
[WEB](https://os2xx.github.io/osp4diss/)
[GITHUB](https://github.com/os2xx/osp4diss/)
[TOP](#)
[BOTTOM](#endofpage)
<br>

