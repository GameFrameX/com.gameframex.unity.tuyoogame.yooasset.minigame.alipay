<div align="center">

<img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />

# GameFrameX YooAsset MiniGame Alipay

[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE.md)
[![Version](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases)
[![Unity Version](https://img.shields.io/badge/Unity-2019.4-black?logo=unity)](https://unity.com/)
[![Documentation](https://img.shields.io/badge/Documentation-docs-blue)](https://gameframex.doc.alianblank.com)

인디 게임 개발자를 위한 올인원 솔루션 · 인디 개발자의 꿈을 실현

<br />

[문서](https://gameframex.doc.alianblank.com) · [빠른 시작](#빠른-시작) · QQ 그룹: 467608841 / 233840761

<br />

[English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | **한국어**

</div>

## 프로젝트 개요

GameFrameX의 YooAsset 알리페이 미니게임 런타임 컴포넌트입니다. Unity WebGL 플랫폼을 대상으로 알리페이 미니게임 파일 시스템 및 에셋 번들 로딩 흐름의 어댑터 구현을 제공합니다.

## 기능

- 알리페이 미니게임 전용 IFileSystem 구현 제공
- 알리페이 미니게임 SDK의 AssetBundle 다운로드 및 캐싱 워크플로우 적응
- 패키지 버전 요청, 매니페스트 로딩, 에셋 번들 다운로드 및 로딩 지원
- 원격 서비스 및 복호화 서비스 연동 가능

## 실행 환경

- Unity 2019.4
- 플랫폼: UNITY_WEBGL
- 조건부 컴파일: ALIPAYMINIGAME
- 의존성: YooAsset, StarkWebGL, AlipayWebGL

## 빠른 시작

### 설치

Unity 프로젝트의 `Packages/manifest.json`을 편집하여 `scopedRegistries` 섹션을 추가하세요:

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

`scopes`는 이 레지스트리를 통해 어떤 패키지를 해석할지 제어합니다. `com.gameframex`로 시작하는 패키지만 이 레지스트리에서 가져옵니다.

Then add the package to `dependencies`:

```json
{
  "dependencies": {
    "com.gameframex.unity.tuyoogame.yooasset.minigame.alipay": "1.0.0"
  }
}
```

## 문서 및 자료

- [공식 문서](https://gameframex.doc.alianblank.com)

## 커뮤니티 및 지원

- QQ 그룹: [가입](https://qm.qq.com/q/3dIpogITg)

## 변경 로그

변경 로그는 [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases)에서 확인하세요.


## 의존성

| 패키지 | 설명 |
|--------|------|
| `com.gameframex.unity.tuyoogame.yooasset` | 1.0.0 |
## 라이선스

자세한 내용은 [LICENSE.md](LICENSE.md) 파일을 참조하세요.
