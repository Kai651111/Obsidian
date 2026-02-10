---
tags:
---

# 1 快捷键与语法
## 1.1 Obsidian及其插件
 - `ctrl+P`：命令面板
 -  `ctrl+w`：编辑模式-阅读模式 切换
 - `ctrl+Tab`：增强编辑-当前行缩进
	- 命令也可以用。
	- 必须写好文字，再缩进。
- `Alt+滚轮`：缩放图片（Mousewheel Image zoom）
- `ctrl+shift+P`：添加breakpage （PDF breakpage），打印用
- Embed：`![Name](markdown address)`：前面的!决定是否Embed在页面上
## 1.2 Markdown
- `ctrl+shift+H`：高亮
-  `ctrl+shift+[`：无序列表
- `ctrl+shift+[`：有序列表
- `ctrl+q`：引用
- \`\`：行内代码 (英文模式下的~) 
- `shift+alt+K`：代码块
- `shift+alt+M`：公式块
- `alt+M`：行内公式块
- `windows+。`：EMOJI 的windows里。
## 1.3 Excalidraw
- `ctrl+e`：excalidraw - markdown切换
- `ctrl+‘`：excalidraw网格线显示
- `ctrl+上下左右`：excalidraw思维导图
- `ctrl+alt+C/V`：复制/粘贴样式
- `ctrl+shift+alt+M`：插入Latex块
- `ctrl+滚轮`：缩放
## 1.4 命令面板
- `左右分屏 split right`
- `ouline 大纲：显示大纲页面`
- `收集：Custom Attachment location`：收集整个库/当前文件夹中的附件。
	- **使用前一定要用git备份！！！！**
- `link converter`：md和wiki链接互转（用于改变md文档的绝对路径和相对路径）
- `Better Export PDF`：导出为PDF
- `Iconic 打开规则书`：为文件夹/ 文件设置icon
- `笔记属性`：打开笔记属性（可以添加tags标签）
	- 也可以显示所有标签，然后找到你想要的那个tag。
- `书签`：添加书签（块、页、标题……）
***
# 2 Obsidian使用方法
## 2.1 基本设置
### 2.1.1 主题
- 使用Velocity主题。原因如下：
	- 这主题是真的好看啊，简洁明了。
	- 唯一一款表格非常看的顺眼的主题。
	- 支持屏蔽一些特有的主体功能：在Style Settings插件里设置。
		- [关闭的features](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210161106.png)
			- 关第一个是因为我喜欢子弹笔记的样式。
			- 缩进guides是因为我原来设置好了缩进。
			- H1是因为H1下面有条线，很讨厌的说。
		- 开启的features我到现在为止是一个没开。
### 2.1.2 文件与链接
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210163102.png)
- 基本设置
	- 第二个：没啥用，就是新建笔记的时候笔记的位置
	- 第三个：你的Custom Attachment Location插件已经帮你弄了，没啥用。
	- 第四个同理。
- Links
	- 第一个：很重要！因为要配合很多插件使用，这个绝对不能动。如果遇到需要使用相对路径的插件，删了他，不用这个插件。
	- 第二个：还没用过，但是好像要重命名触发。
	- 第三个：关闭。因为很多插件只识别md的链接，wiki链接不是别。
	- 第四个：Xmind文件可用。
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210163529.png)
- trash：
	- 开启这个，不然很容易误删。删除的东西会跑到电脑回收站里。
	- 如何浏览已经删除的文件？
		- 同步-已删除文件。
		- ![|300](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210163710.png)
### 2.1.3 同步
- 基本设置：
	- ![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210161831.png)
	- 这个conflict resolution非常重要：一定要把create conflict file打开，就像我有天晚上弄的iconic的图标，结果ipad忘记把插件同步打开了（之间vault搞错了为了用git）、icon全没了。害得我又花了一个小时弄完。
- 选择性同步也全都打开。
	- [选择性同步](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210161716.png)
- 配置文件一定要全都同步。
	- [同步配置文件](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210161621.png)
## 2.2 使用技巧
### 2.2.1 新窗口编辑
- 直接拖动文件标签页到别的地方，可以在新的窗口上编辑。
	- 这样对于你修改设置什么的非常好用：因为在修改插件设置的时候，不能拖动设置的框，就挡住了后面的文本。
	- 但是如果这个时候同时打开了设置，快捷键功能将不能使用。

### 2.2.2 反向链接
- 这个功能很好用，打开之后可以在底部看见反向链接的位置。尤其是再看原理的时候，可以把这些原理的应用都看一遍。
### 2.2.3 插入
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210164220.png)

- 脚注：就是书里面的那个标号，嗯然后插入的地方会在文章最后写出来。
- ![[ExcalidrawSave/Obsidian 快捷键、插件设置和使用指南 26-02-10.excalidraw|395]]
### 2.2.4 笔记属性与标签tag
- 使用命令：笔记属性，你就可以获得一个笔记属性的tag：
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210175927.png)
这个就相当于是另一种分类方式了，就跟zotero里面重要的笔记一样。很好用，可以快速的筛选常用的笔记。
### 2.2.5 书签
ctrl+P：可以直接在这一页上插入书签，然后在这里直接找到：
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210180548.png)
可以看到，还可以添加书签组。
### 2.2.6 文章内链接
输入：
```markdown
[[#
```

![|450](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210184904.png)
***
# 3 第三方插件
## 3.1 Custom Attachment
- 这个插件非常容易导致文件丢失，所以务必用好，然后配合git同步到github里面使用
- 设置详解
![[ExcalidrawSave/Obsidian 使用指南以及插件设置 26-02-10.excalidraw|1287]]
## 3.2 Better Export PDF 与 PDF导出
- 插件的作用：导出PDF的时候可以大致预览。
- 缺点：
	- 导出的时候不能使用A4纸预览页面，不像写LaTeX的时候是SummatraPDF一样的优异的编译性能，而且加载有点慢。
	- 还有可能有导出失败的可能性。
- 优点：
	- 有页眉页脚（我把页眉关了，有点丑。
	- 可以显示预览效果。
	- **可以用css控制：**
		- 这一点很重要，因为PDF导出的时候，经常会截断图片or截断表格之类的东西。由于我现在只遇见了截断表格这个东西我忍受不了以外，其他的还算可以接受。
- 一般的打印PDF流程：
	- 使用**阅读模式预览**。
	- 使用better export PDF来预览（ctrl+P，better就出来了）。
		- 可以回退到编辑模式，再使用`ctrl+滚轮`缩放控制。
	- 选择css：tableprotect。
		- 这个css在`外观-css代码片段`里面可以找到。里面还有非常多的css控制。
	- 导出之后试试效果。
	- 返回编辑模式，在该换页的地方，使用`ctrl+shift+P`<div class="page-break" style="page-break-before: always;"></div>
		- 这样就可以换页了。注意留一个空白行在这个换页符里面。
- 这个导出PDF就是比较麻烦，需要自己一点点调，目前没有更好、更优雅的解决办法，markdown就是不能自动识别A4纸的尺寸，不能在A4底下编辑。

## 3.3 Editing Toolbar
‌‌‌‌　　上面那个很小的东西。我用它一般就是为了添加表格的。
‌‌‌‌　　还有很多命令也用不了，比如居中。我也不知道是没开启css还是什么，也不重要。
‌‌‌‌　　有一些小的功能还挺有意思的，比如直接就可以删除线、高亮，还可以<u>一键全屏</u>。


## 3.4 Excalidraw
‌‌‌‌　　这是一个非常核心的plugin！！
### 3.4.1 设置
#### 3.4.1.1 基本
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210155910.png)

‌‌‌‌　　这个东西就是存放的文件位置。但是上面的那个Attachment的插件，会overide它。所以上面的Attachment的插件一定要把excalidraw的文件夹不当做附件（见上）。

这个自动化看起来挺有意思（还有模板），以后可以研究研究。
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210160103.png)

#### 3.4.1.2 保存
‌‌‌‌　　可以看出，excalidraw支持自动保存。非常棒。
‌‌‌‌　　然后就是第二个功能，因为基本上用不到excalidraw的md视图，所以说不开，节省内存。
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210160144.png)

#### 3.4.1.3 界面&行为
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210160333.png)
‌‌‌‌　　第三个设置，就是你ctrl+e之后，点击阅读模式，他会渲染成图像。

‌‌‌‌　　如果是你想在md文档里插入的excalidraw文件渲染成图像的话（embed），只需要在`[excalidraw名称](地址/名字.excalidraw.md)`的前面，加上一个感叹号!。

- 在**缩放和平移**里面，把![|321](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210182305.png)打开。
- 在**手写笔**里（iPad模式），把单指平移打开。

#### 3.4.1.4 嵌入到Markdown文件中的绘图
- 预览图的格式：SVG Image。
	- 因为如果选Native SVG的话，没办法用`alt+滚轮`缩放。我也不是很需要这个交互功能。
### 3.4.2 使用技巧
#### 3.4.2.1 如何嵌入markdown在画布里？
　　必须自己新建一个markdown文件，然后右键添加链接。
#### 3.4.2.2 使用LaTeX公式
- 使用快捷键就可以，ctrl+shift+alt+M。
- 可以使用默认公式：
	- 在**设置-杂项**里。
## 3.5 Link Converter
‌‌‌‌　　设置里没什么好说的，只需要在命令里面去操控他就行。
‌‌‌‌　　命令也是比较简洁，不太需要理解，就是wiki和md两种链接自己转换格式（在vault还是库中）。记得做好备份！
## 3.6 iconic
这个插件是设置文件夹、文件、正文的图标用的。
- 如果想设置一个文件夹内的`文件/文件夹`自动为一个icon：
	- ![|325](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210183527.png)
	- 前面选文件夹树就行，然后选开头的这个。
	- 有可能后面输入的时候，光标会变成🚫：但是没关系，还是可以继续输入。
- 图标选择：可以用`windows+。`直接emoji。
- 设置：备个份吧（26.2.10）。图片的link如下：
	- [设置1](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210183804.png)
	- [设置2](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210183834.png)
	- [设置3](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210183910.png)
	- [规则书1](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210183941.png)
## 3.7 Manual Sorting
给文件夹自动排序的插件，非常好用。
设置里，只需要把第一项写成：Bottom就醒了，这样新生成的文件就会出现在底部。
## 3.8 Mousewheel Image Zoom
放大缩小的。alt键可以放大所有图片。
## 3.9 Number Headings
可以自动给标题编号，这样可以防止标题错乱的问题。
## 3.10 PDF++
‌‌‌‌　　众所周知，obsidian可以看PDF（有自带的PDF编辑器）。所以我就下了这个插件，还没怎么用。
## 3.11 Style Settings
设置主题的一个插件，很好用。具体见：[2.1.1 主题](工具文档/Obsidian%20快捷键、插件设置和使用指南.md#2.1.1%20主题)。
里面的一个子插件：Contextual Typography。

## 3.12 增强编辑
听说是一个很强大的插件，但是我现在只用它来弄我的文本缩进。
***
## 3.13 Pandoc
这是一个非常非常麻烦的插件。但是我用它也用了一段时间了，不好用。
我的原意，是把这个插件当做一个可以导出word的插件，便于方便在word上面修改。这个功能或许以后工作的时候会需要，所以把以前的倒腾的东西写出来，方便以后查阅。
### 3.13.1 插件配置
pandoc本身算是一个exe文件，里面有很多的指令，可以对md文件进行格式转换到word或者是pdf或者是ePub之类的文件格式。所以pandoc这个插件、是一个控制`pandoc.exe`的一个插件，需要对可执行文件进行配置。
#### 3.13.1.1 官网下载pandoc
pandoc需要在官网上下载。直接在github搜到最新的pandoc就可以了。下载方式就是下载它的压缩包、然后看到`pandoc.exe`就证明你成功了。
#### 3.13.1.2 配置环境变量
由于`pandoc.exe`是一个指令集、得通过powershell或者是cmd来操控。但是我不想只在`pandoc.exe`的文件路径下用这个指令集，我就需要在windows中给他添加环境变量，让cmd找到他。
具体方法很简单，找到高级系统设置-环境变量-PATH-编辑-添加`pandoc.exe`所在的文件路径就行了（甚至都不用写`pandoc.exe`本身）。
#### 3.13.1.3 添加pandoc path到插件设置
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210190332.png)
记得把这个exe给写上。
#### 3.13.1.4 选择pandoc的输出文件夹
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210190445.png)

做完上面这些，重启Obsidian，这样插件就会识别到`pandoc.exe`的路径了。
### 3.13.2 使用pandoc导出word
使用pandoc最简单的方法，就是通过**Obsidian的命令**。直接在命令当中搜索Pandoc，你会看到很多格式之间的互转。当然，这些格式之间的转换出来之后、基本就是依托答辩。
最令人难受的是图片显示不出来，所以得找个办法把图片显示出来。
#### 3.13.2.1 配置图片
- STEP 1：导出格式设置为HTML
	- ![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210191020.png)
	- ![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210191130.png)
	- 设计为HTML，你的图片才能编译。
- STEP 2：确定md文档中的链接的地址格式
	- 还记得在[2.1.2 文件与链接](工具文档/Obsidian%20快捷键、插件设置和使用指南.md#2.1.2%20文件与链接)当中所说：一定要选md格式的绝对路径吗？
	- ——是的，因为这个插件它就只能识别md格式的绝对路径。所以第一步要做的，就是确保你的文档中的图片、是不存在wiki格式的链接和相对路径的，否则这个插件识别不到。
这样导出的时候，应该就能导出为图片了。

> 如果导出的时候，有**文件名的冲突**——很可能会导出失败。

### 3.13.3 使用pandoc与word模板
先上链接（一个github的开源项目）：直接在github里面搜索：`Achuan-2/pandoc_docx_template`
这个项目套用了word模板，可以让输出变得更简洁一些。
但是由于这个项目是直接通过pandoc的命令行操作的，每次要转word实在是太难受了，我就用了插件底下的`Extra Pandoc Arguments`。还有就是一定要配置好几个关键的东西：项目文件里面的word模板的名字一定要改成`template.docx`，以及所有的文件和文件夹（尤其是`.lua`文件还有上面的两个文件夹）存在。
配置图和文件夹图：
![|450](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210191851.png)
![|475](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210191901.png)
```PowerShell
--reference-doc=D:\pandocwordfile\template.docx
--lua-filter=D:\pandocwordfile\markdown-to-docx.lua
```
这样就会成功。

注意：
- 导出的时候，如果有同名word文件在那挡着，很可能会失败。
- 还是会报错，但是会导出成功，只是格式上会出点问题。如果真的需要word编辑，可以自己修修改改。
	- 我觉得自己打印的话，就用[3.2 Better Export PDF 与 PDF导出](工具文档/Obsidian%20快捷键、插件设置和使用指南.md#3.2%20Better%20Export%20PDF%20与%20PDF导出)的方法就好了。
	- 真要这样的话，那一定是一个非常强的分享场景：比如写论文、打印报告之类的。但是换个思路想想，报告可以用css控制，论文的话、得用zotero引用文献、我肯定要用word。谁家好人用obsidian写论文啊。。。
	- 所以我觉得这个插件没有必要。
### 3.13.4 配置存档
[pandoc plugin配置存档](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210192620.png)
 还有一个Extra Pandoc Arguments，上面有了。
***


