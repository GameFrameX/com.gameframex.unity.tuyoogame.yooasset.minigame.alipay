<div align="center">

<img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />

# GameFrameX YooAsset MiniGame Alipay

[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE.md)
[![Version](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases)
[![Documentation](https://img.shields.io/badge/Documentation-docs-blue)](https://gameframex.doc.alianblank.com)

인디 게임 개발자를 위한 올인원 솔루션 · 인디 개발자의 꿈을 실현

<br />

[문서](https://gameframex.doc.alianblank.com) · [빠른 시작](#빠른-시작) · [QQ 그룹](https://qm.qq.com/q/3dIpogITg)

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

### 설치 (선택)

1. `manifest.json`의 `dependencies` 섹션에 다음을 추가:
   ```json
   {"com.gameframex.unity.tuyoogame.yooasset.minigame.alipay": "https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay.git"}
   ```

2. Unity의 Package Manager에서 `Git URL`을 사용하여 패키지 추가: https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay.git

3. 리포지토리를 다운로드하여 Unity 프로젝트의 `Packages` 디렉토리에 배치.

### 사용 방법

1. 알리페이 미니게임 SDK가 통합되어 있고 `ALIPAYMINIGAME` 매크로가 활성화되어 있는지 확인
2. `AlipayFileSystemCreater.CreateFileSystemParameters(...)`로 파일 시스템 매개변수 생성
3. 매개변수를 YooAsset의 파일 시스템 생성 흐름에 전달
4. YooAsset의 표준 흐름에 따라 초기화, 버전 요청, 매니페스트 로딩 및 에셋 로딩 수행

## 문서 및 자료

- [공식 문서](https://gameframex.doc.alianblank.com)

## 커뮤니티 및 지원

- QQ 그룹: [가입](https://qm.qq.com/q/3dIpogITg)

## 변경 로그

변경 로그는 [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/releases)에서 확인하세요.

## 라이선스

이 프로젝트는 MIT 라이선스에 따라 배포됩니다 - 자세한 내용은 [LICENSE](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.alipay/blob/main/LICENSE) 파일을 참조하세요.
