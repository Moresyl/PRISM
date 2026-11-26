# Third-Party Notices

**English** | [简体中文](#第三方组件声明)

PRISM ships with the third-party components below, each under its own license. The full license texts and the machine-checked component inventory are installed with the program in the `ThirdPartyNotices` folder; the master list is `ThirdPartyNotices\THIRD-PARTY-COMPONENTS.txt`. The installed files are authoritative.

| Component | Version | License | Source |
|---|---|---|---|
| LibreHardwareMonitorLib | 0.9.6 | MPL-2.0 | https://github.com/LibreHardwareMonitor/LibreHardwareMonitor |
| BlackSharp.Core, DiskInfoToolkit, RAMSPDToolkit-NDD | 1.0.7 / 1.1.2 / 1.4.2 | MPL-2.0 | https://github.com/Blacktempel |
| HidSharp | 2.6.4 | Apache-2.0 | https://software.seekye.com/hidsharp |
| Mono.Posix.NETStandard | 1.0.0 | MIT and bundled third-party terms | https://github.com/mono/mono |
| Vortice.Direct3D11, Vortice.DirectX, Vortice.DXGI, Vortice.Mathematics | 3.8.3 / 2.1.0 | MIT | https://github.com/amerkoleci/Vortice.Windows |
| SharpGen.Runtime | 2.4.2-beta | MIT | https://github.com/SharpGenTools/SharpGenTools |
| .NET Runtime and Windows Desktop Runtime, System.IO.Ports, System.Management | 10.0 | MIT | https://github.com/dotnet/dotnet |
| Windows SDK projections (Microsoft.Windows.SDK.NET.Ref) | 10.0.26100.57 | Microsoft Windows SDK license | https://aka.ms/WinSDKProjectURL |
| Intel PresentMon | 2.5.1 | MIT | https://github.com/GameTechDev/PresentMon |
| PawnIO driver installer (unmodified, officially signed) | 2.2.0 | See the PawnIO project | https://pawnio.eu/ |
| AMD FidelityFX Super Resolution 1 (derived scaling shader) | — | MIT | https://github.com/GPUOpen-Effects/FidelityFX-FSR |
| AMD FidelityFX CAS (derived sharpening shader) | — | MIT | https://github.com/GPUOpen-Effects/FidelityFX-CAS |
| SweetFX by CeeJay.dk (derived tone and levels effects) | — | MIT | https://github.com/CeeJayDK/SweetFX |

## Notes

- The MPL-2.0 components are the unmodified NuGet binaries; the exact upstream revisions are listed in `THIRD-PARTY-COMPONENTS.txt`.
- The shader effects are reimplemented in PRISM's own HLSL; no third-party effect files are loaded at runtime.
- The game preview images on the filter page are screenshots published by each game's publisher on its official storefront or website. All rights in them belong to their respective publishers; sources are listed in `ThirdPartyNotices\Preview-Scene-Attribution.txt`.
- This file only describes third-party licenses. It does not change the PRISM Software License Agreement.

---

# 第三方组件声明

[English](#third-party-notices) | **简体中文**

PRISM 随附下列第三方组件，按各自的许可证分发。完整许可证文本和组件清单随程序安装在 `ThirdPartyNotices` 目录下，总清单为 `ThirdPartyNotices\THIRD-PARTY-COMPONENTS.txt`，以安装目录中的实际文件为准。

| 组件 | 版本 | 许可证 | 来源 |
|---|---|---|---|
| LibreHardwareMonitorLib | 0.9.6 | MPL-2.0 | https://github.com/LibreHardwareMonitor/LibreHardwareMonitor |
| BlackSharp.Core、DiskInfoToolkit、RAMSPDToolkit-NDD | 1.0.7 / 1.1.2 / 1.4.2 | MPL-2.0 | https://github.com/Blacktempel |
| HidSharp | 2.6.4 | Apache-2.0 | https://software.seekye.com/hidsharp |
| Mono.Posix.NETStandard | 1.0.0 | MIT 及其附带的第三方条款 | https://github.com/mono/mono |
| Vortice.Direct3D11、Vortice.DirectX、Vortice.DXGI、Vortice.Mathematics | 3.8.3 / 2.1.0 | MIT | https://github.com/amerkoleci/Vortice.Windows |
| SharpGen.Runtime | 2.4.2-beta | MIT | https://github.com/SharpGenTools/SharpGenTools |
| .NET 运行时与 Windows 桌面运行时、System.IO.Ports、System.Management | 10.0 | MIT | https://github.com/dotnet/dotnet |
| Windows SDK 投影（Microsoft.Windows.SDK.NET.Ref） | 10.0.26100.57 | Microsoft Windows SDK 许可 | https://aka.ms/WinSDKProjectURL |
| Intel PresentMon | 2.5.1 | MIT | https://github.com/GameTechDev/PresentMon |
| PawnIO 驱动安装程序（官方签名，未修改） | 2.2.0 | 见 PawnIO 项目 | https://pawnio.eu/ |
| AMD FidelityFX Super Resolution 1（据此实现的缩放着色器） | — | MIT | https://github.com/GPUOpen-Effects/FidelityFX-FSR |
| AMD FidelityFX CAS（据此实现的锐化着色器） | — | MIT | https://github.com/GPUOpen-Effects/FidelityFX-CAS |
| CeeJay.dk 的 SweetFX（据此实现的色调与色阶效果） | — | MIT | https://github.com/CeeJayDK/SweetFX |

## 说明

- MPL-2.0 组件均为未修改的 NuGet 二进制文件，对应的上游版本见 `THIRD-PARTY-COMPONENTS.txt`。
- 着色器效果均在 PRISM 自己的 HLSL 中重新实现，运行时不加载任何第三方效果文件。
- 滤镜页的游戏预览图来自各游戏发行商在官方商店页或官网发布的截图，版权归各发行商所有；来源见 `ThirdPartyNotices\Preview-Scene-Attribution.txt`。
- 本文件只说明第三方许可，不改变《PRISM 软件许可协议》的内容。
