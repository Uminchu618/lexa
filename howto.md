    1  ls
    2  mkfs.ext4 /dev/vdb
    3  mkdir /mnt/ext
    4  mount /dev/vdb /mnt/ext
    5  echo "/dev/vdb /mnt/ext ext4 defaults 0 0" >> /etc/fstab
    6  history
