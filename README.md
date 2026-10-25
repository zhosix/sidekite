# SideKite

[English](#english) · [简体中文](#简体中文)

## English

**A versatile, elegant, and efficient signing tool for iOS.**

SideKite brings app discovery, Apple ID and certificate signing, installation, JIT, plugin management, and file tools together on your iPhone or iPad.

[Download for iOS](https://github.com/zhosix/sidekite/releases/latest) · [SideKite Pair](https://github.com/zhosix/sidekitepair) · [Website](https://sidekite.zhosix.com/) · [Support](#support)

### Key features

1. **Apple ID signing**  
   Sign with multiple Apple IDs, manage accounts separately, renew signatures automatically, and export the corresponding signing certificates. Choose an Apple ID from the signing page just like a certificate.

2. **Certificate signing and batch signing**  
   Sign IPA files with imported certificates, process multiple apps in a batch, and reuse or restore signing settings.

   Repeated signing of the same IPA within a short period can be faster, especially for large packages.

3. **JIT support**  
   Enable JIT and configure automatic activation for selected apps.

4. **Flexible injection and dependencies**  
   Customize injection paths, add multiple libraries, and choose weak or required dependencies to suit the target app.

5. **Enhanced plugin management**  
   Take finer control of plugin behavior:

   - Switch plugin languages
   - Control plugin loading
   - Automatically disable problematic plugins
   - Control plugin pop-ups
   - Open or hide plugin controls
   - Block automatic external redirects from plugins
   - View plugin and activity diagnostics

6. **App sources and quick apps**  
   Browse app sources and jailbreak repositories, including supported paid repositories.

   Add GitHub, direct-link, and OpenList resources as quick apps, and download historical versions from GitHub app details.

7. **Advanced file tools**  
   Extract, edit, modify dependencies, and repackage IPA, DEB, dylib, and other supported files. Repair file-import associations for supported self-signed apps.

8. **Installation and device app management**  
   Choose from multiple installation methods, including idevice installation with Advanced Installation. View installed app details such as expiration dates and permissions, and find and favorite TestFlight apps.

9. **File transfers and device connectivity**  
   Use SideKite as a WebDAV server or client, discover nearby devices, and transfer files over HTTP.

   Use the macOS and Windows companion, [SideKite Pair](https://github.com/zhosix/sidekitepair), to install signed IPAs and create Remote Pairing files.

10. **Make it your own**  
    Choose interface languages, theme colors, app icons, and signing-page layouts to fit your workflow.

> Some JIT, advanced installation, and device-management features require device pairing and additional setup. Follow the instructions in the app for your device and iOS version.

### Download and installation

Requires: **iOS 17 or later**

1. Download the IPA from [the latest release](https://github.com/zhosix/sidekite/releases/latest).
2. Sign and install it with your own certificate and provisioning profile, or another trusted installation method.

SideKite is distributed as an **unsigned IPA**. To install it for the first time, use an existing signing tool or a trusted installation method; Apple ID signing becomes available inside SideKite after installation.

Do not download installation packages from unofficial sources or share your certificates, passwords, tokens, or pairing data with others.

### Community

- **Telegram:** [@sidekitezhosix](https://t.me/sidekitezhosix)
- **QQ group:** [1045595997](https://qun.qq.com/universal-share/share?ac=1&authKey=68WjRxihKNF6h0Tiy3YRf38laumuG2iWqSZrljs%2FDKwlbXh3VdjMIr8sh6Q265Cx&busi_data=eyJncm91cENvZGUiOiIxMDQ1NTk1OTk3IiwidG9rZW4iOiIzR09ZT2t5OUNha2NUN1J3OUNTalBxaUJ2ZU13NW9QakNidDJRRWdRZnp5VmxidzBuWGNxRUpIUFN6QUR2MVVtIiwidWluIjoiOTE3NjM5OTUwIn0%3D&data=OaVYdY30H8XnRS8e4AAQ-WCIXe6GHpc23EtL1risW5EbjS003_o-Qvx90Ldgqm9eRgi1DVQ247bltYfuoLXR1A&svctype=4&tempid=h5_group_info)

### Support the author

Donations are entirely voluntary. Thank you for supporting SideKite's continued maintenance.

- **PayPal:** [Support via Ko-fi](https://ko-fi.com/zhosix)
- **WeChat:** [View the appreciation code](https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e)
- **Alipay:** [Open the payment link](https://qr.alipay.com/2m6148879y1ivwkicusrh9e) · [View the QR code](https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162)

<details open>
<summary>WeChat and Alipay QR codes</summary>

Click a code to view it at full size, then scan or save it using the corresponding app.

| WeChat | Alipay |
| :---: | :---: |
| [<img src="https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e" width="200" alt="WeChat appreciation code">](https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e) | [<img src="https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162" width="200" alt="Alipay donation code">](https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162) |

</details>

### Support

- Support and security: `sidekite@zhosix.com`

---

## 简体中文

**全能、美观、高效的 iOS 端签名工具。**

从应用获取、Apple ID 与证书签名，到安装管理、JIT、插件增强与文件处理，SideKite 将常用工具与进阶功能整合在你的 iPhone 或 iPad 上。

[下载 iOS 版](https://github.com/zhosix/sidekite/releases/latest) · [SideKite Pair](https://github.com/zhosix/sidekitepair) · [官方网站](https://sidekite.zhosix.com/) · [支持](#支持)

### 主要功能

1. **Apple ID 签名**  
   支持多账户登录、自动续签和导出对应 ID 证书，在签名页可像选择证书一样选择不同 Apple ID 来签名 IPA。

2. **证书签名与批量签名**  
   使用导入的证书签名 IPA，支持批量处理、签名设置记忆与还原。

   短时间内多次签名同一 IPA 可获得提速，大型 IPA 收益更明显。

3. **JIT 支持**  
   支持开启 JIT，并可为指定 App 配置自动启用。

4. **灵活注入与依赖调整**  
   支持自定义注入路径、多依赖写入，以及弱依赖、强依赖等设置，按目标 App 的需要调整。

5. **增强插件管理**  
   更细致地控制插件行为：

   - 切换插件语言
   - 控制插件加载
   - 自动禁用问题插件
   - 控制插件弹窗
   - 直接打开或隐藏插件操作入口
   - 屏蔽插件的自动外部跳转
   - 查看插件及活动诊断

6. **软件源、越狱源与快捷应用**  
   兼容多种软件源与越狱源，支持适配的付费源。

   将 GitHub、直链和 OpenList 来源添加为快捷应用，并可在 GitHub 应用详情中下载历史版本。

7. **专业文件处理**  
   对 IPA、DEB、dylib 等文件进行解压、编辑、依赖调整与重新打包，并支持修复部分自签 App 的文件导入关联。

8. **安装与设备应用管理**  
   提供多种安装方式，支持搭配高级安装使用 idevice 安装。查看设备 App 的有效期、权限等详情，并可搜索与收藏 TestFlight 应用。

9. **文件传输与设备互联**  
   同时支持 WebDAV 服务端与客户端、附近设备发现和 HTTP 文件传输。

   可搭配 macOS / Windows 桌面助手 [SideKite Pair](https://github.com/zhosix/sidekitepair)，安装已签名 IPA 或创建远程配对文件。

10. **个性化与多语言**  
    提供多种界面语言、主题色、应用图标和签名页布局，按自己的习惯使用。

> 部分 JIT、高级安装和设备管理功能需要完成设备配对及相关设置，请按 App 内说明操作，具体支持情况以设备和 iOS 版本为准。

### 下载与安装

系统要求：**iOS 17 或更高版本**

1. 从[最新发行页面](https://github.com/zhosix/sidekite/releases/latest)下载 IPA。
2. 使用自己的证书、描述文件或其他受信任的方式完成签名与安装。

SideKite 提供**未签名 IPA**。首次安装需借助已有签名工具或受信任的安装方式；安装完成后，即可在 SideKite 内使用 Apple ID 签名等功能。

请勿从非官方来源下载安装包，也不要向他人提供证书、密码、令牌或配对资料。

### 社群

- **Telegram 交流群：** [@sidekitezhosix](https://t.me/sidekitezhosix)
- **QQ 交流群：** [1045595997](https://qun.qq.com/universal-share/share?ac=1&authKey=68WjRxihKNF6h0Tiy3YRf38laumuG2iWqSZrljs%2FDKwlbXh3VdjMIr8sh6Q265Cx&busi_data=eyJncm91cENvZGUiOiIxMDQ1NTk1OTk3IiwidG9rZW4iOiIzR09ZT2t5OUNha2NUN1J3OUNTalBxaUJ2ZU13NW9QakNidDJRRWdRZnp5VmxidzBuWGNxRUpIUFN6QUR2MVVtIiwidWluIjoiOTE3NjM5OTUwIn0%3D&data=OaVYdY30H8XnRS8e4AAQ-WCIXe6GHpc23EtL1risW5EbjS003_o-Qvx90Ldgqm9eRgi1DVQ247bltYfuoLXR1A&svctype=4&tempid=h5_group_info)

### 赞助

赞助完全自愿，感谢你支持 SideKite 的持续维护。

- **PayPal：** [通过 Ko-fi 赞助](https://ko-fi.com/zhosix)
- **微信：** [查看微信赞赏码](https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e)
- **支付宝：** [打开赞助链接](https://qr.alipay.com/2m6148879y1ivwkicusrh9e) · [查看二维码](https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162)

<details open>
<summary>微信与支付宝赞助码</summary>

点击二维码可查看原图，再使用对应 App 扫描或保存识别。

| 微信 | 支付宝 |
| :---: | :---: |
| [<img src="https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e" width="200" alt="微信赞赏码">](https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e) | [<img src="https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162" width="200" alt="支付宝赞助码">](https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162) |

</details>

### 支持

- 支持与安全问题：`sidekite@zhosix.com`
