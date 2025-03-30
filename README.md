# Images
For images, please view the Releases tab.
# Instructions
Kernel is based on linux v6.12.19. Initramfs comes from kernel built from dracut. For rootfs bootstrap glibc, bash, sh, coreutils, upack, systemd, dracut, getty, and a bootloader (ArcaneOS uses a EFI boot stub, but you can use another bootloader like GRUB.) into a upack prefix. After that you compress the rootfs in squashfs format.
<nohtml>*</nohtml> - Upack has no stable release rn, just install the latest beta or alpha version
