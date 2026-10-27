<img width="512" height="512" alt="IMG_20260719_165008_269" src="https://github.com/user-attachments/assets/bf6c8eb0-473c-4f46-9a69-0d95d73f18d3" />
<p align="center"><b>Hi, you came here with a new update! ~ Please read changelogs 😗</b></p>

**Some notes**:
- Android 12 below might not work activity open/close animation
- 32bit devices might not disable completely
- Do not use FULL version if you are on AOSP Custom ROM.

## 4.0

**Changelogs**:
- Added support for Magisk, also detects if you are using Magisk.
- Added some VM (_dirty_background_ratio, dirty_expire_centisecs_) and LMK props
- Added detection if you are on Android Go based on vendor during installation
- Some code improvements
- Restored heapsize

## 3.0

**Changelogs**:
- Full/Lite version is now in one module, you can now select during flash using the volume buttons.
- Added a feature to remove the metamodule detection if you're on Magisk
- Some code improvements
- Size decreased, removed banner and used raw link

## 2.0

**Changelogs**:
- Added mechanism to auto disable if metamodule isn't installed
- Changed activity open/close animation to stock AOSP 
- Changed heapsize 512M (_maybe better multitasking_)
