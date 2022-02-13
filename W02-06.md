---
---
[HOME](index.md)
[ABOUT](README.md)
[WEB](https://osp4diss.vlsm.org/)
[GITHUB](https://github.com/os2xx/osp4diss/)
[TOP](#)
[BOTTOM](#endofpage)
[PREV](index.md#idx07)
[NEXT](index.md#idx07)

# Generate SHA256SUM and SHA256SUM.asc

## Write (or copy) a simple "myscript.sh" script.

* E.g. C.B. Kadal's "[myscript.sh](https://cbkadal.github.io/os212/TXT/myscript.sh)"

```
#!/bin/bash
# REV00 Sun 12 Sep 2021 03:10:00 WIB
# START Sun 12 Sep 2021 03:10:00 WIB

FILES="my*.txt my*.sh"
SHA="SHA256SUM"

echo "rm -f $SHA $SHA.asc"
rm -f $SHA $SHA.asc

echo "sha256sum $FILES > $SHA"
sha256sum $FILES > $SHA

echo "sha256sum -c $SHA"
sha256sum -c $SHA

echo "gpg --output $SHA.asc --armor --sign --detach-sign $SHA"
gpg --output $SHA.asc --armor --sign --detach-sign $SHA

echo "gpg --verify $SHA.asc $SHA"
gpg --verify $SHA.asc $SHA

exit 0

```

<br>
## Run script "myscript.sh"

```
pwd
bash myscript.sh
ls -al
cat SHA256SUM
cat SHA256SUM.asc

```

```
ZCZC 613D0A9D 58C8E226
cbkadal@cbkadal:~/git/os212/TXT$ pwd

/home/cbkadal/git/os212/TXT

ZCZC 613D0A9F A05807FE
cbkadal@cbkadal:~/git/os212/TXT$ bash myscript.sh

rm -f SHA256SUM SHA256SUM.asc
sha256sum my*.txt my*.sh > SHA256SUM
sha256sum -c SHA256SUM
mylog.txt: OK
mypubkey.txt: OK
myrank.txt: OK
myscript.sh: OK

gpg --output SHA256SUM.asc --armor --sign --detach-sign SHA256SUM
gpg --verify SHA256SUM.asc SHA256SUM
gpg: Signature made Sun 12 Sep 2021 02:59:27 WIB
gpg:                using RSA key CE17E9DB8AD01794E3BAE98B60914D29C01C81F1
gpg: Good signature from "Cicak Bin Kadal (CBK) <cbkadal@localhost>" [ultimate]

ZCZC 613D0A9F A05807FE
cbkadal@cbkadal:~/git/os212/TXT$ ls -al
total 32
drwxr-xr-x 2 cbkadal cbkadal 4096 Sep 12 02:59 .
drwxr-xr-x 9 cbkadal cbkadal 4096 Sep 12 02:53 ..
-rw-r--r-- 1 cbkadal cbkadal  674 Sep 10 12:05 mylog.txt
-rw-r--r-- 1 cbkadal cbkadal 3159 Sep 11 21:33 mypubkey.txt
-rw-r--r-- 1 cbkadal cbkadal   67 Sep 11 22:39 myrank.txt
-rw-r--r-- 1 cbkadal cbkadal  393 Sep 12 02:47 myscript.sh
-rw-r--r-- 1 cbkadal cbkadal  310 Sep 12 02:59 SHA256SUM
-rw-r--r-- 1 cbkadal cbkadal  833 Sep 12 02:59 SHA256SUM.asc

ZCZC 613D0A9F A05807FE
cbkadal@cbkadal:~/git/os212/TXT$ cat SHA256SUM
4b4331a114069d33aae50c70ea77df0f2a5b27c2b174a9bcdc248eebc9515970  mylog.txt
91e910f06790e5db817c19877e438795682d641cffabb2b1b92e3fb0c61a6b0b  mypubkey.txt
356b8f903d3f795aa1220f64d64bccf33748fbcf94e62e5ed6463dcfab4c5fb3  myrank.txt
b948dc8a75101b1de62f2717880297c2dfd720b72dce1a00e911778736ba2b90  myscript.sh

ZCZC 613D0A9F A05807FE
cbkadal@cbkadal:~/git/os212/TXT$ cat SHA256SUM.asc
-----BEGIN PGP SIGNATURE-----

iQIzBAABCgAdFiEEzhfp24rQF5TjuumLYJFNKcAcgfEFAmE9Cp8ACgkQYJFNKcAc
gfFBsxAAvhRdg6JK6hPfPkJN+UDweKBNRrBIgaQL1LyhUxnuQbORdh9wUdiznDpg
5K3H1TzTiZ9ESNTPoU/XPaUMSoO0ki/P9JevOYWtVvRO1xLNDES1+kn53W0wCqcW
KTKKylOLc0XnG+Nre6pg9GaJbSoyD3NPlgkG94Nk+B8KivS1hC2WXolnmGnqZRL7
o+NcIe01fzk64NJdNhkmE92TDmm4l0rOwniK7yeVSr81hA2p7L2S8usX1pBdtMcx
L+UUQDmkznRV/UC+YrWoim+eQBtpYKUjMZ6VwjFBrxC0GrjvSxl642hWuyFrnrWv
xP6ResP/zeSjAlKH/Y5l+aNBuv2BWM2A2ooeWBTGofgdPFvqZ5JyXG1suK7KUlwv
0p7Qydy9NvjQrk7ZWT8X4zafe9LTdNO8nG+YqSe8Ipqgck/Yv6FJk42tjMsRU5+G
Mibea+TKKfrWf1S/06FApYFfgwb59srgV7RcO1t9bk5G6vkfhG1G/BIAx8edNgGO
Vk9EM/TEvw/Jv3qiYwI5PkCO3JoOibslwWSkmcylLLkl5cq2rppftlUJAPCemNhR
UpnT329xXhSL/FoWF3ZJVeztvPlw/nR7knznp8PAJmQ+g87sCBaikyQPsV+KmxVw
4U3UsJrksRBvOJ9QOTInVXo1iS7C6Bg38Sn1qNy611mr7aBZP20=
=l5bB
-----END PGP SIGNATURE-----

ZCZC 613D0A9F A05807FE
cbkadal@cbkadal:~/git/os212/TXT$

```

<br>
## Do the four (4) Git Mantras

```
pwd
git add -A
git commit -m "OS212 cbkadal TXT"
git pull
git push

```

```
ZCZC 613D0D25 F90516E3
cbkadal@cbkadal:~/git/os212/TXT$ pwd
/home/cbkadal/git/os212/TXT

ZCZC 613D0D2F 0666DB5B
cbkadal@cbkadal:~/git/os212/TXT$ git add -A

ZCZC 613D0D2F 0666DB5B
cbkadal@cbkadal:~/git/os212/TXT$ git commit -m "OS212 cbkadal TXT"
[master c90272a] OS212 cbkadal TXT
 3 files changed, 19 insertions(+), 19 deletions(-)
 rewrite TXT/SHA256SUM.asc (91%)

ZCZC 613D0D2F 0666DB5B
cbkadal@cbkadal:~/git/os212/TXT$ git pull
Current branch master is up to date.

ZCZC 613D0D32 12B5C030
cbkadal@cbkadal:~/git/os212/TXT$ git push
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 6 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.27 KiB | 1.27 MiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To github.com:cbkadal/os212.git
   0f2ef17..c90272a  master -> master

ZCZC 613D0D34 740F2052
cbkadal@cbkadal:~/git/os212/TXT$

```

<br id="endofpage"><br>
[HOME](index.md)
[ABOUT](README.md)
[WEB](https://osp4diss.vlsm.org/)
[GITHUB](https://github.com/os2xx/osp4diss)
[TOP](#)
[BOTTOM](#endofpage)
[PREV](index.md#idx07)
[NEXT](index.md#idx07)

