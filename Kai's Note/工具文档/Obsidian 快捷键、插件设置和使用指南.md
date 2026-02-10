# 快捷键与语法
## Obsidian及其插件
 - `ctrl+P`：命令面板
 - `ctrl+w`：编辑模式-阅读模式 切换
 - `ctrl+Tab`：增强编辑-当前行缩进
	- 命令也可以用。
	- 必须写好文字，再缩进。
- `Alt+滚轮`：缩放图片（Mousewheel Image zoom）
- `ctrl+shift+P`：添加breakpage （PDF breakpage），打印用
- Embed：`![Name](markdown address)`：前面的!决定是否Embed在页面上
## Markdown
- `ctrl+shift+H`：高亮
-  `ctrl+shift+[`：无序列表
- `ctrl+shift+[`：有序列表
- `ctrl+q`：引用
- \`\`：行内代码 (英文模式下的~)
- `shift+alt+K`：代码块
- `shift+alt+M`：公式块
- `alt+M`：行内公式块
## Excalidraw
- `ctrl+e`：excalidraw - markdown切换
- `ctrl+‘`：excalidraw网格线显示
- `ctrl+上下左右`：excalidraw思维导图
- `ctrl+alt+C/V`：复制/粘贴样式
- `ctrl+shift+alt+M`：插入Latex块
## 命令面板
- `左右分屏 split right`
- `ouline 大纲：显示大纲页面`
- `收集`：Custom Attachment location：收集整个库/当前文件夹中的附件
- `link converter`：md和wiki链接互转（用于改变md文档的绝对路径和相对路径）
- `Better Export PDF`：导出为PDF
- `Iconic 打开规则书`：为文件夹/ 文件设置icon
***
# Obsidian使用方法
## 基本设置
### 主题
- 使用Velocity主题。原因如下：
	- 这主题是真的好看啊，简洁明了。
	- 唯一一款表格非常看的顺眼的主题。
	- 支持屏蔽一些特有的主体功能：在Style Settings插件里设置。
		- [关闭的features](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210161106.png)
			- 关第一个是因为我喜欢子弹笔记的样式。
			- 缩进guides是因为我原来设置好了缩进。
			- H1是因为H1下面有条线，很讨厌的说。
		- 开启的features我到现在为止是一个没开。
## 使用技巧
### 新窗口编辑
- 直接拖动文件标签页到别的地方，可以在新的窗口上编辑。
	- 这样对于你修改设置什么的非常好用：因为在修改插件设置的时候，不能拖动设置的框，就挡住了后面的文本。
	- 但是如果这个时候同时打开了设置，快捷键功能将不能使用。
### 同步
- 基本设置：
	- ![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210161831.png)
	- 这个conflict resolution非常重要：一定要把create conflict file打开，就像我有天晚上弄的iconic的图标，结果ipad忘记把插件同步打开了（之间vault搞错了为了用git）、icon全没了。害得我又花了一个小时弄完。
- 选择性同步也全都打开。
	- [选择性同步](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210161716.png)
- 配置文件一定要全都同步。
	- [同步配置文件](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210161621.png)
## 反向链接
- 这个功能很好用，打开之后可以在底部看见反向链接的位置。尤其是再看原理的时候，可以把这些原理的应用都看一遍。

***
# 第三方插件
## Custom Attachment
- 这个插件非常容易导致文件丢失，所以务必用好，然后配合git同步到github里面使用
- 设置详解
![[ExcalidrawSave/Obsidian 使用指南以及插件设置 26-02-10.excalidraw|1287]]
## Better Export PDF 与 PDF导出
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

## Editing Toolbar
‌‌‌‌　　上面那个很小的东西。我用它一般就是为了添加表格的。
‌‌‌‌　　还有很多命令也用不了，比如居中。我也不知道是没开启css还是什么，也不重要。
‌‌‌‌　　有一些小的功能还挺有意思的，比如直接就可以删除线、高亮，还可以<u>一键全屏</u>。


## Excalidraw
‌‌‌‌　　这是一个非常核心的plugin！！
### 设置
#### 基本
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210155910.png)

‌‌‌‌　　这个东西就是存放的文件位置。但是上面的那个Attachment的插件，会overide它。所以上面的Attachment的插件一定要把excalidraw的文件夹不当做附件（见上）。

这个自动化看起来挺有意思（还有模板），以后可以研究研究。
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210160103.png)

#### 保存
‌‌‌‌　　可以看出，excalidraw支持自动保存。非常棒。
‌‌‌‌　　然后就是第二个功能，因为基本上用不到excalidraw的md视图，所以说不开，节省内存。
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210160144.png)

#### 界面&行为
![](assets/工具文档/Obsidian%20快捷键、插件设置和使用指南/Pasted%20image%2020260210160333.png)
‌‌‌‌　　第三个设置，就是你ctrl+e之后，点击阅读模式，他会渲染成图像。

‌‌‌‌　　如果是你想在md文档里插入的excalidraw文件渲染成图像的话（embed），只需要在`[excalidraw名称](地址/名字.excalidraw.md)`的前面，加上一个感叹号!。



