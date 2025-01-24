# Collected List of Linux Commands & Jargon
### First sourced from Chris Titus Tech

| Base Command | Action |
|---|:---|
|addgroup | Creates a new user group.|
|adduser | Adds a new user to the system.|
|alias ll='ls -la'| Creates an alias ll for a long-format list of files.|
|alias| Creates a shortcut for a command.|
|apropos| Searches the manual page names and descriptions for keywords.|
|apt-get| Installs, updates, or removes packages on Debian-based systems.|
|arp| Displays or modifies the system's ARP table.|
|at| Schedules a one-time task to run at a specific time.|
|awk| Pattern scanning and processing language used for text processing.|
|basename| Strips directory and suffix from filenames.|
|bc| A command-line calculator.|
|bg| Resumes a stopped job in the background.|
|blkid| Displays block device attributes, including UUID.|
|brctl| Manages Ethernet bridges.|
|cat| Displays the content of a file.|
|cd| Changes the current directory.|
|chage| Changes user password expiration information.|
|chattr| Changes file attributes on a Linux file system.|
|chmod| Changes file or directory permissions.|
|chown| Changes file or directory ownership.|
|chroot| Changes the root directory for a command or shell.|
|cmp| Compares two files byte by byte.|
|col| Filters reverse line feeds from input.|
|column| Formats output into columns.|
|comm| Compares two sorted files line by line.|
|cp| Copies files or directories.|
|crontab| Manages cron jobs for automating tasks.|
|cryptsetup| Manages encrypted devices.|
|csplit| Splits a file into pieces based on context.|
|ctrl + z| Pauses a foreground job, allowing it to run in the background.|
|cups| Manages printers (Common Unix Printing System).|
|curl -I| Fetches the HTTP headers from a URL.|
|curl ifconfig.me| Gets your public IP address.|
|curl| Transfers data from or to a server using various protocols.|
|cut| Cuts sections from each line of a file or output.|
|date| Displays or sets the system date and time.|
|dd| Converts and copies files, useful for creating disk images.|
|deluser| Removes a user from the system|
|depmod| Generates modules dependency and map files|
|df| Displays disk space usage|
|diff| Compares the contents of two files line by line.|
|dig| Performs DNS lookups.|
|dirname| Extracts the directory path from a file path.|
|dmesg| tail: Displays recent kernel messages (useful for hardware or system errors).|
|dmesg| Displays kernel ring buffer messages.|
|dstat| Combines and displays system resource statistics, such as CPU, disk, and network usage.|
|du| Shows disk usage of files and directories.|
|e2fsck| Checks the integrity of an ext2/ext3/ext4 file system.|
|echo| Prints text to the terminal or writes text to files.|
|env| Displays the current environment variables.|
|envsubst| Substitutes environment variables in shell commands.|
|ethtool| Configures and displays Ethernet device settings.|
|expire| Forces a password change after a specific period.|
|export| Sets or exports environment variables.|
|exportfs| Maintains the NFS server's exported file systems.|
|factor| Prints the prime factors of a given number.|
|fallocate| Preallocates space to a file.|
|fg| Brings a background job to the foreground.|
|file| Determines file type based on content.|
|find| Searches for files in a directory hierarchy.|
|finger| Displays user information (if installed).|
|free| Displays memory usage.|
|fsck| Checks and repairs a file system.|
|fuser| Identifies processes using files or sockets.|
|fwupdmgr| Firmware update manager for updating hardware firmware.|
|getent| Retrieves entries from databases like passwd, group, or hosts.|
|getfacl| Displays file access control lists (ACLs).|
|gparted| A graphical partition editor (based on parted).|
|grep| Searches for a specific pattern in files.|
|groupadd| Adds a new group to the system.|
|groups| Displays the groups the current user belongs to.|
|gunzip| Decompresses gzip-compressed files.|
|gzip| Compresses files using the gzip format.|
|hdparm| Configures and displays information about SATA/IDE devices.|
|head| Displays the first few lines of a file.|
|hexdump| Displays files in hexadecimal format.|
|history| Shows the history of commands you've run.|
|hostname| Displays or sets the system’s hostname.|
|hostnamectl| Controls the system's hostname.|
|htop| An interactive process viewer (more user-friendly than top).|
|ifconfig| Displays or configures network interfaces.|
|inotifywait| Waits for changes to files or directories using inotify.|
|inotifywatch| Watches for changes in a file or directory using inotify.|
|insmod| Inserts a module into the Linux kernel.|
|ionice| Sets or gets I/O scheduling class and priority.|
|iostat| Reports CPU and I/O statistics for devices and partitions.|
|iotop| Displays real-time disk I/O usage by processes.|
|ip a| Displays IP addresses of the system's network interfaces.|
|ip link| Manages network interfaces.|
|ip r| Displays the routing table.|
|ip| Displays and manages network interfaces, routing, and more.|
|iptables-restore| Restores iptables rules from a file.|
|iptables-save| Outputs current iptables rules to a file.|
|iptables| Configures the IP packet filter rules of the Linux kernel.|
|jobs| Lists all active jobs in the current session.|
|join| Joins lines of two files based on a common field.|
|journalctl -f| Follows the system logs in real time.|
|journalctl| Views systemd logs.|
|kill| Terminates a process by PID.|
|kmod| Interfaces with kernel modules from the command line.|
|last| Displays a list of last logged-in users.|
|lastb| Shows failed login attempts.|
|less| Views the content of a file, one page at a time.|
|ln| Creates hard or symbolic links to files.|
|locate| Quickly finds files by name.|
|logrotate| Manages the automatic rotation and compression of log files.|
|losetup| Configures loopback devices.|
|lp| Sends a file to the printer.|
|lprm| Removes print jobs from the queue.|
|lpstat| Displays the status of the print system.|
|ls| Lists files and directories in the current directory.|
|lsattr| Lists file attributes on a Linux file system.|
|lsblk| Lists information about block devices.|
|lscpu| Displays information about the CPU architecture.|
|lsmod| Lists currently loaded kernel modules.|
|lsns| Lists all active Linux namespaces.|
|lsof| Lists open files and the processes that opened them.|
|lspci| Lists PCI devices connected to the system.|
|lsusb| Lists USB devices connected to the system.|
|man| Displays the manual page for a command.|
|md5sum| Computes and verifies MD5 hashes.|
|mkdir| Creates a new directory.|
|mkfs| Creates a file system on a partition or device.|
|mkswap| Sets up a swap area on a device or file.|
|modprobe| Adds or removes modules from the Linux kernel.|
|mount| Mounts a file system.|
|mpstat| Displays CPU usage statistics.|
|mv| Moves or renames files or directories.|
|nc (netcat)| Reads and writes data across network connections.|
|nc| A versatile networking tool often used for testing and debugging.|
|ncdu| Disk usage analyzer with a user-friendly interface.|
|ncftpget| Downloads files from an FTP server.|
|ncftpput| Uploads files to an FTP server.|
|netstat| Displays network connections, routing tables, and interface statistics.|
|nice| Runs a command with a modified scheduling priority.|
|nl| Numbers the lines of a file.|
|nmcli| Command-line tool for managing NetworkManager.|
|nohup| Runs a command that will continue running after logging out.|
|nslookup| Queries DNS information.|
|od| Displays files in octal, decimal, hexadecimal, or ASCII.|
|parted| A command-line partition editor.|
|parted| A disk partitioning tool.|
|passwd| Changes user passwords.|
|paste| Merges lines of files side by side.|
|pgrep| Searches for processes by name.|
|pidof| Finds the process ID (PID) of a running program.|
|ping| Tests connectivity to a network host.|
|ping6| Tests connectivity to a network host using IPv6.|
|pmap| Reports memory map of a process.|
|pr| Converts text files for printing, adding headers and footers.|
|prlimit| Displays or modifies resource limits of running processes.|
|ps| Shows running processes.|
|pv| Monitors the progress of data through a pipeline.|
|pwd| Prints the current working directory.|
|pwgen| Generates random passwords.|
|read| Reads input from the user or file.|
|reboot| Reboots the system.|
|rename| Renames files using a regular expression.|
|renice|: Alters the priority of running processes.|
|rm| Removes files or directories.|
|rmdir| Removes an empty directory.|
|rmmod| Removes a module from the Linux kernel.|
|rpcinfo| Displays information about RPC services on a networked system.|
|rsync| Synchronizes files and directories between two locations.|
|sar| Collects, reports, or saves system activity information.|
|scp| Securely copies files between hosts over SSH.|
|sed| Stream editor for filtering and transforming text.|
|seq| Prints numbers in a sequence.|
|setfacl| Sets file access control lists (ACLs).|
|sftp| A secure file transfer program over SSH.|
|sha256sum| Computes and verifies SHA-256 hashes.|
|showmount| Displays information about an NFS server.|
|shred| Securely deletes a file by overwriting it.|
|shuf| Shuffles lines of text in random order.|
|shutdown| Shuts down or reboots the system.|
|smartctl| Monitors the health of hard drives using SMART.|
|sort| Sorts the lines of a file alphabetically or numerically.|
|split| Splits a file into pieces.|
|ss -tuln| Lists open network ports (TCP and UDP).|
|ss| A faster alternative to netstat for displaying network connections.|
|ssh| Connects to a remote machine securely via SSH.|
|stat| Displays detailed information about a file or file system.|
|stdbuf| Alters the buffering of input/output for a command.|
|strace| Traces system calls and signals.|
|sudo su| Switches to the root user.|
|sudo| Executes a command with superuser privileges.|
|swapoff| Disables swap space on a device.|
|swapon| Enables swap space on a device.|
|systemctl| Controls the systemd system and service manager.|
|systemd-analyze| Displays system boot performance statistics.|
|tac| Displays a file in reverse line order (opposite of cat).|
|tail| Displays the last few lines of a file.|
|tar| Archives and extracts files using tar format.|
|tcpdump| Captures network traffic for analysis.|
|tee| Reads from standard input and writes to both standard output and files.|
|timedatectl| Manages system time and date settings.|
|timeout| Runs a command with a time limit.|
|tmux| Terminal multiplexer for managing multiple terminal sessions.|
|top| Displays real-time system processes.|
|touch| Creates an empty file or updates the timestamp of an existing file.|
|tput| Initializes terminal capabilities, such as clearing the screen.|
|tr| Translates or deletes characters from input.|
|traceroute| Traces the route packets take to a network host.|
|tree| Displays a directory structure in a tree-like format.|
|tshark| A command-line network packet analyzer.|
|tune2fs| Adjusts tunable file system parameters on ext filesystems.|
|ufw| Simplified firewall management tool (Uncomplicated Firewall).
|ulimit| Displays or sets resource limits for user processes.|
|umount| Unmounts a file system.|
|unalias| Removes an alias for a command.|
|uniq| Removes duplicate lines from a sorted file.|
|unzip| Extracts files from a zip archive.|
|updatedb| Updates the database used by the locate command.|
|uptime| Displays the system uptime and load average.|
|usermod| Modifies user account details.|
|uuidgen| Generates a new universally unique identifier (UUID).|
|vigr| Safely edits the /etc/group file.|
|vipw| Safely edits the /etc/passwd file.|
|vmstat| Reports virtual memory statistics.|
|w| Displays logged-in users and their active processes.|
|wall| Sends a message to all logged-in users.|
|watch| Repeatedly runs a command at regular intervals.|
|watch| Runs a command repeatedly, displaying the ouput and updates.|
|wc| Counts words, lines, and characters in a file.|
|wget| Downloads files from the web.|
|who| Shows who is logged into the system.|
|wipe| Securely erases files or partitions.|
|xargs| Builds and executes command lines from standard input.|
|xclip| Interfaces with the X clipboard from the command line.|
|xdg-open| Opens a file or URL in the user's preferred application.|
|xkill| Terminates a window by clicking on it.|
|xrandr| Configures display screen resolution, rotation, and reflection.|
|xset| Manages X display settings.|
|xxd| Creates a hex dump of a file or converts a hex dump back to binary.|
|yes| Repeatedly outputs a string until stopped (e.g., yes y).|
|yum| Installs, updates, or removes packages on Red Hat-based systems.|
|zip| Compresses files into a zip archive.|
