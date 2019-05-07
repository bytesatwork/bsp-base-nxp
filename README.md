# bytes at work AG BSP base files for IMX8MM based modules

This repository is intended to setup a working Yocto Project environment to
build software for byteDEVKIT IMX8MM by [bytes at work AG](https://www.bytesatwork.io).

## Usage

This repository is used with [meta-bytesatwork](https://github.com/bytesatwork/meta-bytesatwork)
and [meta-bytesatwork-nxp](https://github.com/bytesatwork/meta-bytesatwork-nxp).

Example:

	MACHINE=bytedevkit-imx8mm DISTRO=poky-bytesatwork EULA=1 . setup-environment build

Please have a look at the mentioned repositories for possible combinations of
images, machines, and distros.

For an easier setup, have a look at
[bsp-platform-nxp](https://github.com/bytesatwork/bsp-platform-nxp).
