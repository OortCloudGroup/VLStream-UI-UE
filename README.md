# VLStream UI/UE 设计资料

本仓库用于归档和共享 VLStream 产品体系的界面与用户体验设计资料。VLStream（Video Link Stream）是 OortCloudGroup 面向视频融合与视觉物联网场景打造的平台，覆盖云端管理、视频接入与设备侧应用等产品形态。该仓库聚焦设计交付物，为产品、设计和研发团队提供统一的界面参考与源文件。

## 项目背景

VLStream 的整体产品体系包括 VLStream Cloud、IPCamera、NVR、CMS 桌面客户端，以及 iOS、Android、HarmonyOS 等移动应用。平台围绕视频接入、设备管理和智能分析构建，组织主页介绍的能力包括 WebRTC、决策 AI、算力调度、多租户运营和物联网接入。

其中，VLStream Cloud 承载云端管理与视频业务，相关模块包括工作台、视频聚合、决策 AI、算法仓库和 AI 算力调度。IPCamera 与 NVR 面向前端设备和录像管理场景，移动端设计则支持用户通过移动设备使用 VLStream 产品能力。

## 本仓库收录范围

目前收录以下产品的英文版 UI/UE 设计源文件及配套图片资料：

| 产品 | 设计资料 |
| --- | --- |
| VLStream Cloud | 云端平台设计稿与界面图片 |
| VLStream Cloud Mobile | 移动端设计稿与界面图片 |
| VLStream IPCamera | IPCamera 相关设计稿与界面图片 |
| VLStream NVR | NVR 相关设计稿与界面图片 |

仓库名称中的 UI/UE 分别指用户界面（User Interface）与用户体验（User Experience）。这些资料用于呈现产品界面结构和交互设计，不包含对应产品的应用程序代码。

## 文件说明

- `.mg`：MasterGo 设计源文件，可用于查看或继续编辑设计稿。
- `图.zip`：与对应设计稿配套的图片资料包。
- `英文版` / `英文`：该设计资料为英文界面版本。

## 目录结构

```text
VLStream-UI-UE/
├── README.md
└── VLStream-UI-UE/
    ├── VLStream_Cloud（英文版）.mg
    ├── VLStream_Cloud（英文版）图.zip
    ├── VLStream_Cloud_Mobile（英文）.mg
    ├── VLStream_Cloud_Mobile（英文）图.zip
    ├── VLStream_IPCamera（英文版）.mg
    ├── VLStream_IPCamera（英文版）图.zip
    ├── VLStream_NVR（英文版）.mg
    └── VLStream_NVR（英文版）图.zip
```

## 使用与维护

查看设计稿时，请使用 MasterGo 打开 `.mg` 源文件；如只需浏览导出的界面图片，可查看相应的 `图.zip`。新增或更新资料时，请放入对应产品目录，并保持源文件与配套图片的名称一致，便于查找和版本维护。

## VLStream 相关项目

- [VLStream Cloud](https://github.com/OortCloudGroup/VLStream-Cloud)：云端视频流管理与服务端项目。
- [VLStream Web](https://github.com/OortCloudGroup/VLStream-Web)：Web 视频平台项目。
- [VLStream APP](https://github.com/OortCloudGroup/VLStream-APP)：多平台应用项目。
- [VLStream IPCamera](https://github.com/OortCloudGroup/VLStream-IPCamera)：IPCamera 相关项目。
- [OortCloudGroup](https://github.com/OortCloudGroup)：组织主页与其他相关仓库。
