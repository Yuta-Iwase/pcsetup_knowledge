# カスタムCSS集

カスタムCSSはChrome拡張の[Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)によって導入できます。

## Google検索の「他の人はこちらも検索」を出さなくさせる
サイト更新により度々効かなくなる  
2022/02 更新
```css
#rso div[style="flex-shrink:0"] > div:nth-child(3){
    display: none !important;
}
```

