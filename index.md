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
* [Running a VirtualBox Debian Guest](#idx03)
* [Dress Up Your Virtual Guest](#idx04)
* [PULL from / PUSH to GitHub](#idx05)
* [More](#idx06)
* [OS Assignments](AOS.md)
* [SP Assignments](ASP.md)
* [ETC](#idx08)

<br id="idx00b">
# VirtualBox Guest Preparation

It would be best if you had a hypervisor, i.e., VirtualBox.
It can be installed on Intel's processors of Windows 10, macOS, or Linux.
Using a Download Manager might help for a less reliable internet connection.
For Windows 10, you also need to install PUTTY and WINSCP.

* [FDM: Free Download Manager (Optional)](InstallFDM.md)
* [Downloading and Installing VirtualBox](InstallVirtualBox.md)
* [Downloading and Installing PUTTY and WINSCP](SSHGuest.md)
* [More On MacOS](https://fxdros.github.io/virtualbox-on-macos/)
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
* <span style="color:red;font-weight:bold;">Troubleshooting</span> -- [DNS Failure](osp-117.md)

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
* [EXPORT](#idx01) your Virtual Guest to an OVA file. Estimated OVA size 645 MB.

<br id="idx06">
# More

* [Log Codes](ETC/logCodes.txt)
* [X11 for Windows 10](osp-003.md)
* [How To Shrink and Clean the VirtualBox VDI File](https://lfs.vlsm.org/LFS-02-5.html)
* [TOP (was Table Of Processes)](osp-101.md)

<br id="idx07">
# Assignments

* [OS Assignments](AOS.md)
* [SP Assignments](ASP.md)

<br id="idx08">
# ETC

* [Making and encrypting a tarball](osp-001.md)
* [FUSE Demo](osp-100.md)
* [Kleopatra (Windows 10)](CBKadal3.md)
* [OS Public Key](ETC/ospubkey.txt)

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

