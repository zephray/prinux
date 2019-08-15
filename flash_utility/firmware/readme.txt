These are the images used for the actual Linux OS.

```u-boot-dtb.imx``` is the u-boot image that would be either flashed into NAND or run in the RAM. It can be built by following the u-boot building instructions.

```zImage``` is the Linux kernel image that would be either flashed into NAND or run in the RAM. It can be built by following the kernel building instructions.

```imx6ull-14x14-prime.dtb``` is the device tree blob that would be either flashed into NAND or run in the RAM. It can be built by following the kernel building instructions.

```rootfs.tar.bz2``` is used for flashing Linux into the NAND flash. This would be your root filesystem.

```rootfs.cpio.uboot``` is used for running Linux in the RAM without modifing the Flash.
