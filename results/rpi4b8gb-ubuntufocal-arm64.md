# test results

- Started: 2020-08-25T14:48:20+02:00
- Version: pishrink.sh v0.1.2

## sysinfo

- Distribution: Ubuntu 20.04.1 LTS
- Kernel: Linux 5.4.0-1016-raspi aarch64
- Version: #17-Ubuntu SMP Wed Aug 19 14:54:44 UTC 2020
- Machine: Broadcom Inc. and subsidiaries Device 2711 (rev 10)
- Memory:
  total used free shared buffers cache available
  Mem: 7,6Gi 1,7Gi 3,6Gi 36Mi 12Mi 2,4Gi 5,8Gi
  Swap: 0B 0B 0B

## test-pishrink

### executions

#### pishrink.sh -dz 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-z-flag.img

- time measured: real 3m11,387s user 2m58,001s sys 0m10,807s CPU 98,65%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-z-flag.img.gz from 1,8G to 435M ...
- Compression ratio: 24,66%

#### pishrink.sh -dza 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-za-flag.img

- time measured: real 1m1,855s user 3m9,142s sys 0m14,923s CPU 329,93%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-za-flag.img.gz from 1,8G to 434M ...
- Compression ratio: 24,62%

#### pishrink.sh -dZ 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-Z-flag.img

- time measured: real 24m52,916s user 24m33,604s sys 0m13,627s CPU 99,62%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-Z-flag.img.xz from 1,8G to 297M ...
- Compression ratio: 16,82%

#### pishrink.sh -dZa 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-Za-flag.img

- time measured: real 8m58,706s user 32m20,836s sys 0m13,107s CPU 362,71%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-Za-flag.img.xz from 1,8G to 301M ...
- Compression ratio: 17,09%

#### pishrink.sh -dzc 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-zc-pr154.img

- time measured: real 1m24,762s user 1m11,344s sys 0m10,777s CPU 96,88%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-zc-pr154.img.gz from 1,8G to 471M ...
- Compression ratio: 26,75%

#### pishrink.sh -dzC 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-zC-pr154.img

- time measured: real 8m14,270s user 8m0,582s sys 0m10,763s CPU 99,41%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-zC-pr154.img.gz from 1,8G to 432M ...
- Compression ratio: 24,54%

#### pishrink.sh -dzac 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-zac-pr154.img

- time measured: real 0m30,221s user 1m6,907s sys 0m14,959s CPU 270,89%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-zac-pr154.img.gz from 1,8G to 469M ...
- Compression ratio: 26,64%

#### pishrink.sh -dzaC 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-zaC-pr154.img

- time measured: real 2m27,696s user 8m24,028s sys 0m15,778s CPU 351,95%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-zaC-pr154.img.gz from 1,8G to 432M ...
- Compression ratio: 24,51%

#### pishrink.sh -dZc 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-Zc-pr154.img

- time measured: real 4m29,897s user 4m14,420s sys 0m12,335s CPU 98,83%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-Zc-pr154.img.xz from 1,8G to 371M ...
- Compression ratio: 21,04%

#### pishrink.sh -dZC 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-ZC-pr154.img

- time measured: real 29m51,311s user 29m29,911s sys 0m14,892s CPU 99,63%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-ZC-pr154.img.xz from 1,8G to 269M ...
- Compression ratio: 15,26%

#### pishrink.sh -dZac 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-Zac-pr154.img

- time measured: real 1m44,584s user 5m54,597s sys 0m12,546s CPU 351,06%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-Zac-pr154.img.xz from 1,8G to 373M ...
- Compression ratio: 21,18%

#### pishrink.sh -dZaC 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-ZaC-pr154.img

- time measured: real 11m54,294s user 38m22,666s sys 0m22,197s CPU 325,51%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-ZaC-pr154.img.xz from 1,8G to 276M ...
- Compression ratio: 15,66%

#### pishrink.sh -dZec 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-Zec-pr154.img

- time measured: real 28m34,308s user 28m9,445s sys 0m16,838s CPU 99,53%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-Zec-pr154.img.xz from 1,8G to 338M ...
- Compression ratio: 19,18%

#### pishrink.sh -dZeC 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-ZeC-pr154.img

- time measured: real 45m37,939s user 45m14,245s sys 0m15,848s CPU 99,71%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-ZeC-pr154.img.xz from 1,8G to 268M ...
- Compression ratio: 15,22%

