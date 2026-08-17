# 📝 티스토리 모바일 마크다운 포스터 (Tistory Mobile Markdown Poster)

티스토리 블로그 작성을 더 쉽고 편리하게 도와주는 **모바일/웹 반응형 마크다운 편집기 및 서식 변환 도구**입니다.
티스토리 공식 Open API 종료 이후에도, **인라인 스타일(Inline Styles) 기반 리치 텍스트 클립보드 복사 엔진**을 통해 모바일(HTML 모드가 없는 환경)에서도 **표(Table), 소스코드 구문 강조(Syntax Highlight), 인용구, 제목 스타일**이 깨지지 않고 100% 그대로 적용됩니다.

## 🌐 서비스 접속 URL (Live Demo)

👉 **[티스토리 마크다운 포스팅 & 이미지 매니저 서비스 바로가기](https://hline.github.io/tistory-mobile-markdown-poster/)**

---

## ✨ 주요 기능 (Key Features)

1. **모바일 전용 리치 텍스트(Rich-Text) 인라인 복사 엔진 (Zero-API)**
   - 티스토리 모바일 앱/웹에는 HTML 모드 전환 기능이 없기 때문에, 변환된 HTML의 모든 스타일(테두리, 배경색, 코드 하이라이트 색상)을 태그 내부의 `style="..."`로 자동 인라인화합니다.
   - 하단의 **[📋 모바일 서식 복사]** 버튼을 누르면 클립보드에 `text/html` 서식으로 저장되어, 티스토리 모바일 글쓰기 창에서 **[길게 누르기 > 붙여넣기]**만으로 완성도 높은 서식이 즉시 삽입됩니다.

2. **모바일 마크다운 퀵 툴바 (Mobile Quick Toolbar)**
   - 모바일 키보드에서 특수문자(`#`, `*`, `` ` ``, `|`) 입력이 번거로운 문제를 해결하기 위해 제목(H1~H3), 굵게, 기울임, 코드블록, 표, 인용구, 링크 등을 원터치로 삽입할 수 있는 퀵 툴바를 제공합니다.

3. **모바일 최적화 이미지 순서 정렬 및 태그 삽입**
   - 여러 장의 사진을 선택한 후 `◀`, `▶` 버튼 및 삭제(`✕`) 버튼으로 모바일에서도 손쉽게 순서를 변경하고, 본문에 알맞은 위치에 이미지 삽입 태그를 추가할 수 있습니다.

4. **로컬스토리지 블로그 ID 캐싱 & 원클릭 글쓰기 이동**
   - 티스토리 블로그 아이디를 입력하면 브라우저의 `localStorage`에 자동 저장되며, **[🚀 글쓰기 이동]** 버튼 클릭 시 내 블로그의 글쓰기 화면으로 즉시 새 탭 이동합니다.

5. **코드 블록 구문 강조 (Highlight.js Atom One Dark)**
   - `Marked.js` 및 `Highlight.js`의 'atom-one-dark' 테마가 연동되어 소스 코드를 가독성 높은 다크 테마 디자인으로 변환해 줍니다.

---

## 📱 모바일 사용 방법 (Mobile Workflow)

1. 스마트폰/태블릿 브라우저에서 [배포 URL](https://hline.github.io/tistory-mobile-markdown-poster/)에 접속합니다.
2. 마크다운 퀵 툴바를 활용하여 본문을 작성합니다. (실시간 미리보기 확인)
3. 화면 하단의 **[📋 모바일 서식 복사]** 버튼을 누릅니다.
4. **[🚀 글쓰기 이동]**을 눌러 티스토리 에디터를 연 뒤, 본문 영역을 **길게 눌러 [붙여넣기]**를 실행합니다.
5. 표와 코드 하이라이팅이 완벽히 적용된 글을 확인하고 바로 발행합니다.

---

## 🛠 기술 스택 (Tech Stack)

- **Frontend:** HTML5, Vanilla CSS3, JavaScript (ES6+)
- **Parser & Styler:**
  - [Marked.js](https://github.com/markedjs/marked) - GitHub Flavored Markdown (GFM) 파서
  - [Highlight.js](https://github.com/highlightjs/highlight.js) - 실시간 코드 구문 분석
  - Custom DOM-based CSS Inliner Engine (인라인 스타일 변환기)
- **Deployment:** GitHub Pages
