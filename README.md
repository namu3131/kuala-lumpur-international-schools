# Kuala Lumpur International Schools

GitHub Pages 또는 Vercel에 바로 올릴 수 있는 정적 사이트입니다.

## 포함 파일
- `index.html`
- `robots.txt`
- `sitemap.xml`
- `.nojekyll`

## 배포 전 꼭 수정할 것
`index.html`, `robots.txt`, `sitemap.xml` 안의 `https://example.com/` 을 실제 배포 도메인으로 바꾸세요.

수정 대상:
- `<link rel="canonical">`
- `og:url`
- `og:image`
- `robots.txt`의 Sitemap 경로
- `sitemap.xml`의 `<loc>`

## SEO 체크리스트
- GitHub Pages 또는 사용자 도메인 연결 후 실제 URL로 교체
- Google Search Console 등록
- Naver Search Advisor 등록
- `sitemap.xml` 제출
- `robots.txt` 확인
- 페이지 제목과 설명이 검색 의도에 맞는지 점검
