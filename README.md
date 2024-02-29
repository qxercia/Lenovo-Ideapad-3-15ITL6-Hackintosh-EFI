# Lenovo Ideapad 3 15ITL6 Hackintosh EFI

This repository contains the EFI (Extensible Firmware Interface) configuration files and necessary drivers/kexts for running macOS on the Lenovo Ideapad 3 15ITL6 laptop.

## Table of Contents
1. [Introduction](#introduction)
2. [Disclaimer](#disclaimer)
3. [System Requirements](#system-requirements)
4. [Installation](#installation)
5. [Configuration](#configuration)
6. [Troubleshooting](#troubleshooting)
7. [Credits](#credits)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

This EFI configuration is specifically tailored for the Lenovo Ideapad 3 15ITL6 model, allowing users to install and run macOS on their system. It includes necessary drivers, kexts, and configurations to ensure a smooth Hackintosh experience.

## Disclaimer

Please note that Hackintoshing involves modifying system files and running macOS on unsupported hardware. It may void your warranty and can potentially lead to system instability or data loss. Use this EFI configuration at your own risk. The developers and contributors of this repository are not responsible for any damage caused to your hardware or data loss.

## System Requirements

- Lenovo Ideapad 3 15ITL6 laptop
- USB flash drive (8GB or larger)
- macOS installation image
- Basic understanding of BIOS/UEFI settings and Hackintosh installation process

## Installation

1. Download or clone this repository to your computer.
2. Copy the contents of the `EFI` folder to the EFI partition of your USB flash drive.
3. Configure your BIOS/UEFI settings according to the recommended settings (refer to the Configuration section).
4. Boot from the USB flash drive and proceed with macOS installation.
5. After installation, mount the EFI partition of your macOS drive and copy the EFI folder from the USB flash drive to the EFI partition of your macOS drive.
6. Reboot your system and select the macOS drive from the boot menu.
7. Complete the macOS setup process.

## Configuration

Before booting from the USB flash drive or macOS drive, ensure that your BIOS/UEFI settings are properly configured. Here are the recommended settings:

- **UEFI Boot**: Enabled
- **Legacy Boot**: Disabled
- **Secure Boot**: Disabled
- **SATA Mode**: AHCI
- **VT-d**: Disabled
- **CFG Lock**: Disabled
- **DVMT Pre-Allocated**: 64MB
- **Wake on USB**: Disabled
- **USB Boot**: Enabled
- **Fast Boot**: Disabled
- **Intel SGX**: Disabled
- **Execute Disable Bit**: Enabled
- **Intel Virtualization Technology (VT-x)**: Enabled

## Troubleshooting

If you encounter any issues during the installation or boot process, refer to the following troubleshooting steps:

1. Verify BIOS/UEFI settings are properly configured according to the recommendations.
2. Check for compatibility issues with your hardware components.
3. Ensure that you're using a compatible macOS installation image.
4. Double-check that all necessary files are copied to the EFI partition.
5. Try booting with different boot flags or parameters.
6. Search online forums or communities for solutions to specific issues.

## Credits

This EFI configuration is based on contributions from various developers and Hackintosh enthusiasts. Special thanks to the Hackintosh community for their continuous support and efforts in making macOS run on non-Apple hardware.

## Contributing

Contributions to this repository are welcome. If you have improvements, bug fixes, or additional support for other Lenovo Ideapad models, feel free to submit a pull request.

## License

This repository is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute the contents of this repository for personal or commercial purposes. However, please refer to the License file for detailed terms and conditions.
