# pico_rcm2date

## Overview

This pack centralizes files commonly used to:

- Update PicoFly firmware
- Update RCM Loader firmware
- Inject payloads from Android
- Inject payloads from Windows
- Update Hekate
- Prepare SD cards
- Boot Nintendo Switch payloads

Most users only need one folder depending on their setup.

This pack is intended to centralize files that are often spread across forums, GitHub repositories, and community resources.

---

## Folder Guide

### Rekado_5.4.120

Android payload injector.

Use this folder if you want to inject payloads from an Android device.

Install the included APK and follow the application instructions.

---

### TegraRcmGUI_v2.6_portable

Windows payload injector.

Use this folder if you want to inject payloads from a Windows PC.

Includes:

- APX drivers
- Payload injection tools

Follow the included documentation for installation and usage instructions.

---

### hekate_ctcaer_6.4.2_Nyx_1.8.2

Included Hekate release.

Use this folder to install, update, or replace an existing Hekate installation.

Refer to the included files and documentation for detailed instructions.

---

### payload

Contains:

payload.bin

Use this payload when a guide or tool requests a payload file to inject.

This file can be used with compatible payload injectors such as:

- Rekado
- TegraRcmGUI
- RCM Loader
- PicoFly Toolbox

---

### picofly_update-V2.73

PicoFly firmware update package.

Includes:

- Firmware files
- Update files
- Toolbox payload
- Documentation
- Error code reference

Refer to the included documentation for detailed instructions.

Use this folder when updating an existing PicoFly installation.

---

### rcm_loader_update

RCM Loader update files.

Includes support for:

- RCM Loader One V1
- RCM Loader One Plus V2

Choose the folder matching your hardware version.

The required update files and instructions are included.

---

### sd_utils

MicroSD card utilities.

Includes:

- SD Card Formatter
- guiformat

Recommended workflow when preparing a microSD card:

1. Use SD Card Formatter first.
2. Use guiformat if FAT32 formatting is required.

SD Card Formatter can help restore a clean SD card structure before formatting.

guiformat is commonly used to format large SD cards as FAT32 for Nintendo Switch homebrew usage.

---

## Typical Use Cases

### I want to inject a payload from Android

Use:

Rekado_5.4.120

---

### I want to inject a payload from Windows

Use:

TegraRcmGUI_v2.6_portable

---

### I want to update Hekate

Use:

hekate_ctcaer_6.4.2_Nyx_1.8.2

---

### I want to update PicoFly

Use:

picofly_update-V2.73

---

### I want to update an RCM Loader

Use:

rcm_loader_update

---

### I want to prepare a microSD card

Use:

sd_utils

---

## Notes

Choose the folder that matches your setup or current task.

Most users only need one of the folders provided in this pack.

Several folders include their own documentation and guides.

Refer to the documentation included with each tool for detailed usage instructions.

Version numbers may change in future releases, but the folder purposes remain the same.

This repository is intended as a convenience pack that centralizes commonly used Nintendo Switch files and utilities.

---

## Credits

This pack includes files and tools created by their respective authors.

Original documentation and credits remain included within the corresponding folders whenever available.

This repository centralizes commonly used Nintendo Switch payload injection, update, and SD card preparation tools for convenience.
