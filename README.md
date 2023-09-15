# ubuntu-custom-images

An example repository to show how to build custom Ubuntu images with GitHub Actions

## Usage
- Download a compressed ISO image from the [releases section](https://github.com/epassaro/ubuntu-custom-images/releases)
- Create a bootable pendrive using `dd` or a tool like [ROSA Image Writer](http://wiki.rosalab.ru/en/index.php/ROSA_ImageWriter)

## Details
- Configuration files are located under the `config` folder
- Custom images are built using a [GitHub Actions workflow](https://github.com/epassaro/ubuntu-custom-images/blob/main/.github/workflows/build.yml)
- I made use of the `xubuntu-core` package, resulting in smaller image sizes
- Images are compressed aggressively using `bzip2` (GitHub release assets have a limit of 2GB)

## Credits

This repository makes use of the scripts from the [Live Custom Ubuntu from Scratch](https://github.com/mvallim/live-custom-ubuntu-from-scratch) repository
