# BIOS / UEFI Exploration

## Introduction

Every time I hit the power button on my PC, the BIOS/UEFI firmware is the first to spring into action. This crucial piece of software takes care of everything—from kickstarting the hardware to booting up the operating system. For simplicity, I’ll be referring to both BIOS and UEFI as BIOS from here on out.

Mastering the BIOS is a vital skill, whether I need to tweak the boot order, enable or disable specific hardware, update the firmware, or adjust the system’s clock. Typically, I can enter the BIOS by pressing a specific key—like F10, F2, F12, F1, or DEL—immediately after powering on the machine but before the operating system starts loading. Alternatively, I can dive into the BIOS through the advanced startup options in Windows 10 or 11.

For this lab, I’m diving into the BIOS of a ThinkPad X1 Yoga 6th Gen (20XY,20Y0) - N32ET09W generation laptop using an online simulator. I’ll be navigating through different menus, tinkering with settings, and snapping some screenshots along the way. 

Online Simulator : [BIOS Simulator Center](https://download.lenovo.com/bsco/index.html#/)

<br />

> **Note:** BIOS interfaces vary by manufacturer, with some being text-heavy and others more graphical, but the core functionality is usually quite similar.

---

## Exploring the BIOS Settings

### Checking the Date/Time Menu

First up, I headed to the Date/Time menu to check out the system’s current date and time settings. I captured a screenshot to document the details.

<br />

<p align="center">
  <img src="https://github.com/user-attachments/assets/d4b2dc00-128b-44c1-8ea6-b5b5aaeba599" height="100%" width="100%" alt=""/>
</p>

### Reviewing the UEFI BIOS Version

Next, I dug into the BIOS version and release date. The version on this system was `N32HTXXW`, released on `2020-10-22`. I noted this for future reference.

### Enabling USB Charge in Battery Mode

To ensure that USB devices could charge even when running on battery, I enabled the **USB Charge in Battery Mode** option. After flipping the switch, I grabbed a screenshot to record the change.

<br />

<p align="center">
  <img src="https://github.com/user-attachments/assets/6fbcd10c-acaf-47ec-bc50-a9b1e3c95619" height="100%" width="100%" alt=""/>
</p>

### Enabling Intel® VT-d

To take full advantage of hardware virtualization, I enabled  **Intel® VT-d**. Once again, I took a screenshot to capture these settings in action.

<br />

<p align="center">
  <img src="https://github.com/user-attachments/assets/964273e5-f2f7-4900-a673-7b34cbdb1fd0" height="100%" width="100%" alt=""/>
</p>

### Disabling Bluetooth, USB Ports, and NFC

For an extra layer of security, I disabled a few features: Bluetooth, USB ports, and NFC. I followed this with a final screenshot to show the disabled options.

<br />

<p align="center">
  <img src="https://github.com/user-attachments/assets/358c2573-2cf1-4694-a0c7-7c7a662a77ef" height="100%" width="100%" alt=""/>
</p>

---

## Answering Key Questions

As I continued exploring the BIOS, I uncovered a few critical pieces of information:

- Pressing `F12` during boot brings up the **Boot Device List Option** menu.
- A **Supervisor Password** is essential for blocking unauthorized users from accessing the Boot priority list, Network-related items, and the ability to change the Date & Time in the BIOS.
- Setting a **Power On Password** prevents unauthorized users from booting the system altogether.

---

## Saving and Exiting the BIOS

Before wrapping things up, I made sure to save all my changes. When the system asked for confirmation, I gave the go-ahead to save the configuration and exit the BIOS. Naturally, I captured a screenshot of the confirmation prompt for good measure.

<br />

<p align="center">
  <img src="https://github.com/user-attachments/assets/182f9b26-7bdb-4ce5-b907-bb83d7b4792c" height="100%" width="100%" alt=""/>
</p>

---

### Conclusion

In this lab, I explored the BIOS/UEFI of a Lenovo X1 Yoga 6th generation laptop, navigated its various settings, and honed my ability to manage key system configurations. Every step of the way, I captured screenshots to ensure a thorough and detailed documentation process.
