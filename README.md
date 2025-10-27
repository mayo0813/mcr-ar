# Evangelion AR Viewer 🤖

에반게리온 3D 모델을 WebAR로 볼 수 있는 페이지입니다.

## 📱 기능

- ✅ 브라우저에서 3D 모델 회전 및 확대/축소
- ✅ AR 모드 지원 (iOS/Android)
- ✅ 모바일 최적화
- ✅ 앱 설치 불필요

## 🚀 GitHub Pages 배포 방법

### 1. GitHub 저장소 생성
1. https://github.com 로그인
2. 우측 상단 "+" → "New repository" 클릭
3. Repository name: `evangelion-ar` (원하는 이름)
4. Public 선택
5. "Create repository" 클릭

### 2. 파일 업로드
저장소 페이지에서:
1. "uploading an existing file" 클릭
2. 다음 파일들을 드래그 앤 드롭:
   - `index.html`
   - `evangelion.glb`
   - `README.md` (선택사항)
3. "Commit changes" 클릭

### 3. GitHub Pages 활성화
1. 저장소 Settings 탭 클릭
2. 왼쪽 메뉴에서 "Pages" 클릭
3. Source: "Deploy from a branch" 선택
4. Branch: "main" 선택, 폴더: "/ (root)" 선택
5. "Save" 클릭
6. 약 1-2분 후 페이지 URL 생성됨
   - 형식: `https://[username].github.io/[repository-name]`

### 4. QR 코드 생성
1. 생성된 URL 복사
2. https://www.qr-code-generator.com 접속
3. URL 붙여넣기
4. QR 코드 다운로드

## 📱 사용 방법

### 웹 브라우저
- 마우스 드래그: 모델 회전
- 마우스 휠: 확대/축소
- 모바일: 터치로 회전, 핀치로 확대/축소

### AR 모드
- **Android**: Chrome 브라우저 → "AR로 보기" 버튼
- **iOS**: Safari 브라우저 → AR Quick Look

## 🛠 커스터마이징

`index.html` 파일을 수정하여:
- 색상 변경 (CSS gradient 부분)
- 모델 초기 위치/크기 조정 (camera-orbit)
- 자동 회전 속도 (rotation-per-second)
- 텍스트 및 스타일 변경

## 📝 라이선스

MIT License

## 💡 문제 해결

- **모델이 안 보여요**: GLB 파일명이 `evangelion.glb`인지 확인
- **AR 버튼이 안 눌려요**: HTTPS 환경에서만 작동 (GitHub Pages는 자동 HTTPS)
- **모델이 너무 커요/작아요**: `camera-orbit` 값 조정

---
Made with ❤️ using Model Viewer
