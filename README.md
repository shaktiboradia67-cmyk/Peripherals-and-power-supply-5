# Q1.On your Windows laptop or PC, open 'System Information' and take a screenshot showing your OS version, processor, and RAM details.
Ans.## 💻 System Information Screenshot – Windows

### Procedure

1. Press `Windows + R` to open the Run dialog box.
2. Type `msinfo32` and press Enter to open System Information.
3. Select **System Summary**.
4. Locate the following details:
   - **OS Name / Version:** Windows operating system details.
   - **Processor:** Installed CPU information.
   - **Installed Physical Memory (RAM):** Total installed RAM.
5. Maximize the window so the system details are clearly visible.
6. Press `Windows + Shift + S` to capture a screenshot.
7. Save the screenshot as `system-information.png`.
8. Upload the screenshot to your GitHub repository.

### Expected Result

A screenshot showing the computer's actual operating system version, processor, and installed RAM
# Q2.Download any official Linux distribution ISO (like Ubuntu or Fedora), and use Rufus or BalenaEtcher to create a bootable USB drive for installation.<br><br><em><strong>Hint:</strong> If you don't have a spare USB, use a virtual machine tool like VirtualBox to mount the ISO and start the installation process virtually.</em>
Ans.## 🐧 Download Linux ISO and Create a Bootable USB

### Procedure

