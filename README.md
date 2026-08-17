# 📝 티스토리 마크다운 포스터 (Tistory Mobile Markdown Poster)

티스토리 블로그 작성을 더 쉽고 편리하게 도와주는 **모바일/웹 반응형 마크다운 편집기 및 서식 변환 도구**입니다.
티스토리 공식 Open API 종료 이후에도, **인라인 스타일(Inline Styles) 기반 리치 텍스트 클립보드 복사 엔진**을 통해 **표(Table), 소스코드 구문 강조(Syntax Highlight), 인용구, 제목 스타일**이 깨지지 않고 100% 그대로 적용됩니다.

## 🌐 서비스 접속 URL (Live Demo)

👉 **[티스토리 마크다운 포스터 서비스 바로가기](https://hline.github.io/tistory-mobile-markdown-poster/)**

---

## ✨ 주요 기능 (Key Features)

1. **내 블로그 URL 입력 및 관리자 글쓰기(`manage/newpost/`) 즉시 연결**
   - 블로그 주소(예: `https://myblog.tistory.com` 또는 `myblog`)를 입력하면 자동으로 주소를 분석하여 해당 블로그의 관리자 글쓰기 페이지(`https://[블로그].tistory.com/manage/newpost/`)로 바로 이동합니다. (자동 저장 지원)

2. **모바일 전용 리치 텍스트(Rich-Text) 인라인 복사 엔진 (Zero-API)**
   - 변환된 HTML의 모든 스타일(표 테두리, 배경색, 코드 하이라이트 색상)을 태그 내부의 `style="..."`로 자동 인라인화합니다.
   - 하단의 **[📋 서식 복사]** 버튼을 누르면 클립보드에 리치 텍스트(`text/html`)로 저장되어, 관리자 에디터에서 **[붙여넣기]**만으로 완성도 높은 서식이 즉시 삽입됩니다.

3. **모바일 마크다운 퀵 툴바 (Mobile Quick Toolbar)**
   - 모바일 키보드에서 특수문자(`#`, `*`, `` ` ``, `|`) 입력이 번거로운 문제를 해결하기 위해 제목(H1~H3), 굵게, 기울임, 취소선, 인라인코드, 코드블록, 표, 인용구, 링크 등을 원터치로 삽입할 수 있는 툴바를 제공합니다.

4. **본문 초기화 및 실시간 자동 임시저장 (Clear & Auto Draft Save)**
   - 원클릭으로 본문을 깔끔하게 비울 수 있는 **[🗑️ 본문 초기화]** 버튼 제공.
   - 작성 중인 마크다운 본문이 브라우저 로컬 스토리지에 실시간 자동 저장되어 내용 유실 방지.

5. **코드 블록 구문 강조 (Highlight.js Atom One Dark)**
   - `Marked.js` 및 `Highlight.js`의 'atom-one-dark' 테마가 연동되어 소스 코드를 가독성 높은 다크 테마 디자인으로 변환해 줍니다.

---

## 📱 아이폰 / 모바일 사용 가이드 (Mobile Workflow)

1. 스마트폰 브라우저에서 [배포 URL](https://hline.github.io/tistory-mobile-markdown-poster/)에 접속합니다.
2. 내 티스토리 주소를 입력하고 퀵 툴바를 활용하여 본문을 작성합니다.
3. 화면 하단의 **[📋 서식 복사]** 버튼을 터치합니다.
4. **[🖥️ 데스크탑 모드 글쓰기]**를 눌러 티스토리 관리자 페이지로 이동합니다.
5. **(아이폰 사파리 기준)** 주소창 왼쪽의 **`가(AA)` 버튼 → [데스크탑 웹사이트 요청]**을 누릅니다.
6. 본문 영역을 터치하고 **[붙여넣기]**를 실행하면 표와 코드 하이라이팅이 완벽하게 적용됩니다!

---

## 🛠 기술 스택 (Tech Stack)

- **Frontend:** HTML5, Vanilla CSS3, JavaScript (ES6+)
- **Parser & Styler:**
  - [Marked.js](https://github.com/markedjs/marked) - GitHub Flavored Markdown (GFM) 파서
  - [Highlight.js](https://github.com/highlightjs/highlight.js) - 실시간 코드 구문 분석
  - Custom DOM-based CSS Inliner Engine (인라인 스타일 변환기)
- **Deployment:** GitHub Pages
