# 내 블로그 (Astro 정적 사이트)

이 프로젝트는 Vercel에 바로 배포할 수 있는 **Astro 정적 블로그**입니다.

## 글(포스트) 추가하기
- `src/content/blog/` 폴더에 `*.md` 또는 `*.mdx` 파일을 추가하세요.
- 파일 상단의 frontmatter에 아래 값이 들어가면 목록/상세 페이지가 자동 생성됩니다.
  - `title`
  - `description`
  - `pubDate`
  - `heroImage`(선택)

## 로컬 실행
```sh
npm install
npm run dev
```

## 프로덕션 빌드
```sh
npm run build
```
