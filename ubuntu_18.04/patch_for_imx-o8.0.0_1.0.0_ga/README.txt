1.mtd-utils.zip
解压后拷贝到external目录

2.0001-Fix-build-support-ubifs.patch
到build/make下：
git am 0001-Fix-build-support-ubifs.patch

3.0001-Fix-device-fsl-support-nand-ubifs.patch
到device/fsl下：
git am 0001-Fix-device-fsl-support-nand-ubifs.patch

4.0001-Fix-uboot-support-nand-boot.patch
到vendor/nxp-opensource/uboot-imx下：
git am 0001-Fix-uboot-support-nand-boot.patch

5.0001-Fix-kernel-support-nand-boot.patch
到vendor/nxp-opensource/kernel_imx下：
git am 0001-Fix-kernel-support-nand-boot.patch

6.拷贝mfg_Android_O8.0.0_1.0.0.zip到Windows下使用,使用方法参照README