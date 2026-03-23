# doksam Ember

따뜻하고 자연스러운 색감의 VSCode 테마.
테라코타 악센트와 크림 캔버스 위에 자연의 흙빛 톤을 담았습니다.

> *"눈이 편안한 따뜻한 톤의 코딩 환경"*

---

## 3가지 모드

| 모드 | 설명 |
|------|------|
| **doksam Ember** | 기본. 크림 배경 + 따뜻한 UI |
| **doksam Ember Light** | 밝은 변형. 순백 배경 + 선명한 악센트 |
| **doksam Ember Dark** | 어두운 변형. 웜 다크 배경 + 부드러운 구문 강조 |

---

## 특징

- 🎨 **크림 캔버스** — 순백이 아닌 따뜻한 `#FAF9F6` 배경으로 장시간 눈의 피로 감소
- 🔥 **테라코타 악센트** — `#D97757` 포인트로 커서, 탭, 버튼, 뱃지 통일
- 🌿 **자연 색상 구문 강조** — 올리브 그린, 오커, 번트 시에나, 더스티 모브의 조화
- ✨ **시맨틱 하이라이팅** — TypeScript/JavaScript의 타입, 함수, 변수를 더 정밀하게 구분
- 🖥️ **터미널 ANSI 색상** — 테마 톤에 맞춘 16색 터미널 팔레트
- 🔗 **괄호 쌍 색상화** — 6단계 괄호 색상으로 중첩 구조 한눈에 파악
- 📂 **Git 장식** — 추가/수정/삭제/미추적 파일을 직관적 색상으로 구분

---

## 색상 팔레트

### UI (워크벤치)

| 영역 | 색상 | 이름 |
|------|------|------|
| 에디터 배경 | `#FAF9F6` | 크림 화이트 |
| 기본 텍스트 | `#1A1915` | 웜 블랙 |
| 악센트 | `#D97757` | 테라코타 |
| 사이드바 | `#EEECE7` | 페일 샌드 |
| 패널 | `#F5F3EE` | 라이트 린넨 |
| 보더 | `#E3DFD8` | 오트밀 |

### 구문 강조 (Syntax)

| 역할 | 색상 | 이름 | 대상 |
|------|------|------|------|
| 키워드 | `#C2582A` | 테라코타 딥 | `const`, `if`, `return`, `import` |
| 함수 | `#956D3A` | 오커 | `getUserById()`, `map()` |
| 문자열 | `#697D45` | 올리브 그린 | `"hello"`, `` `template` `` |
| 타입 | `#7D6499` | 더스티 모브 | `interface`, `User`, `Promise` |
| 숫자/상수 | `#B35430` | 번트 시에나 | `42`, `true`, `null`, `MAX_COUNT` |
| 속성 | `#6E5B47` | 웜 브라운 | `.name`, `{ key: }` |
| 주석 | `#A39D93` | 웜 그레이 | `// comment` *(이탤릭)* |
| 매개변수 | `#5C5650` | 차콜 | `(param)` *(이탤릭)* |
| 데코레이터 | `#8E6E99` | 라벤더 | `@decorator` *(이탤릭)* |

---

## 설치

### VS Marketplace (준비 중)

```
ext install doksam.doksam-ember
```

### VSIX로 설치 (로컬)

```bash
# 1. 빌드
npm install -g @vscode/vsce
cd doksam-ember
vsce package

# 2. VSCode에서 설치
# Ctrl+Shift+P → "Extensions: Install from VSIX" → doksam-ember-0.3.0.vsix 선택
```

### 테마 적용

```
Ctrl+Shift+P → "Color Theme" → "doksam Ember" 선택
```

---

## 함께 추천하는 설정

```jsonc
{
  "editor.fontFamily": "'JetBrains Mono', D2Coding, monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.6,
  "workbench.iconTheme": "catppuccin-latte",
  "editor.bracketPairColorization.enabled": true,
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on"
}
```

---

## 라이선스

MIT © 덕삼ol
