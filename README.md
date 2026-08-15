# 📝 티스토리 마크다운 포스팅 & 이미지 매니저 (Tistory Mobile Markdown Poster)

티스토리 블로그 작성을 더 쉽고 편리하게 도와주는 **웹 브라우저 기반 마크다운 편집기 및 이미지 정렬 도구**입니다.
별도의 복잡한 설치나 백엔드 서버 없이 단일 `index.html` 파일로 동작하며, 마크다운 실시간 렌더링 및 드래그 앤 드롭 방식을 통한 직관적인 이미지 순서 정렬 기능을 제공합니다.

## ✨ 주요 기능 (Key Features)

1. **로컬스토리지 블로그 ID 캐싱 (LocalStorage Caching)**
   - 티스토리 블로그 이름(ID) 입력 시 브라우저의 `localStorage`에 자동 저장되어, 페이지를 새로고침하거나 재방문해도 이전 입력값을 안전하게 유지합니다.

2. **드래그 앤 드롭 이미지 정렬 (Drag-and-Drop Image Reordering)**
   - 업로드할 여러 이미지를 한 번에 선택하고, 마우스 드래그를 통해 이미지의 포스팅 순서를 시각적·직관적으로 재정렬할 수 있습니다. 각 카드에는 실시간 순서 번호(Order Badge)와 파일명이 표시됩니다.

3. **고급 마크다운 렌더링 (Markdown & GFM Support)**
   - `Marked.js` 라이브러리를 채택하여 GitHub Flavored Markdown(GFM) 스펙을 준수하는 표(Table)나 자동 줄바꿈(Breaks)을 완벽하게 렌더링합니다.

4. **코드 블록 구문 강조 (Syntax Highlighting)**
   - `Highlight.js`의 'atom-one-dark' 테마가 연동되어 소스 코드를 가독성 높은 디자인으로 변환해 줍니다.

## 🚀 사용 방법 (How to Use)

1. 이 저장소를 클론하거나 `index.html` 파일을 다운로드합니다.
2. 브라우저(Chrome, Safari, Edge 등)에서 `index.html` 파일을 더블 클릭하여 실행합니다.
3. 티스토리 블로그 ID를 입력하고, 이미지를 업로드하여 원하는 순서로 정렬합니다.
4. 마크다운 본문을 입력한 후 **[미리보기 및 변환]** 버튼을 누르거나 실시간 변환 화면을 확인하여 티스토리에 포스팅할 콘텐츠를 미리 검토합니다.

## 🛠 사용된 기술 (Built With)

- **Frontend:** HTML5, CSS3 (Vanilla), JavaScript (ES6)
- **Libraries:**
  - [Marked.js](https://github.com/markedjs/marked) - Markdown Parser
  - [Highlight.js](https://github.com/highlightjs/highlight.js) - Syntax Highlighting
