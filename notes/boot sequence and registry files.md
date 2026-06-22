# Boot Sequence and Registry Files in Windows

The boot sequence is the process a computer follows to start the operating system. In Windows systems, this process involves firmware, boot files, and system configuration stored in the Windows Registry.

---

# 1. Windows Boot Process

The Windows boot process is the series of steps that occur from pressing the power button until the desktop appears.

:contentReference[oaicite:0]{index=0} uses a structured boot sequence involving BIOS/UEFI, bootloader, and system files.

---

## 1.1 Steps in the Windows Boot Sequence

### Step 1: Power On
- Power supply sends electricity to motherboard and components

---

### Step 2: POST (Power-On Self-Test)
- Hardware is checked (CPU, RAM, storage, keyboard)
- Errors are shown using beep codes or messages

---

### Step 3: BIOS/UEFI Initialization
- Firmware starts first control program
- Hardware devices are detected and configured

---

### Step 4: Boot Device Selection
- BIOS/UEFI checks boot order (SSD, HDD, USB, network)

---

### Step 5: Bootloader Execution
- Bootloader loads from disk:
  - **Windows Boot Manager**

---

### Step 6: Windows Operating System Loader
- Loads essential system files into memory:
  - Kernel
  - Device drivers

---

### Step 7: Kernel Initialization
- Windows kernel starts managing hardware and memory

---

### Step 8: User Login Screen
- User authentication appears
- Desktop environment loads after login

---

# 2. Windows Startup Modes

Startup modes are special boot options used for troubleshooting and system recovery.

---

## 2.1 Normal Mode

- Standard startup
- Loads all drivers and services
- Used for everyday operation

---

## 2.2 Safe Mode

Safe Mode starts Windows with minimal drivers and services.

### Characteristics:
- Basic display driver
- Limited functionality
- No third-party applications

### Uses:
- Removing viruses
- Fixing driver issues
- System troubleshooting

---

## 2.3 Safe Mode with Networking

- Same as Safe Mode
- Adds network drivers

### Uses:
- Downloading drivers or updates during troubleshooting

---

## 2.4 Safe Mode with Command Prompt

- No graphical interface
- Uses command-line interface

### Uses:
- Advanced repairs
- Running system commands

---

## 2.5 Recovery Mode (Windows Recovery Environment - WinRE)

Used when Windows cannot boot normally.

Includes tools like:
- Startup Repair
- System Restore
- Reset PC
- Command Prompt

---

# 3. Windows Registry

The Windows Registry is a centralized database that stores configuration settings for the operating system, hardware, and installed applications.

---

## 3.1 Structure of the Registry

The registry is organized into sections called “hives”:

### Common Registry Hives:
- **HKEY_LOCAL_MACHINE (HKLM)** → System-wide settings
- **HKEY_CURRENT_USER (HKCU)** → User-specific settings
- **HKEY_CLASSES_ROOT (HKCR)** → File associations
- **HKEY_USERS (HKU)** → All user profiles
- **HKEY_CURRENT_CONFIG (HKCC)** → Hardware configuration

---

## 3.2 What the Registry Stores

- System settings
- Installed software information
- User preferences
- Hardware configurations
- Startup programs

---

## 3.3 Example Registry Uses

- Setting desktop wallpaper
- Configuring startup applications
- Storing device drivers
- Managing file types

---

## 3.4 Registry Editor

The Registry is managed using:

- **Registry Editor (regedit)**

Allows users to:
- View registry keys
- Modify settings
- Add or delete entries

⚠️ Incorrect changes can cause system failure.

---

## 3.5 Registry at Startup

During boot:
- Windows loads registry hives into memory
- System configuration is applied
- Startup programs are launched

---

# 4. Relationship Between Boot Process and Registry

The boot process depends on registry settings:

- Startup programs are defined in the registry
- Device drivers are loaded based on registry entries
- User login settings are stored in registry hives

---

# 5. Boot Configuration Data (BCD)

Windows also uses Boot Configuration Data (BCD), which is a special database used to control startup behavior.

It replaces older boot.ini systems.

---

## BCD Stores:
- Boot options
- Operating system entries
- Startup settings

---

# 6. Summary

### Windows Boot Process:
1. Power on
2. POST
3. BIOS/UEFI startup
4. Boot device selection
5. Bootloader loads Windows
6. Kernel starts
7. User login

---

### Startup Modes:
- Normal Mode
- Safe Mode
- Safe Mode with Networking
- Command Prompt Mode
- Recovery Environment

---

### Windows Registry:
- Central configuration database
- Stores system, user, and hardware settings
- Loaded during startup
- Critical for system operation

---

# Final Note

The boot sequence ensures the operating system starts correctly, startup modes help with troubleshooting, and the Windows Registry controls how the system behaves and remembers settings.