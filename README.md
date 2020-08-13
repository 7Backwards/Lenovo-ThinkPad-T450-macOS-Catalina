# macOS Catalina (Lenovo ThinkPad T450S)

```  
- Intel 5th Generation Architecture (Broadwell)
- Intel HD Graphics 5500
- Realtek ALC3232/ALC292 Audio Codec
- Intel Series 9 Chipset Family
- macOS Catalina
- working Wifi with stock Intel AC7265
```


   
## Hardware Configuration:

```  
- Intel Core i7-5600U | Broadwell (5th Generation) 
- Dual Core @ 2.7 GHz (up to 3.7 GHz with Turbo Boost) 
- Samsung 8gb (2x4) | DDR3 @ 1600 MHz
- Intel HD 5500 Graphics | 1536 MB VRAM | Full QE/CI & Metal Support  | HDMI Out @ 3840x2160 Max Resolution
- Stock 1920x1080p display
- 3 Solid State Drives | 500G Samsung 850 Evo SATA | 1TB Samsung 840 Evo M.2 | 500G Samsung 840 Evo M.2
- Realtek SDHC | 3x USB 3.1 | HDMI | Intel Gigabit LAN | SIM card  | AUX In/Out | Microphone | HD Webcam 
- Dual Battery Setup (Hot Patched and fully functioning with accurate percentage reporting)   
- Synaptic Three Buttons Trackpad from T450s 
 
```
    
## Build Features:

- This is a fully working catalina setup on a thinkpad t450s/t450, just swap your EFI with mine, this build doesn´t require any wifi swap as it uses the new developed Black80211 and itlwm kexts.

- Touchpad up to 3 fingers Gestures working.

- Bluetooth working.

- Sleep working.

- Battery status working.

- iMessage, FaceTime and AirDrop not tested, please leave your feedback.


## BIOS Configuration Settings:

```  
- CPU: Intel Core i7-5600U
- Memory: 8192 MB
- Wake on LAN disabled for all options
- Intel Rapid Start Disabled
- UEFI Only (CSM Enabled)
- Secure Boot disabled
- Display Memory set to 512 MB 
- Virtualization enabled (VT + disabled)
- All PCIe devices enabled except for finger print sensor (Causes problems when waking from sleep)
- Memory Execution Prevention is enabled
- Hyper threading enabled
```

## Disclaimer:

``` 
- This repo aims to assist people with the same hardware as me,
giving them a solution that works without any additional work.
- I´m not responsible for the development of any kext or any clover configurations present on my EFI,
i simply want to share my working hackintosh solution.
- Any issues please get in contact with jsassu20 or AppleIntelWifi as they are better suited to help you.
- If you want to contribute with any amount please do so on jsassu20 repo as he is responsible for 90% + of the solution.
Enjoy!
``` 

## Credits

jsassu20: For providing the base EFI in which i made tweaks to make it work better for my hardware.

AppleIntelWifi: For providing the kext that enables wifi connection with the stock intel adapter.


