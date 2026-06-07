<div align="center">

<img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />

# GameFrameX YooAsset MiniGame Alipay

[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE.md)
[![Version](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases)
[![Unity Version](https://img.shields.io/badge/Unity-2019.4-black?logo=unity)](https://unity.com/)
[![Documentation](https://img.shields.io/badge/Documentation-docs-blue)](https://gameframex.doc.alianblank.com)

All-in-One Solution for Indie Game Development · Empowering Indie Developers' Dreams

<br />

[Documentation](https://gameframex.doc.alianblank.com) · [Quick Start](#quick-start) · QQ Group: 467608841 / 233840761

<br />

**English** | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

</div>

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

### Installation

Edit your Unity project's `Packages/manifest.json` and add the `scopedRegistries` section:

```json
{
  "scopedRegistries": [
    {
      "name": "GameFrameX",
      "url": "https://gameframex.upm.alianblank.uk",
      "scopes": [
        "com.gameframex"
      ]
    }
  ]
}
```

`scopes` controls which packages are resolved through this registry. Only packages whose names start with `com.gameframex` will be fetched from it.

Then add the package to `dependencies`:

```json
{
  "dependencies": {
    "com.gameframex.unity.tuyoogame.yooasset.minigame.alipay": "1.0.0"
  }
}
```

## Documentation & Resources

- [Official Documentation](https://gameframex.doc.alianblank.com)

## Community & Support

- QQ Group: [Join](https://qm.qq.com/q/3dIpogITg)

## Changelog

See [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases) for changelog.


## Dependencies

| Package | Description |
|---------|-------------|
| `com.gameframex.unity.tuyoogame.yooasset` | 1.0.0 |
## License

See [LICENSE.md](LICENSE.md) for license information.
