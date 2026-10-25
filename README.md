XJYYDS91 Environment Hide
 
Android Root environment hide module | One-click environment bypass | Cross-chip & cross-device support
 
Introduction
 
XJYYDS91 is a root hiding module for Android root environments, providing multiple hiding profiles for games, banking applications. Compatible with mainstream root managers and various bootloader states, auto-adapt for all devices and chips.
 
Keywords: Environment hide, One-click bypass, Detection bypass, Game anti-ban, Banking app root hide, Zygisk, HMA, LSPosed, Keybox, PIF
 
Supported Environments
 
Root Managers
 
- Magisk
- KernelSU
- APatch
- SukiSU
- Alpha
- Delta
 
BL States
 
- Unlocked-free
- Fake relock
- Temporary Root
- Normal unlocked
 
Chips
 
- Qualcomm Snapdragon
- MediaTek Dimensity
- Other chips: fallback to Snapdragon profile automatically
 
Auto detect BL status and SoC model.
 
Profiles
 
Profile Name Target App 
1 Perfect Profile HMA  com.tsng.pzyhrx.hma  
2 HMA-OSS Profile HMA-OSS  org.frknkrc44.hma_oss  
3 No-LSP Profile susfs + HMA  com.tsng.pzyhrx.hma  
4 Temporary Profile Game module + HMA  com.tsng.pzyhrx.hma  
 
Current available: Perfect Profile only
 
Flash Modes
 
Use volume keys to select during installation. Auto select option 1 after 30s timeout.
 
1. Env only, no scheduler (auto detect BL / chip)
2. Env + scheduler (auto detect BL / chip)
3. Custom manual config
 
Scheduler auto rule:
 
- OPPO / OnePlus / realme → Vendor scheduler
- Other brands → Universal scheduler
 
Changelog
 
- Refactored directory layout, separate folders for schedulers, profiles, BL checker, ZygiskNext and root branches
- Device info cache support, reuse cached data on second flash
- Manual edit collected device info, auto launch MT Manager
- Add  flash_log.txt , counter increments each flash, trigger zako easter egg after 3 flashes
- Fallback for broken volume keys: treat info as valid after 30s idle
- Unified volume key control for all menus, default option 1 on timeout
- Prompt to jump to community channel after flash completed (TG / Coolapk / QQ)
- Auto launch corresponding HMA package for selected profile
- Temporary profile (Profile4) ships with Game module
- Profile3 integrated susfs kernel-level hiding
- Auto deploy  keybox.xml ,  pif.prop  and LSPosed config
 
Usage
 
1. Flash module zip via your root manager
2. First run auto collect device information
3. Select flash mode with volume keys or wait 30s auto-select
4. Reboot after installation finished
 
Working path:  /data/adb/XJYYDS91/ 
 
Community
 
- Telegram: [link]
- Coolapk: [link]
- QQ Channel: [link]
- Author: t.me/XJYYDS13
 
Disclaimer
 
For educational purposes only. Do not use for illegal activities.
Rooting your Android device carries risks. Backup your data before flashing.
 
© XJ @XJYYDS91
 
 
 
Note: Content generated with AI and manually tweaked. Open an issue if you have questions.
 
Tags: android, root, hide-root, detection-bypass, magisk, kernelsu, apatch, zygisk, hma, lsposed, keybox, pif, game-anti-detect, banking-hide
 