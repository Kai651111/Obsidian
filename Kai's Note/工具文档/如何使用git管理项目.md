
# 1 在结束学习/写笔记时执行：

- 进入文件夹的根目录（就在电脑上的快捷方式，或者直接点：[Obsidian地址](D:\学术与学习\Obsidian)）
- 然后右键空白处，打开git bash`

```bash
git add . #把所有文件(.)，放入待提交区
git commit -m "comment" #上传备注为“comment”的版本到本地
git push #推送到云端github
```

其他命令：
```bash
git status #查看是否有没有上传的版本。
git log #查看上传的记录和日志
```

注意：
- 单个文件的大小不能超过100MB。
- 如果想要回退，可以去自己的github里面下载。

***
# 2 Git 的真实工作流程

Git 的状态流是这样的：

```
修改文件
→ git add
→ git commit
→ git push
```

每一步的意义不同。
## 2.1 `git add` 是干嘛的

`git add` 的作用是：

> 把修改放进“待提交区”（staging area）

Git 不会自动把你改的文件加入 commit。

你必须“明确告诉它”。

---
# 3 举个 Obsidian 的例子

比如你改了：

```
SmartMaterials.md
AMP.md
```

Git 此时知道你改了，但还没准备提交。

运行：

```bash
git status
```

会看到：

```
modified: SmartMaterials.md
modified: AMP.md
```

---

## 3.1 这时才需要 `git add`

例如：

```bash
git add .
```

意思是：

> 把所有修改加入准备提交的列表。

然后：

```bash
git commit -m "update notes"
```

---

# 4 什么时候需要 git add？

只有三种情况：

---

## 4.1 1）修改了文件

例如编辑笔记。

---

## 4.2 2）新增文件

例如新建：

```
RobotControl.md
```

---

## 4.3 3）删除文件

Git 也需要记录删除。

---

# 5 什么时候不需要 git add？

这些情况下都不需要：

- 只是 `cd` 进入文件夹
    
- 打开 Obsidian
    
- 查看文件
    
- 没有修改任何文件
    

---

# 6 给你一个简单判断规则

记住一句话：

> 只要文件内容发生变化，就需要 `git add`。

否则不用。

---

# 7 针对你现在的 vault（实用建议）

你可以养成一个非常简单的习惯：



不用每次进入文件夹都做。

---

# 8 再给你一个小技巧

你可以先用：

```bash
git status
```

来判断是否需要 `git add`。

如果显示：

```
nothing to commit
```

就不用做任何事。

---

我想确认一个细节，这会影响你以后怎么用 Git：

你现在是打算用 Git：

- 做 **vault 备份**
    
- 做 **多设备同步**
    
- 还是 **版本管理（回滚历史）**