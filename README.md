# CV website

GitHub Pages에서 바로 호스팅할 수 있는 정적 CV 사이트입니다. 빌드 도구가 필요하지 않습니다.

## 내용 수정

`index.html`의 `Your Name`, 소개, 경력, 프로젝트, 학력, 연락처 문구를 실제 내용으로 바꿔 주세요. 경력과 프로젝트는 `<article>` 블록을 복사하거나 삭제해 개수를 맞출 수 있습니다. 색상과 간격은 `styles.css`의 `:root` 변수에서 조정할 수 있습니다. 페이지에 보이는 모든 문구는 영어로 작성되어 있습니다.

## GitHub Pages 배포

1. 개인 계정 `1nteger-c`로 로그인합니다.
2. 새 저장소의 **Owner**를 `1nteger-c`로 선택하고, 저장소 이름을 정확히 `1nteger-c.github.io`로 지정합니다. 빈 저장소로 만들면 현재 폴더의 파일을 올리기 쉽습니다.
3. 이 폴더의 파일들을 저장소 기본 브랜치의 최상위 폴더에 올립니다.
4. 저장소의 **Settings → Pages → Build and deployment**에서 **Deploy from a branch**를 선택합니다.
5. 기본 브랜치와 **/(root)**를 선택하고 저장합니다. 게시 주소는 `https://1nteger-c.github.io/`입니다.

모든 파일 참조는 상대 경로이므로 사용자 사이트에서 그대로 동작합니다. 나중에 별도 도메인을 구입하면 GitHub Pages의 커스텀 도메인 설정으로 연결할 수 있습니다.
