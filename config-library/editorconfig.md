# editorconfig 文件

## 新建

找个编辑器新建就可以，测试（vscode， webstrom即可）

## 介绍



## 基本配置

indent_style: 
设置缩进风格，tab或者空格。tab是hard tabs，space为soft tabs。

indent_size: 缩进的大小（单行间距），即列数，整数。如果indent_style为tab，则此属性默认为tab_width。

tab_width: 设置tab的列数。默认是indent_size。

end_of_line： 换行符，lf、cr和crlf

charset： 编码，latin1、utf-8、utf-8-bom、utf-16be和utf-16le，不建议使用utf-8-bom。

rim_trailing_whitespace： 设为true表示会除去换行行首的任意空白字符。

insert_final_newline: 设为true表明使文件以一个空白行结尾

root: 表明是最顶层的配置文件，发现设为true时，才会停止查找.editorconfig文件。

## 文档

官方文档：<https://github.com/editorconfig/editorconfig/wiki/EditorConfig-Properties>