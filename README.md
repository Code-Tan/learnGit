# learnGit

---------
我理解您需要更便捷更高效的工具记录私信啊个，整理笔记、知识，并将其中承载的价值传播给他人，**Cmd MarkDown**是我的答案---为记录思想和分享知识提供更专业的工具。
您可以使用MarkDown：
>* 整理知识，学习笔记
>* 发布日记，杂文，所见所想
>* 撰写发布技术文稿（技术支持）
>* 撰写发布学术论文（LaTeX 公式支持）
![cmd-markdown-logo](https://www.zubuluo.com/static/img/logo.png)
除了您现在看到的这个 Cmd Markdown 在线版本，您还可以前往一下网址下载：
### [Windows/Linux/Mac 全平台客户端](https://www.zybuluo.com/cmd/)
> 请保留此份 Cmd Markdown 的欢迎搞兼使用说明，如需撰写新稿件，点击顶部工具栏右侧的<i class="icon-file"></i>**新文稿**或者使用快捷键`Ctrl+Alt+N`.
------
## 什么是 Markdown
Markdown 是一种方便记忆，书写的纯文本标记语言，用户可以使用这些标记符号以最小的输入代价生成极富表现力的文档：譬如您正在阅读的这份文档。它使用简单的符号标记不同的标题，分割不同的段落，***粗体** 或者 *斜体* 某些文字，更棒的是，它还可以
### 1. 制作一份待办事宜[Todo列表](https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown#13-待办事宜-todo-列表)
- [ ] 支持以 PDF 格式导出文稿
- [ ] 改进 Cmd 渲染算法，使用局部渲染技术提高渲染效率
- [X] 新增 Todo 列表功能
- [X] 修复 LaTex 公式渲染问题
- [X] 新增 LaTex 公式编号功能
### 2. 书写一个只能守恒公式[^LeTeX]
  $$E=mc^2$$
### 3. 高亮一段代码[^code]

```python
@requires_authorization
class SomeClass:
  pass

  if __name__ == '__main__':
    # A comment
    print 'Hello World'
```
### 4. 高效绘制[流程图](https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown#7-流程图)

```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
```
### 5. 高效绘制[序列图](https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown#8-序列图)

```seq
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```
### 6. 高效绘制[甘特图](https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown#9-甘特图)

```gantt
    title 项目开发流程
    section 项目确定
      需求分析      :a1, 2016-06-22, 3d
      可行性报告     :after a1, 5d
      概念验证      : 5d
    section 项目实施
      概要设计      :2016-07-05 , 5d
      详细设计      :2016-07-05 , 10d
      编码      :2016-07-15, 10d
      测试      :2016-07-22, 5d
    section 发布验收
      发布:     2d
      验收:     3d
```

### 7. 绘制表格

| 项目 | 价格 | 数量|
| -------| -------:| :-------:|
| 计算机 | \$1600 | 5 |
| 手机 | \$500 | 12 |
| 笔 | \$1 | 234 |

### 8. 更详细语法说明
想要查看更详细的语法说明，可以参考准备的 [Cmd Markdown简明语法说明][1] ,进阶用户可参考 [Cmd Markdown 高阶语法手册][2] 了解更多高级功能。
总而言之，不同于其它 *所见即所得* 的编辑器：你只需要使用键盘专注于书写文本内容，就可以生成印刷的排版格式，省却在键盘和工具栏之间来回切换，调整内容和格式的麻烦。 **Markdown 在流畅的书写和印刷级的阅读体验之间找到平衡.**目前它已经成为世界上最大的技术分享网站 Github 和 技术问答网站 stackOverFlow 的御用书写格式。

[^LaTeX]: 支持 **LaTeX** 编辑显示支持，例如:$\sum_{i=1}^n a_i=0$

[1]: https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md/-help.markdown
[2]: https://www.zybuluo.com/mdeditor?url=https//www.zybuluo.com/static/editor/md/-help.markdown#cmd-markdown-高阶语法手册
