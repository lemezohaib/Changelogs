## AwakenOS v3.5 unofficial for Redmi Note 10 Pro (sweet)

### Device Changelogs:

#### 8-feb-2023
Update kernel to 4.14.304
Compiled with latest playground Clang 17
Added Sevtinge's Leica Camera 
Update blobs from MIUI V13.0.15.0.SKFMIXM
Update the s5kgw3 camera libraries from MIUI V13.0.9.0.SKFINXM
Uprev IQtiRadio with v2.6
Uprev ImsRadio version to 1.7
Uprev Bluetooth Audio HIDL to 2.1
Uprev IFactory version to 2.3.
Update GPS to LA.UM.9.1.r1-13000-SMxxx0.QSSI13.0
Revert gps PROXY_APP_PACKAGE_NAME OEM change
Improved adaptive refresh rate
Disable SF composition prediction model
Force device to treat 170M as sRGB in SF
Disable redir_party_num
ViLTE should work now?
Fixed an issue with wi-fi
Fixed Netflix HDR
Fixed ripple animation for sfps
Fixed system ui crash when unlocking the device with sfps
Enabled battery health
Tons of other misc. changes


### Notes:
• Use latest recovery (https://t.me/RedmiNote10ProChannel/1254) 
• Use latest MIUI 13.x firmware for your region

Credits:
• Aryan and Vantom for sources

### Changelog for awakenOS v3.5:
// New features:
• Removed text from expanded screenshot chip
• Made per-app volume work with multi audio focus
• Re-organized device info page
• Updated SimpleDeviceConfig

// Fixed issues:

• Fixed issue where in-call vibration options didn't show if multiple vibration intensity overlay was enabled
• Fixed issue where smartspace animation seemed to be broken for Pixel Launcher
• Fixed lock screen status bar was overlapping on Quick Settings (QS) panel
• Fixed some phantom spaces were left behind on status bar clock after enabling AM/PM styles
