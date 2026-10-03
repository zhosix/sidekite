# SideKite

[English](#english) · [简体中文](#简体中文)

## English

**A versatile, elegant, and efficient signing tool for iOS.**

From finding apps and working with files to signing and installation, SideKite brings everyday tools and advanced features together, alongside plugin management, file transfers, and device connectivity.

[Download the latest release](https://github.com/zhosix/sidekite/releases) · [Installation and verification](#download-and-installation) · [Support](#support)

### Key features

1. **App sources and jailbreak repositories**  
   Access app resources from multiple types of app sources and jailbreak repositories in one place.

2. **Quick apps**  
   Add files from GitHub, direct links, and OpenList as quick apps to keep your go-to download sources together.

3. **Advanced file tools**  
   Extract, edit, modify dependencies, and repackage IPA, dylib, and other supported file types.

4. **Flexible signing and injection**  
   Choose from a range of signing options, with support for code injection at arbitrary paths and adding multiple dependencies.

5. **Enhanced plugin management**  
   Take finer control of plugin behavior:

   - Switch plugin languages
   - Control plugin loading
   - Automatically disable problematic plugins
   - Control plugin pop-ups
   - Open or hide plugin controls
   - Block automatic external redirects from plugins
   - View plugin and activity diagnostics

6. **File transfers and device connectivity**  
   Use SideKite as a WebDAV server or client, discover nearby devices, and transfer files over HTTP.

7. **App installation and management**  
   Install IPA files in one step, manage apps on your device, and find and favorite TestFlight apps.

8. **Multilingual interface**  
   Choose from multiple interface languages.

### Download and installation

> SideKite was formerly known as LinkFlow. Historical releases, IPA filenames, and checksums remain unchanged. Existing website and service endpoints remain available during the transition.

Download the latest version from this repository's [Releases](https://github.com/zhosix/sidekite/releases) and verify its SHA-256 checksum against the one provided on the release page.

Requires: **iOS 17 or later**

SideKite is distributed as an unsigned IPA. Sign and install it using certificates and provisioning profiles you lawfully hold, or a trusted installation method. Do not download installation packages from unofficial sources or share your certificates, passwords, tokens, or pairing data with others.

### Verify your download

macOS:

```bash
shasum -a 256 LinkFlow_2.0.6.ipa
```

Windows PowerShell:

```powershell
Get-FileHash .\LinkFlow_2.0.6.ipa -Algorithm SHA256
```

The checksum must exactly match the value in the release's `SHA256SUMS` file.

### Support

- [Official website](https://sidekite.zhosix.com/)
- [Privacy policy](https://sidekite.zhosix.com/privacy)
- Support and security: `sidekite@zhosix.com`

### Community

- [QQ community · 1045595997](https://qun.qq.com/universal-share/share?ac=1&authKey=68WjRxihKNF6h0Tiy3YRf38laumuG2iWqSZrljs%2FDKwlbXh3VdjMIr8sh6Q265Cx&busi_data=eyJncm91cENvZGUiOiIxMDQ1NTk1OTk3IiwidG9rZW4iOiIzR09ZT2t5OUNha2NUN1J3OUNTalBxaUJ2ZU13NW9QakNidDJRRWdRZnp5VmxidzBuWGNxRUpIUFN6QUR2MVVtIiwidWluIjoiOTE3NjM5OTUwIn0%3D&data=OaVYdY30H8XnRS8e4AAQ-WCIXe6GHpc23EtL1risW5EbjS003_o-Qvx90Ldgqm9eRgi1DVQ247bltYfuoLXR1A&svctype=4&tempid=h5_group_info)
- [Telegram community · @sidekitezhosix](https://t.me/sidekitezhosix)

### Support the project

Sponsorship is entirely voluntary. Thank you for supporting ongoing development and maintenance.

- [WeChat](https://sidekite.zhosix.com/assets/sponsor/wechat-sponsor.png) — view the sponsorship QR code.
- [Alipay](https://qr.alipay.com/2m6148879y1ivwkicusrh9e) — open the payment page.
- [PayPal](https://ko-fi.com/zhosix) — via Ko-fi.

---

## 简体中文

**全能、美观、高效的 iOS 端签名工具。**

从应用获取、文件处理到签名安装，SideKite 将常用工具与专业功能整合在一起，并提供插件管理、文件传输与设备互联能力。

[下载最新版本](https://github.com/zhosix/sidekite/releases) · [安装与校验](#下载与安装) · [支持](#支持)

### 主要功能

1. **软件源与越狱源**  
   兼容多种类型的软件源与越狱源，集中获取应用资源。

2. **快捷应用**  
   将 GitHub、直链和 OpenList 来源的文件添加为快捷应用，集中管理常用下载来源。

3. **专业文件处理**  
   对 IPA、dylib 等文件进行解压、编辑、依赖调整与重新打包。

4. **灵活签名与注入**  
   提供多种签名选项，支持任意路径程序注入及多依赖写入。

5. **增强插件管理**  
   更细致地控制插件行为：

   - 切换插件语言
   - 控制插件加载
   - 自动禁用问题插件
   - 控制插件弹窗
   - 直接打开或隐藏插件操作入口
   - 屏蔽插件的自动外部跳转
   - 查看插件及活动诊断

6. **文件传输与设备互联**  
   同时支持 WebDAV 服务端与客户端，提供附近设备发现及 HTTP 文件传输。

7. **应用安装与管理**  
   一键安装 IPA，管理设备上的 App，搜索与收藏 TestFlight 应用。

8. **多语言界面**  
   支持多种界面语言。

### 下载与安装

> SideKite 原名 LinkFlow。历史 Release、IPA 文件名与校验值保持不变；过渡期间旧版官网和服务入口继续保留。

请从本仓库的 [Releases](https://github.com/zhosix/sidekite/releases) 下载最新版本，并核对发布页提供的 SHA-256。

系统要求：**iOS 17 或更高版本**

SideKite 提供未签名 IPA，需要使用自己合法持有的证书、描述文件或受信任的安装方式完成签名与安装。请勿从非官方来源下载安装包，也不要向他人提供证书、密码、令牌或配对资料。

### 校验下载文件

macOS：

```bash
shasum -a 256 LinkFlow_2.0.6.ipa
```

Windows PowerShell：

```powershell
Get-FileHash .\LinkFlow_2.0.6.ipa -Algorithm SHA256
```

校验值应与 Release 中的 `SHA256SUMS` 完全一致。

### 支持

- [官方网站](https://sidekite.zhosix.com/)
- [隐私政策](https://sidekite.zhosix.com/privacy)
- 支持与安全问题：`sidekite@zhosix.com`

### 官方社群

- [QQ 交流群 · 1045595997](https://qun.qq.com/universal-share/share?ac=1&authKey=68WjRxihKNF6h0Tiy3YRf38laumuG2iWqSZrljs%2FDKwlbXh3VdjMIr8sh6Q265Cx&busi_data=eyJncm91cENvZGUiOiIxMDQ1NTk1OTk3IiwidG9rZW4iOiIzR09ZT2t5OUNha2NUN1J3OUNTalBxaUJ2ZU13NW9QakNidDJRRWdRZnp5VmxidzBuWGNxRUpIUFN6QUR2MVVtIiwidWluIjoiOTE3NjM5OTUwIn0%3D&data=OaVYdY30H8XnRS8e4AAQ-WCIXe6GHpc23EtL1risW5EbjS003_o-Qvx90Ldgqm9eRgi1DVQ247bltYfuoLXR1A&svctype=4&tempid=h5_group_info)
- [Telegram 交流群 · @sidekitezhosix](https://t.me/sidekitezhosix)

### 赞助支持

赞助完全自愿，感谢你支持项目持续开发与维护。

- [微信](https://sidekite.zhosix.com/assets/sponsor/wechat-sponsor.png) — 查看赞赏码。
- [支付宝](https://qr.alipay.com/2m6148879y1ivwkicusrh9e) — 打开收款页面。
- [PayPal](https://ko-fi.com/zhosix) — 通过 Ko-fi 赞助。
