# font-test

> 问题说明
* 英文字体转换没有问题
* 中文字体转换时无明确报错
```
    Mac:test Origin$ font-spider index.html
    Loading ...not support cmap format:2
    not support cmap format:2
    Font family: font_test
    Original size: 4911.362 KB
    Include chars:  AHPSaeorsy“”不世个为么也人什他以们会但你信假做别又可后呢在坛多她好如子它定就己希式微志怎懂成我方是有望杂来果样永然界的相看能自表被解论设评读达远都里长面，／：？
    Chars length: 87
    Font id: c0acb983a986a9483f6b38247bbd83df
    CSS selectors: .font-test
    Font files:
    File font/font_test.eot created: 2.76 KB
    File font/font_test.woff2 created: 1.568 KB
    File font/font_test.woff created: 2.736 KB
    File font/font_test.ttf created: 2.66 KB
    File font/font_test.svg created: 5.057 KB

```
* 对比转换英文字体的CLI,多了如下提示
```
    Loading ...not support cmap format:2
        not support cmap format:2
```

