# 대화나눔 본문체

[배포처 바로가기](https://www.dhpharmfont.com/sansserif)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Daehwa Nanum`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Daehwa Nanum';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Light.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Light.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Light.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Light.ttf') format('truetype');
}
@font-face {
  font-family: 'Daehwa Nanum';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Regular.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Regular.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Regular.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Regular.ttf') format('truetype');
}
@font-face {
  font-family: 'Daehwa Nanum';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Bold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Bold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Bold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/DaehwaNanum/DaehwaNanum-Bold.ttf') format('truetype');
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Daehwa Nanum", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
대화나눔 본문체의 지적 재산권은 대화제약에 있습니다. 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 인쇄물, 웹사이트, 영상물, 포장지 등 다양한 영역에서사용할 수 있지만, 회사 로고에 사용하는 것을 제한합니다.
```
