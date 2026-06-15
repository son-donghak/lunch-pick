# 🍱 오늘 점심 뭐 먹지?

직장인을 위한 점심 메뉴 추천 도구입니다. 설치·로그인·서버 없이 `index.html` 파일 하나로 동작합니다.

## 기능
- 🎲 오늘의 점심 메뉴 추천 (이모지 + 카테고리)
- 🔄 마음에 안 들면 다른 메뉴로 재추천
- ✅ 먹은 메뉴를 날짜별로 저장 (브라우저 localStorage, 서버 전송 없음)
- 🚫 최근 N일(기본 5일)간 먹은 메뉴는 추천에서 자동 제외 → 매일 다른 메뉴
- 🗺️ 추천 메뉴를 카카오맵·네이버지도·구글맵에서 내 위치 기준으로 바로 검색
- 📢 Google AdSense 광고 슬롯 준비됨

## 사용
`index.html`을 브라우저로 열면 끝입니다.

## 배포 (GitHub Pages)
1. 이 저장소를 GitHub에 push
2. 저장소 **Settings → Pages → Source: `main` 브랜치 / `/ (root)`** 선택
3. 잠시 후 `https://<사용자명>.github.io/<저장소명>/` 에서 접속

## Google AdSense 연동
1. https://adsense.google.com 에서 사이트 등록 후 승인
2. `index.html` 안의 `ca-pub-0000000000000000` 을 본인 게시자 ID로 교체
3. `<head>`의 주석 처리된 `<script>`와 광고 슬롯의 `<ins>` 블록 주석 해제
4. 광고 단위의 `data-ad-slot` 값 교체

> 애드센스는 공개된 실제 URL이 있어야 승인됩니다. GitHub Pages 주소로 신청 가능합니다.
