# 부산 이벤트 웹페이지

“부산 시민 AI 체험의 날” 행사 안내 웹페이지입니다. 사용자가 제공한 행사 정보만 반영하며, 확정되지 않은 정보는 “미정”으로 표시합니다.

## 사이트

- 홈페이지: https://lee-seongwouk.github.io/busan-event-webpage/
- 저장소: https://github.com/Lee-Seongwouk/busan-event-webpage

## 파일 구성

- `event_homepage.html`: 프로젝트 규칙에 따른 최종 웹페이지. HTML, CSS, 대표 이미지를 한 파일에 포함합니다.
- `index.html`: GitHub Pages 기본 주소에서 보여주는 웹페이지. `event_homepage.html`과 같은 내용입니다.
- `outputs/event_plan.md`: 행사 기획 내용.
- `outputs/event_homepage_review.md`: 행사 정보 및 화면 확인 결과.
- `data/`: 이미지 원본과 이미지 제작 프롬프트.

## 로컬 확인

`event_homepage.html`을 브라우저에서 열면 됩니다. 패키지 설치나 빌드 과정은 필요하지 않습니다.

## 수정 및 배포

GitHub Pages는 `main` 브랜치의 루트 폴더를 배포합니다. `event_homepage.html` 수정 후에는 `index.html`에도 같은 내용을 반영하고 커밋·푸시합니다.

PowerShell에서 기본 페이지를 동기화하는 명령:

```powershell
Copy-Item -LiteralPath 'event_homepage.html' -Destination 'index.html'
```

`.nojekyll` 파일은 정적 파일을 그대로 제공하도록 설정합니다. 행사 일정이나 신청 링크 등 새로운 정보는 확정된 뒤 반영합니다.
