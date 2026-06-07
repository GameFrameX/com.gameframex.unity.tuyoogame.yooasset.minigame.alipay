<div align="center">

<img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />

# GameFrameX YooAsset MiniGame Alipay

[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE.md)
[![Version](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases)
[![Unity Version](https://img.shields.io/badge/Unity-2019.4-black?logo=unity)](https://unity.com/)
[![Documentation](https://img.shields.io/badge/Documentation-docs-blue)](https://gameframex.doc.alianblank.com)

獨立遊戲前後端一體化解決方案 · 獨立遊戲開發者的圓夢大使

<br />

[文檔](https://gameframex.doc.alianblank.com) · [快速開始](#快速開始) · QQ群: 467608841 / 233840761

<br />

[English](README.md) | [简体中文](README.zh-CN.md) | **繁體中文** | [日本語](README.ja.md) | [한국어](README.ko.md)

</div>

## 項目簡介

GameFrameX 的 YooAsset 支付寶小遊戲運行時組件，面向 Unity WebGL 平台，提供與支付寶小遊戲檔案系統、資源包載入流程的適配實作。

## 功能特性

- 提供支付寶小遊戲專用的 IFileSystem 實作
- 適配支付寶小遊戲 SDK 的 AssetBundle 下載與快取流程
- 支援包版本請求、清單載入、資源包下載與載入
- 可對接遠端服務與解密服務

## 運行環境

- Unity 2019.4
- 平台：UNITY_WEBGL
- 條件編譯：ALIPAYMINIGAME
- 依賴：YooAsset、StarkWebGL、AlipayWebGL

## 快速開始

### 安裝

編輯 Unity 專案的 `Packages/manifest.json`，添加 `scopedRegistries` 部分：

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

`scopes` 控制哪些套件透過此註冊表解析。只有以 `com.gameframex` 開頭的套件才會從這個註冊表取得。

Then add the package to `dependencies`:

```json
{
  "dependencies": {
    "com.gameframex.unity.tuyoogame.yooasset.minigame.alipay": "1.0.0"
  }
}
```


## 文檔與資源

- [官方文檔](https://gameframex.doc.alianblank.com)

## 社區與支援

- QQ群: [加入](https://qm.qq.com/q/3dIpogITg)

## 更新日誌

查看 [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases) 了解更新日誌。

## 開源協議

本專案基於 MIT 協議開源 - 詳見 [LICENSE](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE) 檔案。