#### pishrink.sh -dZeac 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-Zeac-pr154.img

- time measured: real 10m15,287s user 32m57,301s sys 0m13,569s CPU 323,61%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-Zeac-pr154.img.xz from 1,8G to 342M ...
- Compression ratio: 19,39%

#### pishrink.sh -dZeaC 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-ZeaC-pr154.img

- time measured: real 17m17,854s user 53m3,139s sys 0m21,804s CPU 308,82%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-ZeaC-pr154.img.xz from 1,8G to 276M ...
- Compression ratio: 15,63%

#### pishrink.sh -dz 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-z-env.img

2020-08-20-raspios-buster-armhf-lite-z-env.img: 72.0% -- replaced with 2020-08-20-raspios-buster-armhf-lite-z-env.img.gz

- time measured: real 1m27,995s user 1m12,118s sys 0m12,309s CPU 95,94%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-z-env.img.gz from 1,8G to 471M ...
- Compression ratio: 26,75%

#### pishrink.sh -dZ 2020-08-20-raspios-buster-armhf-lite.img 2020-08-20-raspios-buster-armhf-lite-Z-env.img

2020-08-20-raspios-buster-armhf-lite-Z-env.img: 372,8 MiB / 1.683,7 MiB = 0,221, 16 MiB/s, 1:47

- time measured: real 1m57,187s user 5m52,141s sys 0m12,299s CPU 311,00%
- pishrink.sh: Shrunk 2020-08-20-raspios-buster-armhf-lite-Z-env.img.xz from 1,8G to 373M ...
- Compression ratio: 21,18%

### archives by size:

```bash
-rw-r--r-- 1 root root 471M Aug 25 18:09 2020-08-20-raspios-buster-armhf-lite-z-env.img.gz
-rw-r--r-- 1 root root 471M Aug 25 15:26 2020-08-20-raspios-buster-armhf-lite-zc-pr154.img.gz
-rw-r--r-- 1 root root 469M Aug 25 15:36 2020-08-20-raspios-buster-armhf-lite-zac-pr154.img.gz
-rw-r--r-- 1 root root 435M Aug 25 14:48 2020-08-20-raspios-buster-armhf-lite-z-flag.img.gz
-rw-r--r-- 1 root root 434M Aug 25 14:51 2020-08-20-raspios-buster-armhf-lite-za-flag.img.gz
-rw-r--r-- 1 root root 432M Aug 25 15:28 2020-08-20-raspios-buster-armhf-lite-zC-pr154.img.gz
-rw-r--r-- 1 root root 432M Aug 25 15:36 2020-08-20-raspios-buster-armhf-lite-zaC-pr154.img.gz
-rw-r--r-- 1 root root 373M Aug 25 18:10 2020-08-20-raspios-buster-armhf-lite-Z-env.img.xz
-rw-r--r-- 1 root root 373M Aug 25 16:13 2020-08-20-raspios-buster-armhf-lite-Zac-pr154.img.xz
-rw-r--r-- 1 root root 371M Aug 25 15:39 2020-08-20-raspios-buster-armhf-lite-Zc-pr154.img.xz
-rw-r--r-- 1 root root 342M Aug 25 17:41 2020-08-20-raspios-buster-armhf-lite-Zeac-pr154.img.xz
-rw-r--r-- 1 root root 338M Aug 25 16:27 2020-08-20-raspios-buster-armhf-lite-Zec-pr154.img.xz
-rw-r--r-- 1 root root 301M Aug 25 15:17 2020-08-20-raspios-buster-armhf-lite-Za-flag.img.xz
-rw-r--r-- 1 root root 297M Aug 25 14:52 2020-08-20-raspios-buster-armhf-lite-Z-flag.img.xz
-rw-r--r-- 1 root root 276M Aug 25 16:15 2020-08-20-raspios-buster-armhf-lite-ZaC-pr154.img.xz
-rw-r--r-- 1 root root 276M Aug 25 17:51 2020-08-20-raspios-buster-armhf-lite-ZeaC-pr154.img.xz
-rw-r--r-- 1 root root 269M Aug 25 15:43 2020-08-20-raspios-buster-armhf-lite-ZC-pr154.img.xz
-rw-r--r-- 1 root root 268M Aug 25 16:55 2020-08-20-raspios-buster-armhf-lite-ZeC-pr154.img.xz
```
