# 123 매직루틴 — GitHub Pages 무료 배포 파일

## 업로드 전 한 번만 수정할 부분
GitHub 아이디가 예를 들어 `seoyoonkang`이면 아래 주소의 `YOUR-GITHUB-USERNAME`을 `seoyoonkang`으로 바꾸세요.

- `index.html`의 canonical 주소
- `sitemap.xml`의 `<loc>` 주소
- `robots.txt`의 Sitemap 주소

저장소 이름을 `123-magic-routine`이 아닌 다른 이름으로 만들었다면, 세 파일의 `/123-magic-routine/` 부분도 실제 저장소 이름으로 바꾸세요.

## GitHub Pages 게시
1. GitHub에서 `123-magic-routine` 이름의 Public 저장소를 만듭니다.
2. 이 폴더 안의 파일 4개를 저장소의 최상위 위치에 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Deploy from a branch**를 선택하고, Branch는 `main`, Folder는 `/ (root)`를 선택한 뒤 저장합니다.
5. 생성된 `https://깃허브아이디.github.io/123-magic-routine/` 주소를 확인합니다.

## 검색 등록
### Google
1. Google Search Console에서 위 주소를 **URL 접두어** 방식으로 속성 추가합니다.
2. 소유권 확인 뒤 URL 검사에서 메인 주소의 색인을 요청합니다.
3. Sitemaps 메뉴에서 `sitemap.xml`을 제출합니다.

### Naver
1. 네이버 서치어드바이저에 위 주소를 사이트로 등록합니다.
2. 소유 확인 후 사이트맵 주소 `https://깃허브아이디.github.io/123-magic-routine/sitemap.xml`을 제출합니다.
3. 웹페이지 수집 요청을 합니다.

## 파일 구성
- `index.html`: 랜딩페이지
- `123-magic-routine-free-preview.pdf`: 무료 선공개본. 페이지 버튼과 연결됨
- `sitemap.xml`: 검색엔진용 사이트맵
- `robots.txt`: 검색 로봇 수집 허용 설정
