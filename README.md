###CN
normalize.css是一个可定制的CSS文件，使浏览器渲染所有 元素始终与现代接轨。

依托项目研究为默认浏览器 风格之间的差异来精确的目标只需要从 规范效益的方式。

查看测试文件

安装
* [npm](http://npmjs.org/): `npm install --save normalize.css`
* [cdnjs](https://cdnjs.com/libraries/normalize/)
* [Download](http://necolas.github.io/normalize.css/latest/normalize.css).
新公共管理：安装，节省normalize.css NPM
CDNJS
下载。
不应该在normalize.css其他样式。

建议包括normalize.css文件为未开发的 库代码。

它是做什么的？

保留有用的默认值，不像许多CSS重置。
规范风格的宽范围的元素。
纠正错误和常见的浏览器的不一致。
提高了细微的改进，可用性。
解释了什么是代码并使用详细的评论。
浏览器支持

铬（最新）
边缘（最新）
Firefox（最新）
火狐ESR
Internet Explorer 8
歌剧（最新）
Safari 6
normalize.css V1提供传统的浏览器 支持（6，Safari 4）， 但不再积极。

扩展的细节

额外的细节和normalize.css深奥的部分解释。

预编码，大骨节病，桑普，

这个等宽，等宽字体：黑客将继承和缩放 字体大小为预格式化文本。重复等宽是 故意。来源。

子，支持

通常，使用子或啜饮对所有 浏览器文本的线框的高度。来源。

SVG：不（：根）

添加溢出：隐藏修复了IE9的SVG渲染。早期版本的IE 不支持SVG的，所以我们可以放心的使用：not()和root选择器，使用默认的样式表 UA浏览器应用此样式。SVG 邮件列表的讨论

input[type="search"]

搜索输入默认是不完全可设置样式。在Chrome和Safari上 OSX/iOS你不能控制字体，填充，边境，或背景。在 Chrome和Safari在Windows你不能控制边境正确。它将边框宽度但只显示一个边框颜色（不能控制） 1px，外。应用WebKit的外观：文本框针对这些问题，不排除搜索输入的好处（例如 显示过去的搜索）。

Legend

添加边框：0修正IE 8–11臭虫颜色（是的，颜色）不 继承Legend。

贡献

请阅读贡献原则。

致谢

normalize.css是一个项目尼古拉斯加拉赫 共同创造，乔纳森尼尔。
###EN
# normalize.css v3

Normalize.css is a customisable CSS file that makes browsers render all
elements more consistently and in line with modern standards.

The project relies on researching the differences between default browser
styles in order to precisely target only the styles that need or benefit from
normalizing.

[View the test file](http://necolas.github.io/normalize.css/latest/test.html)

## Install

* [npm](http://npmjs.org/): `npm install --save normalize.css`
* [cdnjs](https://cdnjs.com/libraries/normalize/)
* [Download](http://necolas.github.io/normalize.css/latest/normalize.css).

No other styles should come before Normalize.css.

It is recommended that you include the `normalize.css` file as untouched
library code.

## What does it do?

* Preserves useful defaults, unlike many CSS resets.
* Normalizes styles for a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Improves usability with subtle improvements.
* Explains what code does using detailed comments.

## Browser support

* Chrome (latest)
* Edge (latest)
* Firefox (latest)
* Firefox ESR
* Internet Explorer 8+
* Opera (latest)
* Safari 6+

[Normalize.css v1 provides legacy browser
support](https://github.com/necolas/normalize.css/tree/v1) (IE 6+, Safari 4+),
but is no longer actively developed.

## Extended details

Additional detail and explanation of the esoteric parts of normalize.css.

#### `pre, code, kbd, samp`

The `font-family: monospace, monospace` hack fixes the inheritance and scaling
of font-size for preformatted text. The duplication of `monospace` is
intentional.  [Source](http://en.wikipedia.org/wiki/User:Davidgothberg/Test59).

#### `sub, sup`

Normally, using `sub` or `sup` affects the line-box height of text in all
browsers. [Source](http://gist.github.com/413930).

#### `svg:not(:root)`

Adding `overflow: hidden` fixes IE9's SVG rendering. Earlier versions of IE
don't support SVG, so we can safely use the `:not()` and `:root` selectors that
modern browsers use in the default UA stylesheets to apply this style. [SVG
Mailing List discussion](http://lists.w3.org/Archives/Public/public-svg-wg/2008JulSep/0339.html)

#### `input[type="search"]`

The search input is not fully stylable by default. In Chrome and Safari on
OSX/iOS you can't control `font`, `padding`, `border`, or `background`. In
Chrome and Safari on Windows you can't control `border` properly. It will apply
`border-width` but will only show a border color (which cannot be controlled)
for the outer 1px of that border. Applying `-webkit-appearance: textfield`
addresses these issues without removing the benefits of search inputs (e.g.
showing past searches).

#### `legend`

Adding `border: 0` corrects an IE 8–11 bug where `color` (yes, `color`) is not
inherited by `legend`.

## Contributing

Please read the [contribution guidelines](CONTRIBUTING.md).

## Acknowledgements

Normalize.css is a project by [Nicolas Gallagher](https://github.com/necolas),
co-created with [Jonathan Neal](https://github.com/jonathantneal).
