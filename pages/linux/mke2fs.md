# mke2fs

> Create a Linux filesystem inside a partition.
> More information: <https://manned.org/mke2fs>.

- Create an ext2 filesystem in partition 1 of device b (`sdb1`):

`mke2fs -t ext2 {{/dev/sdb1}}`

- Create an ext3 filesystem in partition 1 of device b (`sdb1`):

`mke2fs -t ext3 {{/dev/sdb1}}`

- Create an ext4 filesystem in partition 1 of device b (`sdb1`):

`mke2fs -t ext4 {{/dev/sdb1}}`
