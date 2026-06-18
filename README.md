# Artist Home Demo

GitHub Pages에 올리기 위한 정적 홈페이지 파일입니다.

## 들어있는 파일

- `index.html`: 홈페이지 본문, 스타일, 재생/구매 테스트 스크립트
- `album-visual.svg`: 첫 화면 이미지

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

같은 폴더에 `music` 폴더를 만들고 MP3 파일을 넣은 뒤, `index.html`의 오디오 부분을 실제 파일 주소로 연결하면 됩니다.

예:

```html
<audio controls src="music/my-demo.mp3"></audio>
```

## 현재 상태

현재 버전은 무료 감상, 로컬 음원 선택, 후원/구매 테스트 버튼까지 동작하는 데모입니다. 실제 카드 결제는 아직 연결되어 있지 않습니다.
