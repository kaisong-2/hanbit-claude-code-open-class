# 한빛+ 클로드 코드 오픈 강좌 랜딩페이지

개발자 없이, 4시간 뒤엔 내 업무를 AI가 대신합니다.
10/22(목) 업무자동화 편 · 10/29(목) 콘텐츠 제작 편 — 한빛빌딩 A동 강의실 40

- Vercel: https://hanbit-claude-code-open-class.vercel.app
- GitHub Pages: https://kaisong-2.github.io/hanbit-claude-code-open-class/

## 구성
- `index.html` — 단일 파일 랜딩페이지 (인라인 CSS/JS, 한빛 디자인 시스템 토큰)
- `hanbit-logo.png` — 한빛+ 로고
- `hero2-visual.webp` — 히어로 일러스트 (한빛 틸 톤, 캔버스 애니메이션 오버레이)

## 수정 포인트
- 가격·신청 링크: `index.html` 하단 `CONFIG` 객체 (`apply`에 한빛+ 결제 URL 3개 입력)
- 커리큘럼·예시 프로젝트: `CURR`, `PROJ`, `THUMB` 데이터
