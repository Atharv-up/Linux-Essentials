[01-Linux-and-Unix.md](https://github.com/user-attachments/files/23623111/01-Linux-and-Unix.md)
### Unix

- Developed in the **1960s and 1970s** at **AT&T Bell Labs** by **Ken Thompson, Dennis Ritchie**, and others.
    
- Designed as a **portable**, **multi-tasking**, and **multi-user** system.
    
- Originally proprietary but led to many influential variants:
    
    - ***BSD (Berkeley Software Distribution)**
        
    - ***AIX (IBM)**
        
    - ***HP-UX (Hewlett-Packard)**
        
    - ***Solaris (Sun Microsystems)**
        
- Historically dominant in **academia, enterprise servers**, and **research systems**.
    

---

### Linux

- Created by **Linus Torvalds** in **1991**.
    
- Inspired by Unix principles but **built from scratch**.
    
- Uses the **GNU General Public License (GPL)**.
    
- Often combined with **GNU utilities** to form **GNU/Linux**.
    
- Widely used in **servers, desktops, IoT**, and **supercomputers**.

****
### 💻 Popular Linux Distributions

- 🟠 **Ubuntu**
    
- 🔴 **Debian**
    
- 🔵 **Fedora**
    
- 🧰 **Red Hat Enterprise Linux (RHEL)**
    
- 🧱 **CentOS**
    
- ⚙️ **Arch Linux**
    
- 🛡️ **Kali Linux**
    
- 🐧 **SUSE Linux**
    

---

### ❓ What Is An Operating System?

🧠 An **Operating System (OS)** is system software that:

- Manages **hardware** 🖥️
    
- Manages **software resources** ⚙️
    
- Provides services for **computer programs** 📦
    

---

##### 🔄 Basic Flow Of Operation

`👤 User → 🧩 Application → 🖥️ OS → 🔧 Hardware`

---
##### 🐚 With Shell And Kernel

`👤 User → 🐚 Shell → 🧠 Kernel → 🔧 Hardware`

****
#### ⚙️ Functions of an Operating System

1. 🧠 _Process Management
    
2. 💾 _Memory Management
    
3. 📁 _File System Management
    
4. 🔌 _Device Management
    
5. 🔒 _Security and Protection
    
6. 🖥️ _User Interface
    
7. 🌐 _Network Management
    
8. 📊 _System and Performance Monitoring
	
9. 🔄 _Utility and Support Services

****
### 🌟 Features of Linux

##### 1. 🔓 Open Source (GPL License)  
	    
Linux is distributed under the GNU General Public License (GPL), allowing anyone to view, modify, and distribute the source code. This promotes transparency, community development, and innovation.
	
##### 2. 🧠 Multitasking  
	 
Linux can handle multiple tasks simultaneously without slowing down. Each task is treated as a separate process managed by the kernel.
    
##### 3. 👥 Multiuser Capability  
	 
Multiple users can access the system at the same time without interfering with each other’s processes or files—ideal for servers and enterprises.
    
##### 4. 📱💻 Portability  
	 
Linux runs on a wide range of hardware platforms, from smartphones to supercomputers, thanks to its kernel being written in portable C and assembly.
    
##### 5. 🔒 Security  
	 
Offers robust features like file permissions, user roles, firewall tools (`iptables`, `firewalld`), and SELinux. Open-source nature allows vulnerabilities to be found and fixed quickly.
    
##### 6. 🧱 Stability and Reliability  
	 
Known for running for years without crashes or reboots—perfect for mission-critical systems.
    
##### 7. 🛠️ Customizability  
	 
Everything from the kernel to the desktop environment can be customized. Users can build their own Linux distributions.
    
##### 8. 🌍 Community Support  
	 
A global community provides updates, forums, tutorials, and support on platforms like Stack Overflow and Reddit.
    
##### 9. 🚀 Performance  
	 
Lightweight and optimized, Linux efficiently manages resources, making it ideal for servers and high-performance computing.
    
##### 10. 📟 Unix Compatibility  
	
Compatible with traditional Unix commands and behavior, easing the transition for Unix users and supporting tool reuse.
    
##### 11. 📈 Scalability  
	
Can scale from embedded systems to large-scale enterprise/cloud environments. Supports clusters, containers, and distributed computing.

****
### 🧰 Linux Distributions

#### 🟩 Debian-Based (e.g., Debian, Ubuntu, Linux Mint)

##### ✅ Pros:

- **User-friendly**: Especially Ubuntu and its derivatives.
    
- **APT Package Manager**: Easy package management via `apt` and `dpkg`.
    
- **Vast Repositories**: Huge number of precompiled packages.
    
- **Strong Community Support**: Plenty of tutorials, forums, and guides.
    
- Most users use this 
	
##### ❌ Cons:

- **Slow to adopt bleeding-edge software** (especially Debian Stable).
    
- **Extra abstraction layers** (like in Ubuntu) might be unnecessary for advanced users.
    

##### 🛠️ Use Cases:

- _General-purpose desktops (Ubuntu, Mint)
    
- _Servers (Debian, Ubuntu Server)
    
- _Great for **beginners** and **enterprise environments**

****
#### 🟥 Red Hat-Based (e.g., RHEL, CentOS, Fedora, Rocky, AlmaLinux)

##### ✅ Pros:

- **RPM Package Manager**: Uses `yum` or `dnf` (Fedora, newer RHEL).
    
- **SELinux support**: Enhanced system security.
    
- **Enterprise-grade**: Stable, long-term support (RHEL, Rocky, AlmaLinux).
    
- **Fedora**: Cutting-edge and upstream source for RHEL features.
    

##### ❌ Cons:

- **Proprietary features**: RHEL requires a paid subscription.
    
- **Software availability**: More limited than Debian (especially older RHEL versions).
    
- **Configuration complexity**: Often more complex than Debian systems.
    

##### 🛠️ Use Cases:

- **Enterprise environments**
    
- **Commercial web hosting**
    
- **Security-focused systems**
****
#### 🟦 Arch-Based (e.g., Arch Linux, Manjaro, EndeavourOS)

##### ✅ Pros:

- **Rolling release**: Always up to date with the latest software.
    
- **Pacman & AUR**: Powerful package manager and a huge user-contributed repo.
    
- **Minimalist by design**: Build exactly what you need, no bloat.
    
- **Excellent documentation**: Arch Wiki is top-tier and community-driven.
    

##### ❌ Cons:

- **Not beginner-friendly**: Especially true for vanilla Arch.
    
- **Rolling release can introduce breaking changes**.
    
- **Requires manual configuration and ongoing maintenance**.
    

##### 🛠️ Use Cases:

- *Advanced users
    
- _Developers who want full control
    
- _Enthusiasts who value customization and minimalism

****
#### 🟩 Unix-Like (BSD Family: FreeBSD, OpenBSD, NetBSD, etc.)

##### ✅ Pro:

- **True Unix heritage**: Clean and consistent system design.
    
- **Security-focused**: OpenBSD is especially known for its security.
    
- **ZFS support**: Excellent support, especially in FreeBSD.
    
- **Ports system**: Allows source-based package installation with high flexibility.
    

##### ❌ Cons:

- **Smaller ecosystem**: Fewer precompiled packages than Linux.
    
- **Hardware support**: Not as broad as Linux.
    
- **Less community support**: Compared to mainstream Linux distros.
    

##### 🛠️ Use Cases:

- _**Firewalls and routers**: Especially OpenBSD and pfSense.
    
- _**High-performance servers**: FreeBSD is commonly used.
    
- _**Academic and research**: Known for reliability and structure
 

****
## 🧾 Summary Table – Linux/Unix Families

| **Feature**                  | ==**Debian-Based**==            | ==**Red Hat-Based**==           | ==**Arch-Based**==             | ==**BSD Family**==             |
| ---------------------------- | ------------------------------- | ------------------------------- | ------------------------------ | ------------------------------ |
| ==**Ease of Use         **== | High                            | Medium                          | Low (Arch), Medium (Manjaro)   | Low to Medium                  |
| ==**Package Manager**==      | `APT`                           | `YUM / DNF`                     | `Pacman / AUR`                 | `pkg / Ports`                  |
| ==**Release Model**==        | Stable / LTS(long term service) | Stable (RHEL), Rolling (Fedora) | Rolling (real time update)     | Mostly Stable                  |
| ==**Community Support**==    | Huge                            | Large                           | Growing                        | Niche                          |
| ==**Security Focus**==       | Moderate                        | High (with SELinux)             | User-dependent                 | Very High (especially OpenBSD) |
| ==**Customization**==        | Moderate                        | Moderate                        | Very High                      | High (via Ports)               |
| ==**Market Share**==         | ~50% (esp. Ubuntu)              | ~25% (mainly servers)           | ~5% (enthusiast desktop users) | <1% (mostly servers)           |

****

| ==**Distribution Type**==  | ==**Package Format**== | ==**Installer**== | ==**Package Tool**== | ==**Examples**==     |
| -------------------------- | ---------------------- | ----------------- | -------------------- | -------------------- |
| **Debian-Based**           | `.deb`                 | `dpkg`            | `apt`                | Ubuntu, Kali Linux   |
| **Red Hat-Based**          | `.rpm`                 | `rpm`             | `yum` / `dnf`        | Fedora, CentOS, RHEL |
| **Arch-Based**             | N/A                    | `pacman`          | `pacman`             | Arch Linux, Manjaro  |
| **Unix-Like (BSD Family)** | Varies                 | `ports` / `pkg`   | `pkg_add` / `pkg`    | FreeBSD, OpenBSD     |
****
# Windows Directory Structure
### 📁 Windows Directory Structure (C:)

##### 📂 C:\

- **The Root of the System Drive**
    
    - Contains system-critical folders and files.
        

##### 📂 Windows

- **Main Operating System Directory**
    
    - Contains OS components like:
        
        -  **🛠️ System32**: Core Windows system files (DLLs, EXEs, drivers).
            
        - 🗃️ **WinSxS**: Side-by-side assemblies (Windows component store).
            
        - 🕒 **Temp**: Temporary files.
            
        - 📋 **Logs**: System and installation logs.
            

##### 📂 Program Files

- **Default Folder for 64-bit Applications**
    
    - Used on 64-bit Windows.
        

##### 📂 Program Files (x86)

- **Default Folder for 32-bit Applications**
    
    - Used on 64-bit Windows.
##### 🧑‍💻 Users

- **Contains User Profiles**, each as a subfolder:
    
    - **Default**: Template for new user profiles.
        
    - **Public**: Shared user space.
        
    - **YourUsername**: Personal files like:
        
        - 🖥️ **Desktop**
            
        - 📄 **Documents**
            
        - 📥 **Downloads**
            
        - ⚙️ **AppData**: Hidden, for app data and configurations.
            

##### 📂 ProgramData

- **Stores Application Data** shared across all users:
    
    - Often used for app settings or cache.
        
    - Hidden by default.
        

##### 🗂️ System Volume Information

-  **Contains System Restore Points** and volume metadata:
    
    - Restricted access.
        
    - System-managed.
    
##### ♻️ $Recycle.Bin

- **Stores Deleted Files** for all users:
    
    - Includes recycle bin contents.
        

##### 📂 Documents and Settings

- **Legacy Folder** from Windows XP:
    
    - Typically a **junction point** now (redirects to **Users**).
        

##### 📂 PerfLogs

- **Stores Performance Logs**:
    
    - Generated by system diagnostics.
        

##### 🚑 Recovery

- **Contains Windows Recovery Environment (WinRE) Files**:
    
    - Used for factory reset or troubleshooting.


###### 📄 System Files

| ==**File**==        | ==**Purpose**==                           |
| ------------------- | ----------------------------------------- |
| `pagefile.sys`      | Virtual memory page file.                 |
| `swapfile.sys`      | Used by modern Windows apps for swapping. |
| `DumpStack.log.tmp` | Temp file for crash dump analysis.        |
****
# Linux Directory Structure 
### 📁 Linux Directory Structure
##### Linux is a File based operating system

| **Directory** | **Purpose**                                                                                       |
| ------------- | ------------------------------------------------------------------------------------------------- |
| `/`           | Root directory; the top level of the filesystem hierarchy.                                        |
| `/bin`        | Essential **user binaries** (e.g., `ls`, `cp`, `mv`). Needed for booting and single-user mode.    |
| `/sbin`       | Essential **system binaries** (e.g., `init`, `fsck`, `reboot`). Mainly for system administration. |
| `/lib`        | Shared **libraries** needed by `/bin` and `/sbin` programs.                                       |
| `/lib64`      | 64-bit specific shared libraries. Present on 64-bit systems.                                      |
| `/etc`        | System-wide **configuration files** and startup scripts.                                          |
| `/dev`        | **Device files** representinrepresentingg hardware (e.g., `/dev/sda`, `/dev/null`).               |
| `/proc`       | Virtual filesystem for **kernel and process information**.                                        |
| `/var`        | **Variable data** like logs (`/var/log`), mail, spool files, cache.                               |
| `/tmp`        | **Temporary files.** Usually cleared on reboot.                                                   |
| `/usr`        | Secondary hierarchy for **user applications** and libraries (`/usr/bin`, `/usr/lib`).             |
| `/boot`       | Files needed to **boot** the system (e.g., kernel, GRUB configs).                                 |
| `/opt`        | **Optional** third-party or add-on software packages.                                             |
| `/srv`        | **Service data** (e.g., for web servers, FTP).                                                    |
| `/home`       | **Home directories** for normal users (e.g., `/home/alex`).                                       |
| `/root`       | Home directory for the **root user**.                                                             |
| `/mnt`        | **Temporary mount point** for manually mounted filesystems.                                       |
| `/media`      | **Auto-mounted removable media** (e.g., USB drives, CDs).                                         |


#### With Analogy to the windows

| ==**Directory**== | ==**Purpose**==                                                                                                                                           | ==**Windows Analogy**==                                                                       |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `/`               | The **root directory** is the top of the Linux filesystem, where everything starts.                                                                       | Similar to `C:\` in Windows—it's the base of the entire filesystem.                           |
| `/bin`            | Contains **essential user binaries** (e.g., `ls`, `cp`, `mv`) required for basic operations. (needed for booting and single user mode)                    | Like `C:\Windows\System32` where key executable files are located.                            |
| `/sbin`           | Holds **system administration binaries** (e.g., `reboot`, `fsck`) typically used by administrators.                                                       | Similar to admin tools in `C:\Windows\System32`.                                              |
| `/lib`            | Contains shared **libraries** required by programs in `/bin` and `/sbin`.                                                                                 | Like DLL files in `C:\Windows\System32`.                                                      |
| `/lib64`          | Stores **64-bit versions** of shared libraries for 64-bit systems.                                                                                        | Similar to a subfolder for 64-bit libraries in Windows.                                       |
| `/etc`            | Houses **configuration files** and scripts used by the system and applications.                                                                           | Similar to the Registry or INI configuration files in `C:\Windows`.                           |
| `/dev`            | Contains **device files** representing hardware like disks, printers, and terminals. here devices are represented as files (e.g., `/dev/sda` for a disk). | Like Device Manager in Windows,                                                               |
| `/proc`           | A **virtual filesystem** that shows system and process information in real-time.                                                                          | Comparable to Task Manager or Resource Monitor in Windows.                                    |
| `/var`            | Stores **variable data** such as logs (`/var/log`), emails, and temporary files created by running services.                                              | Similar to `C:\ProgramData` or log files in `C:\Windows\Logs`.                                |
| `/tmp`            | Used for **temporary files**, which are usually cleared upon reboot.                                                                                      | Similar to the Temp folder in `C:\Windows\Temp`.                                              |
| `/usr`            | A directory for **user-installed applications** and their files (e.g., `/usr/bin`, `/usr/lib`).                                                           | Like `C:\Program Files` or `C:\Program Files (x86)` in Windows.                               |
| `/boot`           | Contains all files needed to **boot** the system, such as the kernel and GRUB configurations.                                                             | Similar to the Boot Configuration Data (BCD) in Windows or boot-related files like `bootmgr`. |
| `/opt`            | Used for **optional or third-party software** installed on the system.                                                                                    | Like `C:\Program Files` for non-standard or custom-installed software.                        |
| `/srv`            | Holds **data for services** such as web servers and FTP servers.                                                                                          | No direct analogy, but similar to folders used by IIS or FTP in `C:\inetpub`.                 |
| `/home`           | Contains **personal files and directories** for regular users (e.g., `/home/alex`).                                                                       | Similar to `C:\Users\<username>` where personal documents and settings are stored.            |
| `/root`           | The **home directory** for the root (administrator) user.                                                                                                 | Similar to the Admin account's profile folder in `C:\Users\Administrator`.                    |
| `/mnt`            | A **temporary mount point** for manually attached filesystems like external drives.                                                                       | Similar to mounting external drives to a letter like `E:\` in Windows.                        |
| `/media`          | Used for **automatically mounted external media** like USB drives or CDs.                                                                                 | Similar to AutoPlay in Windows for USB drives or DVDs.                                        |

****
##### Linux Directory Structure by Importance

1. **`/` (Root Directory)**: The most important directory; the base of the entire Linux filesystem.
    
2. **`/usr`**: The second most important directory; stores user applications, libraries, and essential programs.

****
## CentOS Stream 9 Installation 🖥️

### ✔️ Requirements:

- **💾 Minimum System Requirements:**
    
    -  _🧠 2 GB RAM (4 GB recommended)
        
    - 📂 _20 GB Disk Space (40 GB+ recommended)
        
- **🔧 Tools Needed:**
    
    - 💿 _Bootable USB (16+ GB or more)
        
    - 🌐 _ISO image from centos.org/download
        
    - 📝 _Partitioning plan
        

### 📥 Download CentOS ISO:

1. 🌎 Visit https://www.centos.org/download.
    
2. 📀 Choose **CentOS Stream 9 DVD ISO**.
    
3. 💾 Save the `.iso` file to your computer.

****
### 🛠️ Create Bootable USB

- Use one of the following tools:
    
    - **Windows:** [Rufus](https://rufus.ie)
        
    - **Linux/macOS:** `dd` or Etcher
        

**Example (Linux):**

`dd if=CentOS-Stream-9-*.iso of=/dev/sdX bs=4M status=progress && sync`

> Replace `/dev/sdX` with your actual USB device (not partition).

---

### 🚀 Boot and Start Installation

1. Insert the USB and reboot your system.
    
2. Enter **BIOS/UEFI Boot Menu** (usually `F12`, `ESC`, or `F2`).
    
3. Select the USB drive.
    
4. Choose **Install CentOS Stream 9**.
    

---

### 🌐 Select Installation Options

1. **Language:** Choose your preferred language.
    
2. **Installation Destination:** Click and select your target disk.
    
3. Choose **Custom Partitioning** and set up partitions.

---

### 🧾 Check Swap Usage

`free -h`

---

### 🧱 Recommended Partition Layout

For a 40 GB+ disk, here's a typical partitioning scheme:

| **Mount Point** | **Size** | **Filesystem** | **Type** | **Description**                 |
| --------------- | -------- | -------------- | -------- | ------------------------------- |
| `/boot`         | 1 GB     | xfs            | Standard | Bootloader files                |
| `swap`          | 2–4 GB   | swap           | Swap     | Virtual memory (match RAM size) |
| `/`             | 15–30 GB | xfs            | Root     | System and application files    |

****
### 📊 Swap Space Guidelines

| **RAM Size** | **Recommended Swap Space** |
| ------------ | -------------------------- |
| `< 2 GB`     | 2 × RAM                    |
| `2 – 4 GB`   | 1 × RAM                    |
| `> 8 GB`     | At least 4 GB              |
****
### ⏳ Begin Installation

- Click **Begin Installation**.
    
- Wait for the installation to complete.
    
- Remove USB when prompted and reboot.
    

---

### 🔧 Post-Installation Setup

1. **Log in and update the system**:
    
    `dnf update -y`
    
2. **Enable EPEL (Extra Packages for Enterprise Linux)**:
    `dnf install epel-release -y`
    
3. **Install basic tools**:
    
    `sudo dnf install -y wget curl vim git net-tools`
****
### Login Methods in Linux

##### **🖥️ Graphical (GUI)**:

- 🌟 Uses **X Window System**.
    
- 🖼️ Common Desktop Environments:
    
    - 🟢 **GNOME** (Default).
        
    - 🔵 **KDE Plasma** (Alternative).
        

**➡️ Switch to GUI Console**:

`Ctrl + Alt + F7`

---

##### 💻 Virtual Console (Text-Based / CUI)**:

- ⌨️ Access virtual terminals using:

`Ctrl + Alt + F1 to F6`

****
#### Make the Following setting 
**power** 
- performance mode 
- Screen blank - never
- automatic suspend - Off

****
### 💻 Init Runlevels (Legacy Systems)

Used in **SysVinit** systems, each runlevel defines a specific system state:

| 🔢 Runlevel | 📝 Description                    |
| ----------- | --------------------------------- |
| **0**       | 🛑 Halt (Shutdown)                |
| **1**       | 👤 Single-user mode (Maintenance) |
| **2**       | 👥 Multi-user (No networking)     |
| **3**       | 🧑‍💻 Multi-user (Text-only)      |
| **4**       | ⚙️ Undefined / Custom             |
| **5**       | 🖼️ Multi-user with GUI           |
| **6**       | 🔁 Reboot                         |

---

### 🛠️ Example `init` Commands
`init 0   # 🛑 Shutdown
`init 1   #👤 Single-user mode
`init 3   # 💻 Console mode (no GUI)
`init 5   # 🖼️ Graphical mode
`init 6   # 🔁 Reboot`

****




## Establish SSH Connection
##### 1. What is SSH?

_SSH (Secure Shell) allows you to securely access a server from another device using a terminal.

---

##### 2. Login to the Server

- Use another user’s account to log in to your server. Run this command on your terminal:
    
    `ssh armour@192.168.1.10`
    
- Replace `username` with the name of the user you have access to and `server-ip` with the server's IP address.
    

---

##### 3. Switch to Root User

- Once logged in, switch to the root user by typing:
    
    `su -root`
    
- Enter the root password when asked. You’ll now have full access as the root user.
    

---

##### 4. Enable SSH for Root Login

- While logged in as root, open the SSH configuration file:
    
    `vim /etc/ssh/sshd_config`
    
- Find the line that looks like this:
    
    `#PermitRootLogin prohibit-password`
    
- Change it to this:
    
    `PermitRootLogin yes`
    
- Save the file and exit. In `vim`, press `Esc`, then type `:wq` and hit `Enter`.
    

---

##### 5. Restart SSH Service

- Restart the SSH service to apply the changes:
    
    `systemctl restart sshd`
    

---

##### 6. Login as Root

- Now, log out of the server:
    
    `exit`
    
- Connect to the server directly as the root user:
    
    `ssh root@server-ip`
    
- Enter the root password when prompted.
    

---

##### 7. Security Reminder

- Allowing root login via SSH can be risky. To improve security, make sure to:
    
    - _Use a strong root password.
        
    - _Restrict server access using a firewall or allow only certain IP addresses.
****


### 🔧 Extra Tips and Useful Commands

###### 🌀 Check Current Runlevel

`runlevel`

###### 🧠 Check Kernel Version

`uname -r`

###### 🏷️ Check Linux Distribution


`cat /etc/os-release`

###### 📂 List All Mounted Filesystems

`df -h`

###### 📝 List All Running Processes

`ps aux`

****









