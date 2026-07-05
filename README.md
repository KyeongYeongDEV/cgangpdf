# CgangPDF

무료 PDF 페이지 편집·압축 웹사이트. 파일이 서버로 전송되지 않고 브라우저 안에서만 처리됩니다.

**https://cgangpdf.com**

## 기능

- 페이지 순서 변경(드래그) · 페이지 삭제 — 무손실 저장
- 썸네일 클릭 → 전체화면 미리보기, ←/→ 페이지 넘기기
- 3단계 압축 (저화질 72dpi / 중화질 150dpi / 고화질 300dpi)
- 압축 결과가 원본보다 커지면 저장 전 경고
- 파일 크기 제한 100MB (브라우저 메모리 보호)

## 구조

정적 사이트라 빌드 과정이 없습니다. 폴더를 그대로 호스팅하면 됩니다.

| 경로 | 내용 |
|---|---|
| `index.html` | 앱 + 소개·사용법·FAQ·팁 |
| `about.html` `privacy.html` `contact.html` | 정책·안내 페이지 |
| `vendor/` | [pdf.js](https://mozilla.github.io/pdf.js/) (Apache-2.0), [pdf-lib](https://pdf-lib.js.org/) (MIT) |
| `robots.txt` `sitemap.xml` | 검색엔진용 |

## 로컬 실행

`index.html`을 브라우저로 열면 끝입니다. 별도 서버가 필요 없습니다.
