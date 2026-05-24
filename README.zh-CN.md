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
  独立游戏前后端一体化解决方案 · 独立游戏开发者的圆梦大使
</p>

<p align="center">
  <a href="https://gameframex.doc.alianblank.com">文档</a> ·
  <a href="#快速开始">快速开始</a> ·
  <a href="https://qm.qq.com/q/3dIpogITg">QQ群</a> ·
  语言: <a href="README.md">English</a> ·
  **简体中文** ·
  <a href="README.zh-TW.md">繁體中文</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.ko.md">한국어</a>
</p>

---

## 项目简介

GameFrameX 的 YooAsset 支付宝小游戏运行时组件，面向 Unity WebGL 平台，提供与支付宝小游戏文件系统、资源包加载流程的适配实现。

## 功能特性

- 提供支付宝小游戏专用的 IFileSystem 实现
- 适配支付宝小游戏 SDK 的 AssetBundle 下载与缓存流程
- 支持包版本请求、清单加载、资源包下载与加载
- 可对接远程服务与解密服务

## 运行环境

- Unity 2019.4
- 平台：UNITY_WEBGL
- 条件编译：ALIPAYMINIGAME
- 依赖：YooAsset、StarkWebGL、AlipayWebGL

## 快速开始

### 安装方式（任选其一）

1. 在 `manifest.json` 的 `dependencies` 中添加：
   ```json
   {"com.gameframex.unity.tuyoogame.yooasset.minigame.alipay": "https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay.git"}
   ```

2. 在 Unity 的 Package Manager 使用 Git URL 添加：https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay.git

3. 直接下载仓库放到 Unity 项目的 `Packages` 目录。

### 使用说明

1. 确保已接入支付宝小游戏 SDK，并启用 `ALIPAYMINIGAME` 宏
2. 通过 `AlipayFileSystemCreater.CreateFileSystemParameters(...)` 生成文件系统参数
3. 将参数传入 YooAsset 的文件系统创建流程
4. 按照 YooAsset 的常规流程进行初始化、版本请求、清单加载与资源加载

## 文档与资源

- [官方文档](https://gameframex.doc.alianblank.com)

## 社区与支持

- QQ群: [加入](https://qm.qq.com/q/3dIpogITg)

## 更新日志

查看 [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases) 了解更新日志。

## 开源协议

本项目基于 MIT 协议开源 - 详见 [LICENSE](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE) 文件。
