# Hackintosh CLOVER for Hasee Z6-SL5 D1

## [中文版](https://github.com/Measureless/Hackintosh_Hasee_Z6-SL5D1/blob/master/%E4%B8%AD%E6%96%87%E8%AF%B4%E6%98%8E.md)

## About this project
- The original project comes from [TioaTyan/Hackintosh_Hasee_Z6-SL7D1](https://github.com/TioaTyan/Hackintosh_Hasee_Z6-SL7D1).
- In order to get into macOS High Sierra 10.13.6, argument in config.plist has been modified to "-v cpus=1 xpcm-free dart=0 kext-dev-mode=1".
- The wireless network adapter is Intel® Dual Band Wireless-AC 3165 which doesn't have macOS driver. I suggest to replace it by Broadcom® BCM94352Z.
- In order to update the system normally, [AppleALC](https://github.com/acidanthera/AppleALC/releases) and [Lilu](https://github.com/acidanthera/Lilu/releases) in the kexts were updated to the newest versions.
- Updated [BrcmPatchRAM](https://bitbucket.org/RehabMan/os-x-brcmpatchram/downloads/) to the newest version.