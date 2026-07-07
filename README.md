# 자랭의 정석 GitHub Pages 패키지

이 폴더는 GitHub Pages에 그대로 올릴 수 있는 정적 사이트입니다.

## 파일 구조

- `index.html`: 화면, 편집기, 렌더링 로직
- `rules.json`: 모두가 보게 될 공통 문서 데이터

## 운영 방식

1. GitHub 저장소를 하나 만듭니다.
2. 이 폴더 안의 `index.html`과 `rules.json`을 저장소 루트에 올립니다.
3. GitHub Pages를 켜고 배포 브랜치와 루트 폴더를 선택합니다.
4. 접속자는 모두 같은 `rules.json` 기준 문서를 봅니다.
5. 내용을 수정할 때는 웹 페이지의 편집 기능으로 수정한 뒤 `rules.json 받기`를 누릅니다.
6. 내려받은 `rules.json`을 GitHub 저장소의 기존 `rules.json`에 덮어쓰면 모두에게 반영됩니다.

## 주의

- 브라우저의 `저장` 버튼은 현재 사용자 브라우저에 임시 저장합니다.
- 모두에게 반영하려면 반드시 GitHub의 `rules.json` 파일을 교체해야 합니다.
- GitHub 토큰은 이 HTML 안에 넣지 마세요. 공개 페이지에서는 토큰이 그대로 노출됩니다.
