PC用に
```html
<!-- viewportを読み込むための<meta>タグを記述してください -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="responsive.css" />
<link href="wide.css" rel="stylesheet" media="screen and (min-width: 768px)">
```
```css
/* ------------------------------------ */
/* ▼PC用デザインとして付け足すデザイン */
/* ------------------------------------ */
@media (min-width: 1024px) {
}
  
  /* -------------------------------------------- */
  /* ▼タブレット用デザインとして付け足すデザイン */
  /* -------------------------------------------- */
@media (min-width: 768px) {
}
```


スマートフォン向けサイトの作り方
```css
@media(max-width: 670px) {
  .item {
    width: 100%;
  }
}
```
