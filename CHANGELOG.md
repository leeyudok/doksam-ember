# Changelog

## 0.4.0 (2026-07-08)

- 최신 VSCode 규격에 맞춰 현행화
- `engines.vscode`를 `^1.96.0`으로 상향
- 마켓플레이스 메타데이터 추가 (`galleryBanner`, `pricing`, `extensionKind`, `homepage`, `bugs`, `qna`)
- 최신 VSCode 색상 토큰 보강 (3개 테마 공통)
  - 스티키 스크롤 (`editorStickyScroll.*`)
  - 인레이 힌트 (`editorInlayHint.*`)
  - 인라인 제안 / 고스트 텍스트 (`editorGhostText.foreground`)
  - 메뉴 (`menu.*`, `menubar.*`)
  - 키 바인딩 라벨 (`keybindingLabel.*`)
  - 툴바 (`toolbar.*`)

## 0.3.0 (2026-03)

- 테라코타 악센트 팔레트 정리 및 컬러 수정
- 아이콘을 덕삼이 얼굴 일러스트로 교체
- 테마 JSON `name` 필드 소문자 통일

## 0.1.0 (2026-03-23)

- 초기 릴리즈
- 워크벤치 UI 색상 (크림 배경 + 테라코타 악센트)
- 구문 강조 (TypeScript/JavaScript, HTML/JSX, CSS, JSON, Markdown, SQL, Regex)
- 시맨틱 하이라이팅 지원
- 터미널 ANSI 색상
- 괄호 쌍 색상화
- Git 장식 색상
