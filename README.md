<div align="center">
    <h1>DocsifyScrollToTop</h1>
    <div>基于Docsify的页面滚动回顶部的插件</div>
    <br/>
    <img width=700 src="./snapshot.png" alt="效果图" />
</div>


### 特性
- 🎉 支持自动显示隐藏，靠近顶部时则隐藏按钮
- 🎉 支持平滑滚动，不依赖jquery等别的插件
- 🎉 支持修改文本
- 🎉 支持调整位置


### 使用
1. 在 index.html 中引入脚本
```html
<script src="//unpkg.com/docsify-scroll-to-top/dist/docsify-scroll-to-top.min.js"></script>
```

2. 配置插件（可选）
```js
window.$docsify = {
    // ...
    scrollToTop: {
        auto: true,
        text: 'Top',
        right: 15,
        bottom: 15,
        offset: 500
    }
};
```


### 配置项
scrollToTop.auto
* 默认: true
* 类型: Boolean
* 描述: 是否自动隐藏按钮

scrollToTop.text
* 默认: Top
* 类型: String
* 描述: 按钮文字

scrollToTop.right
* 默认: 15
* 类型: Number
* 描述: 按钮距离窗口右侧距离

scrollToTop.bottom
* 默认: 15
* 类型: Number
* 描述: 按钮距离窗口底部距离

scrollToTop.offset
* 默认: 500
* 类型: Number
* 描述: 页面滚动多少距离后显示按钮，当auto配置为true时才有效果


### 相关链接
[Docsify](https://github.com/docsifyjs/docsify/)


### LICENSE
MIT
