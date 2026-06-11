# 学习MarkDown格式搜集的资料
# stuff about MarkDown 
---
__Advertisement :)__

- __[pica](https://nodeca.github.io/pica/demo/)__ - high quality and fast image
  resize in browser.
- __[babelfish](https://github.com/nodeca/babelfish/)__ - developer friendly
  i18n with plurals support and easy syntax.

You will like those projects!

---

# h1 Heading 8-)
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## 水平线

___

---

***


## 版式替换

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!
*** 
+ *列表开始*
  - 子列表
  - 演示字字列表
    * 子子列表  

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```
```c
int func(char* x)={
    return strlen(x);
}
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)


## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"

![百度例子](https://pics0.baidu.com/feed/aa18972bd40735fa9cd3d6868c2aa6bd0f240873.jpeg?token=e3d9d89608c5fba2eb2ddc2e2c409ada "演示啊")
## Plugins

The killer feature of `markdown-it` is very effective support of
[syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).


### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

> Classic markup: :wink: :cry: :laughing: :yum:
>
> Shortcuts (emoticons): :-) :-( 8-) ;)

8-) 
:-(
--- 
### Unicode Emoj
明白了，你是用于**技术文档、笔记、教程、报告**这类正式写作场景，不需要表情符号（🔥👍🎉❤️），而需要**标点、箭头、数学符号、逻辑符号、UI标识**等。

下面是 **10 个适合文档编写的常用 Unicode 符号**，附带可直接复制的 HTML 实体编码：

| 符号 | 含义 | 适用场景 | HTML实体编码（直接复制） |
| :---: | :--- | :--- | :--- |
| ✅ | 正确/完成 | 核对清单、测试通过、功能支持 | `&#x2705;` |
| ❌ | 错误/失败 | 测试失败、不支持的功能 | `&#x274C;` |
| ➜ | 右箭头（细） | 流程指向、菜单路径（如 设置 ➜ 高级） | `&#x279C;` |
| → | 右箭头（标准） | 逻辑推导、流程 | `&#x2192;` |
| • | 项目符号 | 替代 `-` 或 `*` 的无序列表 | `&#x2022;` |
| ✓ | 对勾（细体） | 正式文档中的复选框标记 | `&#x2713;` |
| ✗ | 叉号（细体） | 错误标记，比 ❌ 更正式 | `&#x2717;` |
| ① ② ③ | 带圈数字 | 步骤编号、优先级 | `&#x2460;` `&#x2461;` `&#x2462;` |
| ▶ | 右三角 | 折叠/展开、播放、下一步 | `&#x25B6;` |
| | 不间断空格 | 防止自动换行 | `&#xA0;` 或 `&nbsp;` |

> **特别推荐**：如果你写命令行帮助或技术表格，`✓` 和 `✗` 比 Emoji 版的 ✅ ❌ 更干净、不干扰行高。

**补充一个实用的组合（不是表情符）**

| 符号 | 含义 | 编码 |
| :---: | :--- | :--- |
| ⌘ | 命令键（苹果） | `&#x2318;` |
| ⌥ | 选项键 | `&#x2325;` |
| ⌃ | 控制键 | `&#x2303;` |
| ⇧ | 上档键 | `&#x21E7;` |
| ⌫ | 删除键 | `&#x232B;` |

这些在写软件操作说明（Mac 用户）时非常有用，而且完全是纯文本符号，不是图片。

你可以直接复制 `&#xxxx;` 这一段到 Markdown 源码里使用。如果需要其他特定符号（比如数学上的 ∀ ∃ ∈、表格用的 ─ │ ┼、或者度量单位 µ Ω 等），告诉我你的文档领域，我可以再列一批。

>
see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.

    "块，可以用tab开始，自动强调成块区"

### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

- 19^th^
- H~2~O


### [\<ins>](https://github.com/markdown-it/markdown-it-ins)

++Inserted text++


### [\<mark>](https://github.com/markdown-it/markdown-it-mark)

==Marked text==


### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.


### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)

Term 1

:   Definition 1
with lazy continuation.

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

~ Third paragraph of definition 2.

_Compact style:_

Term 1
  ~ Definition 1

Term 2
  ~ Definition 2a
  ~ Definition 2b


### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning
*here be dragons*
:::
