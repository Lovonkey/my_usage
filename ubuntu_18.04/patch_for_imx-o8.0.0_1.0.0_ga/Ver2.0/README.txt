1.0001-Fix-build-vendor-fix-parttion.patch
到device/fsl下：
git am 0001-Fix-build-vendor-fix-parttion.patch

2.0001-Add-mount-system-and-vendor.patch
到vendor/nxp-opensource/kernel_imx下：
git am 0001-Add-mount-system-and-vendor.patch

3.0001-Fix-allow-ubifs.patch
到system/sepolicy
git am 0001-Fix-allow-ubifs.patch

4.0001-Fix-support-ubifs.patch
到system/core
git am 0001-Fix-support-ubifs.patch

5.0001-Add-support-vendor.patch
到external/mtd-utils
git am 0001-Add-support-vendor.patch
