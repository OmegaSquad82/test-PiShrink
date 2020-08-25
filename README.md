# test-PiShrink

Small script to test additional compression options by @framps and @nhkhai for the great [PiShrink](https://github.com/Drewsif/PiShrink).

Currently it doesn't need any command line parameters. You can provide the image's name which must reside in the same directory as the script, otherwise it will fetch an upstream image. I've took a few lines from `pishrink.sh` itself to ensure it's being called with root privileges and necessary tools are installed. When it's done all the `gz`, `xz` and `log` files will be removed. The code has passed through `shellcheck` and code style is enforced with `shfmt`.

## requirements

- `bash` (approximately v4 or newer)
- `curl` (must support `filename_effective`)
- `pishrink.sh` of either `master` or PR#154 commit `4e90956eb1cd60f7e0ed33756d01d4d637c9b01c`

## PiShrink versions supported

While the former supports the flags `-azZ` and environment variables resulting in 4 + 2 permutations of compression options the latter carries three more flags `-cCe` resulting in 15 + 2 permutations. An Utility to download an install PiShrink to the system is also provided.

## usage

- `sudo ./install-pishrink <treeish> <target>` # installs 'master' into '/usr/local/bin/'
- `sudo ./test-pishrink <image>` # downloads and extracts 'raspios_lite_armhf_latest'

## results

There are resultsets provided for reference:

- [Raspberry Pi 4B 4GB running Raspbian Lite on armv7l](results/rpi4b4gb-raspbian-armhf.md)
- [Raspberry Pi 4B 4GB running RasPiOS Full on aarch64](results/rpi4b4gb-raspios-arm64.md)
- [Raspberry Pi 4B 8GB running Ubuntu 20.04 Focal Fossa on aarch64](results/rpi4b8gb-ubuntufocal-arm64.md)
