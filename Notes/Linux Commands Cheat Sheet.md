# Linux Commands Cheat Sheet

| Command       | Description | Format & Example |
|--------------|-------------|------------------|
| `access` | Checks if a program has access to a specified file | `access filename` - Check if `filename` is accessible |
| `accton` | Enables or disables process accounting | `accton /var/log/account` - Enable process accounting |
| `aclocal` | Generates `aclocal.m4` files from `configure.in` | `aclocal` - Generate `aclocal.m4` |
| `acpi` | Displays battery status and other ACPI info | `acpi -V` - Show all ACPI information |
| `acpi_available` | Checks if ACPI subsystem is available | `acpi_available` - Returns 0 if available |
| `acpid` | Handles ACPI events and notifies user-space programs | `acpid -d` - Start `acpid` in debug mode |
| `addr2line` | Converts addresses into file names and line numbers | `addr2line -e a.out 0x400123` - Translate address in `a.out` |
| `agetty` | Manages terminal access for users | `agetty tty1` - Start `agetty` on `tty1` |
| `alias` | Creates an alias for a command | `alias ll='ls -la'` - Create alias `ll` for `ls -la` |
| `amixer` | CLI mixer for ALSA sound driver | `amixer set Master 50%` - Set volume to 50% |
| `aplay` | Plays audio files using ALSA | `aplay sound.wav` - Play `sound.wav` |
| `aplaymidi` | Plays MIDI files using ALSA | `aplaymidi -p 128:0 file.mid` - Play `file.mid` |
| `apropos` | Searches manual pages for a keyword | `apropos network` - Search for network-related commands |
| `apt` | High-level CLI for package management | `apt install vim` - Install Vim |
| `apt-get` | Installs, updates, removes packages | `apt-get update` - Update package list |
| `aptitude` | Interactive package management interface | `aptitude` - Open interactive package manager |
| `ar` | Creates, modifies, extracts archives | `ar x archive.a` - Extract `archive.a` |
| `arch` | Prints system architecture | `arch` - Show architecture (e.g., `x86_64`) |
| `arp` | Manipulates ARP cache | `arp -a` - Show ARP cache |
| `aspell` | Spell checker for text files | `aspell check file.txt` - Check spelling in `file.txt` |
| `atd` | Schedules jobs to run later | `at now + 5 minutes` - Run command in 5 minutes |
| `atrm` | Removes scheduled jobs | `atrm 2` - Remove job ID 2 |
| `atq` | Displays pending scheduled jobs | `atq` - Show job queue |
| `autoconf` | Generates configure scripts | `autoconf` - Create `configure` script |
| `autoheader` | Creates template header files | `autoheader` - Generate `config.h.in` |
| `automake` | Generates `Makefile.in` files | `automake --add-missing` - Add missing files |
| `autoreconf` | Automatically rebuilds configuration scripts | `autoreconf -i` - Rebuild with missing files |
| `autoupdate` | Updates `configure.in` to a newer Autoconf | `autoupdate` - Update `configure.in` |
| `awk` | Pattern scanning and text processing | `awk '{print $1}' file.txt` - Print first column of `file.txt` |
| `banner` | Prints text in large ASCII letters | `banner Linux` - Print `Linux` in large letters |
| `basename` | Strips directory from filenames | `basename /home/user/file.txt` - Output: `file.txt` |
| `batch` | Executes commands when system load is low | `echo "ls" | batch` - Run `ls` when idle |
| `bc` | Command-line calculator | `echo '5+3' | bc` - Output: `8` |
| `bg` | Resumes a suspended job in the background | `bg %1` - Resume job 1 in background |
| `biff` | Mail notification system | `biff y` - Enable mail notifications |
| `bind` | Sets Readline key bindings | `bind -p` - Show current key bindings |
| `bison` | Parser generator (like yacc) | `bison -d parser.y` - Generate parser files |
| `break` | Exits a loop prematurely | `for i in {1..5}; do if [[ $i -eq 3 ]]; then break; fi; echo $i; done` |
| `builtin` | Executes a shell built-in command | `builtin echo "Hello"` - Run `echo` as built-in |
| `bzcmp` | Compares bzip2-compressed files | `bzcmp file1.bz2 file2.bz2` |
| `bzdiff` | Displays differences in bzip2 files | `bzdiff file1.bz2 file2.bz2` |
| `bzgrep` | Searches in bzip2-compressed files | `bzgrep pattern file.bz2` |
| `bzip2` | Compresses/decompresses files | `bzip2 file.txt` - Compress `file.txt` |
| `bzless` | Views bzip2-compressed files | `bzless file.bz2` |
| `bzmore` | Paginates bzip2-compressed files | `bzmore file.bz2` |
| `cal` | Displays a calendar | `cal 2025` - Show calendar for 2025 |
| `case` | Multi-conditional statement in shell | `case $var in 1) echo One;; 2) echo Two;; esac` |
| `cat` | Displays, concatenates file contents | `cat file.txt` |
| `cc` | C language compiler | `cc program.c -o program` |
| `ccrypt` | Encrypts and decrypts files | `ccrypt -e file.txt` |
| `cd` | Changes the current directory | `cd /home/user` |
| `cfdisk` | Disk partition table management | `cfdisk /dev/sda` |
| `chage` | Manages user password expiry | `chage -l user` |
| `chattr` | Changes file attributes | `chattr +i file.txt` |
| `chfn` | Changes user information | `chfn user` |
| `chgrp` | Changes group ownership | `chgrp users file.txt` |
| `chkconfig` | Manages services | `chkconfig --list` |
| `chmod` | Changes file permissions | `chmod 755 file.sh` |
| `chown` | Changes file owner | `chown user:group file.txt` |
| `chpasswd` | Changes multiple passwords | `echo "user:newpass" | chpasswd` |
| `chroot` | Changes root directory | `chroot /mnt` |
| `chsh` | Changes default shell | `chsh -s /bin/bash` |
| `chvt` | Used to switch between different TTY (TeleTYpewriter) terminals available. | `chvt 3` (Switches to TTY3) |
| `cksum` | Displays a CRC (Cyclic Redundancy Check) value, the byte size of the file, and the file name. | `cksum file.txt` |
| `clear` | Clears the terminal screen. | `clear` |
| `cmp` | Compares two files byte by byte to check if they are identical. | `cmp file1.txt file2.txt` |
| `col` | Filters out reverse line feeds, reading from standard input and writing to standard output. | `cat file.txt | col` |
| `colcrt` | Formats text processor output for viewing on CRT displays. | `colcrt file.txt` |
| `colrm` | Removes selected columns from a file. | `colrm 5 10 < file.txt` |
| `column` | Displays the contents of a file in columns. | `column -t file.txt` |
| `comm` | Compares two sorted files line by line, displaying common and unique lines. | `comm file1.txt file2.txt` |
| `compress` | Reduces file size and appends a `.Z` extension. | `compress file.txt` |
| `continue` | Skips the current iteration in a loop. | `for i in {1..5}; do if [ $i -eq 3 ]; then continue; fi; echo $i; done` |
| `cp` | Copies files or directories. | `cp source.txt destination.txt` |
| `cpio` | Processes archive files like `.cpio` or `.tar`. | `find . -name "*.txt" | cpio -ov > archive.cpio` |
| `cpp` | Preprocessor used by C compiler before compilation. | `cpp program.c` |
| `cron` | Schedules tasks to run at predetermined times. | `crontab -e` (Edit cron jobs) |
| `crontab` | Manages cron job schedules. | `crontab -l` (Lists cron jobs) |
| `csplit` | Splits a file into multiple parts. | `csplit file.txt 10` |
| `ctags` | Generates an index (or tag) file for easy code navigation. | `ctags -R .` |
| `cupsd` | Manages printing system using Internet Printing Protocol. | `sudo systemctl restart cupsd` |
| `curl` | Transfers data to or from a server using supported protocols. | `curl -O https://example.com/file.txt` |
| `cut` | Extracts specific sections from lines of a file. | `cut -d: -f1 /etc/passwd` |
| `cvs` | Version control system to track file history. | `cvs commit -m "Updated file"` |
| `date` | Displays or sets the system date and time. | `date +"%Y-%m-%d"` |
| `dc` | Evaluates arithmetic expressions using postfix notation. | `echo "2 3 + p" | dc` |
| `dd` | Converts and copies files at the byte level. | `dd if=/dev/sda of=backup.img bs=4M` |
| `declare` | Declares shell variables and functions. | `declare -i num=10` |
| `depmod` | Generates dependency descriptions for kernel modules. | `sudo depmod -a` |
| `df` | Displays available and used disk space. | `df -h` |
| `diff` | Compares two files line by line. | `diff file1.txt file2.txt` |
| `diff3` | Compares three files line by line. | `diff3 file1.txt file2.txt file3.txt` |
| `dir` | Lists directory contents. | `dir /home/user` |
| `dirname` | Extracts directory path from a file path. | `dirname /home/user/file.txt` |
| `dirs` | Displays a list of remembered directories. | `dirs` |
| `disable` | Disables a printer or service. | `disable printer_name` |
| `dmesg` | Prints kernel ring buffer messages. | `dmesg | tail` |
| `dmidecode` | Retrieves system hardware information. | `sudo dmidecode -t system` |
| `domainname` | Displays the system’s NIS domain name. | `domainname` |
| `dos2unix` | Converts a DOS text file to UNIX format. | `dos2unix file.txt` |
| `dosfsck` | Checks and repairs an MS-DOS file system. | `sudo dosfsck /dev/sdb1` |
| `dstat` | Displays system resource usage statistics. | `dstat -cdngy` |
| `du` | Shows disk usage of files and directories. | `du -sh /home/user` |
| `dump` | Backs up a filesystem to storage. | `dump -0 -f backup.dump /dev/sda1` |
| `dumpe2fs` | Displays superblock information of a filesystem. | `dumpe2fs /dev/sda1` |
| `dumpkeys` | Dumps current keyboard translation table. | `dumpkeys` |
| `echo` | Prints text to the terminal. | `echo "Hello, World!"` |
| `ed` | Launches the `ed` text editor. | `ed file.txt` |
| `egrep` | Extended version of `grep` for pattern matching. | `egrep 'pattern' file.txt` |
| `eject` | Ejects removable media. | `eject /dev/cdrom` |
| `emacs` | Opens the `emacs` text editor. | `emacs file.txt` |
| `enable` | Enables a printer or service. | `enable printer_name` |
| `env` | Prints environment variables or runs a command in a custom environment. | `env | grep PATH` |
| `eval` | Executes a command stored in a variable. | `eval echo \$HOME` |
| `ex` | Line editor mode of `vi`. | `ex file.txt` |
| `exec` | Replaces the current shell process with a new command. | `exec ls` |
| `exit` | Exits the current shell session. | `exit` |
| `expand` | Converts tabs to spaces. | `expand file.txt` |
| `expect` | Automates interactive command execution. | `expect script.exp` |
| `export` | Marks an environment variable for child processes. | `export PATH=$PATH:/new/path` |
| `expr` | Evaluates expressions. | `expr 10 + 5` |
| `factor` | Displays the prime factors of a number. | `factor 100` |
| `fc` | Lists, edits, or re-executes shell commands. | `fc -l` |
| `fc-cache` | Builds font cache for applications. | `fc-cache -fv` |
| `fc-list` | Lists available fonts. | `fc-list | grep Arial` |
| `fdisk` | Partition management tool. | `sudo fdisk -l` |
| `fg` | Brings a background job to the foreground. | `fg %1` |
| `fgrep` | Searches for fixed-character strings in a file. | `fgrep "search_term" file.txt` |
| `file` | Determines the type of a file. | `file document.txt` |
| `find` | Finds files and directories. | `find /home -name "*.txt"` |
| `finger` | Displays user information. | `finger username` |
| `fmt` | Formats text files. | `fmt -w 80 file.txt` |
| `fold` | Wraps lines of text to a specified width. | `fold -w 50 file.txt` |
| `for` | Loops through a list of items. | `for i in {1..5}; do echo $i; done` |
| `free` | Displays system memory usage. | `free -h` |
| `fun` | Draws patterns in the terminal. | `fun` |
| `function` | Defines a function in a shell script. | `function greet() { echo "Hello, $1"; }` |
| `g++` | Compiles C++ programs. | `g++ -o output file.cpp` |
| `gawk` | Pattern scanning and processing tool. | `gawk '{print $1}' file.txt` |
| `gcc` | Compiles C programs. | `gcc -o output file.c` |
| `gdb` | GNU debugger for debugging programs. | `gdb ./a.out` |
| `getent`      | Used to get the entries in a number of important text files called databases                      | `getent passwd`                                       |
| `gpasswd`     | Used to administer the /etc/group and /etc/gshadow                                                  | `gpasswd -A user groupname`                           |
| `grep`        | Searches a file for a particular pattern of characters, and displays all lines that contain that pattern | `grep 'pattern' file.txt`                             |
| `groupadd`    | Used to create a new user group                                                                   | `groupadd newgroup`                                   |
| `groupdel`    | Used to delete an existing group                                                                  | `groupdel groupname`                                  |
| `groupmod`    | Used to modify or change the existing group on Linux system                                        | `groupmod -n newgroup oldgroup`                       |
| `groups`      | Groups are the collection of users. Groups make it easy to manage users with the same security and access privileges | `groups username`                                     |
| `grpck`       | Verifies the integrity of the groups information. Checks entries in /etc/group and /etc/gshadow     | `grpck`                                               |
| `grpconv`     | Used to convert to shadow groups. Creates a gshadow from the group and optionally existing gshadow | `grpconv`                                             |
| `gs`          | Invokes Ghostscript, an interpreter for Adobe Systems PostScript and Portable Document Format (PDF) | `gs file.ps`                                          |
| `gunzip`      | Used to compress or expand a file or list of files in Linux                                         | `gunzip file.gz`                                      |
| `gzexe`       | Used to compress executable files and also automatically uncompress and execute the files          | `gzexe file`                                          |
| `gzip`        | Compresses files. Each single file is compressed into a single file                               | `gzip file.txt`                                       |
| `halt`        | Instructs the hardware to stop all CPU functions, reboots or stops the system                      | `halt`                                                |
| `hash`        | Maintains a hash table of recently executed programs                                               | `hash`                                                |
| `hdparm`      | Gets statistics about the hard disk, alters writing intervals, acoustic management, and DMA settings | `hdparm -t /dev/sda`                                  |
| `head`        | Prints the top N number of data from the given input                                               | `head -n 10 file.txt`                                 |
| `help`        | Displays information about shell built-in commands                                                | `help cd`                                             |
| `hexdump`     | Used to filter and display specified files in a human-readable specified format                   | `hexdump -C file.txt`                                 |
| `history`     | Views the previously executed commands                                                           | `history`                                             |
| `host`        | Used for DNS (Domain Name System) lookup operations                                              | `host example.com`                                    |
| `hostid`      | Displays the Host’s ID in hexadecimal format                                                     | `hostid`                                              |
| `hostname`    | Obtains the DNS name and sets the system’s hostname or NIS domain name                            | `hostname`                                            |
| `hostnamectl` | Provides an API to control Linux system hostname and change related settings                      | `hostnamectl set-hostname new-hostname`               |
| `htop`        | A command-line utility that monitors the system’s vital resources or server’s processes in real-time | `htop`                                                |
| `hwclock`     | Utility for accessing the hardware clock, also called Real Time Clock (RTC)                      | `hwclock`                                             |
| `iconv`       | Converts text in one encoding into another encoding                                              | `iconv -f utf-8 -t ascii file.txt`                    |
| `id`          | Finds out user and group names and numeric IDs (UID or group ID) of the current user or another user | `id username`                                         |
| `if`          | Executes commands based on conditions                                                            | `if [condition]; then command; fi`                    |
| `ifconfig`    | Configures the kernel-resident network interfaces                                                | `ifconfig eth0 up`                                    |
| `iftop`       | A network analyzing tool to view bandwidth-related stats                                         | `iftop`                                               |
| `ifup`        | Brings the network interface up, allowing it to transmit and receive data                        | `ifup eth0`                                           |
| `import`      | Captures a screenshot of an active page and outputs it as an image file                           | `import screenshot.png`                               |
| `info`        | Reads documentation in the info format. Provides detailed information compared to the main page    | `info coreutils`                                      |
| `insmod`      | Inserts modules into the kernel                                                                   | `insmod module.ko`                                    |
| `install`     | Copies files and sets attributes                                                                  | `install file /path`                                  |
| `iostat`      | Monitors system input/output statistics for devices and partitions                               | `iostat`                                              |
| `iotop`       | Displays and monitors disk IO usage and existing IO utilization by process                        | `iotop`                                               |
| `ip`          | Performs network administration tasks                                                            | `ip addr show`                                        |
| `ipcrm`       | Removes IPC (Inter-Process Communication) resources                                             | `ipcrm -M <shm_id>`                                   |
| `ipcs`        | Shows information on inter-process communication facilities                                    | `ipcs`                                                |
| `iptables`    | Sets up and maintains tables for the Netfilter firewall for IPv4, included in the Linux kernel     | `iptables -L`                                          |
| `iptables-save`| Saves the current iptables rules in a user-specified file                                        | `iptables-save > /path/to/rules-file`                  |
| `iwconfig`    | Displays parameters and wireless statistics from /proc/net/wireless                             | `iwconfig wlan0`                                      |
| `join`        | Joins lines of two files based on a key field present in both files                               | `join file1.txt file2.txt`                            |
| `journalctl`  | Views systemd, kernel, and journal logs                                                          | `journalctl -xe`                                      |
| `kill`        | Used to terminate processes manually. Sends a signal to a process which terminates it            | `kill 1234`                                           |
| `last`        | Displays the list of all users logged in and out since the file /var/log/wtmp was created         | `last`                                                |
| `less`        | Reads contents of a text file one page at a time                                                 | `less file.txt`                                       |
| `let`         | Evaluates arithmetic expressions on shell variables                                              | `let result=5+5`                                      |
| `ln`          | Creates links between files                                                                      | `ln -s /path/to/file linkname`                        |
| `locate`      | Finds files by name                                                                               | `locate file.txt`                                     |
| `look`        | Shows the lines beginning with a given string                                                    | `look string file.txt`                                |
| `lsblk`       | Displays details about block devices (except ram disks)                                          | `lsblk`                                               |
| `lshw`        | Generates detailed information of the system’s hardware configuration from various files         | `lshw`                                                |
| `lsmod`       | Displays the status of modules in the Linux kernel, shows loaded modules                         | `lsmod`                                               |
| `lsof`        | Lists all open files                                                                              | `lsof`                                                |
| `lsusb`       | Displays information about USB buses and connected devices                                       | `lsusb`                                               |
| `mailq`       | Prints the mail queue (list of messages in the mail queue)                                       | `mailq`                                               |
| `man`         | Displays the user manual of any command                                                          | `man ls`                                              |
| `md5sum`      | Verifies data integrity using MD5 (Message Digest Algorithm 5)                                   | `md5sum file.txt`                                     |
| `mkdir`       | Creates directories, supports multiple directory creation                                       | `mkdir dir1 dir2`                                     |
| `modinfo`     | Displays information about a Linux Kernel module                                                | `modinfo module_name`                                 |
| `more`        | Views text files in the command prompt, one screen at a time                                    | `more file.txt`                                       |
| `mount`       | Mounts a filesystem found on a device to the Linux filesystem tree rooted at ‘/’                 | `mount /dev/sda1 /mnt`                                |
| `mpstat`      | Reports processor-related statistics                                                            | `mpstat`                                              |
| `mv`          | Moves one or more files or directories from one place to another                                | `mv file.txt /new/location/`                          |
| `nc (netcat)` | A powerful networking, security, or network monitoring tool                                     | `nc -l 1234`                                          |
| `netstat`     | Displays network-related information such as connections, routing tables, and interface stats    | `netstat -tuln`                                       |
| `nmcli`       | Controls NetworkManager, displays network device status, creates and manages network connections | `nmcli device status`                                 |
| `nslookup`    | A network administration tool for querying DNS to obtain domain name or IP address mapping      | `nslookup example.com`                                |
| `od`          | Converts content of input into different formats with octal as the default                      | `od file.txt`                                         |
| `passwd`      | Changes the user account passwords                                                                | `passwd username`                                     |
| `paste`       | Joins files horizontally, outputting lines from each file, separated by tabs                     | `paste file1.txt file2.txt`                           |
| `pidof`       | Finds out the process IDs of a specific running program                                          | `pidof process_name`                                  |
| `ping`        | Checks network connectivity between a host and server/host                                      | `ping 8.8.8.8`                                        |
| `pinky`       | A user information lookup command that gives details of all logged-in users                     | `pinky`                                               |
| `pmap`        | Displays the memory map of a process                                                              | `pmap 1234`                                           |
| `poweroff`    | Sends an ACPI signal which instructs the system to power down                                    | `poweroff`                                            |
| `printf`      | Displays the given string, number, or other format specifiers on the terminal                    | `printf "Hello, World\n"`                             |
| `ps`          | Lists currently running processes and their PIDs, with additional options                       | `ps aux`                                              |
| `pwd`         | Prints the path of the working directory, starting from the root                                 | `pwd`                                                 |
| `ranlib`      | Generates an index to an archive                                                                  | `ranlib file.a`                                       |
| `rcp`         | Copies files from one computer to another                                                        | `rcp file user@remote:/path`                          |
| `read`        | Reads up a specified number of bytes from a file descriptor into a buffer                        | `read varname`                                        |
| `readelf`     | Gets information of ELF (Executable and Linkable Format) files                                  | `readelf -h file`                                    |
| `readlink`    | Prints resolved symbolic links or canonical file names                                          | `readlink /path/to/symlink`                           |
| `reboot`      | Instructs the system to restart or reboot                                                        | `reboot`                                              |
| `rename`      | Renames files according to the regular expression perlexpr                                       | `rename 's/.txt/.bak/' *.txt`                         |
| `reset`       | Initializes the terminal, useful after a program leaves the terminal in an abnormal state       | `reset`                                               |
| `restore`     | Restores files from a backup created using the dump command                                     | `restore`                                             |
| `return`      | Exits from a shell function                                                                      | `return`                                              |
| `rev`         | Reverses the lines characterwise                                                                  | `rev file.txt`                                        |
| `rm`          | Removes objects such as files, directories, symbolic links from the filesystem                   | `rm file.txt`                                         |
| `rmdir`       | Removes empty directories from the filesystem                                                   | `rmdir dir_name`                                      |
| `rmmod`       | Removes a module from the kernel                                                                  | `rmmod module_name`                                   |
| `route`       | Works with the IP/kernel routing table                                                            | `route`                                               |
| `rsync`       | A utility for Unix-like systems to sync files and directories between two hosts                  | `rsync -av source/ destination/`                      |
| `sar`          | Monitors Linux system’s resources like CPU usage, Memory utilization, I/O devices consumption, etc.       | `sar -u 1 3`                                              |
| `scp`          | Securely copies file(s) between servers.                                                                  | `scp file.txt user@remote:/path`                           |
| `screen`       | Provides the ability to launch and use multiple shell sessions from a single SSH session                  | `screen`                                                  |
| `script`       | Records all terminal activities.                                                                          | `script output.log`                                       |
| `scriptreplay` | Replays a typescript/terminal activity stored in the log file recorded by the `script` command.           | `scriptreplay output.log`                                 |
| `sdiff`        | Compares two files and writes the results in a side-by-side format.                                       | `sdiff file1.txt file2.txt`                               |
| `sed`          | Performs text substitution, replacement, insertion, deletion, and manipulation.                          | `sed 's/old/new/' file.txt`                               |
| `select`       | Creates a numbered menu for users to select an option.                                                    | `select option in "opt1" "opt2"; do echo $option; done`    |
| `seq`          | Generates numbers from FIRST to LAST with an optional increment.                                          | `seq 1 2 10`                                              |
| `setsid`       | Runs a program in a new session.                                                                           | `setsid command`                                          |
| `shift`        | Shifts/moves the command line arguments to one position left.                                             | `shift`                                                   |
| `showkey`      | Prints the scan codes, key codes, or ASCII code of each key pressed.                                      | `showkey`                                                 |
| `shred`        | Deletes a file completely from the hard disk, making it unrecoverable.                                    | `shred -u file.txt`                                       |
| `shutdown`     | Shuts down the system in a safe way.                                                                       | `shutdown -h now`                                         |
| `sleep`        | Creates a dummy job to delay execution for a specified amount of time.                                    | `sleep 5`                                                 |
| `source`       | Reads and executes the content of a file (set of commands) in the current shell script.                  | `source script.sh`                                        |
| `sort`         | Sorts a file or output in a specific order.                                                               | `sort file.txt`                                           |
| `split`        | Splits large files into smaller files.                                                                     | `split -l 1000 largefile.txt smallfile_`                  |
| `ssh`          | Protocol used to securely connect to a remote server/system.                                             | `ssh user@hostname`                                       |
| `strace`       | A powerful process monitoring, diagnostic, and instructional tool.                                       | `strace ls`                                               |
| `stty`         | Changes and prints terminal line settings.                                                                | `stty -a`                                                 |
| `sudo`         | Executes a command as a superuser or with superuser privileges.                                           | `sudo apt update`                                         |
| `sum`          | Finds checksum and counts blocks in a file.                                                               | `sum file.txt`                                            |
| `sync`         | Synchronizes cached writes to persistent storage.                                                        | `sync`                                                    |
| `systemctl`    | Examines and controls the state of the `systemd` system and service manager.                             | `systemctl status`                                        |
| `tac`          | Concatenates and prints files in reverse order.                                                           | `tac file.txt`                                            |
| `tail`         | Prints the last N number of lines from the given input.                                                  | `tail -n 10 file.txt`                                     |
| `tar`          | Creates and extracts archive files.                                                                       | `tar -xzvf file.tar.gz`                                   |
| `tee`          | Reads standard input and writes it to both standard output and one or more files.                         | `echo "hello" | tee file.txt`                             |
| `time`         | Executes a command and prints a summary of real-time, user CPU time, and system CPU time spent.           | `time ls`                                                 |
| `top`          | Provides a dynamic, real-time view of the running system.                                                | `top`                                                     |
| `touch`        | Creates, changes, and modifies timestamps of a file.                                                     | `touch file.txt`                                          |
| `tr`           | A utility for translating or deleting characters in the input.                                           | `echo "abc" | tr 'a-z' 'A-Z'`                             |
| `tracepath`    | Traces the path to a destination, discovering the MTU along the path.                                    | `tracepath example.com`                                   |
| `traceroute`   | Prints the route that a packet takes to reach the host.                                                  | `traceroute example.com`                                  |
| `tree`         | Recursively lists directories and files in a tree-like format.                                           | `tree`                                                    |
| `tty`          | Displays information about the terminal, printing the terminal's file name connected to standard input.  | `tty`                                                     |
| `type`         | Describes how its argument would be translated if used as a command.                                     | `type ls`                                                 |
| `uname`        | Displays information about the system.                                                                   | `uname -a`                                                |
| `unexpand`     | Converts spaces into tabs and writes the produced output to the standard output.                         | `unexpand file.txt`                                       |
| `uniq`         | Reports or filters out the repeated lines in a file.                                                     | `uniq file.txt`                                           |
| `unix2dos`     | Converts a Unix text file to DOS format.                                                                  | `unix2dos file.txt`                                       |
| `until`        | Executes a set of commands as long as the final command's exit status is not zero.                       | `until ping -c 1 google.com; do echo "Retrying"; done`    |
| `uptime`       | Displays how long the system has been active (running).                                                  | `uptime`                                                  |
| `useradd`      | Adds user accounts to the system.                                                                         | `useradd username`                                        |
| `usermod`      | Changes the properties of a user in Linux through the command line.                                      | `usermod -aG sudo username`                               |
| `username`     | Provides a set of commands to fetch the username and its configurations from the Linux host.             | `username`                                                |
| `users`        | Shows the usernames of users currently logged in to the system.                                          | `users`                                                   |
| `userdel`      | Deletes a user account and its related files.                                                           | `userdel username`                                        |
| `vi`           | The default visual editor that comes with UNIX operating systems.                                        | `vi file.txt`                                             |
| `vmstat`       | A performance monitoring command that provides information about processes, memory, disk, and CPU.      | `vmstat`                                                  |
| `vnstat`       | Monitors network parameters such as bandwidth consumption and traffic flowing in/out.                    | `vnstat`                                                  |
| `w`            | Displays who is logged on and what they are doing.                                                      | `w`                                                       |
| `wall`         | Displays a message or contents of a file on the terminals of all currently logged-in users.             | `wall message.txt`                                        |
| `watch`        | Executes a program periodically, showing its output in fullscreen.                                      | `watch -n 1 'date'`                                       |
| `wc`           | Counts the number of lines, words, bytes, and characters in a file.                                      | `wc file.txt`                                             |
| `wget`         | Downloads files from the server, works in the background without hindering the current process.         | `wget http://example.com/file.zip`                        |
| `whatis`       | Gets a one-line manual page description of a command.                                                   | `whatis ls`                                               |
| `which`        | Locates the executable file associated with a command by searching the path environment variable.       | `which ls`                                                |
| `while`        | Repeatedly executes a set of commands as long as the condition is true.                                  | `while true; do echo "Running"; sleep 1; done`            |
| `who`          | Displays information about the currently logged-in users.                                                | `who`                                                     |
| `whoami`       | Displays the username of the current user.                                                               | `whoami`                                                  |
| `write`        | Allows a user to communicate with other users by copying lines from one user’s terminal to another’s.    | `write user`                                              |
| `xargs`        | Builds and executes commands from standard input, converting input to arguments of a command.            | `echo "file1 file2" | xargs cat`                          |
| `xdg-open`     | Opens a file or URL in the user’s preferred application.                                                | `xdg-open file.txt`                                       |
| `yes`          | Prints a continuous output stream of the given string, or ‘y’ if no string is provided.                 | `yes "Hello"`                                             |
| `zdiff`        | Invokes the diff program on files compressed with gzip.                                                 | `zdiff file1.gz file2.gz`                                 |
| `zdump`        | Prints the current time in the specified time zone.                                                     | `zdump /etc/localtime`                                    |
| `zgrep`        | Searches expressions in a file, even if the file is compressed.                                         | `zgrep "pattern" file.gz`                                 |
| `zip`          | A compression and file packaging utility for Unix, creates .zip archives.                              | `zip archive.zip file.txt`                                |
