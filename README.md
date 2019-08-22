# Asus Vivobook Max X441UVK Hackintosh

*Please!! Read carefully before applying on your device.* <br>
This time I have updated my device's BIOS to the latest version. The latest version is currently at <b>X441UVK.324</b>. <br>
Good luck!!

## Specification

- Model     : X441UVK
- BIOS      : X441UVK.324
- CPU       : Intel Core i3-7100U
- RAM       : 8GB DDR4 2133Mhz
- Storage   : 240GB SSD + 1TB HDD
- iGPU      : Intel HD Graphics 620
- eGPU      : Nvidia Geforce 920MX
- Trackpad  : ELAN 1200 I2C
- Wifi      : Qualcomm Atheros AR9565
- Ethernet  : Realtek 8101E/8102E
- Audio     : Realtel ALC255 Revision 2
- USB       : Intel series
- Boot Mode : UEFI

## Whats Work?

- QE/CI Graphics Intel HD Graphic 620
- CPU Power Management
- Sleep/Wake
- Shutdown and Restart
- All USB with Maximum Speed
- Brightness
- Ethernet
- Wifi
- Battery Indicator
- Keyboard
- Trackpad
- HDMI
- Audio
- HD Camera
- Fn Keys
- Trim Support for SSD
- etc

## Not Work

- SD Card Reader 
- VGA
- etc

## How to Use

1. Download the source at the following link https://github.com/alfinauzikri/Asus-Vivobook-Max-X441UVK-Hackintosh/releases
2. Select based on the macOS version used on the device
3. Extract and then there is an EFI folder that is ready to use
4. Backup your old EFI folder
5. Then, move the new EFI folder containing the files that are ready to use
6. Run after completing all the steps above
7. Feedback is needed, in order to make the repository, even better and more useful. Thank you!!

## How to Fix

### Wifi

1. Download the <b>AirPortAtheros40.kext</b> file for the <b>AR9565 model</b> from my repository and <b>Kextbeast 2.0.2</b> from tonymacX86.com or internet
2. Extract <b>AirPortAtheros40.kext.zip</b> and place <b>AirPortAtheros40.kext</b> on the desktop
3. Run Kextbeast 2.0.2 and select the installation location at *Library/Extensions*
4. Reboot

### Audio

1. Download the <b>CodecCommander.kext</b> file from my repository and <b>Kextbeast 2.0.2</b> from tonymacX86.com or internet
2. Extract <b>CodecCommander.kext.zip</b> and place <b>CodecCommander.kext</b> on the desktop
3. Run Kextbeast 2.0.2 and select the installation location at *Library/Extensions*
4. After the above steps are complete, Download the ALCPlugFix for ALC255 from the following repository https://github.com/black-dragon74/ALCPlugFix/releases
5. Run the script
6. And reboot after complete all.

### FN Keys
1. Download the <b>AsusSMC</b> package from the following repository https://github.com/hieplpvip/AsusSMC/releases
2. Extract package and run the script install_daemon.sh
3. Reboot

![Screenshot](X441UVK-SS.png?raw=true)

alfinauzikri | t.me/alfinauzikri

Thanks for all support

- https://github.com/andreszerocross
- https://github.com/daliansky 
- https://github.com/acidanthera
- https://github.com/Dids
- https://github.com/RehabMan
- https://github.com/hieplpvip
- etc
