# TheDesignUncle Admin Dashboard

관리자 전용 링크 대시보드입니다.

## GitHub 업로드 파일

아래 파일과 폴더를 함께 올리면 됩니다.

- `index.html`
- `admin-dashboard.html`
- `assets/`

## 링크 수정 위치

`index.html` 또는 `admin-dashboard.html` 하단의 `adminLinks` 배열에서 각 버튼의 `url` 값을 실제 주소로 바꾸면 됩니다.

```javascript
url: "https://example.com"
```

## GitHub Pages

GitHub Pages로 공개할 경우 `index.html`이 자동으로 첫 화면으로 열립니다.

## GitHub Pages 설정 순서

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더 안의 파일들을 저장소 최상위에 업로드합니다.
3. 저장소 화면에서 `Settings`로 이동합니다.
4. 왼쪽 메뉴에서 `Pages`를 선택합니다.
5. `Build and deployment` 항목에서 `Deploy from a branch`를 선택합니다.
6. Branch는 `main`, 폴더는 `/root`를 선택하고 저장합니다.
7. 잠시 후 표시되는 GitHub Pages 주소로 접속합니다.

## 꼭 같이 올릴 파일

`assets/typelogo-white.png`가 빠지면 상단 로고가 보이지 않습니다.
