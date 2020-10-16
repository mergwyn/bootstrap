# bootstrap

Scripts to bootstrap containers and physical machines.

The zfs sub directory contains a series of scripts designed to setup a zfs root. largely based on https://github.com/zfsonlinux/pkg-zfs/wiki/HOWTO-install-Ubuntu-16.04-to-a-Whole-Disk-Native-ZFS-Root-Filesystem-using-Ubiquity-GUI-installer

These scripts go alittle further with whole disk support in the they use the standard partitioning from zpool create.

Firstly setup the "conf" file as you wish, then incremently run each of the numbered scripts, checking output as you go.  i guess the scripts could be combined into a single script, but i like the cautious approach.
