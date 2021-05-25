# Manjaro ARM Rock64
[![iso_build](https://github.com/manjaro-arm/rock64-images/workflows/image_build_all/badge.svg)](https://github.com/manjaro-arm/rock64-images/actions)

## description

Release Branch for Manjaro ARM images for the Rock64

## where can I download an iso?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-arm/rock-images/releases)

## sources

- [image profile](https://github.com/manjaro-pinephone/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d rock64 -e $EDITION`
