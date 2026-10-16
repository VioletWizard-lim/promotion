# 중등 승진 가산점 계산기 (인천)

인천광역시교육청 공고 제2026-319호(2026. 7. 24.) 「교육공무원승진규정 중 가산점 부여기준(중등)」을 바탕으로 한 간이 계산기입니다.

- `index.html` 하나로 동작합니다. 브라우저로 열거나 GitHub Pages로 게시하면 됩니다.
- 인사기록카드의 경력사항(학교·기간), 보직·담임 기간, 직무연수 학점, 상훈 등을 옮겨 적으면 공통·선택가산점을 항목·그룹 상한에 맞춰 계산합니다.
- 입력 내용은 사용자의 브라우저(localStorage)에만 저장되며 서버로 전송되지 않습니다.
- 공식 평정 결과가 아니며, 중복 경력은 경고만 표시합니다.

## GitHub Pages로 게시하기

`.github/workflows/pages.yml`이 `index.html`을 GitHub Pages에 자동 배포합니다. 처음 한 번만 설정하세요.

1. 저장소 **Settings → Pages → Build and deployment → Source**를 **GitHub Actions**로 바꿉니다.
2. **Actions** 탭에서 ‘GitHub Pages 배포’ 워크플로를 선택하고 **Run workflow**를 누릅니다. (이후에는 `main` 또는 현재 기본 브랜치에 푸시할 때마다 자동 배포됩니다.)
3. 배포가 끝나면 `https://violetwizard-lim.github.io/promotion/` 주소로 접속할 수 있습니다.

> 배포 환경(github-pages)은 기본적으로 저장소의 기본 브랜치에서만 배포를 허용합니다. 기본 브랜치를 `main`으로 바꾸면 워크플로도 그대로 동작합니다.
