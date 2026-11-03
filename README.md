# 남훈 ♥ 예빈 모바일 청첩장

## GitHub Pages로 올리기
1. GitHub에서 새 저장소(public)를 만듭니다. 예: `wedding`
2. 이 폴더 안의 파일 전부(index.html, support.js, image-slot.js, assets/, .nojekyll)를 저장소 루트에 업로드합니다.
3. Settings → Pages → Branch: `main` / `/(root)` → Save
4. 1~2분 뒤 `https://<아이디>.github.io/wedding/` 에서 열립니다.

## 카카오톡 미리보기 설정
index.html 상단의 `https://YOUR-DOMAIN/` 두 곳을 실제 주소로 바꿉니다.
- og:image → `https://<아이디>.github.io/wedding/assets/og.jpg`
- og:url → `https://<아이디>.github.io/wedding/`

바꾼 뒤 https://developers.kakao.com/tool/clear/og 에서 주소를 넣고 캐시를 초기화하세요.

## 구성
- index.html — 청첩장 본문
- support.js, image-slot.js — 실행에 필요한 스크립트
- assets/ — 사진, 인트로 영상(intro.mp4), 배경음악(bgm.mp3), 카톡 미리보기 이미지(og.jpg)
