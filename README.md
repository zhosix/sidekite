# SideKite

[简体中文](#sidekite) | [English](#english)

SideKite，一款全能、美观、高效的 iOS 端签名工具。

项目现已更名为 SideKite。历史 Release、IPA 文件名及校验值保持不变；过渡期间旧版官网和服务入口继续保留。

## 主要功能

1. **软件源支持**  
   支持各类型软件源和越狱源。

2. **快捷应用**  
   支持将来自 GitHub、直链和 OpenList 的文件添加为快捷应用。

3. **专业文件处理**  
   支持 IPA、dylib 等文件的解压、编辑、依赖编辑及重新打包。

4. **丰富的签名功能**  
   支持任意路径程序注入、多依赖写入等多种签名操作。

5. **插件管理增强**  
   提供多项插件控制与诊断功能：

   - 切换插件语言
   - 控制插件加载
   - 自动禁用问题插件
   - 控制插件弹窗
   - 直接打开或隐藏插件操作入口
   - 屏蔽插件的自动外部跳转
   - 插件及活动诊断

6. **文件传输与设备互联**  
   支持作为 WebDAV 服务端和客户端，提供附近设备发现及 HTTP 传输功能。

7. **应用安装与管理**  
   支持一键安装 IPA、设备 App 管理，以及 TestFlight 应用搜索与收藏。

8. **多语言支持**  
   提供多种界面语言。

## 下载

请从本仓库的 [Releases](https://github.com/zhosix/sidekite/releases) 下载最新版本，并核对发布页提供的 SHA-256。

当前公开版本：**LinkFlow 2.0.6（构建 20260914）**  
系统要求：**iOS 17 或更高版本**

SideKite 提供未签名 IPA，需要使用自己合法持有的证书、描述文件或受信任的安装方式完成签名与安装。请勿从非官方来源下载安装包，也不要向他人提供证书、密码、令牌或配对资料。

## 校验下载文件

macOS：

```bash
shasum -a 256 LinkFlow_2.0.6.ipa
```

Windows PowerShell：

```powershell
Get-FileHash .\LinkFlow_2.0.6.ipa -Algorithm SHA256
```

校验值应与 Release 中的 `SHA256SUMS` 完全一致。

## 支持

- [官方网站](https://linkflow.zhosix.com/)
- [隐私政策](https://linkflow.zhosix.com/privacy)

---

## English

SideKite — a versatile, elegant, and efficient signing tool for iOS.

The project has been renamed to SideKite. Historical releases, IPA filenames, and checksums remain unchanged. Existing website and service endpoints remain available during the transition.

### Key features

1. **Software sources**  
   Supports various types of app sources and jailbreak repositories.

2. **Quick apps**  
   Add files from GitHub, direct download links, and OpenList as quick apps.

3. **Advanced file tools**  
   Extract, edit, manage dependencies, and repackage IPA, dylib, and other supported file types.

4. **Flexible signing**  
   Supports code injection at arbitrary paths, adding multiple dependencies, and a range of signing options.

5. **Enhanced plugin management**  
   Provides plugin controls and diagnostics:

   - Switch plugin languages
   - Control plugin loading
   - Automatically disable problematic plugins
   - Control plugin pop-ups
   - Open or hide plugin controls
   - Block automatic external redirects from plugins
   - Plugin and activity diagnostics

6. **File transfer and device connectivity**  
   Works as both a WebDAV server and client, with nearby device discovery and HTTP file transfers.

7. **App installation and management**  
   Install IPA files in one step, manage apps on your device, and search for and favorite TestFlight apps.

8. **Multiple languages**  
   Offers multiple interface languages.

### Download

Download the latest version from this repository's [Releases](https://github.com/zhosix/sidekite/releases) and verify its SHA-256 checksum against the one provided on the release page.

Current public release: **LinkFlow 2.0.6 (build 20260914)**  
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

- [Official website](https://linkflow.zhosix.com/)
- [Privacy policy](https://linkflow.zhosix.com/privacy)
