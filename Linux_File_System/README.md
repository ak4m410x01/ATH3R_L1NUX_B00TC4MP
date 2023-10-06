# Linux File System

<div align="center">
    <img src="./assets/images/linux-file-system.png" width="100%">
</div>
<br/>

### (1) / :

- the root file system (directory) from where all other directories are available.

<div align="center">
    <img src="./assets/images/root file system.png" width="100%">
</div>
<br/>

### (2) /bin/ :

- Essential commands (binaries).
- All commands that are accessible to all users.
  <br/>

### (3) /boot/ :

- Boot loader files (kernel, grub, initrd).
  <br/>

### (4) /dev/ :

- device files (hard drives, USB devices).
  <br/>

### (5) /etc/ :

- System-Global configuration files.
  <br/>

### (6) /home/ :

- Home directory for users.
  <br/>

### (7) /lib/ :

- Libraries for the binaries and Kernal Modules.
  <br/>

### (8) /media/ :

- mount point for external/removable devices (CD / DVD / USB).
  <br/>

### (9) /mnt/ :

- Temporary mount point.
  <br/>

### (10) /opt/ :

- optional application software packages.
  <br/>

### (11) /proc/ :

- Virtual filesystem for processes and kernel.
  <br/>

### (12) /root/ :

- Home directory for the root user.
  <br/>

### (13) /run/ :

- Run-time variable data. Information about the running system since the last boot.
  <br/>

### (14) /sbin/ :

- Essential system binaries.
- binaries for administrative commands, accessible for root user and administrator only.
  <br/>

### (15) /srv/ :

- services data directories .
  <br/>

### (16) /sys/ :

- Contains device, drivers, and kernel information.
  <br/>

### (17) /tmp/ :

- Temporary files.
  <br/>

### (18) /usr/ :

- Contains commands and applications for all users.
- Secondary hierarchy, read-only access.
  <br/>

### (19) /var/ :

- Variable files, files that are expected to often change. For example, log files.
  <br/>

---

# File system Navigation

- Before learning how to navigate the filesystem, it's good to know how Linux organizes data.
- Navigation is based on the concept of paths. These paths specify what directories to traverse to reach a particular subdirectory or file. <br/><br/>

- There are two types of paths: **Absolute paths** and **relative paths**.<br/><br/>

### (1) Absolute path

- An absolute path is a **complete path** to a resource, beginning at the **filesystem's root**.<br/><br/>
- for example :

```
   [root@localhost ~]# cat /usr/share/doc/libICE/COPYING

```

<br/>

### (2) Relative path

- Relative paths vary by your location in the filesystem, the path changes depending on where you are and where you're going.<br/><br/>

note :<br/>

- single dot ( **.** ) means: current working directory.
- double dot ( **..** ) means: parent working directory.
- tilde ( **~** ) means: the home directory of the currently logged-in user.<br/><br/>

for example :

```
   [root@localhost log]# pwd
    /var/log
    [root@localhost log]# cd ../../etc/
    [root@localhost etc]#

```

---

### Print working directory (pwd)

- The `pwd` command **prints the current/working directory**, telling where you are currently located in the filesystem.<br/><br/>

<div align="center">
    <img src="./assets/images/pwd ex1.png" width="80%">
</div>
<br/><br/><br/>

### Change directory (cd)

- The `cd` command lets you **change to a different directory**.<br/>

1. `cd -`: Changing to the Previous Directory.
2. `cd ..`: Changing to Parent Directory.
3. `cd /`: Changing to the Root Directory.
4. `cd` = `cd ~`: Changing Back to the Home Directory.
5. `cd ~[username]` : Changing to Another User's Home Directory.<br/><br/>

---

<br />

### [outlines](../README.md)
