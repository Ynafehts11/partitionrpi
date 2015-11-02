# partitionrpi
sudo apt-get install xfsprogs
sudo fdisk /dev/mmcblk0
sudo mkfs.xfs -f /dev/mmcblk0p3
sudo mount -t xfs /dev/mmcblk0p3 /storage
df -Th /storage 
