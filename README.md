# Artist Home Demo

GitHub Pages에 올리기 위한 정적 홈페이지 파일입니다.

## 들어있는 파일

- `index.html`: 홈페이지 본문, 스타일, 재생/구매 테스트 스크립트
- `site-content.js`: 홈페이지 문구, 링크, 곡 정보를 담은 설정 파일
- `admin-local.html`: 내 컴퓨터에서 `site-content.js`를 쉽게 만드는 관리자 편집기
- `album-visual.svg`: 첫 화면 이미지
- `music/free.wav`: 무료 재생용 음악 파일 위치

## GitHub Pages에 올리는 순서

1. GitHub에서 새 저장소를 만듭니다.
2. 저장소 이름은 예를 들어 `artist-home`처럼 정합니다.
3. 이 폴더 안의 `index.html`, `album-visual.svg`, `README.md`를 업로드합니다.
4. 저장소의 `Settings`로 갑니다.
5. 왼쪽 메뉴에서 `Pages`를 엽니다.
6. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
7. Branch를 `main`, folder를 `/root`로 선택하고 저장합니다.
8. 잠시 기다리면 `https://사용자이름.github.io/저장소이름/` 주소가 생깁니다.

## 나중에 실제 음악 파일을 넣을 때

같은 폴더에 `music` 폴더를 만들고 WAV 파일을 넣으면 됩니다. 파일 이름은 아래처럼 맞춰주세요.

`music/free.wav`

현재 `index.html`은 무료 재생 버튼을 누르면 먼저 `music/free.wav`를 재생하도록 되어 있습니다. 파일이 아직 없으면 임시 데모 사운드를 재생합니다.

WAV 파일은 용량이 커질 수 있으니, 너무 길거나 큰 파일이면 나중에 MP3로 바꾸는 편이 좋습니다.

## 관리자 편집기 사용법

1. 내 컴퓨터에서 `admin-local.html`을 엽니다.
2. 사이트 이름, 첫 화면 문구, YouTube/Instagram 링크, 곡 정보를 수정합니다.
3. `site-content.js 저장` 버튼을 누릅니다.
4. 다운로드된 `site-content.js`를 GitHub 저장소에 다시 업로드합니다.
5. 잠시 기다리면 GitHub Pages 홈페이지에 반영됩니다.

주의: 이 관리자 편집기는 내 컴퓨터에서 쓰는 편집 도구입니다. GitHub Pages 자체에는 로그인 관리자 기능이 없으므로, 최종 반영은 GitHub에 `site-content.js`를 업로드해야 합니다.

## 현재 상태

현재 버전은 무료 감상, 로컬 음원 선택, 후원/구매 테스트 버튼까지 동작하는 데모입니다. 실제 카드 결제는 아직 연결되어 있지 않습니다.
