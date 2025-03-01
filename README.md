# Images
For images, please view the Releases tab.
# Code
Kernel is based on linux v6.13.5. Initramfs comes from kernel.
For rootfs, build stable versions of coreutils, glibc, upack*, bash, sh, systemd, booster, a bootloader (ArcaneOS typically would use an EFI boot stub, but you could use another bootloader such as GRUB) and its dependencies (ex. upack requires curl and libzip), then `upack init`

<nohtml>*</nohtml> - Upack has no stable release rn, just install the latest beta or alpha version
