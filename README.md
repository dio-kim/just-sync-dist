# just-sync (배포 전용)

옵시디언 저장소 동기화 플러그인 **just-sync** 의 배포 전용 레포입니다.
**소스는 여기 없습니다** — 이 레포는 BRAT 이 읽는 `manifest.json` 과
릴리스 에셋만 담습니다.

## 설치

1. 옵시디언에서 커뮤니티 플러그인 **BRAT** 을 설치한다
2. 명령 팔레트에서 `BRAT: Add a beta plugin for testing`
3. `dio-kim/just-sync-dist` 를 입력한다

데스크톱·모바일 모두 같은 절차입니다. 이후 업데이트는 BRAT 이 가져옵니다.

## 수동 설치

릴리스에서 `main.js` 와 `manifest.json` 을 받아 볼트의
`.obsidian/plugins/just-sync/` 에 넣습니다.

## 구성

| 위치 | 무엇 |
|---|---|
| 기본 브랜치 `manifest.json` | BRAT 의 버전 판정 대상 |
| 릴리스 에셋 `main.js` | 실제 번들 — git 에 커밋되지 않는다 |
| 릴리스 에셋 `manifest.json` | 설치 시 함께 내려간다 |

태그 · 릴리스 이름 · `manifest.json` 의 `version` 셋은 항상 같습니다.
