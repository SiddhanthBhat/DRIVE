#  DRIVE – Diagnostic Recovery Integrated Versatile Environment

**DRIVE** is a lightweight, USB-bootable operating system designed for system diagnostics, file recovery, and hardware troubleshooting. Built on top of TinyCore Linux, DRIVE is packed with essential tools to help recover data, fix boot issues, and diagnose hardware failures.

## Features

- **Quick Boot:** Boots directly from a USB stick for fast access to system diagnostics.
- **Hardware Diagnostics:** Tools to test memory, hard drives (including S.M.A.R.T.), and more.
- **File Recovery:** Recover lost partitions or deleted files using powerful recovery tools.
- **Boot Repair:** Fix corrupted bootloaders for both Linux and Windows systems.
- **Lightweight and Efficient:** Minimal system requirements, perfect for use on older hardware.
  
## Included Tools

- **Filesystem and Partition Management:** `GParted`, `parted`, `e2fsprogs`, `ntfs-3g`, `exfat-utils`, `xfsprogs`, `btrfs-progs`
- **Disk Health and Recovery:** `TestDisk`, `PhotoRec`, `smartmontools`, `ddrescue`
- **Memory Diagnostics:** `MemTest86+`
- **Antivirus and Security:** `ClamAV`, `chkrootkit`
- **Backup and Cloning:** `Clonezilla`, `rsync`, `tar`
- **Networking Tools:** `net-tools`, `iputils-ping`, `ethtool`
- **Bootloader Tools:** `GRUB`, `boot-repair`, `chntpw`
- **System Utilities:** `lshw`, `htop`, `inxi`, `mc` (Midnight Commander)
  
## Getting Started

### Prerequisites

- A USB stick with at least **512MB** of free space.
- A tool to flash the ISO to your USB stick, such as:
  - [Rufus](https://rufus.ie/) (Windows)
  - [Balena Etcher](https://www.balena.io/etcher/) (Windows/Mac/Linux)
  - `dd` (Linux/Unix-based systems)

### Download the ISO

You can download the latest version of the MDROS ISO from the [Releases page](https://github.com/yourusername/mdros/releases).

### Creating a Bootable USB

#### Using Rufus (Windows):
1. Download and open [Rufus](https://rufus.ie/).
2. Select your USB stick under **Device**.
3. Select the MDROS ISO file under **Boot Selection**.
4. Click **Start** and wait for the process to complete.
5. Boot from the USB stick by restarting your computer and selecting the USB as the boot device in your BIOS/UEFI settings.

#### Using Balena Etcher (Windows/Mac/Linux):
1. Download and install [Balena Etcher](https://www.balena.io/etcher/).
2. Open Etcher and click **Flash from file** to select the MDROS ISO.
3. Choose your USB stick as the target device.
4. Click **Flash** and wait for the process to complete.
5. Restart your computer and boot from the USB stick.

#### Issues and Support
If you encounter any issues or have suggestions, please open an issue in the Issues tab.

#### License
This project is licensed under the MIT License. See the LICENSE file for more details.

#### Acknowledgments
TinyCore Linux for the minimal base OS.
The open-source community for providing essential diagnostic and recovery tools.
TestDisk, PhotoRec, MemTest86+, and all other projects integrated into this recovery OS.
