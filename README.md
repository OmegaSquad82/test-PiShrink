# test-PiShrink

Small script to test additional compression options by @framps and @nhkhai for the great [PiShrink](https://github.com/Drewsif/PiShrink).

Currently it doesn't need any command line parameters. You can provide the image's name which must reside in the same directory as the script being called. For convenience you may use use the `fetch-raspios_lite_armhf_latest` utility. I've took a few lines from `pishrink.sh` itself to ensure it's being called with root privileges. I've hard coded the image's name to a current version of Raspbian. The code has passed through `shellcheck` and code style is enforced with `shfmt`. When you're done with all the `gz`, `xz` and `log` files then `clean-artifacts` will remove them for you.

## requirements

- `bash` (approximately v4 or newer)
- `curl` (must support `filename_effective`)
- `lsb_release`, `uname`, `time` from GNU / Debian
- `pishrink.sh` of PR #154 (with 12 + 2 permutations of compression options)

## usage

- `./fetch-raspios_lite_armhf_latest`
- `sudo ./test-pishrink`<image>
- `sudo ./clean-artifacts`

## results

There is an initial [Raspberry Pi 4B 8GB running Ubuntu 20.04 Focal Fossa on aarch64](results/rpi4b8gb-ubuntufocal-arm64.md) resultset provided for reference.
