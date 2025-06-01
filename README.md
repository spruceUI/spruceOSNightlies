# SpruceUI Nightly Repository

🚨 **Warning** 🚨

This repository is automatically generated as part of our nightly builds. It contains experimental and potentially unstable versions of our software.

As of May, 2025 these build are targeted towards the Miyoo A30, Miyoo Flip, Trimui Brick and Smart Pro. The same SD card can be used for all of these devices, simply swap the card over and it will work! 

Interested in being a tester? To provide feedback and speak with the development team please join our Discord server [here](https://discord.gg/KjR5uMQQt9)

**MIYOO FLIP USERS PLEASE USE [THIS](https://github.com/spruceUI/spruceOS/releases/download/flip0.0/miyoo355_fw.img) FIRMWARE**

To update FW paste the img file onto the root of a fat32 card (blank is best!) and boot your device. it will show a rocket ship and reboot when it is done. 

## ⚠️ Important Notices

- **Unstable Builds**: This repository contains **work-in-progress** code. Features may be incomplete, change unexpectedly, or break entirely.
- **No Guarantees**: We make **no promises** about stability, functionality, or continued support for anything in this repository.
- **No Support**: Issues related to nightly builds will not receive any attention. For stable releases, refer to our [main repository](https://github.com/spruceUI/spruceOS) or [latest release](https://github.com/spruceUI/spruceOS/releases/latest).
- **Not backwards compatible**: Due to the nature of WIP builds, you will likely need to do a fresh install of the eventual public stable release. Simply using the OTA will likely break things. 
## 🧪 Experimental Warning
- **Data Loss**: Using this software may result in corrupted data or loss of existing configs.
- **Incompatible Changes**: Backward AND Forward compatibility is not guaranteed between nightly versions. Manual updates are occasionally required.
- **Security Risks**: Nightly builds have not been fully tested for vulnerabilities or exploits.

## ⚙️ Installation

1) Read the warnings on this page!
2) Format a fresh, name brand SD card to FAT32.
3) Download the .7z from the most  recent “release” on the this repo.
4) Extract the .7z onto a folder on your computer.
5) Copy and paste ALL files from this folder directly to the root of your fresh SD card. Make sure to get the hidden `.tmp_update` folder!
6) Boot your device with this SD card inserted into the righthand slot if your using a Flip.
7) Give it a few minutes and let it do its thing! When the installation is complete, you will land in spruceUI.

## 🚡 Updating

There are a couple of ways to update, OTA, EZ, and manually.

OTA: Connect to wifi and run the updater app, if your wifi connection holds on this is all you need to do! 

EZ: Download the latest Nightly Release 7z and paste it directly onto the root of your SD card WITHOUT unzipping it. An EZupdater app will show up on your device, click on it and that is all you need to do!

Manual:

1) Delete everything EXCEPT the `Roms` `BIOS` `Saves` and `Persistent` folders from your SD card.
2) Download the .7z from the most  recent “release” on the this repo.
3) Extract the .7z onto a folder on your computer.
4) Copy and paste ALL files from this folder directly to the root of your fresh SD card. Make sure to get the hidden `.tmp_update` folder!
5) Boot your device with this SD card inserted into the righthand slot if your using a Flip.
6) Give it a few minutes and let it do its thing! When the installation is complete, you will land in spruceUI.

## 🤝 Contribution
We appreciate your feedback and bug reports! However, please be aware of the following:

- Contributions targeting nightly/development builds should expect rapid iteration and potential rework.
- Issues unrelated to nightly builds should be reported in our main repository issue tracker with a clear description telling us it is for the **Development** branch.
- Interested in being a tester? To provide feedback and speak with the development team please join our Discord server [here](https://discord.gg/KjR5uMQQt9)


## 📖 Documentation
Documentation will lag behind or be non existant for nightly builds.

## 🌟 Why Nightly?
Nightly builds help us:
- Validate new features in real-world scenarios.
- Get early feedback from developers and power users.
- Accelerate the development cycle of our software.
