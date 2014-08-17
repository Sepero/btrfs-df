btrfs-df
========

Print btrfs file system disk free space, similar to standard df

Usage:

    # btrfs-df 
    Filesystem      Size     Used    Avail Use% Mounted on
    /dev/sdb1    461.94G  535.36M       NA   NA /mnt/btrfs1

Currently this script does not support printing available space or percentage used. The output is designed to look and feel similar to that of standard `df`.

Depends on: bash, btrfs-tools, awk, printf
