# OS History

### Outlines:

##### 1. Open Source & Closed Source

##### 2. Operating System Difinition & Layers

##### 3. History

##### 4. Linux Distros

---

## 1. Open Source & Closed Source

- ### Open Source
  _Open source software is software with source code that anyone can inspect, modify, and enhance._

<div align="center">
    <img src="./assets/images/open_source.png">
</div>

---

- ### Closed Source
  _Closed-source software refers to software products whose creators restrict the use of its source code._

<div align="center">
    <img src="./assets/images/closed_source.png">
</div>

---

- ### Open Source vs Closed Source

<div align="center">
    <img src="./assets/images/open_source_diff_closed_source.jpg">
</div>

---

- ### Examples

<div align="center">
    <img src="./assets/images/open_source_vs_closed_source_examples.png">
</div>

---

## 2. Operating System Difinition & Layers

**_An operating system (OS) is system software that manages computer hardware and software resources, and provides common services for computer programs._**

<br />

<div align="center">
    <img src="./assets/images/operating_system_placement.png">
</div>

### Operating System Layers

<br />

<div align="center">
    <img src="./assets/images/operating_system_structure.png" width="60%">
</div>

---

## 3. OS History

### Before 1964

**_operating systems was one tasking operating system like batch processing os, time sharing os, ..._**

### In 1964

- MIT => edu (Project Owner)
- GE (General Electric) => $$, hardware
- Bell Labs now is AT&T => research => implementation

DARPA net (USA of Defense) support project

target: time sharing operating system

---

### Between 1965 => 1968

#### Multics OS (Multi information and Computer Services):

**1. Ring Protection (level0,1,2,3)**
**2. File Hierarchy**
**3. Dynamic Linking**
**4. Multiprocessing**
**5. Online reconfiguration**
**6. ACL (Access Control List)**

**Multics OS not success**

<div align="center">
    <img src="./assets/images/Multics-logo.png" width="40%" height="300">
    <img src="./assets/images/Multics_features.png" width="40%" height="300">
</div>

<br />

**Bell Labs engineer refused the ring desing**

**Ken Thompson & Dennis Retchie Last 2 left project**

<br/>

<div align="center">
    <img src="./assets/images/Ken_Thompson_and_Dennis_Ritchie--1973.jpg" width="40%">
    <br/>
    <p style="font-size: 20px;">Ken Thompson (left) with Dennis Ritchie (right)</p>
</div>

<div align="center">
    <img src="./assets/images/Alan Turing The Once Obscure Father of Computer Science.png" width="40%">
    <br/>
    <p style="font-size: 20px;">Alan Turing The Once Obscure Father of Computer Science</p>
</div>

<br/>

### 1970

**Ken Thompson Develop Unics**

<div align="center">
    <img src="./assets/images/Ken-Thompson.png" width="40%" height="500">
    <img src="./assets/images/ken_thompson_develop_go_lang.jpeg" width="40%" height="500">
</div>

<br/>

**Unics (Uni information and Computer Services)**

<br/>

<div align="center">
    <img src="./assets/images/multics_vs_unix.png" width="50%">
</div>

**Dennis Retchie develop C Lang**

<div align="center">
    <img src="./assets/images/dennis_ritchie5.jpg" width="50%">
</div>

**Brain Kerningan write most popular c lang book with dennis retchie.**
**Suggest to Convert Unics to _`Unix`_**

<div align="center">
    <img src="./assets/images/brian_kernighan.jpg" width="50%">
</div>

### 1971-1972-1972

**unix v1, unix v2, unix vn....**

**published in university -> free releases**

---

### 1976

#### Berkeley University

<div align="center">
    <img src="./assets/images/Berkeley%20University.png" width="40%">
</div>

**Bill Joy post graduated student is original author of vi, csh,apps like ed, joe, TCP/IP....**

<div align="center">
    <img src="./assets/images/Bill_Joy.jpg" width="40%">
</div>

<p style="font-size: 20px;font-weight: bold;">
    1977,78,79
    <br />
    BSD 1,2,3
    <br />
    BSD v3 added virtual memory implementation
    <div align="center">
        <img src="./assets/images/virtual-memory-diagram1.png" width="50%">
        <br />
        <br />
        <img src="./assets/images/virtual-memory-diagram2.jpg" width="50%">
        <br />
        <br />
        <br />
        <img src="./assets/images/Difference-Between-Physical-and-Virtual-Memory-Comparison-Summary.jpg" width="70%">
    </div>
</p>

---

### unix -> license

<p style="font-size: 20px;font-weight: bold;">
1981 SYS III
<br />
1982 SYS V

</p>

1. IBM buy license => AIX
2. HP buy license => HP UX
3. Apple buy license => MAC OS X
4. Sun buy license => Sun Solaris

DARBA => TCP/IP
BSD 4.3 implement TCP/IP v1

Net/1,2

- 386 BSD
  - Free BSD
  - NetBSD
    - OpenBSD
- BSD Inc

UCL vs BSD

