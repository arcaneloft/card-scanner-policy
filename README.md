# 명함 스캐너 — 개인정보처리방침

Google Play / AdMob 에 등록하는 개인정보처리방침 문서만 담은 저장소다.
앱 소스는 별도의 비공개 저장소에 있다.

**게시 주소:** https://kimusani.github.io/card-scanner-policy/

## 고칠 때

`index.html` 을 고쳐서 푸시하면 GitHub Pages 가 몇 분 안에 반영한다.

앱 동작이 바뀌면 반드시 같이 고칠 것 — 특히 아래 셋은 방침과 Play 데이터 안전 양식을
동시에 바꿔야 한다.

- 광고를 켜거나 끌 때 (7항)
- 결제를 붙일 때 (8항)
- 서버로 무언가를 보내기 시작할 때 (1·4항)

## 검색엔진에 안 잡히게

`index.html` 의 `<meta name="robots" content="noindex, nofollow">` 로 색인을 막는다.

**`robots.txt` 로 크롤링을 막지 말 것.** 크롤러가 페이지를 못 읽으면 noindex 태그도 못
읽어서, 링크만 보고 URL 을 색인해 버리는 일이 생긴다. 읽게 두고 색인만 막는 게 맞다.

이 저장소에 페이지를 더 올릴 때도 같은 두 줄을 넣는다.
