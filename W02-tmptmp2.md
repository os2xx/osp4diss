---
---
[HOME](index.md)
[ABOUT](README.md)
[WEB](https://osp4diss.vlsm.org/)
[GITHUB](https://github.com/os2xx/osp4diss/)
[TOP](#)
[BOTTOM](#endofpage)
[PREV](W02-01.md)
[NEXT](W02-03.md)

<br>
## Importing the Operating Systems public key

* Source: <https://osp4diss.vlsm.org/ETC/rmspubkey.txt>

```
wget -c https://osp4diss.vlsm.org/ETC/rmspubkey.txt
gpg --import rmspubkey.txt
gpg --list-keys

```

```
cbkadal@cbkadal:~/tmp$ wget -c https://osp4diss.vlsm.org/ETC/rmspubkey.txt
--2022-02-07 22:33:36--  https://osp4diss.vlsm.org/ETC/rmspubkey.txt
Resolving osp4diss.vlsm.org (osp4diss.vlsm.org)... 185.199.111.153, 185.199.110.153, 185.199.109.153, ...
Connecting to osp4diss.vlsm.org (osp4diss.vlsm.org)|185.199.111.153|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 3143 (3.1K) [text/plain]
Saving to: ‘rmspubkey.txt’

rmspubkey.txt      100%[===========================>]   3.07K  --.-KB/s    in 0s      

2022-02-07 22:33:36 (14.9 MB/s) - ‘rmspubkey.txt’ saved [3143/3143]

cbkadal@cbkadal:~/tmp$ gpg --import rmspubkey.txt
gpg: key 63FB12B215403B20: public key "RMS46 (RMS46) <rms46@ui.ac.id>" imported
gpg: Total number processed: 1
gpg:               imported: 1

cbkadal@cbkadal:~/tmp$ gpg --list-keys
/home/cbkadal/.gnupg/pubring.kbx
--------------------------------
pub   rsa4096 2021-09-11 [SC] [expires: 2023-02-07]
      CE17E9DB8AD01794E3BAE98B60914D29C01C81F1
uid           [ultimate] Cicak Bin Kadal (CBK) <cbkadal@localhost>
sub   rsa4096 2021-09-11 [E] [expires: 2023-02-07]

pub   rsa4096 2022-02-07 [SC] [expires: 2023-02-07]
      055FEB594B351CC03DE992C563FB12B215403B20
uid           [ unknown] RMS46 (RMS46) <rms46@ui.ac.id>
sub   rsa4096 2022-02-07 [E] [expires: 2023-02-07]

```

<br id="endofpage"><br>
[HOME](index.md)
[ABOUT](README.md)
[WEB](https://osp4diss.vlsm.org/)
[GITHUB](https://github.com/os2xx/osp4diss)
[TOP](#)
[BOTTOM](#endofpage)
[PREV](W02-01.md)
[NEXT](W02-03.md)

