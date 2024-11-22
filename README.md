# VMware-Installation-Steps on Windows PC
This repository provides step-by-step instructions, screenshots, and troubleshooting tips for installing and setting up VMware Workstation/Player on a Windows PC

# What is VMware Workstation?

VMware is a powerful virtualization platform that allows you to run multiple operating systems on a single machine.

---

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Installation Steps](#installation-steps)
3. [Troubleshooting](#troubleshooting)
4. [Resources](#resources)

---

## Prerequisites

Before proceeding with the installation, ensure the following:

1. **System Requirements**:
   - Windows 10 or later.
   - Minimum 4 GB RAM (8 GB or more recommended).
   - At least 20 GB free disk space.

2. **Download VMware Workstation/Player**:
   - Go to the [VMware Official Website](https://www.vmware.com/) and download the latest version of:
     - **VMware Workstation Pro** (Paid) 
     - OR **VMware Workstation Player** (Free for personal use).

3. **Enable Virtualization**:
   - Check if virtualization is enabled in your BIOS/UEFI settings:
     - Restart your PC and access the BIOS/UEFI (usually by pressing **DEL**, **F2**, or **F10** during boot).
     - Enable options like **Intel VT-x** or **AMD-V**.

---

## Installation Steps

Follow these steps to install VMware on a Windows PC:

### 1. Download the Installer
- Visit [VMware’s official site](https://www.vmware.com/) and download the appropriate version (Player or Workstation).

### 2. Run the Installer
- Locate the downloaded `.exe` file and double-click it to start the installation.

### 3. Follow Installation Wizard
1. **Accept License Agreement**:
   - Read and accept VMware's license agreement.
   
2. **Choose Installation Path**:
   - Use the default path or specify a custom folder.
   
3. **Select Options**:
   - Choose whether to enable features like VMware Tools updates and customer experience improvement.

4. **Install**:
   - Click "Install" and wait for the process to complete.

5. **Finish Installation**:
   - After the installation completes, click "Finish."

### 4. Launch VMware
- Open VMware Workstation/Player from the Start menu or desktop shortcut.

### 5. Create a Virtual Machine
1. Click **"Create a New Virtual Machine"**.
2. Choose the installation source:
   - ISO file (e.g., Ubuntu, Windows, etc.).
3. Follow the on-screen prompts to configure:
   - Disk size.
   - RAM and CPU allocation.
4. Start the virtual machine and proceed with the OS installation.

---

## Troubleshooting

### Issue: **VT-x is not enabled**
- **Solution**: Enable virtualization in the BIOS/UEFI.
  1. Restart your computer and access the BIOS/UEFI.
  2. Enable options like **Intel VT-x**, **Intel Virtualization Technology**, or **AMD-V**.

### Issue: **Installer blocked by antivirus**
- **Solution**: Temporarily disable your antivirus software during installation.

### Issue: **VM crashes on startup**
- **Solution**: Check if your system has sufficient resources (RAM, disk space, etc.).

### Logs and Support
- Refer to VMware logs for debugging.
- Contact VMware support for additional help.

---

## Resources

- [VMware Official Documentation](https://docs.vmware.com/)
- [BIOS Virtualization Guide](https://www.intel.com/content/www/us/en/support/articles/000020699/processors.html)
- [VMware Community Forums](https://communities.vmware.com/)

---

## Contribution
Feel free to contribute by submitting issues or pull requests for improvements.

---

### Author
Created by [Parthiban M].  
For queries, contact at [parthibanmurugesann@gmail.com].

---

