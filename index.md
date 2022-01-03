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
* OS Assignments
  * TBA.
* SP Assignments
  * TBA.
* [ETC](#idx08)

<br id="idx00b">
# VirtualBox Guest Preparation

It would be best if you had a hypervisor, i.e., VirtualBox.
It can be installed on Windows 10, macOS, or Linux.
Using a Download Manager might help for a less reliable internet connection.
For Windows 10, you also need to install PUTTY and WINSCP.

* [FDM: Free Download Manager (Optional)](InstallFDM.md)
* [Downloading and Installing VirtualBox](InstallVirtualBox.md)
* [Downloading and Installing PUTTY and WINSCP](SSHGuest.md)
* [More On MacOS](https://fxdros.github.io/virtualbox-on-macos/)
  --- managed by FXDROS, since 2021.

<br id="idx01">
# Import/Export/Delete a Virtual Guest

* [EXPORTing a VirtualBox Guest (OVA)](DebianGuestExportOva.md)
* [RENAMing a VirtualBox Guest](DebianGuestExportOva1.md)
* [IMPORTing a VirtualBox Guest with a different Name](DebianGuestImportOva.md)
* [EXPORT IMPORT VirtualBox Guest(s)](ExportImportGuests.md)
* [DELETING Debian VirtualBox Guest(s)](DebianGuestDeleteOva.md)

<br id="idx02">
# Installing a VirtualBox Debian Guest (ISO File)

* [VirtualBox: NEW EMPTY Guest with 16GB + 32 GB disks](DebianGuestOnVirtualBox1.md) (E.g. DEB11-00)
* [VirtualBox: General](DebianGuestOnVirtualBox2.md)
* [VirtualBox: System](DebianGuestOnVirtualBox3.md)
* [VirtualBox: Display](DebianGuestOnVirtualBox4.md)
* [VirtualBox: Storage](DebianGuestOnVirtualBox5.md)
* [VirtualBox: Audio](DebianGuestOnVirtualBox6.md)
* [VirtualBox: Network](DebianGuestOnVirtualBox7.md)
* [Downloading Debian ISO Image](DebianISOImage.md)
* [Installing Debian Netinst Guest on VirtualBox](InstallDebianNetinst.md)
* [EXPORT](#idx01) your Virtual Guest as "DEB11-01.ova" (after shutdown).

<br id="idx03">
# Running a VirtualBox Debian Guest

* [IMPORT](#idx01) E.g. "DEB11-01.ova".
* [RENAME](#idx01) your Virtual Guest as "Guest-01a".
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
* [EXPORT](#idx01) your Virtual Guest to an OVA file. E.g. "Guest-01a.ova" (after shutdown).
  Estimated OVA size 355 MB.

<br id="idx04">
# Dress Up Your Virtual Guest

* [IMPORT](#idx01) your Virtual Guest from "Guest-01a.ova".
* [RENAME](#idx01) the Guest to "Guest-01b".
* [PASTE: passing “NEW LINE” or not?](osp-116.md)
* [Update Your Debian Guest](osp-102.md)
* [Adding Debian Packages](osp-103.md)
* [Adding UserName](osp-104.md) -- E.g. "dummy" and "CicakBinKadal"
* [Rename Hostname](osp-105.md)
* [.bash_profile](osp-106.md)
* [.vimrc](osp-107.md)
* [.bash_aliases](osp-108.md)
* [SUPERUSER](osp-109.md)
* [EXPORT](#idx01) your Virtual Guest to an OVA file. E.g. "Guest-01b.ova" (after shutdown).
  Estimated OVA size 614 MB.

<br id="idx05">
# PULL from / PUSH to GitHub.com

* [IMPORT](#idx01) your Virtual Guest from "Guest-01b.ova".
* [RENAME](#idx01) your Virtual Guest as "Guest-01c".
* [SSH: Generating public/private rsa key pair](osp-110.md)
* [SSH: Put a Public Key at GitHub.com](osp-111.md)
* [GIT: .gitconfig](osp-112.md)
* [GIT: cloning from GitHub.com](osp-113.md)
* [mylog: Updating add commit push](osp-114.md)
* [EXPORT](#idx01) your Virtual Guest to an OVA file. E.g. "Guest-01c.ova" (after shutdown).
  Estimated OVA size 645 MB.

<br id="idx06">
# More

* [Log Codes](ETC/logCodes.txt)
* [X11 for Windows 10](osp-003.md)
* [How To Shrink and Clean the VirtualBox VDI File](https://lfs.vlsm.org/LFS-02-5.html)
* [TOP (was Table Of Processes)](osp-101.md)

<br id="idx07">
# Assignments

## Cicak Bin Kadal: Assignment Week 02

* [Read OSC10 chapter 16 + 17](https://www.os-book.com/OS10/slide-dir/)
* [Try Demos in https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/](https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/)
* [Generating a GnuPG KEY PAIR](CBKadal2.md)
* [List of current GnuPG KEYS](W02-01.md)
* [Importing the Operating Systems public key](W02-02.md)
* [Signing the Operating Systems public key (Optional)](W02-03.md)
* [Export Public Key “mypubkey.txt”](W02-04.md)
* [Update your bookmark links. See C.B. Kadal&#39;s "LINKS/"](https://cbkadal.github.io/os212/LINKS/)
* [Review your peer links](W02-05.md)
* [Update your log. See C.B. Kadal&#39;s "mylog.txt"](https://cbkadal.github.io/os212/TXT/mylog.txt)
* [Submit Your Week 02 Assignment](W02-06.md)

<br id="idx0703">
## Cicak Bin Kadal: Assignment Week 03

* [Read OSC10 chapter 13 + 14 +15](https://www.os-book.com/OS10/slide-dir/)
* [Try Demos in https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/](https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/)
* [Try Previous MidTerm Problems](https://rms46.vlsm.org/2/198.pdf)
* [Check if your ”.bash_aliases” file is up-todate](https://osp4diss.vlsm.org/osp-108.html)
* [Add/Create An Extra Virtual Disk](W03.md)
  * [Finding Your New Disk](W03-01.md)
  * [Formating Your New Disk](W03-02.md)
  * [Mounting Your New Disk](W03-03.md)
  * [Change Owner Your New Disk](W03-04.md)
  * [Test Your New Disk](W03-05.md)
* [Update your bookmark links. See C.B. Kadal&#39;s "LINKS/"](https://cbkadal.github.io/os212/LINKS/)
* [Review your peer links](W02-05.md)
* [Update your log. See C.B. Kadal&#39;s "mylog.txt"](https://cbkadal.github.io/os212/TXT/mylog.txt)
* [Submit Your Week 03 Assignment](W03-06.md)

<br id="idx0704">
## Cicak Bin Kadal: Assignment Week 04

* [Read OSC10 chapter 9](https://www.os-book.com/OS10/slide-dir/)
* [Try Demos in https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/](https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/)
* [Try Previous MidTerm Problems](https://rms46.vlsm.org/2/199.pdf)
* [Install Package List 2 (TLPI)](osp-103.md#idxpl2)
* [Fetch and Extract File "WEEK04.tar.bz2.asc"](W04.md)
  * [Compiling The Linux Programming Interface (TLPI)](W04-01.md)
  * [TLPI: Result](W04-02.md)
  * [Create a new "$HOME/RESULT/W04/" directory](W04-03.md)
* [Update your bookmark links. See C.B. Kadal&#39;s "LINKS/"](https://cbkadal.github.io/os212/LINKS/)
* [Review your peer links](W02-05.md)
* [Update your log. See C.B. Kadal&#39;s "mylog.txt"](https://cbkadal.github.io/os212/TXT/mylog.txt)
* Submit Your Week 04 Assignment. [See Week 03](W03-06.md).


<br id="idx0705">
## Cicak Bin Kadal: Assignment Week 05

* [Read OSC10 chapter 10](https://www.os-book.com/OS10/slide-dir/)
* [Try Demos in https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/](https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/)
* [Try Previous MidTerm Problems](https://rms46.vlsm.org/2/200.pdf)
* [How Low (Memory) Can You Go?](W05-01.md)
  * Fetch and Extract File <https://os.vlsm.org/WEEK/WEEK05.tar.bz2.asc>.
    * For example, see [Fetch and Extract File “WEEK04.tar.bz2.asc”](W04.md)
    * The passphrase will be available during the Zoom Session. Please remind your Lecturer.
  * [Modify mymemory2.c](W05-02.md)
  * Study and run script "000-README.txt"
    * For example, see [Compiling TLPI](W04-01.md).
  * Copy the result (WEEK05-MEMORY.txt) into folder $HOME/RESULT/W05/.
    * For example, see [Create a new “$HOME/RESULT/W04/” directory](W04-03.md).
* [Update your bookmark links. See C.B. Kadal&#39;s "LINKS/"](https://cbkadal.github.io/os212/LINKS/)
* [(Optional) Any suggestions/tips for the next semester class? See C.B. Kadal&#39;s "TIPS/"](https://cbkadal.github.io/os212/TIPS/)
* [Review your peer links](W02-05.md)
* [Update your log. See C.B. Kadal&#39;s "mylog.txt"](https://cbkadal.github.io/os212/TXT/mylog.txt)
* Submit Your Week 05 Assignment. [See Week 03](W03-06.md).

<br id="idx0706">
## Cicak Bin Kadal: Assignment Week 06

* [Read OSC10 chapter 3, 4](https://www.os-book.com/OS10/slide-dir/)
* [Try Demos in https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/](https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/)
* [Try Previous FinalTerm Problems](https://rms46.vlsm.org/2/201.pdf)
* [Fork() and Shared Memory](W06-01.md)
  * Fetch and Extract File <https://os.vlsm.org/WEEK/WEEK06.tar.bz2.asc>.
    * For example, see [Fetch and Extract File “WEEK04.tar.bz2.asc”](W04.md)
    * The passphrase will be available during the Zoom Session. Please remind your Lecturer.
  * Study and run script "000-README.txt"
    * For example, see [Compiling TLPI](W04-01.md).
  * Observe how processes share variables.
  * Copy the result into folder $HOME/RESULT/W06/:
    * WEEK06-FORK.txt
    * WEEK06-SHARE.bin 
    * For example, see [Create a new “$HOME/RESULT/W04/” directory](W04-03.md).
* [Update your bookmark links. See C.B. Kadal&#39;s "LINKS/"](https://cbkadal.github.io/os212/LINKS/)
* [(Optional) Any suggestions/tips for the next semester class? See C.B. Kadal&#39;s "TIPS/"](https://cbkadal.github.io/os212/TIPS/)
* [Review your peer links](W02-05.md)
* [Update your log. See C.B. Kadal&#39;s "mylog.txt"](https://cbkadal.github.io/os212/TXT/mylog.txt)
* Submit Your Week 06 Assignment. [See Week 03](W03-06.md).

<br id="idx0707">
## Cicak Bin Kadal: Assignment Week 07

* [Read OSC10 chapter 6, 7, 8](https://www.os-book.com/OS10/slide-dir/)
* [Try Demos in https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/](https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/)
* [Try Previous FinalTerm Problems](https://rms46.vlsm.org/2/202.pdf)
* Synchronization and Shared Memory
  * Fetch and Extract File <https://os.vlsm.org/WEEK/WEEK07.tar.bz2.asc>.
    * For example, see [Fetch and Extract File “WEEK04.tar.bz2.asc”](W04.md)
    * The passphrase will be available during the Zoom Session. Please remind your Lecturer.
  * Study and run script "000-README.txt"
    * For example, see [Compiling TLPI](W04-01.md).
  * Observe how shared memory works.
  * Read and study file 001-how-to-get-file-WEEK07-REPORT2.txt
  * Copy the result into folder $HOME/RESULT/W07/:
    * WEEK07-MYSHARE.bin
    * WEEK07-REPORT0.txt
    * WEEK07-REPORT1.txt
    * WEEK07-REPORT2.txt
    * For example, see [Create a new “$HOME/RESULT/W04/” directory](W04-03.md).
* [Update your bookmark links. See C.B. Kadal&#39;s "LINKS/"](https://cbkadal.github.io/os212/LINKS/)
* [(Optional) Any suggestions/tips for the next semester class? See C.B. Kadal&#39;s "TIPS/"](https://cbkadal.github.io/os212/TIPS/)
* [Review your peer links](W02-05.md)
* [Update your log. See C.B. Kadal&#39;s "mylog.txt"](https://cbkadal.github.io/os212/TXT/mylog.txt)
* Submit Your Week 07 Assignment. [See Week 03](W03-06.md).

<br id="idx0708">
## Cicak Bin Kadal: Assignment Week 08

* [Read OSC10 chapter 5](https://www.os-book.com/OS10/slide-dir/)
* [Try Demos in https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/](https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/)
* [Try Previous FinalTerm Problems](https://rms46.vlsm.org/2/203.pdf)
* [Linux From Scratch 11.0 Chapter 01-04](W08-01.md)
* [Linux From Scratch 11.0 Chapter 05](W08-02.md)
* [Update your bookmark links. See C.B. Kadal&#39;s "LINKS/"](https://cbkadal.github.io/os212/LINKS/)
* [(Optional) Any suggestions/tips for the next semester class? See C.B. Kadal&#39;s "TIPS/"](https://cbkadal.github.io/os212/TIPS/)
* [Review your peer links](W02-05.md)
* [Update your log. See C.B. Kadal&#39;s "mylog.txt"](https://cbkadal.github.io/os212/TXT/mylog.txt)
* Submit Your Week 08 Assignment. [See Week 03](W03-06.md).

<br id="idx0709">
## Cicak Bin Kadal: Assignment Week 09

* [Read OSC10 chapter 11](https://www.os-book.com/OS10/slide-dir/)
* [Try Demos in https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/](https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/)
* [Try Previous FinalTerm Problems](https://rms46.vlsm.org/2/204.pdf)
* [Linux From Scratch 11.0 part 2](W09.md)
* [Update your bookmark links. See C.B. Kadal&#39;s "LINKS/"](https://cbkadal.github.io/os212/LINKS/)
* [(Optional) Any suggestions/tips for the next semester class? See C.B. Kadal&#39;s "TIPS/"](https://cbkadal.github.io/os212/TIPS/)
* [Review your peer links](W02-05.md)
* [Update your log. See C.B. Kadal&#39;s "mylog.txt"](https://cbkadal.github.io/os212/TXT/mylog.txt)
* Submit Your Week 09 Assignment. [See Week 03](W03-06.md).

<br id="idx0710">
## Cicak Bin Kadal: Assignment Week 10

* [Read OSC10 chapter 12](https://www.os-book.com/OS10/slide-dir/)
* [Try Demos in https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/](https://github.com/UI-FASILKOM-OS/SistemOperasi/tree/master/Demos/)
* [Try Previous FinalTerm Problems](https://rms46.vlsm.org/2/205.pdf)
* [Linux From Scratch 11.0 part 3](W10.md)
* [Update your bookmark links. See C.B. Kadal&#39;s "LINKS/"](https://cbkadal.github.io/os212/LINKS/)
* [(Optional) Any suggestions/tips for the next semester class? See C.B. Kadal&#39;s "TIPS/"](https://cbkadal.github.io/os212/TIPS/)
* [Review your peer links](W02-05.md)
* [Update your log. See C.B. Kadal&#39;s "mylog.txt"](https://cbkadal.github.io/os212/TXT/mylog.txt)
* Submit Your Week 10 Assignment. [See Week 03](W03-06.md).

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

