## Pixel Experience Plus unofficial for Redmi Note 10 Pro (sweet)

### Device Changelogs:

#### 8-March-2023
Update kernel to 4.14.307
Merge latest caf tag LA.UM.9.1.r1-13100-SMxxx0.QSSI13.0
Update blobs from v14.0.2.0.TKFEUXM
Add miuicamera from v14.0.2.0.TKFEUXM
Import HotwordEnrollment blobs
Fixed battery drain issues by gms

### Notes:
• EROFS build
• VantomKernel is the default kernel
• Use latest recovery (https://t.me/RedmiNote10ProChannel/1254) 
• Use latest MIUI 14.x firmware

Credits:
• Aryan and Vantom for sources
• Gianni for testing


#### 20-feb-2023
Update kernel to 4.14.304
Compiled with latest playground Clang 17
Aperture camera as default with aux lense support and multiple video framerates
Update blobs from MIUI V14.0.1.0.TKFMIXM
Update the s5kgw3 camera libraries from MIUI V13.0.9.0.SKFINXM
Added translations for XiaomiParts
Adjust status bar padding once again (thanks Nayan)
Included a possible fix for NFC for JAPAN variants
Speed up auto brightness ramp up
Limit AOD and ambient display refresh rate to 60Hz
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
Fixed ripple animation for sfps
Fixed system ui crash when unlocking the device with sfps
Tons of other misc. changes

##$ Source Changelogs:
- February security patch
- Fixed safetynet and gpay
- Updated Translations
- Minor issues fixed
- Implement cutout force full screen
- Implement bluetooth dialog
- Added hotspot toggle in internet dialog
- Remove text from expanded screenshot chip
- Added deepsleep preference in about phone
- Implement double tap to trigger doze
- Wi-Fi: Increase 5 GHz network signal tolerance
