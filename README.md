<p align="center">
  <img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="GameFrameX Logo" width="160" />
</p>

<h1 align="center">GameFrameX YooAsset MiniGame Alipay</h1>

<p align="center">
  <a href="https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases">
    <img src="https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay?style=flat-square" alt="Version" />
  </a>
  <a href="https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay?style=flat-square" alt="License" />
  </a>
  <a href="https://gameframex.doc.alianblank.com">
    <img src="https://img.shields.io/badge/Documentation-online-blue?style=flat-square" alt="Documentation" />
  </a>
</p>

<p align="center">
  All-in-One Solution for Indie Game Development · Empowering Indie Developers' Dreams
</p>

<p align="center">
  <a href="https://gameframex.doc.alianblank.com">Documentation</a> ·
  <a href="#quick-start">Quick Start</a> ·
  <a href="https://qm.qq.com/q/3dIpogITg">QQ Group</a> ·
  Language: **English** ·
  <a href="README.zh-CN.md">简体中文</a> ·
  <a href="README.zh-TW.md">繁體中文</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.ko.md">한국어</a>
</p>

---

## Project Overview

GameFrameX YooAsset MiniGame Alipay runtime component for Unity WebGL platform. Provides adapter implementation for Alipay Mini Game file system and asset bundle loading.

## Features

- Provides Alipay Mini Game specific IFileSystem implementation
- Adapts Alipay Mini Game SDK's AssetBundle download and caching workflow
- Supports package version requests, manifest loading, asset bundle download and loading
- Compatible with remote services and decryption services

## Requirements

- Unity 2019.4
- Platform: UNITY_WEBGL
- Conditional compilation: ALIPAYMINIGAME
- Dependencies: YooAsset, StarkWebGL, AlipayWebGL

## Quick Start

### Installation (choose one)

1. Add the following to the `dependencies` section of your `manifest.json`:
   ```json
   {"com.gameframex.unity.tuyoogame.yooasset.minigame.alipay": "https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay.git"}
   ```

2. In Unity's Package Manager, use `Git URL` to add the package: https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay.git

3. Download the repository and place it in your Unity project's `Packages` directory. It will be loaded automatically.

### Usage

1. Ensure Alipay Mini Game SDK is integrated and `ALIPAYMINIGAME` macro is enabled
2. Use `AlipayFileSystemCreater.CreateFileSystemParameters(...)` to generate file system parameters
3. Pass the parameters to YooAsset's file system creation workflow
4. Follow YooAsset's standard workflow for initialization, version requests, manifest loading, and asset loading

## Documentation & Resources

- [Official Documentation](https://gameframex.doc.alianblank.com)

## Community & Support

- QQ Group: [Join](https://qm.qq.com/q/3dIpogITg)

## Changelog

See [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases) for changelog.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE) file for details.
