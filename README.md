android_kernel_Google_glass_1
=============================

The kernel source for OMAP devices. Branches beginning with "glass-omap-" contain the source for Google Glass. For example, the kernel source for XE17.3 is "glass-omap-xrv60b"

Checkout the desired branch into {CM.ROOT}/kernel/Google/glass_1 and build the recovery image with the following in your BoardConfig.mk:

```
TARGET_KERNEL_SOURCE := kernel/Google/glass_1
TARGET_KERNEL_CONFIG := notle_defconfig
```
