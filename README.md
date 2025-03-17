# Images
For images, please view the Releases tab.
# Code
Kernel is based on linux v6.12.19. Initramfs comes from kernel.
For rootfs, build LTS versions of coreutils, glibc, upack*, bash, sh, systemd, dracut, a bootloader (ArcaneOS typically would use an EFI boot stub, but you could use another bootloader such as GRUB) and its [build] dependencies (ex. upack requires rust) then compress in squashfs format

<nohtml>*</nohtml> - Upack has no stable release rn, just install the latest beta or alpha version
