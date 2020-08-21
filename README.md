Awesome-Install
===============


-------------------------------------------
Installation guide for arch awesome on xfce
-------------------------------------------


*Install arch linux following the arch wiki guide*



https://wiki.archlinux.org/index.php/Installation_guide:

- Set the keyboard layout

- Connect to the internet

- Update the system clock

- Partition the disks

- Format the partitions

- Mount the file systems

- Select the mirrors

- Install essential packages: base base-devel linux linux-firmware linux-headers networkmanager vim man-db man-pages texinfo grub efibootmgr

- Fstab

- Chroot

- Time zone

- Localization

- Network configuration

- Root password

- Boot loader

- microcode

- Reboot

## Post installation

### Add user

- useradd -m -g wheel username

- passwd username

### Give sudo to user

- Modify /etc/sudoers
