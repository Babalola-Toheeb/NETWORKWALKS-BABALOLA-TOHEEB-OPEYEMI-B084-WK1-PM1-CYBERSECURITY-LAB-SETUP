#NETWORKWALKS-BABALOLA-TOHEEB-OPEYEMI-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP

### Internship Details
- **Intern Name:** Babalola Toheeb Opeyemi
- **Intern ID:** NW-084-0PJ
- **Batch:** B084
- **Domain:** Cybersecurity
- **Week:** WK1 - PM1
- **Project:** Cybersecurity Lab Setup - VirtualBox and Kali Linux

### Note on My Lab Environment
> I already have VMware Workstation installed on my system prior to this internship. I also already have Kali Linux VM and a Windows OS VM installed and configured, so I used my existing VMware-based lab for this task instead of setting up a fresh VirtualBox environment. The functionality and objectives remain the same.

### Project Objective
To demonstrate a working cybersecurity lab environment for penetration testing.

### My Current Lab Setup
- **Hypervisor:** VMware Workstation (Already Installed)
- **Attacker Machine:** Kali Linux VM (Already Installed)
- **Victim / Target Machine:** Windows OS VM (Windows 10/11)
- **Network Mode:** NAT / Host-Only - Both VMs can communicate

### Steps Verified in My Existing Lab

#### 1. Verified VMware Workstation
- VMware Workstation is installed and working
- Checked version and VM list

#### 2. Verified Kali Linux VM
- Booted Kali Linux VM in VMware
- Verified tools are working

#### 3. Verified Windows OS VM
- Booted Windows VM as target machine

#### 4. Network Connectivity Check
Ran inside Kali:
```bash
whoami
uname -a
ip a
ping <Windows-VM-IP>
sudo apt update
