
## Ease of Use
This plugin was designed for note-takers to have a more productive Markdown and HTML editing workflow in Obsidian. The ZH-Enhanced-Editing plugin provides a multitude of auto-formatting and hotkeys for many syntax combos to speed up your writing and editing. When you use the ZH-Enhanced-Editing plugin, it will take your editing productivity to the next level(hopefully)! 

ZH 增强编辑插件为大量编辑动作组合提供了简单、快捷的操作。如果您需要在 Obsidian 中高频率地编辑和写作，ZH 增强编辑插件可以大幅提高您的 MD、HTML 语法编辑效率。增强编辑模式下的多项功能，如转换链接语法、转换文本（标题语法、高亮语法、着重语法、上下标语法、注释内容、代码块等）样式、粘贴excel表格、获取多种信息（笔记相对路径、标注或无语法文本等）、修复错误语法、添加或去除空行、追加或去除空格、去除断行、替换标点、转换中英标点、转换文件路径等。
## Demos and Tutorials

MD syntax formatting & text formatting

https://user-images.githubusercontent.com/75353922/154607370-ddbb6769-274a-435a-8ff4-d6c0cf653a00.mp4

Indentation for code block
![代码块中自动缩进](https://user-images.githubusercontent.com/75353922/154606695-dac97419-e5fa-4241-8c53-26cae665df67.gif)

Enhanced paste

https://user-images.githubusercontent.com/75353922/154606994-9ea137d5-b98e-4672-819a-4f87ee7e9613.mp4

Study cards

https://user-images.githubusercontent.com/75353922/154607209-dd443b24-3e6a-471c-889b-3e5bf650f747.mp4

Study cards with css

https://user-images.githubusercontent.com/75353922/154607301-e49f7a7b-5f27-45f5-a1d8-589e07554d68.mp4


Add and remove `[[]]` with hotkeys

![crtl-z1](https://user-images.githubusercontent.com/75353922/134824770-fbe84438-cca6-48a5-b378-ea96b4625b50.gif)

Add and remove multiple  `[[]]`

![crtl-z](https://user-images.githubusercontent.com/75353922/134824671-521d5554-30d7-42bc-bfd4-663a26c2a6a9.gif)




More Gif demos and video tutorials are coming in the future…
## Updates
#### Version 0.4.1 (updated on 2022-2-14)
        Add the function "Cursor Control by Keybroad: Alt+ I J K L U O" to control the cursor position in the editing area by using the main keyboard area.
        Enhance the function of "MD syntax formatting brush": When no text is selected, press Alt+C +G +S +U +N to turn on or off this function.

#### Version 0.4.0 (updated on 2022-2-13)
        Continue to streamline and optimize the js file code, please test it thoroughly, if you have any problems, please give us your feedback!
        Enhance "smart line feed" function
            Support pressing enter to add a line break in the body
            Support pressing enter in a list line to keep a normal line break
            Indentation effect after pressing enter in ``code block``.

        Enhance the function of "convert ungrammatical text", support removing the corresponding syntax characters after mouse click on the syntax part of the text.

#### Version 0.3.9 (updated on 2022-2-12)
        Streamline and optimize js file code
        Enhance the function of "Delete current paragraph Ctrl+D": if it is in [[]], it will delete the link content first, and when it meets the ordered list item, it will reduce the order number normally.

#### Version 0.3.8 (updated on 2022-1-23)
        Improve "Smart Symbol Alt+;" function, convert Dataview (dv), Query (qy), Mermaid (mm), js, ja, py, css and other words to ```block`` syntax.
        Improve "fix accidental line break" function, remove extra spaces at the end of lines
        Fix "insert empty line above, insert empty line below" function.

#### Version 0.3.7 (updated on 2022-1-18)
        Support selecting the text of the paragraph where the cursor is located
        Support selecting the text of the whole sentence where the cursor is located
        Support converting the selected text to Anki digging effect
        Improve the function of embedding the current URL page, support the automatic processing of Tencent, B station and oil pipe video URLs

#### Version 0.3.6 (updated on 2022-1-13)
        No longer specify shortcut keys for low-frequency operation functions
        One-click designation as the file name of the current note is available after crossing out the text.
            Note: Automatic global modification is not available for now. Only recommended when creating new documents.

        One-click embedding of the current URL page into the note after selecting the URL.

#### Version 0.3.5 (updated on 2022-1-2)
        Smart Symbols: automatically convert, match, or skip bracket symbols, shortcut Alt+;
            Enter [(or [(then press the shortcut key to convert to 〖)
            Press the shortcut key after 〖Enter Text| to match 〗
            Press the shortcut key at the cursor of "Enter Text|" to skip the symbols
	    
## Features
 
-  Alt+Z
	 - [Add or remove MD/Wiki Link]　Add or remove `[[link]]` symbols at both ends of the selected text. Also support the conversion of multi-line or multi-sentence titles and texts separated by Newline character \n or Comma to MD/Wiki Link.
	 - 【转换内链语法】　在选文两端添加或去除` [[链接]] `符号。支持转换由换行符\n 或顿号、分隔的多行或多句标题文本为内链语法。
- Ctrl+ 1-6:
	- [Convert heading level]　Specify or cancel the current line of text as an N-level heading
	- 【转换标题语法】　指定或取消当前行文本为 N 级标题
 - Alt+G
	- [Add or remove highlighting]　Add or remove` ==highlight== `symbol at both ends of the selected text
	 - 【转换高亮语法】　在选文两端添加或去除` ==高亮== `符号
 - Alt+ ` 
	 - 【Add or remove inline code】　Add or remove the symbol of `` `inline code` `` at both ends of the selected text
	 - 【转换行内代码】　在选文两端添加或去除  `` `行内代码` `` 符号
 - Ctrl+Shift+M
	- [Add or remove code block] 　Add or remove the symbol of `` ```code block``` `` at both ends of the selected text
	-  【转换代码块】　在选文两端添加或去除 `` ```代码块``` `` 符号	
- Auto-pairing
	- [Convert superscript] 　Add or remove the` <sup>superscript</sup> `syntax at both ends of the selected text
	- 【转换上标】　在选文两端添加或去除` <sup>上标</sup> `语法
	- 【Conversion subscript】　Add or remove the` <sub>subscript</sub>` syntax at both ends of the selected text
	- 【转换下标】　在选文两端添加或去除 `<sub>下标</sub>` 语法
	- 【Selected texts】　Add or remove 【】symbols at both ends of the selected texts
	- 【选文】　在选文两端添加或去除 【】符号
	- (Selected text) 　Add or remove the () symbol at both ends of the selected text 
	- （选文）　在选文两端添加或去除 （）符号
	- 「Selected text」 　Add or remove the「 」 symbol at both ends of the selected text
	- 「选文」　在选文两端添加或去除 「」符号
	- 《Selected text》 　Add or remove the《》 symbol at both ends of the selected text
	- 《选文》在选文两端添加或去除《》符号
- Ctrl+Shift+Alt+Z
	- [English to Chinese punctuation]　 Convert English punctuation to Chinese punctuation, such as,.?!" etc
	- 【英转中文标点】　将笔记中的英文标点转换为中文标点，如,.?!"
- Ctrl+Shift+Alt+Y
	- [Transfer English punctuation] 　 Convert Chinese punctuation to English punctuation, such as. ? ! " etc
	- 【中转英文标点】　将笔记中的中文标点转换为英文标点，如，。？！“等
- Shift+Alt+F
	- [ Path conversion]　 convert` c:\\windows `and` [](file:///c:\/windows) `path syntax to each other 
	- 【转换路径语法】　将 `c:\\windows` 与` [](file:///c:\/windows) `路径语法相互转换
- Select and Convert
	- [Simplified to Traditional] 　 Convert simplified Chinese characters to traditional Chinese characters
	- 【简体转为繁体】　将笔记中的简体汉字转换为繁体汉字
	- [Traditional to Simplified] 　 Convert the traditional Chinese characters to simplified Chinese characters
	- 【繁体转为简体】　将笔记中的繁体汉字转换为简体汉字 
- Ctrl+Alt+V
	- [Paste MD table]　 directly paste the copied Office Excel table into MarkDown table
	- 【粘贴 MD 表格】　将复制的 Office 表格直接粘贴为 MarkDown 语法表格
- Ctrl+Shift+J
	-  [Fix wrong syntax]　Fix the wrong MD syntax in the notes, such as 1. List,` [] () `link, `[[]]() `backlinks, etc. 
	-  【修复错误语法】　修复笔记中的错误 MD 语法，如 1。列表、【】（）链接、`[[]]() `回链等
- Ctrl+Alt+D
	- [Fix unexpected line breaks]　Fix unexpected line break (delete line breaks at the end that are not punctuation such as sentence, question, exclamation mark)
	- 【修复意外断行】　修复笔记中的意外断行（删除结尾不是句、问、叹号等标点的换行符）
- Select and Search
	- 【Search the current text】　Search the selected content in the current document on the search panel.
	- 【搜索当前文本】　通过搜索面板在当前文档中搜索划选内容。
- Ctrl+Shift+T
	- [Get time information]　Get the time information in the current line, and control the video in the linked note to jump and play
	- 【获取时间信息】　获取当前行中的时间信息，并控制链接笔记中的视频进行跳转播放
- Ctrl+Shift+B
	- [Get labeled text] 　 get title, highlight, comment and paragraph prefix (#label, comment, reflection, remark) and other text content
	- 【获取标注文本】　获取标题、高亮、注释及段落前缀（#标注、批注、反思、备注）等文本内容
- Ctrl+Alt+C
	- 【Get text without syntax】　Get the selected text after removing markdown syntax characters
	- 【获取无语法文本】　获取去除 markdown 语法字符后的选文
- Select and Convert
	- 【Get relative path】　Get the relative path of the current note in the library directory.
	- 【获取相对路径】　获取当前笔记在库目录内的相对路径
- Ctrl+Shift+L
	- 【Batch insert blank lines】　Insert blank lines in the middle of the selected text line or the full text
	- 【批量插入空行L】　在划选的文本行或全文中间批量插入空白行
	- 【Batch removal of blank lines】　Batch removal of blank lines in selected text or full text
	- 【批量去除空行】　批量去除划选文本或全文中的空白行
- Ctrl+Shift+K
	- 【Add space at the end】　Add two spaces at the end of each text line to have a line break effect in preview mode
	- 【末尾追加空格】　在每个文本行的末尾追加两个空格，以在预览模式时具有换行效果
	- [Remove trailing spaces]　Remove the space characters at the end of each text line in batches
	- 【去除末尾空格】　批量去除每个文本行末尾的空格字符
- Select and Convert
	- 【Add Chinese-English Space】　Add spaces in batches between Chinese characters and letters in the text, such as china China.
	- 【添加中英间隔】　在正文的汉字与字母之间批量添加空格，如 china 中国
	- [Remove all spaces] 　Remove all full and half-width spaces in the text
	- 【去除所有空格】　去除正文中所有的全、半角空格


## Installation
1. Download the [latest release](https://github.com/shaggyfeng/Obsidian-ZH-Enhanced-editing/releases)
1. Extract the folder from the zip to your vault's plugins folder: `<vault>/.obsidian/plugins/`  
Note: On some machines, the `.obsidian` folder may be hidden. On MacOS you should be able to press `Command+Shift+Dot` to show the folder in Finder.
1. Reload Obsidian
1. If prompted about Safe Mode, you can disable safe mode and enable the plugin.
## Old Changelog
```
2021-09-26
Updated readme.md in English 
```
``` 
2021-09-22
Added the following Hotkeys:
【转换内链语法　　Alt+Z】　在选文两端添加或去除 [[链接]] 符号
　支持转换由换行符\n 或顿号、分隔的多行或多句标题文本为内链语法。

增强编辑模式中的【功能　　快捷键】　说明......')
【转换标题语法　　Ctrl+ 1-6】　指定或取消当前行文本为N级标题
【转换高亮语法　　Alt+G】　在选文两端添加或去除 ==高亮== 符号
【转换行内代码　　Alt+`】　在选文两端添加或去除 `行内代码` 符号
【转换代码块　　Ctrl+Shift+M】　在选文两端添加或去除 ```代码块```符号
【转换上标】　在选文两端添加或去除 <sup>上标</sup> 语法
【转换下标】　在选文两端添加或去除 <sub>下标</sub> 语法
【选文】　在选文两端添加或去除 【】符号
（选文）　在选文两端添加或去除 （）符号
「选文」　在选文两端添加或去除 「」符号
《选文》　在选文两端添加或去除 《》符号
【英转中文标点　　Ctrl+Shift+Alt+Z】　将笔记中的英文标点转换为中文标点，如,.?!"等
【中转英文标点　　Ctrl+Shift+Alt+Y】　将笔记中的中文标点转换为英文标点，如，。？！“等
【转换路径语法　　Shift+Alt+F】　将 c:\\windows 与 [](file:///c:\/windows) 路径语法相互转换
【简体转为繁体】　将笔记中的简体汉字转换为繁体汉字
【繁体转为简体】　将笔记中的繁体汉字转换为简体汉字
【粘贴MD表格　　Ctrl+Alt+V】　将复制的Office表格直接粘贴为MarkDown语法表格
【修复错误语法　　Ctrl+Shift+J】　修复笔记中的错误MD语法，如1。列表、【】（）链接、[[]]()回链等
【修复意外断行　　Ctrl+Alt+D】　修复笔记中的意外断行（删除结尾不是句、问、叹号等标点的换行符）
【搜索当前文本】　通过搜索面板在当前文档中搜索划选内容。
【获取时间信息　　Ctrl+Shift+T】　获取当前行中的时间信息，并控制链接笔记中的视频进行跳转播放
【获取标注文本　　Ctrl+Shift+B】　获取标题、高亮、注释及段落前缀（#标注、批注、反思、备注）等文本内容
【获取无语法文本　　Ctrl+Alt+C】　获取去除markdown语法字符后的选文
【获取相对路径】　获取当前笔记在库目录内的相对路径。
【批量插入空行　　Ctrl+Shift+L】　在划选的文本行或全文中间批量插入空白行
【批量去除空行　　Ctrl+Alt+L】　批量去除划选文本或全文中的空白行
【末尾追加空格　　Ctrl+Shift+K】　在每个文本行的末尾追加两个空格，以在预览模式时具有换行效果
【去除末尾空格　　Ctrl+Alt+K】　批量去除每个文本行末尾的空格字符
【添加中英间隔】　在正文的汉字与字母之间批量添加空格，如 china 中国。
【去除所有空格】　去除正文中所有的全、半角空格
```
## Checklist
- [x] Translate plugin’s settings
- [x] keep updating new features
- [x] Translate Readme from chinese to English
- [x] Add options to change hotkeys mapping
- [ ] Add options to enable and disable hotkeys
- [ ] Be on the community plugin page within Obsidian the APP

## About
Silkworm ([蚕子](https://jq.qq.com/?_wv=1027&k=hgkmKRoE)) is the actual developer of this plugin. However, it is not convenient for him to look after the plugin outside the Obsidian's [Chinese community](https://mubu.com/doc/1BMHfhwEQ2G). Therefore, I (Shaggy Feng, also known as, Mouth on Cloud) am the “corresponding developer” who is maintaining this plugin here on Github. 
## Support
If Silkworm（蚕子）wants to have a cup of coffee once a while, I might be able to set up a support page for him (me). 

- You can support this plugin by
	- [buy me a coffee](https://www.buymeacoffee.com/jVX2kezGxH/support-zh-enhanced-editing-plugin)
	- [patreon](https://patreon.com/user?u=69756148)
	- 微信支付WeChat ![微信支付WeChat](https://user-images.githubusercontent.com/75353922/154621909-41ab2146-b71c-4a16-a818-0a7c646336b8.JPG)


Thank you for your ❤️️ and support!
