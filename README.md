# Create Pack

롬 폴더를 팩 하나로 정리해 RetroBat·Pegasus·ES-DE 용으로 내보내는 Windows 앱의 소개 페이지와 사용 설명서.

- `index.html` — 소개
- `manual.html` — 사용 설명서. 손으로 고치지 않는다 — 앱 저장소 `scratchpad/site/build-manual.mjs` 가 `manual.src.html` 에 그림 · 네모칸 · 범례를 끼워 만든다
- `updates.html` — 업데이트 내역(판마다 맨 위에 더한다)
- `assets/site.css` — 세 쪽 공통 꾸밈(앱 레트로 테마 「패미컴 크림」 · 검정 테마)
- `assets/manual/` — 설명서 그림(`build-manual.mjs` 가 복사한다)
- `assets/*.png` — 로고 · 카트리지 · 내려받기 스프라이트(앱 그림 묶음에서 가져옴)
- `fonts/` — Galmuri14 · PressStart2P(쓰는 글자만 남겨 줄인 것 · 사용 허락은 옆 LICENSE 파일)

화면은 지어낸 예시 팩으로 찍었다. 게임 파일·BIOS·열쇠는 없다.
