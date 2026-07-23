# DayPixel 회사 및 서비스 사이트

DayPixel의 공식 회사 소개와 주섬주섬 서비스 지원을 제공하는 정적 사이트입니다.

## 포함 파일

- `index.html`: DayPixel 회사 및 서비스 소개
- `support.html`: 주섬주섬 고객지원
- `privacy.html`: 주섬주섬 개인정보 처리방침
- `styles.css`: 공통 디자인 시스템
- `app-ads.txt`: AdMob 판매자 인증 파일
- `robots.txt`, `sitemap.xml`: 검색 엔진 공개 설정

## 배포 후 반드시 확인할 URL

브라우저에서 아래 경로가 HTML이 아니라 텍스트 한 줄로 보여야 합니다.

```txt
https://daypixel.kr/app-ads.txt
```

정확한 내용:

```txt
google.com, pub-8339330183989965, DIRECT, f08c47fec0942fa0
```

## App Store Connect 입력값

- 지원 URL: `https://daypixel.kr/support.html`
- 개인정보 처리방침 URL: `https://daypixel.kr/privacy.html`
- 마케팅 URL: `https://daypixel.kr/`

## AdMob에서 할 일

1. App Store Connect에 위 URL을 저장합니다.
2. AdMob의 앱 인증 화면에서 `업데이트 확인`을 누릅니다.
3. `app-ads.txt` 크롤링은 바로 반영되지 않을 수 있으므로 보통 하루 정도 기다립니다.
