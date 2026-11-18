# 대학생 쇼핑 습관 및 소비 선호도 설문조사

한국어 설문조사 웹사이트입니다.

## 웹사이트 배포
저장소의 `.github/workflows/pages.yml` 워크플로가 `main` 브랜치에 변경 사항이 push될 때 GitHub Pages에 자동 배포합니다.

최초 배포 전에 저장소의 **Settings → Pages → Build and deployment → Source**에서 **GitHub Actions**를 선택해 주세요. 이후 **Actions** 탭에서 배포 작업이 완료되면 사이트 주소를 확인할 수 있습니다.

## 실제 응답 수집 설정
GitHub Pages는 정적 호스팅이므로 설문 응답을 자체 저장하지 않습니다. 현재 제출 URL은 설정되어 있지 않으며, 제출 버튼은 응답이 저장된 것처럼 표시하지 않습니다.

응답 수집을 위해 Formspree 등 폼 수집 서비스를 설정한 뒤 `index.html` 스크립트의 `FORM_ENDPOINT` 값에 발급받은 URL을 입력하고 커밋해야 합니다.

이름과 의견은 선택 항목입니다. 개인정보 보호를 위해 실명 대신 별칭을 사용하거나 이름을 비워 둘 수 있습니다.
