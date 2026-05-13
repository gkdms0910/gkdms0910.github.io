# 주섬주섬 앱 사이트 배포 체크리스트

이 폴더는 AdMob `app-ads.txt` 인증과 App Store Connect 지원 URL/개인정보 처리방침 URL에 사용할 수 있는 정적 사이트입니다.

## 포함 파일

- `index.html`: 앱 소개 페이지
- `support.html`: 지원 URL
- `privacy.html`: 개인정보 처리방침 URL
- `app-ads.txt`: AdMob 판매자 인증 파일

## 배포 후 반드시 확인할 URL

브라우저에서 아래 경로가 HTML이 아니라 텍스트 한 줄로 보여야 합니다.

```txt
https://배포도메인/app-ads.txt
```

정확한 내용:

```txt
google.com, pub-8339330183989965, DIRECT, f08c47fec0942fa0
```

## App Store Connect 입력값

- 지원 URL: `https://배포도메인/support.html`
- 개인정보 처리방침 URL: `https://배포도메인/privacy.html`
- 마케팅 URL: `https://배포도메인/`

## AdMob에서 할 일

1. App Store Connect에 위 URL을 저장합니다.
2. AdMob의 앱 인증 화면에서 `업데이트 확인`을 누릅니다.
3. `app-ads.txt` 크롤링은 바로 반영되지 않을 수 있으므로 보통 하루 정도 기다립니다.
