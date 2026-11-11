# so230.github.io

서비스 소개·안내 페이지 (GitHub Pages, 공개 저장소). **원래 공개할 내용만** 둔다 — 프로그램 코드는 각 서비스의 비공개 저장소에.

## 구조 (폴더 = 주소)
- `index.html` → https://so230.github.io/ (서비스 목록)
- `moapack/index.html` → https://so230.github.io/moapack/ (모아팩 소개)
- `assets/style.css` → 공통 디자인 (흰색·검정 + 포인트 빨강)

새 페이지는 폴더를 만들고 그 안에 `index.html`을 두면 `https://so230.github.io/폴더이름/`으로 열린다.
예) 이용약관 `moapack/terms/index.html` → https://so230.github.io/moapack/terms/

## 반영
`main`에 올리면 1~2분 뒤 자동 반영.

## 정식 오픈 때 할 일
- 각 페이지의 `<meta name="robots" content="noindex, nofollow">` 삭제 (지금은 검색엔진 차단)
- 모아팩 이용약관·개인정보 처리방침(법률 검토 후), 화면 하단 사업자 정보 추가
- '테스트 운영 중' 표시 제거
