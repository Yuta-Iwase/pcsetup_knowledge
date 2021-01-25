# カスタムCSS集

カスタムCSSはChrome拡張の[Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)によって導入できます。

## Google検索の「他の人はこちらも検索」を出さなくさせる
サイト更新により度々効かなくなる  
2021/01 更新
```css
html>body>div#main>div#cnt>div#rcnt>div>div#center_col>div#res>div#search>div>div>div>div>div>div:nth-child(3){
    display: none !important;
}
```

