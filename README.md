# odroid-c2-mainline-patches

This is a set of patches to enable hdmi support on odroid-c2.  
I am **not** the author of these patches, I've just picked the (almost) whole bunch on kernel patchwork.

odroidc2-enable-scpi-dvfs.patch enable scpi without need for uboot fdt voodoo.  
odroidc2-tx-clock-0.patch - this is OPTIONAL, if your emmc works fine out of the box - don't apply it, mine doesn't (CRC errors and RO) so I do need this one.

Huge thanks go for the people from baylibre (https://github.com/baylibre) who are bringing meson support into mainline and all the kernel developers.  
Huge "booooo" goes for hardkernel for not supporting their own hardware, and leaving odroid-c2 users with an outdated kernel plagued by hacks and affected by CVEs.

