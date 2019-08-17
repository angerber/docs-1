---
layout: article
title: Install Pop!_OS On Your System76 Computer
description: >
  Full instructions on installing Pop!_OS your computer.
keywords:
  - Pop!\_OS
  - 18.04
  - Restore
  - Reinstall
  - Installation
  - Driver
  - system76-driver
  - system76-driver-nvidia
  - Release
  - System76
image: http://support.system76.com/images/pop-icon.png
hidden: false
section: pop-ubuntu

---

The following guide describes how to download the Pop!\_OS.iso image, write it to a flash drive, and install it on the hardware of your choice.

Requirements: At the time of this writing Pop!\_OS only runs on 64-bit x86 architecture, 2GB RAM is required, and 4GB RAM and 20GB storage is recommended.

## Make Bootable Drive

Please see our instructions for making and booting from a live disk of Pop!\_OS [here](/articles/live-disk/).

## Installing Pop!\_OS

The first step after booting from your new live disk is to select your language:

![Language](/images/install-pop/1_language.png)

Next, select your keyboard layout and region:

![Keyboard](/images/install-pop/2_keyboard.png)

Now, you can choose to either install Pop!\_OS, or try Demo Mode to test out the OS before installing:

![Try or Install](/images/install-pop/3_try_or_install.png)

Here, you can opt to erase the currently-installed operating system and install Pop!\_OS on the selected drive. If you need to Dual Boot or want to have a separate Home partition or place the /tmp partition on a different drive, select Custom Partitioning on the left:

![Disk setup](/images/install-pop/4_disk.png)

### Full Disk Encryption

Encrypting your drive adds an extra layer of security to your machine. However, if your encryption password is lost or forgotten, you will lose all access the contents of the drive. If you would like to encrypt the drive, select **Choose Password**. If not, then select **Don't Encrypt**.

![Encrypt option](/images/install-pop/5_encrypt_notice.png)

If you chose to encrypt your drive, you will be brought to this screen. Here, you will choose your encryption password. This password will be requested every time the system boots:

![Encrypt password](/images/install-pop/6_encrypt_password.png)

Let the Pop!\_OS install commence!

![Progress](/images/install-pop/7_progress.png)

Pop!\_OS has been successfully installed on your computer. Awesome work! You can choose to reboot your computer to create your new user account for the OS, or you can shut down and set it up later:

![Success](/images/install-pop/8_success.png)


#### NVIDIA Graphics

The Pop!\_OS NVIDIA ISO includes the drivers for NVIDIA graphics cards. However, if you installed from the Intel/AMD ISO and your system has a discrete NVIDIA graphics card, or if you added one later, you will need to manually install the drivers for your card to get the optimum performance. Please run the following command in a command terminal to install the driver:

```
sudo apt install system76-driver-nvidia
```
