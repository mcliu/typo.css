## TYPO.CSS

目的: 在一致化浏览器排版效果的同时，构建最适合中文阅读的网页排版。

排版是一个麻烦的问题，需要精心设计，而这个设计却是常被视觉设计师所忽略的。前端工程师更常看到这样的问题，但不便变更。因为在多个 OS 中的不同浏览器渲染不同，改动需要多的时间做回归测试，所以改变变得更困难。而像我们一般使用的 Yahoo、Eric Meyer 和 Alice base.css 中采用的 Reset 都没有很好地考虑中文排版。TYPO.CSS 要做的就是解决中文排版的问题。

## TYPO.CSS 已经在如下浏览器测试通过：

- Mozilla Firefox
- Google Chome
- Opera
- IE 6/7/8/9
- iPhone

## API 简介

建议看源代码，特别是注释，需要认真看。`typo.css` 主要包括：

- 浏览器重设：包括HTML5
- 清除浮动：添加 class `.clearfix`
- 排版：添加 class `.typo`
- 增强类：
 - 专名号：`<u>` 标签或者 class `.type-unique`

## 开源许可

作者：[Sofish Lin](http://sofish.de)<br />
TYPO.CSS 基于 MIT License 开源，使用代码只需说明来源，或者引用 [license.txt](https://github.com/sofish/typo.css/blob/master/license.txt) 即可。
