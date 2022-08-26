![a52banner](https://i.imgur.com/Xp3zFk2.png)
# A52S-Hidden-Mods
Credit goes to the original creator UltraHQ [Github](https://github.com/UltraHQ). This version is modified by me to work on the A52.


#### For more mods on CSC-Level also get: [A72-CSC-Mods](https://github.com/UltraHQ/A72-CSC-Mods)

### Installation:
1. Download the module from the releases
2. Open the magisk app and go to modules
3. Click the "Install from storage" button and select the .zip you just downloaded 

> Note: It should only be used on the Galaxy A52s 5G (SM-A528B) running the corresponding android security patch version as written in the releases. Trying on other devices is at your own risk.<br/>The changes are always reversable, by simply removing the module in magisk.

### Troubleshooting:
- If camera app crashes (or other issues like error on 64MP mode) please clear camera app data.
- If system apps start crashing, boot into your Recovery and on
  <details open>
  <summary>Stock recovery</summary>
  1. Wipe cache partition</br>2. Repair apps
  </details>
  <details open>
  <summary>TWRP recovery</summary>
  1. Wipe cache partition</br>2. Wipe dalvik cache
  </details>
- To make Object / Shadow / Reflection Eraser show, update [Samsung Photo Editor](https://www.apkmirror.com/apk/samsung-electronics-co-ltd/samsung-photo-editor/) by installing the latest APK.
- To fix Samsung Health root detection, I recommend using [SamsungAppsPatcher](https://adil.hanney.org/SamsungAppsPatcher/)

### Known bugs:
- None. Please report, if you find any

#### Added OS Features:
- Higher Audio Quality (Disabled DRC, which deeply compresses audio)
- Disabled Samsung Marketing
- High-End Animations
- Enhanced CPU Responsiveness
- Added High Performance mode (also known as Enhanced Processing mode)
- Voice Recorder Interview mode
- AOD to Lockscreen Transition
- Full Edge Lighting
- Fixed Smart View (Normally broken on rooted devices)
- Enhance Photo Feature in Gallery
- Codec support for APE, DSD and HDR10+ content
- Camera Privacy Toggle
- ADPS (Wi-Fi Power Saving)
- Enabled [mDNIe](https://www.samsung.com/global/galaxy/what-is/mdnie/)
- Enabled Resolution changing (FHD, HD - only visible in Bixby Routines)
- Setting to limit battery charge to 85%
- Smart Widgets
- Samsung Smart Suggestions (Smart Calendar, Smart Widgets Auto Rotation, ..)


#### Added Camera Features:
- Extended pro (video) mode features: Histogram, Focus peaking, Zoom, Reset button, Expanded shutter speed
- Unlimited Video File Size
- EIS Support / Video stabilization @ 4K (Disable energy saving mode to avoid lag)
- AI Detail Enhancer feature (64MP mode)
- Object/Shadow/Reflection Eraser (Update [Samsung Photo Editor](https://www.apkmirror.com/apk/samsung-electronics-co-ltd/samsung-photo-editor/) to make it work, by installing the latest APK)
- Full single take (Full AI, Second Editing, ..) (Dosen't work yet on the A52 but if i make it work ill create a update release)
- Full Beauty features (Beauty in Live Focus, Beauty Brighten, Body Beauty, change skin tone)
- Torch Flash in Live Focus
- Review feature
- Audio Input Control (In pro video mode - Limitation: Only internal microphone)
- Improved Scene Detection
- S-Series Photo Processing (I removed this from the code because it makes the photos look bad on the A52)
- S-Series AI-Models & AI Features
- Video Audio Zoom
- Full Intelligent Recognition (like Smart Scan Text Extraction)
- Full Live Focus (all S-Series effects)
- [Galaxy Watch Camera Controller](https://www.samsung.com/us/support/answer/ANS00084676/)
- Higher Gallery Zoom Quality
- Video Auto FPS
- Many, not worth to mention, additions
