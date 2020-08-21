# test-PiShrink

Simple script to test additional compression options by @framps for the great [PiShrink](https://github.com/Drewsif/PiShrink).

Currently it doesn't need any command line parameters. You can provide the image's name which must reside in the same directory as the script being called. For convenience you may use use the `fetch-raspios_lite_armhf_latest` utility. I've took a few lines from `pishrink.sh` itself to ensure it's being called with root privileges. I've hard coded the image's name to a current version of Raspbian. The code has passed through `shellcheck` and code style is enforced with `shfmt`.

## usage

- `./fetch-raspios_lite_armhf_latest`
- `sudo ./test-pishrink`<image>
- `sudo ./clean-artifacts`

## results

There is a [RESULTS.md](RESULTS.md) file provided for reference (thx @framps for the hint) for a run on my Raspberry Pi 4B 8GB running Ubuntu 20.04 Focal Fossa.