1. **Download Linux ISO:** Visit the official [Ubuntu website](https://ubuntu.com/download/desktop) and download the latest Ubuntu Desktop ISO file.

2. **Download Rufus:** Visit the official [Rufus website](https://rufus.ie/) and download Rufus for Windows.

3. **Insert USB Drive:** Connect a USB flash drive with at least 8 GB of storage to the computer. Back up its contents because the process will erase the drive.

4. **Open Rufus:** Launch Rufus and select the USB drive under **Device**.

5. **Select ISO File:** Click **SELECT** and choose the downloaded Ubuntu ISO file.

6. **Configure Settings:** Keep the recommended settings unless your system requires different options.

7. **Create Bootable USB:** Click **START**, confirm the required options, and wait until Rufus displays **READY**.

8. **Boot from USB:** Restart the computer and open the boot menu using the appropriate key for your device. Select the USB drive.

9. **Start Linux:** Select the Ubuntu installation or live-session option to begin using Linux.

### Expected Result

A bootable USB drive containing the Ubuntu Linux installer is created successfully and can be used to start the Linux installation process.

### Safety Precautions

- Download ISO files only from official websites.
- Back up all important USB drive data before creating the bootable drive.
- Select the correct USB drive in Rufus to avoid erasing another storage device.
- Installing an operating system can modify or erase existing data, so review the installation options carefully.
# Q3.On a macOS device (or using a macOS virtual machine), open 'System Preferences' and change the desktop wallpaper, then adjust the system language to Hindi or Gujarati.<br><br><em><strong>Hint:</strong> Find 'Language & Region' in System Preferences to add or change languages.</em>
Ans.## 🍎 macOS: Change Desktop Wallpaper and System Language

### Procedure

#### 1. Change Desktop Wallpaper
1. Open the Apple menu () and select **System Preferences**.
2. Click **Desktop & Screen Saver**.
3. Choose a wallpaper from the available images or select a personal picture.
4. Verify that the desktop background has changed.

#### 2. Change System Language
1. Open **System Preferences** from the Apple menu ().
2. Select **Language & Region**.
3. Click the **+** button under Preferred Languages.
4. Select **Hindi** or **Gujarati** from the language list.
5. Click **Add** and choose the new language as the primary language if prompted.
6. Restart or log out and log back in if required for the change to take effect.

### Expected Result
The macOS desktop wallpaper is changed successfully, and Hindi or Gujarati is added or selected as the preferred system language.

### Conclusion
Changing the wallpaper and language settings allows users to personalize the macOS interface according to their preferences.

**Note:** Menu names and available options may vary by macOS version. On newer versions, these settings may be located under **System Settings → Wallpaper** and **System Settings → General → Language & Region**.
# Q4.Install a fresh copy of Ubuntu Linux (real or virtual machine) and create a new user account named 'gamer'. After installation, enable automatic login for this user and take a screenshot of the login screen showing the username.
## 🐧 Ubuntu Installation and User Account Setup

### Procedure

1. **Install Ubuntu:** Download the Ubuntu ISO from the [official Ubuntu website](https://ubuntu.com/download/desktop) and install it on a computer or in a virtual machine using VirtualBox.

2. **Create a User Account:** During installation, create a new user account with the username `gamer` and set a secure password.

3. **Complete Installation:** Finish the installation and restart Ubuntu.

4. **Enable Automatic Login:** Open **Settings → System → Users** (the menu location may vary by Ubuntu version). Unlock the settings using administrator authentication, select the `gamer` account, and enable **Automatic Login**.

5. **Verify the Account:** Log out or restart the system and confirm that Ubuntu automatically logs in as `gamer`.

6. **Take a Screenshot:** Capture the Ubuntu login screen or user session showing the `gamer` username. Save the screenshot as `ubuntu-gamer.png`.

### Expected Result

Ubuntu is installed, the `gamer` user account is created, and automatic login is enabled successfully.

### Screenshot Evidence

Attach your actual screenshot showing the `gamer` username to your GitHub project.

### Security Note

Automatic login reduces security because anyone with physical access to the computer may be able to access the account without entering a password. Use this setting only on a trusted device or virtual machine.
# Q5.Use ChatGPT to generate a step-by-step guide for installing Windows 10 on a laptop, including partitioning tips and post-installation settings for privacy and updates. Follow the guide and note any steps that were unclear or missing.
Ans. # 💻 Windows 10 Installation Guide for a Laptop

## 1. Requirements
- A laptop that meets Windows 10 system requirements.
- A USB drive with at least 8 GB of storage.
- An official Windows 10 ISO file from Microsoft.
- A bootable USB created using Rufus or Microsoft's installation media tool.
- A backup of all important files.
- A valid Windows license, if activation is required.

## 2. Prepare the Laptop
1. Back up important documents, photos, and other files.
2. Download the Windows 10 ISO from the official Microsoft website.
3. Create a bootable USB installation drive.
4. Connect the laptop to its charger.
5. Restart the laptop and open the boot menu using the manufacturer's designated key.
6. Select the USB drive to start Windows Setup.

## 3. Install Windows 10
1. Select the preferred language, time format, and keyboard layout.
2. Click **Install now**.
3. Enter the product key, or select the option to continue without one if available.
4. Accept the license terms.
5. Select **Custom: Install Windows only (advanced)** for a clean installation.
6. Choose the target drive or partition for Windows.
7. Review the selected partition carefully before making changes.
8. Click **Next** and wait for Windows to copy files and complete installation.
9. Follow the setup instructions after the laptop restarts.

## 4. Partitioning Tips
- Back up all important data before modifying partitions.
- Identify the correct internal drive before deleting or formatting anything.
- For a clean installation, delete or format partitions only when you understand their purpose and intend to erase their contents.
- Do not delete recovery or manufacturer partitions unnecessarily.
- Allow Windows Setup to create the required system partitions when using unallocated space.
- Keep sufficient space available for Windows, applications, updates, and personal files.

## 5. Initial Windows Setup
1. Select your region and keyboard layout.
2. Connect to a trusted Wi-Fi network if available.
3. Create or sign in to a user account.
4. Review each privacy prompt carefully.
5. Disable optional data sharing and advertising personalization features that you do not need.

## 6. Privacy Settings
After installation, open **Settings → Privacy** and review the following:
- **Diagnostics & feedback:** Choose the least extensive diagnostic data option available.
- **Location:** Disable location access for apps that do not need it.
- **Camera and microphone:** Allow access only to trusted applications.
- **Background apps:** Disable unnecessary background activity.
- **Advertising ID:** Turn off personalized advertising where available.

## 7. Install Updates and Drivers
1. Open **Settings → Update & Security → Windows Update**.
2. Click **Check for updates**.
3. Install available security updates and restart when prompted.
4. Check Device Manager for missing drivers or warning icons.
5. Install appropriate chipset, graphics, audio, Wi-Fi, and touchpad drivers from the laptop manufacturer's official website.
6. Check Windows Update again after restarting.

## 8. Post-Installation Checks
- Confirm that Windows is activated.
- Verify that Wi-Fi, audio, keyboard, touchpad, and webcam work correctly.
- Check available storage space.
- Enable Windows Security and ensure antivirus protection is active.
- Create a restore point if System Protection is available.
- Back up important files regularly.

## 9. Unclear or Missing Steps Noted

- **Boot menu key:** The correct key varies by laptop manufacturer and model.
- **Partition selection:** The appropriate partition depends on the existing drive layout and whether a clean installation is intended.
- **Drivers:** Some laptops require manufacturer-specific drivers that Windows may not install automatically.
- **Activation:** A valid license or eligible digital entitlement may be required.
- **Privacy options:** Available settings can differ depending on the Windows edition and version.

## Conclusion

Following these steps helps prepare the laptop, install Windows 10, configure privacy settings, install updates, and verify basic hardware functionality.

**Important:** Windows 10 reached the end of standard support on October 14, 2025. For a laptop used online in 2026, consider a supported operating system or an eligible extended security update option.
