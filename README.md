<div align="center">

# 🧘 고요의 순간

**마음의 평화를 찾는 현대인을 위한 명상 사이트**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

[📖 기능 소개](#-기능-소개) • [🚀 사용 방법](#-사용-방법) • [⚙️ 커스터마이징](#️-커스터마이징)

</div>

---

## 📖 프로젝트 소개

**고요의 순간**은 바쁜 현대인들이 일상 속에서 마음의 평화를 찾을 수 있도록 돕는 명상 커뮤니티 사이트입니다. 

단일 HTML 파일로 구현되어 있어 **설치나 빌드 과정 없이** 바로 사용할 수 있으며, 모든 기능이 클라이언트 사이드에서 동작합니다.

### ✨ 주요 특징

- 🎯 **단일 파일 구조** - 하나의 HTML 파일에 모든 기능 포함
- 🚀 **즉시 실행 가능** - 빌드나 설치 과정 불필요
- 📱 **완전 반응형** - 모바일, 태블릿, 데스크톱 모든 기기 지원
- 🎨 **세련된 디자인** - 부드러운 색상과 애니메이션
- ⚡ **빠른 로딩** - CDN 기반 경량 구조

---

## 🎯 기능 소개

### 🏠 홈 페이지
- 히어로 섹션과 소개
- 최신 소식 미리보기
- 갤러리 썸네일

### 📰 소식 섹션
- 소식 목록 및 상세 보기
- 카테고리별 분류
- 조회수 표시
- 이전/다음 소식 네비게이션
- 관련 소식 추천
- SNS 공유 기능 (Facebook, Twitter)

### 🖼️ 갤러리
- 이미지 그리드 레이아웃
- 모달 팝업으로 확대 보기
- 호버 효과

### 📚 자료실
- PDF, 음성, 영상, 문서 자료
- 타입별 배지 표시
- 다운로드 기능

### 💬 커뮤니티
- 게시판 목록
- 실시간 검색 기능
- 게시글 작성
- 조회수 표시

### 👥 소개
- 조직 소개
- 팀 멤버 프로필
- 비전 및 미션

---

## 🚀 사용 방법

### 로컬에서 실행

`index.html` 파일을 브라우저에서 직접 열면 됩니다. 더블클릭하거나 브라우저로 드래그하세요.

> 💡 **참고**: 인터넷 연결이 필요합니다 (Bootstrap CDN 및 이미지 로딩)

### GitHub Pages로 호스팅

1. GitHub 저장소에 `index.html` 파일 업로드
2. 저장소 **Settings** > **Pages** 이동
3. **Source**에서 브랜치와 폴더 선택 (보통 `main` 브랜치, `/ (root)` 폴더)
4. 저장 후 몇 분 뒤 `https://your-username.github.io/repository-name/` 에서 확인

---

## 🛠️ 기술 스택

| 기술 | 용도 | 버전 |
|------|------|------|
| **HTML5** | 마크업 구조 | - |
| **CSS3** | 스타일링 및 애니메이션 | - |
| **JavaScript (ES6+)** | 인터랙티브 기능 | - |
| **Bootstrap** | 반응형 UI 프레임워크 | 5.3.2 |
| **Google Fonts** | 웹 폰트 (Nanum Gothic, Rubik) | - |

### 📦 의존성

모든 의존성은 CDN을 통해 로드되므로 별도 설치가 필요 없습니다:

- Bootstrap 5.3.2 (CSS & JS)
- Google Fonts API

---

## 🎨 디자인 특징

- **색상 팔레트**: 따뜻한 베이지 톤과 테라코타 악센트
- **타이포그래피**: 한글 (나눔고딕) + 영문 (Rubik)
- **애니메이션**: 부드러운 페이드인 및 호버 효과
- **레이아웃**: 카드 기반 그리드 시스템

---

## 📱 브라우저 지원

| 브라우저 | 최소 버전 |
|----------|----------|
| Chrome | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Edge | 90+ |

---

## ⚙️ 커스터마이징

모든 코드가 `index.html` 단일 파일에 포함되어 있어 쉽게 수정할 수 있습니다.

### 색상 변경

파일 내 `<style>` 섹션의 CSS 변수를 수정하세요:

```css
:root {
    --background: #fdfaf6;    /* 배경색 */
    --foreground: #4a4a4a;     /* 텍스트 색상 */
    --primary-accent: #D98880; /* 주요 악센트 색상 */
}
```

### 데이터 수정

소식, 갤러리, 자료실, 커뮤니티 게시글 등의 데이터는 파일 하단의 `<script>` 섹션에 JavaScript 객체로 정의되어 있습니다. 직접 수정하면 됩니다.

---

## 📁 파일 구조

```
meditation-site/
└── index.html    # 모든 기능이 포함된 단일 HTML 파일
```

단일 파일로 구성되어 있어 관리가 간단합니다!

---

## 📝 라이선스

이 프로젝트는 자유롭게 사용, 수정, 배포할 수 있습니다.

---

## 🤝 기여하기

버그 리포트나 기능 제안은 언제든 환영합니다! 이슈를 등록하거나 Pull Request를 보내주세요.

---

<div align="center">

**⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요! ⭐**

Made with ❤️ for peaceful minds

</div>
