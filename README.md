# Lenovo Thinkpad X1 Carbon 4th gen Hackintosh Ventura/Sonoma

### Introduction

Files and steps related to Hackintosh-ing a Thinkpad X1 Carbon 4th Gen laptop using Opencore bootloader.
Before using any of these files, make sure you have similar hardware.
> *Though your cases may vary..*



Tested On Ventura 13.7 and Sonoma 14.0
, Opencore Version: 0.9.5

Download Link
https://drive.google.com/file/d/1wlWE5n5il62Dh1KgMUqiFglPvZY7qtfH/view?usp=drive_link
> *If you're upgrading from Big Sur or Monterey make sure you disableed WiFi and Bluetooth kexts*
  
 
 <p align="center">
 <kbd><br>SONOMA
  <br><br>
  <kbd><img src="https://github.com/aalmahmudsk/Lenovo-Thinkpad-X1-Carbon-4th-Gen-Hackintosh-Ventura-Sonoma/blob/main/Sonoma.png"/></kbd></kbd>




### My Hardware

* Model: Thinkpad X1 Carbon Gen 4-2016
* Processor: Intel Core i5-6300U (2C, 2.6 / 3.4GHz, 4MB)vPro
* Graphics: Integrated Intel HD Graphics 520
* Memory: 8GB Soldered
* Display: 14" HD (1080P) IPS
* Sound Card: Conexant CX20753/4
* Storage: 256GB SSD M.2 NVME
* WLAN + Bluetooth: Intel Dual Band Wireless AC 8260
> Airportitwlm is preconfigured based on the branch you use.
> If you face any issues try different versions. Kexts for BigSur, Monterey and Ventura already available.
> Just Enable and Disable accordingly in config.plist.
* Camera: 720p
* Keyboard: Backlit
* Fingerprint Reader: Yes
* Battery: 3-cell (23Wh) + 3-cell (26Wh)

### Bios
- `Security -> Security Chip`: **Disabled**;
- `Memory Protection -> Execution Prevention`: **Enabled**;
- `Virtualization -> Intel Virtualization Technology`: **Enabled**;
- `Virtualization -> Vt-directed IO`: **Disabled**;
- `Internal Device Access -> Bottom Cover Tamper Detection`: must be **Disabled**;
- `Anti-Theft -> Computrace -> Current Setting`: **Disabled**;
- `Secure Boot -> Secure Boot`: **Disabled**;
- `UEFI/Legacy Boot`: **UEFI Only**;
- `CSM Support`: **No**.

 
 ### What's Working?
 
 * CPU Power Management ~1W on IDLE `Ventura` `Sonoma`
 * Intel HD 520 Graphics incuding graphics acceleration `Ventura` `Sonoma`
 * USB ports `Ventura` `Sonoma`
 * Internal camera working fine on FaceTime, Skype, Zoom and others `Ventura` `Sonoma`
 * Sleep / Wake / Shutdown / Reboot `Ventura` `Sonoma`
 * Onelink+ Port with Intel Gigabit Ethernet support `Ventura` `Sonoma`
 * Wifi, Bluetooth, Airdrop, Handoff, Continuity, Sidecar wireless some functionalities may be buggy or broken on Intel WLAN cards `Ventura` `Sonoma`
 * iMessage, FaceTime, App Store, iTunes Store Please generate your own SMBIOS `Ventura` `Sonoma`
 * Speakers and headphones combo jack `Ventura` `Sonoma`
 * Battery management `Ventura` `Sonoma`
 * Keyboard map and hotkeys with YogaSMC `Ventura` `Sonoma`
 * Trackpad, Trackpoint and physical buttons all macOS gestures working thanks to VoodooRMI `Ventura` `Sonoma`
 * SIP and FileVault 2 can be turned on
 * HDMI with digital audio passthrough
 * MiniDP
 * Micro SD Card Reader slow r/w speed but works

 ### What's not Working

 * Fingerprint Reader


