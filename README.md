# Ryzentosh-5950X-B550-5700XT

:information_source: **The current version is fully macOS Monterey and Ventura compatible.**

<br/>

[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.0-lightblue.svg)](https://github.com/acidanthera/OpenCorePkg)
[![macOS](https://img.shields.io/badge/macOS-13.2.1-F09337.svg)](https://www.apple.com/macos/ventura)

<img src="截屏2023-03-08 17.04.50.png" style="width: 800px; height: auto;">

## :computer: Hardware:

| **Category** | **Component**                                                                    |
| ------------ | -------------------------------------------------------------------------------- |
| **CPU**      | 3.4 GHz AMD Ryzen 9 5950X 16-Core Processor      |
| **GPU**      | AMD Radeon RX 5700 XT 8 GB                       |
| **RAM**      | 128 GB 3000 MHz DDR4                             |
| **CHIPSET**  | TUF GAMING B550M-PLUS WIFI II [Asus](https://www.asus.com/motherboards-components/motherboards/tuf-gaming/tuf-gaming-b550m-plus-wifi-ii/) |
| **SSD**      | ZHITAI TiPlus7100 1TB                            |
| **Wi-Fi/BT** | Broadcom BCM94360CD                              |
| **Ethernet** | Realtek RTL8125B                                 | 

## :white_check_mark: Working:

- [x] CPU power management.
- [x] Graphics acceleration.
- [x] Keyboard & Mouse
- [x] Wi-Fi.
- [x] Bluetooth.
- [x] HDMI video & audio output.
- [x] Ethernet.
- [x] VGA WebCam.
- [x] AirDrop & Handoff.
- [x] iCloud & App Store.
- [x] iMessage & FaceTime.

## :x: Not working:

Bluetooth and Audio are not working because I don't need and am lazy to solve it. USB ports aren't mapped.(lazy)

## :closed_lock_with_key: SMBIOS

You will need to generate your own SMBIOS and configure, since is required to fully work with macOS. As per this [guide](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo) you can use the following SMBIOS: iMacPro1,1 or MacPro7,1. Note that if your hardware is different for the one mentioned [here](#computer-hardware) you have tho choose an appropriate SMBIOS, more details in the [guide](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html).

Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to generate your own unique SMBIOS and then copy each parametter following path (recomended to follow the guide above):

- Config.plist -> PlatformInfo -> Generic

<img src="https://github.com/gabrielcasag/EFI-RYZEN-5600-B550-RX6600/blob/main/assets/smbios.png" style="width: 800px; height: auto;">


## Credits:

[**Apple**](http://apple.com/)

[**Acidanthera**](https://github.com/acidanthera)

[**Dortania**](https://dortania.github.io/getting-started/)

[**Gabriel Luchina**](https://luchina.com.br)

[**Gabriel Gasperi Casagrande**](https://github.com/gabrielcasag/EFI-RYZEN-5600-B550-RX6600)(for the structure of README)
