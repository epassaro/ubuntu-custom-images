# ubuntu-custom-images

An example repository to show how to build custom Ubuntu images with GitHub Actions

## Usage
- Download an compressed ISO image from the [releases section](https://github.com/epassaro/ubuntu-custom-images/releases)
- Create a bootable pendrive using `dd` or a tool like [ROSA Image Writer](http://wiki.rosalab.ru/en/index.php/ROSA_ImageWriter)

## Details
- Custom images are built using a [GitHub Actions workflow](https://github.com/epassaro/ubuntu-custom-images/blob/main/.github/workflows/build.yml)
- I selected the LXDE desktop environment and compressed the ISO using the `bz2` algorithm because GitHub assets have a limit of 2GB

## Credits

This repository makes use of the scripts from [Live Custom Ubuntu from Scratch](https://github.com/mvallim/live-custom-ubuntu-from-scratch)
