# 레코체

[배포처 바로가기](https://recipekorea.com/bbs/board.php?bo_table=ld_0308&wr_id=2479)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Recipekorea`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Recipekorea/Recipekorea.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Recipekorea/Recipekorea.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Recipekorea';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Recipekorea/Recipekorea.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Recipekorea/Recipekorea.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Recipekorea/Recipekorea.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Recipekorea/Recipekorea.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Recipekorea/subsets/Recipekorea-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Recipekorea/subsets/Recipekorea-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Recipekorea", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
사용범위 : 개인/상업적 용도 사용가능 
 
저작권자 : 레시피코리아 
 
사용규정 : 게임/유료 소프트웨어 사용시 
*글꼴 출처 표기시 사용가능 
 
 
레코체 파일을 자신의 홈페이지/블로그 등에 올려두고 판매하고싶다 
* 불가능/폰트자체를 거래하는 행위는 어떤 방식으로도 불가함
```
