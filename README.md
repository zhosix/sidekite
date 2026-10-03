# SideKite

[简体中文](#sidekite) | [English](#english)

SideKite（原 LinkFlow）官方 iOS 安装包与版本发布页。

项目现已更名为 SideKite。历史 Release、IPA 文件名及校验值保持不变；过渡期间旧版官网和服务入口继续保留。

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

Official iOS downloads and releases for SideKite (formerly LinkFlow).

The project has been renamed to SideKite. Historical releases, IPA filenames, and checksums remain unchanged. Existing website and service endpoints remain available during the transition.

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
