# TrueMark Disk Script

This script is an answer to issues suffered where NVME disk order is
unpredictable and inconsistent. This script will list disk devices in a
predictable order. For AWS and Terraform, this means disks will be listed in
the order they were defined for the EC2 instance.

## Remote Install
sudo bash <(curl -sL https://raw.githubusercontent.com/truemark/tmdisk/master/install)

## Usage

List out all disks in order
```bash
tmdisk
```

Get the first disk name
```bash
tmdisk 0
```

Get the second disk name
```bash
tmdisk 1
```

