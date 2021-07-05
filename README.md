[![](https://img.shields.io/github/last-commit/coolsnowwolf/lede/master?color=FFFFFF&label=%E6%BA%90%E7%A0%81%E6%9B%B4%E6%96%B0)](https://github.com/coolsnowwolf/lede)

OpenWrt Own — 设备固件Action编译
==============================================================================================================

​	使用GitHub Action自动编译OpenWrt固件

## 固件下载
<details>
 <summary><b>&nbsp;&nbsp;&nbsp; ARM 设备编译状态及固件下载</b></summary>

<br/>

点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 即可跳转到该设备固件下载页面
|     ARM设备    |   ARM设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-------------: |:-----------------: | :-----------------: |  :-----------------: |
|    [![](https://img.shields.io/badge/OpenWrt-树莓派_4B-FFFFFF.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/.github/workflows/raspberrypi4.yml)    | [![](https://github.com/IvanSolis1989/OpenWrt-DIY/workflows/Build%20RaspBerryPi4%20OpenWrt/badge.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions/workflows/raspberrypi4.yml)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/config/ARM/arm-extra.config)  | 含 USB 网卡驱动 |
|      [![](https://img.shields.io/badge/OpenWrt-NanoPi_R2S-FFFFFF.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/.github/workflows/r2s.yml)     |  [![](https://github.com/IvanSolis1989/OpenWrt-DIY/workflows/Build%20NanoPi%20R2S%20OpenWrt/badge.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions/workflows/r2s.yml)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/config/ARM/arm-extra.config)  | ZIP 解压后刷写 |
|      [![](https://img.shields.io/badge/OpenWrt-NanoPi_R4S-FFFFFF.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/.github/workflows/r4s.yml)|  [![](https://github.com/IvanSolis1989/OpenWrt-DIY/workflows/Build%20NanoPi%20R4S%20OpenWrt/badge.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions/workflows/r4s.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/config/ARM/arm-extra.config)  | ZIP 解压后刷写 |
|     [![](https://img.shields.io/badge/OpenWrt-香橙派_Zero_Plus-FFFFFF.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/.github/workflows/opzp.yml)   | [![](https://github.com/IvanSolis1989/OpenWrt-DIY/workflows/Build%20Orange%20Pi%20Zero%20Plus%20OpenWrt/badge.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions/workflows/opzp.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/config/ARM/opzp.config) |   |

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 到 Actions 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; 高通 设备编译状态及固件下载</b></summary>

<br/>

点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 即可跳转到该设备固件下载页面
|     高通平台     |   高通设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-------------: |:-----------------: | :-----------------: |  :-----------------: |
|        [![](https://img.shields.io/badge/OpenWrt-竞斗云-FFFFFF.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/.github/workflows/gdock.yml)         |[![](https://github.com/IvanSolis1989/OpenWrt-DIY/workflows/Build%20G-Dock%20OpenWrt/badge.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions/workflows/gdock.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/config/Qualcomm/Qualcomm-extra.config)  | |

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 到 Actions 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; MIPS 设备编译状态及固件下载</b></summary>

<br/>

**注意：** 考虑到 MIPS 设备的 CPU 性能及 RAM/ROM 量配置，功能较其他设备做了很大范围的删减。 

MIPS 设备推荐使用 Padavan 固件： [![](https://img.shields.io/badge/-Padavan_固件仓库_1-FFFFFF.svg)](https://github.com/hanwckf/rt-n56u) [![](https://img.shields.io/badge/-Padavan_固件仓库_2-FFFFFF.svg)](https://opt.cn2qq.com/padavan/) [![](https://img.shields.io/badge/-Padavan_固件仓库_3-FFFFFF.svg)](https://github.com/gorden5566/padavan)

点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 即可跳转到该设备固件下载页面
|     MIPS设备     |   MIPS设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-------------: |:-----------------: | :-----------------: |  :-----------------: |
|        [![](https://img.shields.io/badge/OpenWrt-极路由_B70-FFFFFF.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/.github/workflows/B70.yml)        |[![](https://github.com/IvanSolis1989/OpenWrt-DIY/workflows/Build%20HiWiFi%20B70%20OpenWrt/badge.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions/workflows/B70.yml)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/blob/main/config/MIPS/MIPS-extra.config) | |

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 到 Actions 进一步查看。

</details>

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 其他

<details>
 <summary>&nbsp;&nbsp;&nbsp; USB 网卡</summary>

<br/>

**USB 有线网卡**

推荐使用基于 AX88179（[绿联20256](https://union-click.jd.com/jdc?e=&p=AyIGZRprFQETA10cXSVGTV8LRGtMR1dGFxBFC1pXUwkEAEAdQFkJBVsWAxYPUh1ETEdOWmVdIHFbakcpHD4LGBJsV3suc1ducxNNVxkyEzdWGlsVBhcEVRNYJTISAGVNNRUDEwZUGlgTAhQ3VCtbEgIRAVATUxYCEQdUK1wVCyJcAHVfRVBCUAEYXBQFQQICK2slASI3ZRtrFjJQaVRIWRIEEAZRGQsRUhdVABkLEVIQV1xIDhYDFQdQElkTMhAGVB9S)）或 RTL8153（[山泽UW013](https://union-click.jd.com/jdc?e=&p=AyIGZRtYFAUWA1MdXBYyFQVTH14UByJDCkMFSjJLQhBaGR4cDF8QTwcKWUcYB0UHCwUQAVEeWhAdS0IJRmt9dE9wLGwwV2JUUyliWBxEDEdQGilTDh43VCtYFAISA1AYWx0BIjdVHGtXbFBXCVACQVlKTwErWiUCFQdWHV4dChYBUhtZJQUSDmVADnsGQlUFTA8WBRMABh4MJTIiBGUraxUyETcXdVkcBhIHUxxSFAcXB1AeCBALGwJdEgxHCxpQVhpTRQERN1caWhEL)） 芯片的 USB 有线网卡设备。

</details>

## 鸣谢

[OpenWrt 官方库](https://github.com/openwrt/openwrt)

[OpenWrt-DIY库](https://github.com/IvanSolis1989/OpenWrt-DIY)

[P3TERX 的 Action 库](https://github.com/P3TERX/Actions-OpenWrt)

[Lean 的 OpenWrt 库](https://github.com/coolsnowwolf/lede)

[Lienol 的 Packages 库](https://github.com/Lienol/openwrt-packages)

[SuLingGG 的 OpenWrt-Rpi 库](https://github.com/SuLingGG/OpenWrt-Rpi)

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>