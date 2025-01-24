# Setting up a Drive to autoconnect at startup on Fedora

## Use command to get drive information:
```
lsblk -f 
```

## Information needed
- Partition Name example: /dev/nvme1n1p1
- File System: BTFRS EXT4 ETC
- UUID
- Mount Pain


```bash
$ cat /etc/fstab

#
# /etc/fstab
# Created by anaconda on Tue Dec 24 22:13:08 2024
#
# Accessible filesystems, by reference, are maintained under '/dev/disk/'.
# See man pages fstab(5), findfs(8), mount(8) and/or blkid(8) for more info.
#
# After editing this file, run 'systemctl daemon-reload' to update systemd
# units generated from this file.
#
UUID=HASHNUMBER /                       btrfs   subvol=root,compress=zstd:1 0 0
UUID=HASHNUMBER /boot                   ext4    defaults        1 2
UUID=HASHNUMBER /home                   btrfs   subvol=home,compress=zstd:1 0 0
UUID=HASHNUMBER /run/media/username/drivename ext4    defaults,nofail        0 2
```
