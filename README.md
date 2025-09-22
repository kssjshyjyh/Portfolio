# 개인 CV 웹사이트

모던하고 반응형인 개인 CV 웹사이트입니다. 깔끔한 디자인과 인터랙티브한 기능을 제공합니다.

## ✨ 특징

- **반응형 디자인**: 모바일, 태블릿, 데스크톱 모든 기기에서 최적화
- **다크/라이트 테마**: 사용자 선호에 따른 테마 전환 기능
- **부드러운 애니메이션**: 스크롤 기반 애니메이션과 인터랙션
- **최신 웹 기술**: HTML5, CSS3, Vanilla JavaScript 사용
- **GitHub Pages 호환**: 무료 호스팅 지원

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: CSS Grid, Flexbox, CSS 변수, 애니메이션
- **JavaScript**: ES6+, Intersection Observer API
- **Font Awesome**: 아이콘 라이브러리

## 📱 주요 기능

### 네비게이션
- 고정 상단 네비게이션 바
- 스무스 스크롤링
- 활성 섹션 하이라이팅
- 모바일 메뉴 지원

### 테마 전환
- 다크/라이트 모드 토글
- 로컬 스토리지에 설정 저장
- 부드러운 테마 전환 애니메이션

### 인터랙티브 요소
- 프로젝트 카드 3D 틸트 효과
- 스킬 태그 호버 애니메이션
- 스크롤 기반 요소 등장 애니메이션
- 타이핑 애니메이션

## 🚀 설치 및 실행

1. 저장소 클론
```bash
git clone https://github.com/your-username/cv-website.git
cd cv-website
```

2. 웹 브라우저에서 `index.html` 파일 열기

또는 로컬 서버 실행:
```bash
# Python 3
python -m http.server 8000

# Node.js (http-server 패키지 필요)
npx http-server

# VS Code Live Server 확장 프로그램 사용
```

## 📄 섹션 구성

1. **홈**: 인트로 및 주요 정보
2. **소개**: 자기소개 및 통계
3. **경력**: 업무 경험 타임라인
4. **교육**: 학력 정보
5. **기술**: 기술 스택 및 도구
6. **프로젝트**: 주요 프로젝트 포트폴리오
7. **연락처**: 연락처 정보 및 소셜 링크

## 🎨 커스터마이징

### 개인 정보 수정
`index.html` 파일에서 다음 정보를 수정하세요:
- 이름 및 직책
- 연락처 정보
- 경력 사항
- 교육 배경
- 기술 스택
- 프로젝트 정보

### 스타일 커스터마이징
`style.css` 파일의 CSS 변수를 수정하여 색상과 스타일을 변경할 수 있습니다:

```css
:root {
    --primary-color: #3b82f6;    /* 주요 색상 */
    --secondary-color: #1e40af;  /* 보조 색상 */
    --accent-color: #f59e0b;     /* 강조 색상 */
}
```

### 소셜 링크 연결
`script.js` 파일에서 소셜 미디어 링크를 실제 URL로 연결하세요.

## 📦 GitHub Pages 배포

1. GitHub 저장소 생성
2. 코드 푸시
3. Settings > Pages에서 Source를 "Deploy from a branch" 선택
4. Branch를 "main" 선택
5. 몇 분 후 `https://your-username.github.io/cv-website`에서 접속 가능

## 🔧 추가 기능 (향후 계획)

- [ ] 다국어 지원
- [ ] 연락처 폼 기능
- [ ] 블로그 섹션
- [ ] PWA (Progressive Web App) 지원
- [ ] 애니메이션 성능 최적화

## 📞 문의

프로젝트에 대한 질문이나 제안사항이 있으시면 언제든 연락주세요!

- 📧 이메일: sunghoon@email.com
- 💼 LinkedIn: [프로필 링크]
- 🐙 GitHub: [GitHub 프로필]

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 있습니다. 자유롭게 사용하고 수정해주세요.

---

⭐ 이 프로젝트가 도움이 되었다면 스타를 눌러주세요!