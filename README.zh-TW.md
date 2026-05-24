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
  獨立遊戲前後端一體化解決方案 · 獨立遊戲開發者的圓夢大使
</p>

<p align="center">
  <a href="https://gameframex.doc.alianblank.com">文檔</a> ·
  <a href="#快速開始">快速開始</a> ·
  <a href="https://qm.qq.com/q/3dIpogITg">QQ群</a> ·
  語言: <a href="README.md">English</a> ·
  <a href="README.zh-CN.md">简体中文</a> ·
  **繁體中文** ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.ko.md">한국어</a>
</p>

---

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

### 安裝方式（任選其一）

1. 在 `manifest.json` 的 `dependencies` 中加入：
   ```json
   {"com.gameframex.unity.tuyoogame.yooasset.minigame.alipay": "https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay.git"}
   ```

2. 在 Unity 的 Package Manager 使用 Git URL 加入：https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay.git

3. 直接下載倉庫放到 Unity 專案的 `Packages` 目錄。

### 使用說明

1. 確保已接入支付寶小遊戲 SDK，並啟用 `ALIPAYMINIGAME` 巨集
2. 透過 `AlipayFileSystemCreater.CreateFileSystemParameters(...)` 生成檔案系統參數
3. 將參數傳入 YooAsset 的檔案系統建立流程
4. 按照丫ooAsset 的常規流程進行初始化、版本請求、清單載入與資源載入

## 文檔與資源

- [官方文檔](https://gameframex.doc.alianblank.com)

## 社區與支援

- QQ群: [加入](https://qm.qq.com/q/3dIpogITg)

## 更新日誌

查看 [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases) 了解更新日誌。

## 開源協議

本專案基於 MIT 協議開源 - 詳見 [LICENSE](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE) 檔案。
