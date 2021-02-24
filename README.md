# Nullboard

Nullboard 是看板/任务列表管理器的极简风格，旨在紧凑，易读且易于使用。

en: https://nullboard.io/preview

zh: https://board.dingeral.com/

![Nullboard](https://nullboard.io/images/nullboard-example-alt.png?z)

该名称也恰好缩写为 [NB](https://en.wikipedia.org/wiki/Nota_bene)，我认为这是一个很好的称呼。

## 简单

* 单页 Web 应用程序 - 仅一个 HTML 文件，一个古老的 jQuery 包和一个 webfont 包。
* 可以完全脱机使用。实际上，正是出于这种用途而编写的。

## 本地存储

* 所有数据都存储在本地，现在使用 [localStorage](https://developer.mozilla.org/en/docs/Web/API/Window/localStorage)。
* 数据也可以以简单的 JSON 格式导出到纯文本文件或从纯文本文件导入。

## Beta

仍处于测试阶段。注意使用。

## UI & UX

整个过程主要是要使其易于使用。

一切都是可编辑的，所有更改都将自动保存，并保留最近 50 个修订以供撤消 / 重做：

![In-place editing](https://nullboard.io/images/nullboard-inplace-editing.gif?x)

可以在需要的地方直接快速添加新笔记，例如在现有笔记之前或之后：

![Ctrl-add note](https://nullboard.io/images/nullboard-ctrl-add-note.gif?x)

也可以拖动笔记，包括在其他列表之间来回拖动：

![Drag-n-drop](https://nullboard.io/images/nullboard-drag-n-drop.gif?x)

默认情况下，几乎所有控件都处于隐藏状态，以将视觉混乱程度降至最低：

![Hidden controls](https://nullboard.io/images/nullboard-hidden-controls.gif?x)

更长的笔记可以折叠起来以仅显示第一行，以使看板更紧凑：

![Collapsed notes](https://nullboard.io/images/nullboard-collapsed-notes.gif?x)

字体为 [Barlow](https://tribby.com/fonts/barlow/) 既窄又清晰易读。绝对出色的设计！

![Barlow speciment](https://nullboard.io/images/barlow-specimen.png?y)

笔记也可以设置为看起来有所不同。这对于将列表划分为几个部分很有用：

![Raw notes](https://nullboard.io/images/nullboard-raw-notes.gif?x)

可以识别以 https:// 和 http:// 开头的链接。它们将在鼠标悬停时“抖动”，并且可以通过右键单击菜单打开。

![Links on hover](https://nullboard.io/images/nullboard-links-on-hover.gif)

按下 CapsLock 将突出显示所有链接，并使它们左键单击。

![Links reveal](https://nullboard.io/images/nullboard-links-reveal.gif)

列表也可以移动，尽管不如笔记方便：

![List swapping](https://nullboard.io/images/nullboard-list-swap.gif?x)

黑白主题，字号可变。

![Theme and zoom](https://nullboard.io/images/nullboard-theme-and-zoom.gif?x)

还有:

* 支持具有近乎即时切换的多块板
* 撤消 / 重做每个板 50 个修订版（可在代码中配置）
* 键盘快捷键，包括通过注释制表符

## 注意事项

* 专为台式机和键盘 / 鼠标设计
* 基本上未在移动设备上经过测试，并且没有点击 / 触摸输入
* 在 Firefox 中运行，在 Chrome 中进行了测试，应该在 Safari 中运行，并且可能在 Edge 中运行
* 使用 localStorage 来存储板 / 列表 / 笔记，因此请注意[清除缓存](https://stackoverflow.com/questions/9948284/how-persistent-is-localstorage)

如果你发现 bug，请提出问题。

## Docker 版本

看这个[仓库](https://github.com/rsoper/nullboard)。

## 背景

Nullboard 以一种非常有效的方式处理 ToDo 列表。对我而言。

尝试了很多选择，几乎都选择了，但没有一个是 100％。

**Trello** 不错，但不想将数据存储在网络中。

**Wekan** 看起来很有前途，但太过笨重，不支持离线使用或本地存储选项。

**Things** 很美，但不是完成工作的正确工具。

**Inkscape** - 我没骗你 - 带着一堆文本项目的杂乱列表其实还可以，但是扩展性不好。

纯文本文件的同上。

纸片是也行，但重新整理物品是相当麻烦的。

所以终于被惹恼了，坐下来写下我想要的东西。

而且，瞧，Nullboard 出来了=> https://nullboard.io/preview

## 许可证

The [2-clause BSD license](https://opensource.org/licenses/BSD-2-Clause/) with the [Commons Clause](https://commonsclause.com/).

也就是说，只要不尝试出售它，就可以使用，更改和重新分发它。

## Updates

通过 [@nullboard](https://twitter.com/nullboard) 在推特上发布更新。
