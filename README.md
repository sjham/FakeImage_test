# AI Image Fake Detector Interactive Page

이 프로젝트는 뉴욕타임스 스타일의 '스크롤링 인터랙티브(Scrollytelling)' 웹페이지입니다.
복잡한 설정 없이 **GitHub Pages**를 통해 즉시 완전 자동 배포되도록 만들어졌습니다.

## 🚀 3분 만에 무료 배포하는 방법

1. **GitHub Repository 생성**
   - GitHub에 로그인하고 새로운 Repository를 만듭니다 (Public 추천).

2. **파일 업로드**
   - 압축을 푼 뒤, 폴더 안의 **모든 파일과 폴더**를 생성한 Repository에 업로드(Push)합니다.
   - ⚠️ 주의: 톱니바퀴 아이콘이 있는 `.github` 폴더(숨김 폴더일 수 있음)가 누락되지 않도록 꼭 함께 업로드하세요!

3. **GitHub Pages 설정 (클릭 3번)**
   - Repository 상단의 **[Settings]** 탭으로 이동합니다.
   - 왼쪽 메뉴에서 **[Pages]**를 클릭합니다.
   - **Build and deployment** 섹션의 **Source** 드롭다운에서 `GitHub Actions`를 선택합니다.

🎉 **끝입니다!** 
약 1분 뒤 상단의 [Actions] 탭에서 초록색 체크마크가 뜨면, `https://[본인아이디].github.io/[저장소이름]` 주소로 인터랙티브 페이지에 접속할 수 있습니다.

---

## ✏️ 내가 만든 이미지로 교체하는 방법
현재 `index.html` 내에는 고화질 임시(Placeholder) 이미지가 삽입되어 있습니다.

1. `index.html` 파일을 엽니다.
2. 약 108번째 줄에 있는 아래 코드를 찾습니다.
   ```html
   <img id="ai-image" src="https://images.unsplash.com/photo-..." alt="...">
   ```
3. `src="..."` 안의 주소를 직접 생성하신 AI 이미지 URL이나, 같이 업로드한 이미지 파일 경로(예: `./my-fake-image.jpg`)로 변경하고 저장(Commit)하면 끝입니다!
