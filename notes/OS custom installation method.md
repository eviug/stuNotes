```markdown id="custom-installation-recovery"
# Custom Installation Process and System Recovery Options

A custom installation process allows advanced control over how an operating system is installed, restored, or recovered. It is commonly used in IT environments, upgrades, repairs, and system deployment.

---

# 1. Custom Installation Process

A custom installation means the user manually configures installation settings instead of using default options.

It is used when:
- Installing OS on a new computer
- Replacing a damaged system
- Reorganizing storage partitions
- Deploying multiple systems in a network

---

# 2. Disk Cloning

Disk cloning is the process of making an exact copy of a hard drive or SSD, including:
- Operating system
- Installed applications
- User settings
- Files and folders
- Boot records

---

## 2.1 How Disk Cloning Works

1. Source disk (original system) is selected  
2. Target disk (new drive) is connected  
3. Cloning software copies all data sector-by-sector  
4. New drive becomes bootable system

---

## 2.2 Uses of Disk Cloning

- Upgrading HDD to SSD
- Deploying identical systems in organizations
- Fast system recovery
- Backup of entire system

---

## 2.3 Advantages

- Saves installation time
- Keeps system configuration intact
- Quick recovery option

---

## 2.4 Disadvantages

- Requires same or larger storage size
- Copies errors or malware if present
- Requires special software

---

# 3. Network Installation

Network installation is installing an operating system over a network instead of using USB or DVD.

---

## 3.1 How It Works

1. Computer boots from network (PXE boot)
2. Connects to a server
3. Downloads OS installation files
4. Installation runs remotely

---

## 3.2 Requirements

- Network Interface Card (NIC)
- Boot server (PXE server)
- Stable network connection

---

## 3.3 Advantages

- Centralized installation
- Useful for many computers
- Faster deployment in organizations

---

## 3.4 Disadvantages

- Requires technical setup
- Depends on network stability
- Not suitable for home users

---

# 4. Restore, Refresh, and Recover

Modern operating systems provide tools to fix system problems without full reinstallation.

---

# 4.1 System Restore

System Restore returns the computer to a previous working state using restore points.

## How It Works:
- Periodic restore points are saved
- System files and settings are rolled back

## What It Affects:
- System files
- Drivers
- Registry settings

## What It Does NOT Affect:
- Personal files (documents, photos)

---

## Advantages:
- Quick fix for system errors
- No data loss

## Limitations:
- Must have restore points enabled
- Does not fix hardware problems

---

# 4.2 Refresh (Reset Keep My Files)

Refresh reinstalls the operating system while keeping personal files.

## What It Does:
- Reinstalls Windows system files
- Removes installed apps
- Keeps personal data

## Uses:
- Fix slow performance
- Remove system corruption

---

## Advantages:
- Keeps personal files
- Fixes OS issues

## Disadvantages:
- Apps must be reinstalled
- Settings may reset

---

# 4.3 Reset / Recovery (Remove Everything)

This option restores the system to factory state.

## What It Does:
- Removes all files
- Removes apps
- Reinstalls fresh OS

## Uses:
- Selling or disposing of a PC
- Severe system failure

---

# 5. System Recovery Options

System recovery options help repair or restore a damaged operating system.

---

## 5.1 Startup Repair

Automatically fixes boot problems such as:
- Missing boot files
- Corrupted startup configuration

---

## 5.2 Safe Mode

Starts the computer with minimal drivers.

Used for:
- Removing viruses
- Fixing driver issues
- Troubleshooting software problems

---

## 5.3 Command Prompt Recovery

Advanced tool used to run commands like:
- Boot repair commands
- Disk checks
- File recovery operations

---

## 5.4 System Image Recovery

Restores the entire system from a saved image.

Includes:
- OS
- Applications
- Settings
- Files

---

## 5.5 BIOS/UEFI Recovery Options

Some systems allow recovery at firmware level:
- Reset BIOS settings
- Recover corrupted firmware
- Restore boot configuration

---

# 6. Comparison of Recovery Methods

| Method | Keeps Files | Keeps Apps | Complexity | Use Case |
|---|---|---|---|---|
| System Restore | Yes | Yes | Easy | Fix minor issues |
| Refresh | Yes | No | Medium | Fix OS corruption |
| Reset | No | No | Easy | Full reinstall |
| Disk Cloning | Yes | Yes | Medium | Backup/upgrade |
| Network Install | Depends | Depends | Advanced | Bulk installation |

---

# 7. Summary

Custom installation and recovery methods provide flexible ways to install, repair, and restore operating systems.

### Key points:
- Disk cloning creates exact system copies
- Network installation installs OS via network servers
- System restore rolls back system settings
- Refresh reinstalls OS while keeping files
- Reset restores factory settings
- Recovery tools fix boot and system problems

These methods ensure systems can be maintained, repaired, and deployed efficiently in both personal and professional environments.
```
