# TIDE BREAK v3 (3D hack) — Standalone

Project AS 온보딩 미니게임 **TIDE BREAK v3 (3D hack)** 의 단일 파일 빌드.

`tide_break_v3_hack_STANDALONE.html` 한 파일에 게임 코드·에셋·라이브러리(three.js r128 + GLTFLoader/DRACOLoader/SkeletonUtils + DRACO 디코더)를 전부 임베드한 **완전 오프라인 self-contained** HTML입니다.

## 실행

별도 서버 없이 파일을 브라우저로 열면 됩니다.

- 더블클릭 (`file://`) — 인터넷 연결 불필요
- 또는 정적 서버: `python -m http.server 8765` → `http://localhost:8765/tide_break_v3_hack_STANDALONE.html`

## 조작

- 모바일: 화면 드래그로 좌우 이동
- PC: 좌클릭 드래그 또는 ← → 키

## 빌드 정보

- 크기: ~60.7 MB (에셋 base64 인라인 포함)
- 라이브러리·에셋·설정 JSON·텍스처 전부 data URI / 인라인 처리 → 외부 네트워크 요청 0
- 배포본 정리: DEV 패널·호출 버튼·화면 버전 뱃지 제거
- 원본: `aqua-sl-minigame-hack` 의 `games/tide_break_v3_lab_3d_hack`
