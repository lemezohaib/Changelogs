## AwakenOS v3.4 unofficial for Redmi Note 10 Pro (sweet)

### Device Changelogs:

#### 2-feb-2023
Update kernel to 4.14.304
Update blobs from MIUI V13.0.16.0.SKFMIXM
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
Added toggle to disable ripple effect
Fixed ripple animation for sfps
Fixed system ui crash when unlocking the device with sfps
Enabled battery health
Tons of other misc. changes


### Notes:
• Kernel comes with built in su support.
• Use latest recovery (https://t.me/RedmiNote10ProChannel/1254) 
• Use latest MIUI 13.x firmware for your region

Credits:
• Aryan and Vantom for sources

### Source Changelogs:
// New features:
• Introducing hotspot client manager
• Introducing split status bar icon controls for vibrate and mute
• Added support for showing battery level for AirPods series
• Allowing users to disable clipboard overlay
• Allowing users to quick pull down Quick Settings with one finger

// Fixed issues:
• Fixed issue where alarm icon doesn't show in Quick Settings
• Fixed issue with battery tint on light mode in Quick Settings
• Misc fixes and improvements