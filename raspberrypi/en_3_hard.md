What is the name of the default graphical environment in Raspberry Pi OS?
- LXDE
- GNOME
- KDE

What utility allows you to create and manage disk partitions in Linux?
- fdisk
- mkfs
- mount

Which file in Linux contains system configurations for booting?
- /boot/grub/grub.cfg
- /etc/fstab
- /var/log/syslog

How can you check the filesystem consistency on a Raspberry Pi without unmounting the system?
- Using the `fsck -n` command
- Using the `df -h` command
- Using the `lsblk` command

What is the purpose of the `initramfs` parameter during Linux boot?
- To provide a temporary filesystem for booting the system before mounting the root filesystem
- To configure the network during boot
- To manage swap space on the system

How can you enable the execution of scripts at system startup on a Raspberry Pi?
- By placing the script in the `/etc/init.d/` directory and creating a symbolic link in `/etc/rc.d/`
- By editing the `/etc/rc.local` file to run the script at the end of the boot process
- By using the `update-rc.d` command to add the script to the runlevels

Which file in Linux contains definitions of available hardware devices?
- `/proc/devices`
- `/etc/devices`
- `/var/log/dmesg`

What command is used to verify the integrity of installed packages on a Debian-based distribution?
- `debsums`
- `dpkg`
- `apt-get`

Which configuration file is used to specify network options for interfaces in Linux when using `systemd-networkd`?
- `/etc/systemd/network/*.network`
- `/etc/network/interfaces`
- `/etc/sysconfig/network-scripts/ifcfg-*`

What is the "Loadable Kernel Module" (LKM) and how is it used in Linux?
- A module that can be dynamically loaded or unloaded into the Linux kernel
- A type of system configuration file
- A network service for managing data traffic

How can you list all currently loaded kernel modules on a Linux system?
- Using the `lsmod` command
- Using the `modprobe` command
- Using the `dmesg` command

What is the purpose of the `mknod` command in Linux?
- To create special device files (device nodes) in the filesystem
- To create directories and normal files
- To modify system configuration

What Linux tool is used to adjust network configuration on systems with `NetworkManager`?
- `nmcli`
- `ifconfig`
- `netstat`

What is "Zswap" in Linux and how does it affect system performance?
- A swap compression mechanism that improves performance by reducing disk access
- A type of file for storing backups
- A network module for managing quality of service

What is the purpose of the `udevadm` tool in Linux?
- To manage `udev` events and rules for hardware device handling
- To monitor CPU usage in real-time
- To configure the filesystem

How can you obtain detailed information about interrupts and IRQ handling on a Linux system?
- Using the `cat /proc/interrupts` command
- Using the `top` command
- Using the `lsmod` command

Which file on a Raspberry Pi defines the behavior of the `GPU` and other hardware-related settings?
- `/boot/config.txt`
- `/etc/raspberrypi-config.txt`
- `/etc/gpu.conf`

What command is used to change the priority of processes in Linux?
- `renice`
- `nice`
- `ps`

What is the difference between `apt-get` and `apt` in package management on Debian and its derivatives?
- `apt` is a more modern interface to `apt-get`
- `apt-get` handles only package updates, while `apt` handles installation and removal
- `apt` is used only for security packages, while `apt-get` is for all packages

How can you configure static routing on a Raspberry Pi so that traffic to a specific network goes through a specific gateway?
- By editing the `/etc/network/interfaces` file or configuring rules in `/etc/iproute2/rt_tables`
- By using `route add` in the `/etc/rc.local` file
- By configuring the gateway in `/etc/resolv.conf`

What is `journalctl` in systems using `systemd`, and how is it used?
- A tool for viewing and analyzing system logs
- A utility for creating custom log files
- A command for checking filesystem integrity

How can you monitor network traffic in real-time?
- By running `tcpdump` with the appropriate parameters
- By using `netstat` with real-time monitoring options
- By configuring the `iptables` configuration file

What is `eBPF` (Extended Berkeley Packet Filter) and how is it used in Linux?
- A mechanism for running packet filtering and analysis programs
- A tool for network data compression
- A hardware module to enhance networking

What does the term `cgroups` mean in Linux and what is its function?
- A mechanism to control and limit resource usage
- A configuration file for setting user permissions
- A tool for file compression

How can you create a mount point in a Linux system using `mount`?
- By using the `mount` command followed by the device and desired mount point
- By editing the `/etc/fstab` file and using `mount -a`
- By running `mkfs` to create a filesystem on the device

What command is used to check the status of network connections and routing tables in Linux?
- `ip route show`
- `ss -tuln`
- `traceroute`

What is `tmpfs` in Linux and how is it used?
- A temporary filesystem in memory that provides temporary storage
- A type of hard disk storage device
- A compressed file format

What is the purpose of the `/etc/sudoers` file and how is it correctly edited?
- To define rules for the `sudo` command, edited using `visudo`
- To configure system network options
- To store system service configurations