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
  インディゲーム開発者向けオールインワンソリューション · インディ開発者の夢を支援
</p>

<p align="center">
  <a href="https://gameframex.doc.alianblank.com">ドキュメント</a> ·
  <a href="#クイックスタート">クイックスタート</a> ·
  <a href="https://qm.qq.com/q/3dIpogITg">QQグループ</a> ·
  言語: <a href="README.md">English</a> ·
  <a href="README.zh-CN.md">简体中文</a> ·
  <a href="README.zh-TW.md">繁體中文</a> ·
  **日本語** ·
  <a href="README.ko.md">한국어</a>
</p>

---

## プロジェクト概要

GameFrameX の YooAsset アリペイミニゲームランタイムコンポーネント。Unity WebGL プラットフォーム向けに、アリペイミニゲームのファイルシステムとアセットバンドル読み込みフローの適配実装を提供します。

## 機能

- アリペイミニゲーム専用の IFileSystem 実装を提供
- アリペイミニゲーム SDK の AssetBundle ダウンロードとキャッシュワークフローに適配
- パッケージバージョンリクエスト、マニフェスト読み込み、アセットバンドルダウンロードと読み込みをサポート
- リモートサービスと復号サービスに対応

## 動作環境

- Unity 2019.4
- プラットフォーム：UNITY_WEBGL
- 条件付きコンパイル：ALIPAYMINIGAME
- 依存関係：YooAsset、StarkWebGL、AlipayWebGL

## クイックスタート

### インストール（いずれかを選択）

1. `manifest.json` の `dependencies` セクションに以下を追加：
   ```json
   {"com.gameframex.unity.tuyoogame.yooasset.minigame.alipay": "https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay.git"}
   ```

2. Unity の Package Manager で `Git URL` を使用してパッケージを追加：https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay.git

3. リポジトリをダウンロードして Unity プロジェクトの `Packages` ディレクトリに配置。

### 使用方法

1. アリペイミニゲーム SDK が統合され、`ALIPAYMINIGAME` マクロが有効になっていることを確認
2. `AlipayFileSystemCreater.CreateFileSystemParameters(...)` でファイルシステムパラメータを生成
3. パラメータを YooAsset のファイルシステム作成フローに渡す
4. YooAsset の標準フローに従って初期化、バージョンリクエスト、マニフェスト読み込み、アセット読み込みを行う

## ドキュメントとリソース

- [公式ドキュメント](https://gameframex.doc.alianblank.com)

## コミュニティとサポート

- QQグループ: [参加](https://qm.qq.com/q/3dIpogITg)

## 変更履歴

変更履歴は [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases) をご覧ください。

## ライセンス

このプロジェクトは MIT ライセンスの下で公開されています - 詳細は [LICENSE](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE) ファイルをご覧ください。
