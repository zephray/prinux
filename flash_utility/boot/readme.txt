These are the images used for nand flashing environment. They will not be flashed into NAND Flash, they are only used during flashing process.

Put ```fsl-image-mfgtool-initramfs-imx_mfgtools.cpio.gz.u-boot```, ```zImage```, ```imx6ull-14x14-prime.dtb```, ```u-boot-dtb.imx```, and ```u-boot-dtb-nomtdpart.imx``` here.

```fsl-image-mfgtool-initramfs-imx_mfgtools.cpio.gz.u-boot``` and ```zImage``` can be found in NXP's Linux OS release (need to be 4.14 or newer, can be found at https://www.nxp.com/design/software/embedded-software/linux-software-and-development-tools/embedded-linux-for-i.mx-applications-processors:IMXLINUX?tab=Design_Tools_Tab).

```imx6ull-14x14-prime.dtb``` can be built by following the kernel building instructions.

```u-boot-dtb.imx``` can be built by following the uboot building instructions.

```u-boot-dtb-nomtdpart.imx``` is a modified version of u-boot, which does not pass NAND partition informations to the kernel, allowing doing operations to the whole NAND flash such as backup and restore the original OS.
