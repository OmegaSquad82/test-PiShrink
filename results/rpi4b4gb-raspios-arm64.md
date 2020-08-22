# test results

- Started: 2020-08-22T16:05:26+02:00
- Version: pishrink.sh v0.1.2.2

## sysinfo

- Distribution: Debian GNU/Linux 10 (buster)
- Kernel: Linux
- Release: 5.4.51-v8+
- Version: #1333 SMP PREEMPT Mon Aug 10 16:58:35 BST 2020
- Machine: aarch64

## test-pishrink

### executions

#### pishrink.sh -dzc 2020-05-27-raspios-buster-lite-armhf.img 2020-05-27-raspios-buster-lite-armhf-zc.img

- time measured: 72.46user 13.65system 1:32.97elapsed 92%CPU
- pishrink.sh: Shrunk 2020-05-27-raspios-buster-lite-armhf-zc.img.gz from 1,8G to 472M ratio 26,65% ...

#### pishrink.sh -dz 2020-05-27-raspios-buster-lite-armhf.img 2020-05-27-raspios-buster-lite-armhf-z.img

- time measured: 177.52user 12.99system 3:17.34elapsed 96%CPU
- pishrink.sh: Shrunk 2020-05-27-raspios-buster-lite-armhf-z.img.gz from 1,8G to 434M ratio 24,54% ...

#### pishrink.sh -dzC 2020-05-27-raspios-buster-lite-armhf.img 2020-05-27-raspios-buster-lite-armhf-zC.img

- time measured: 484.24user 12.89system 8:24.08elapsed 98%CPU
- pishrink.sh: Shrunk 2020-05-27-raspios-buster-lite-armhf-zC.img.gz from 1,8G to 432M ratio 24,42% ...

#### pishrink.sh -dzac 2020-05-27-raspios-buster-lite-armhf.img 2020-05-27-raspios-buster-lite-armhf-zac.img

- time measured: 66.42user 16.90system 0:34.77elapsed 239%CPU
- pishrink.sh: Shrunk 2020-05-27-raspios-buster-lite-armhf-zac.img.gz from 1,8G to 470M ratio 26,54% ...

#### pishrink.sh -dza 2020-05-27-raspios-buster-lite-armhf.img 2020-05-27-raspios-buster-lite-armhf-za.img

- time measured: 187.32user 15.91system 1:05.29elapsed 311%CPU
- pishrink.sh: Shrunk 2020-05-27-raspios-buster-lite-armhf-za.img.gz from 1,8G to 434M ratio 24,51% ...

#### pishrink.sh -dzaC 2020-05-27-raspios-buster-lite-armhf.img 2020-05-27-raspios-buster-lite-armhf-zaC.img

- time measured: 507.00user 16.00system 2:28.91elapsed 351%CPU
- pishrink.sh: Shrunk 2020-05-27-raspios-buster-lite-armhf-zaC.img.gz from 1,8G to 432M ratio 24,39% ...

#### pishrink.sh -dZac 2020-05-27-raspios-buster-lite-armhf.img 2020-05-27-raspios-buster-lite-armhf-Zac.img

- time measured: 336.57user 13.00system 1:43.56elapsed 337%CPU
- pishrink.sh: Shrunk 2020-05-27-raspios-buster-lite-armhf-Zac.img.xz from 1,8G to 373M ratio 21,05% ...

#### pishrink.sh -dZa 2020-05-27-raspios-buster-lite-armhf.img 2020-05-27-raspios-buster-lite-armhf-Za.img

- time measured: 1801.21user 15.14system 8:14.32elapsed 367%CPU
- pishrink.sh: Shrunk 2020-05-27-raspios-buster-lite-armhf-Za.img.xz from 1,8G to 301M ratio 16,99% ...

#### pishrink.sh -dZaC 2020-05-27-raspios-buster-lite-armhf.img 2020-05-27-raspios-buster-lite-armhf-ZaC.img

- time measured: 290.69user 18.95system 1:45.47elapsed 293%CPU
- Command exited with non-zero status 18 (xz: insufficient memory)
