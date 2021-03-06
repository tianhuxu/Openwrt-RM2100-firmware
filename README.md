# Build OpenWrt using GitHub Actions
![Linksys WRT32X](https://github.com/whoshoe/openwrt-firmwares/workflows/Linksys%20WRT32X/badge.svg)
![Newifi D2](https://github.com/whoshoe/openwrt-firmwares/workflows/Newifi%20D2/badge.svg)
![Redmi AC2100](https://github.com/whoshoe/openwrt-firmwares/workflows/Redmi%20AC2100/badge.svg)
![Raspberry Pi 4B](https://github.com/whoshoe/openwrt-firmwares/workflows/Raspberry%20Pi%204B/badge.svg)

This repository is mainly for personal use. The goal is to automate the build process for routers using GitHub Actions.
Supported routers:
- Linksys WRT32X/WRT32XB
- Newifi D2
- Xiaomi Redmi AC2100
- Raspberry Pi 4B

Note: 
Considering the instability of proprietary drivers which could cause dropped signal or random downtime. For Newifi D2 and Xiaomi Redmi AC2100, open source wireless drivers (for both 2.4G and 5G) are used instead of proprietary drivers.

Newifi D2 packages
  - kmod-mt7603
  - kmod-mt76x2
  - wpad-openssl
  
Xiaomi Redmi AC2100 packages
  - kmod-mt7603
  - kmod-mt7615e
  - kmod-mt7615-firmware
  - wpad-openssl

Raspberry Pi 4B USB driver
  - kmod-usb-net-asix (works for asix AX88772B chip)
  - kmod-usb-net-rtl8152 (works for RTL8153 chip)

## Acknowledgments

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)
- [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
## License

[MIT](https://github.com/whoshoe/openwrt-firmwares//blob/main/LICENSE)