researches left bell labs (richard stallman,....)

<div align="center">
    <img src="./assets/images/richard stallman.jpg" width="500" height="550">
    <img src="./assets/images/Richard_Stallman.jpg" width="400" height="550">
</div>

---

## 1983 -> 1991

<p style="font-size: 20px;font-weight: bold;">
GNU Project => GNU Not Unix
<br/>
target => programs then kernal
<br/>
write apps, libs, shell, compiler like gcc
<br/>
but not write kernal
</p>

---

## 1987

<p style="font-size: 20px;font-weight: bold;">
Andrew S. Tanenbaum write MiniX OS
<br />
microkernal and very small os (12,000 line of code)
</p>

<div align="center">
    <img src="./assets/images/Andrew S. Tanenbaum.jpg" width="500" height="550">
    <img src="./assets/images/Andrew_S._Tanenbaum_2012.jpg" width="400" height="550">
</div>

<div align="center">
    <img src="./assets/images/minix_os.jpg" width="90%">
</div>

---

## 1974

<p style="font-size: 20px;font-weight: bold;">
    Gary Kildall
    <br/>
    DRI: Digital Research Inc
    <br/>
    CP/M: assembly
</p>

<div align="center">
    <img src="./assets/images/gray_kildall.jpeg" width="50%">
</div>

---

<p style="font-size: 20px;font-weight: bold;">
    SCP
    <br />
    1.5 month
    <br />
    tim paterson: 86-Dos: Disk based operating system
</p>

<div align="center">
    <img src="./assets/images/tim%20paterson.jpg" width="50%">
</div>

---

<p style="font-size: 20px;font-weight: bold;">
    MS:
    <br/>
    1. Basic Interpreter
    <br/>
    2. Xenix OS
    <br/>
    <br/>
    IBM want os for thier PC then deal with MS
    <br/>
    MS Buy 86-Dos From SCP = 25,000$ with non exclusive rights
    <br/>
    MS failed to run 86-Dos on IBM PC
    <br/>
    tim paterson work on MS and take 2 month to run 86-Dos on IBM PC
    <br/>
    MS buy all 86-Dos rights from SCP = 50,000$
    <br/>
    MS earn 70,000,000$
    <br/>
    MS-Dos -> win 95,98,2000,....,11
</p>

<div align="center">
    <img src="./assets/images/basic_interpreter.png" width="40%">
    <img src="./assets/images/microsoft-unix-xenix.jpg" width="40%">
    <img src="./assets/images/windows history.png" width="100%">
</div>

---

<p style="font-size: 20px;font-weight: bold;">
Apple Lisa OS based on free BSD
<br/>
MAC OS X kernal based on free BSD
</p>

<div align="center">
    <img src="./assets/images/Apple-lisa-1.jpg" width="40%">
    <img src="./assets/images/mac os x version 1.0.png" width="40%">
    <br />
    <img src="./assets/images/mac-os_history.jpg" width="80%">
</div>

---

<p style="font-size: 20px;font-weight: bold;">
    appliances
    <br/>
    1. routers
    <br/>
    2. switches
    <br/>
    3. firewalls
    <br/>
    <br/>
    all based on free BSD
    <br/>
    <br/>
    Sony PlayStation based on free BSD
</p>

<div align="center">
    <img src="./assets/images/ps4.jpg" width="80%">
    <img src="./assets/images/PfSense-installation-1.png" width="80%">
</div>

---

## 1991

<p style="font-size: 20px;font-weight: bold;">
fresh graduated student [linus torvaldos]
<br />
<br />
write linux kernal
<br />
support multithreading
<br />
<br />
1994
<br />
linux -> 1.0.0
<br />
<br />
GNU/Linux Not Linux only
</p>

<div align="center">
    <img src="./assets/images/linus_torvaldos.jpg" width="40%">
    <img src="./assets/images/linus_torvaldos1.jpg" width="50.7%">
    <img src="./assets/images/kill-command-on-linux.jpg" width="91.5%">
</div>

---

## 4. Linux Distros

1. Red Hat
   1. RHEL
      1. CentOS
      2. Scientific Linux
         1. Heli OS
   2. Fedora
      1. Fedora Server
      2. Fedora Workstation

---

2. Suse Linux
   1. SLES [Suse Linux Enterprise Server]
   2. Open Suse

---

3. Debian
   1. Ubuntu
      1. Ubuntu Server
      2. Ubuntu Desktop
      3. Linux Mint
      4. Parrot Security
   2. Kali Linux

---

5. Arch Linux
   1. Arch linux
   2. Manjaro
   3. Black Arch

---

<div align="center">
    <img src="./assets/images/os_family_tree.png" width="100%">
</div>

---

<div align="center">
    <img src="./assets/images/Linux_distros_tree.png" width="100%">
</div>

---

## CLI vs GUI

<div align="center">
    <img src="./assets/images/CLI_vs_GUI.jpg" width="100%">
</div>

---

<br />

### [outlines](../README.md)
