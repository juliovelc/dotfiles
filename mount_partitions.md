# In order to mount partitions in linux, follow the steps below:
1. Run `sudo blkid -c /dev/null` -> this will display all all partitions and devices
2. Find the partition reading the labels, create an empty folder, there the partition will be mounted, one empty folder per partition
3. Run `sudo mount -t <type> /dev/<partition name> /mnt/<empty directory name> (type and partition name is extracted from blkid output)
4. This process is temporary until I use the unmount command, or restart the pc, to make it permanent, I need to enter it into /etc/fstab. Run `sudo mount -a` to mount everythin in /etc/fstab



