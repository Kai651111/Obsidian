# 使用Zotero进行PDF的翻译：
**思路**：运行脚本——关闭防火墙——Zotero右键pdf、找到pdf2zh，进行翻译（并且监控cmd的状态）
### 运行脚本流程
- 打开cmd，输入以下：
```
cd C:\Users\Keiran\zotero-pdf2zh\server
```
- 然后运行脚本
```
python server.py
```
- 记得关闭防火墙。

接下来就可以执行后面的流程了。
### PS：
- 这个翻译的翻译引擎是deepseek的api。具体的API我写在了password里面。
- github项目官网：[GitHub - guaguastandup/zotero-pdf2zh: PDF2zh for Zotero | Zotero PDF中文翻译插件](https://github.com/guaguastandup/zotero-pdf2zh)
	- 不懂的问题看Readme.md
- 小红书：[最好的Zotero PDF开源翻译插件 - 小红书](https://www.xiaohongshu.com/explore/6835cf2a000000002001cb23?source=webshare&xhsshare=pc_web&xsec_token=AByYgg_3q4kcWby9kkgh1bbusrKL2cvXE0YMF0zftPp5w=&xsec_source=pc_share)
### 课件翻译：绝了
![375](assets/工具文档/Zotero使用指南/Pasted%20image%2020260207190113.png)
- 点击**第三个**：双语对照。他就会生成一个左中右英的pdf文件，再导入到onenote里面，完美。
***
w