# 👻 PHANTOM BLE Spoofer (v1.0)

![Status](https://img.shields.io/badge/Status-Freeware-green)
![Platform](https://img.shields.io/badge/Platform-Android-green)
![Core](https://img.shields.io/badge/Core-BLE%20Advertising-blue)
![Version](https://img.shields.io/badge/Version-1.0%20(Initial%20Release)-3947a9)
![Security](https://img.shields.io/badge/Purpose-Educational%20Spoofing-red)
![Presets](https://img.shields.io/badge/Presets-Samsung%20%26%20Apple-pink)

**PHANTOM** is an advanced mobile BLE spoofer application for Android. The application integrates essential pre-configured profiles for popular consumer electronics to mimic their Bluetooth identities via LE advertising packets.

> [!WARNING]
> **DISCLAIMER / LEGAL NOTICE**
> 
> This application was created **solely for educational purposes** and for **authorized testing** of Bluetooth discovery mechanisms on your own devices.
> 
> The author assumes no liability for any issues caused by the misuse of this software. Using offensive modules or attempting to spoof devices without the owner's explicit permission may violate local laws. By installing this application, you agree to the terms of the EULA.

## 🚀 Features (v1.0)

The toolkit is divided into core functions:

### 🎧 Device Emulation & Spoofing
*   **Verified Presets:** Includes stable, verified advertising profiles for various **Samsung Galaxy Buds** and **Galaxy Watch** models.
*   **Experimental Presets:** Includes active advertising profiles for **Apple FindMy** and **AirPods** (requires experimental mode toggle).
*   **Bluetooth Name Spoofing:** Temporarily changes the device's local name to match the selected target (where permitted by the OS).

### 📡 BLE Advertising Core
*   **Samsung Protocol Handler:** Implements necessary GATT Service setup (e.g., Battery Service) alongside LE advertising for Samsung device mimicry.
*   **Apple Protocol Handler:** Adjusts advertising data length and structure for iOS compatibility (FindMy/AirPods profiles).
*   **Real-time Status:** Live feedback on the current advertising status and target device selected.

### ⚙️ System & Settings
*   **Toggleable Modes:** Allows enabling/disabling the visibility of experimental (potentially less stable) presets.
*   **System Logging:** On-device console log to track successful activations, failures, and system events.
*   **Automatic Cleanup:** Ensures original device name and BLE advertising are restored upon termination.

---

## 📥 Download & Installation

The application is distributed **only via this GitHub repository**.

1.  Navigate to the **[Releases](../../releases)** tab of this repository.
2.  Download the latest `.apk` file or the full source code archive.
3.  Install the application on your Android device (you may need to allow installation from unknown sources).
4.  Launch the app and ensure necessary **Bluetooth Permissions** are granted.

> **Requirements:** Android device supporting BLE Advertising (generally Android 5.0+).

### 🛡️ Important Note Regarding Permissions
To function correctly, PHANTOM requires several system permissions, including **Location** (for pre-Android 12 BLE scanning/advertising) and **Bluetooth Connect/Advertise** permissions (Android 12+). Granting these is essential for the core functionality.

### 🔑 Administrator Privileges (N/A)
As a standard Android application, PHANTOM runs under its own permission context managed by the operating system. No manual "Run as Administrator" is required, though permission requests must be accepted by the user.

---

## 📜 License

**PHANTOM** is **Freeware**.
It is provided "as is" for educational use.

❌ **RESTRICTIONS:**
*   Reverse Engineering, decompilation, or modification of the source code is strictly prohibited.
*   Using the application to interfere with unauthorized networks or devices is prohibited.
*   Selling or sub-licensing the application is prohibited.

See the code comments for licensing context.
