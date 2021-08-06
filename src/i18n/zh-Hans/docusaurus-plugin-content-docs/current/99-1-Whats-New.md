---
title: "更新历史"
description: "更新历史"
---

## v0.6.0

此版本，我们带来了诸多的全新特性

### 支持生成和分享 AF code

现在，您可以通过页面上的分享按钮来生成 AFCode 。得到 AFCode 之后，可以通过搜索栏将对应的收藏快速的导入到自己的收藏栏中。这将对于以下场景非常有用：

- 您有一个非常棒的资源需要分享给你的朋友，但是手动复制链接感觉一点也不酷
- 您有一个无法不分享给他人的精彩网址希望通过你的博客文章分享给广大的网友，但是在一些博客站点上并不支持外站超链接（比如微信公众号）
- 您觉得自己对于一些收藏的 Tag 标记简直惊为天人，必须让你的朋友好好看看，但是每个 Tag 手动拷贝一下真的有点蠢

因此，独乐乐不如众乐乐。快来适用最新的 AFCode 分享吧。

试试把以下这段内容复制到你的搜索栏试试：

```bash
af://1eyJ1IjoiaHR0cHM6Ly9taWNyb3NvZnRlZGdlLm1pY3Jvc29mdC5jb20vYWRkb25zL2RldGFpbC9hbWF6aW5nLWZhdm9yaXRlcy9ia25qZ2Jwa2Fsb2FqY3BoY2NwY25haGVnZmdsZmllaSIsInQiOiJBbWF6aW5nIEZhdm9yaXRlcyAtIE1pY3Jvc29mdCBFZGdlIEFkZG9ucyIsInRzIjpbXX0=
```

![AF code](/images/20210805-001.gif)

### 更快更好的交互体验

我们将收藏和编辑书签的交互对话框移入了管理页面。这使得您可以更快的编辑自己的标签，比起之前那种恼人的等待，这简直太棒了。

![better UX](/images/20210805-002.gif)

### 热门标签

我们在搜索栏下方添加了一个“热门标签栏”，您点击过的标签将会在这里展示，以便您可以更容易的找到自己标记的内容。

![Hot tag](/images/20210805-003.gif)

## v0.5.10

Changes

- 暂时移除了 AOT 发布，等待 .net 6 pre7 进行修复 @newbe36524 (#73)

🛠 Improvements

- UI 界面部分优化 @newbe36524 (#75)

## v0.5.9

Changes

🛠 Improvements

- 升级 AntDeign 组件为 0.9 版本 @newbe36524 (#72)

## v0.5.8

Changes

🛠 Improvements

- 现在，你可以在 Chrome 扩展商店中安装这个扩展了 @newbe36524 (#71)

## v0.5.7

Changes

🛠 Improvements

- 更好看的初次加载动画 UX @newbe36524 (#69)

## v0.5.6

Changes

🌟 New Features

- 支持生成和分享 AF 代码 @newbe36524 (#67)

🐞 Bug Fixes

- 修复部分云同步功能失败的问题 @newbe36524 (#66)

## v0.5.5

Changes

🐛 Bug Fixes

- 修复书签编辑界面的一些 BUG

## v0.5.4

Changes

- 支持在管理页面进行书签编辑
- 搜索性能优化，从 500 毫秒下降为 50 毫秒
- 支持在点击扩展按钮时立即添加收藏，而无需等待

## v0.5.3

Changes

- 优化用户搜索框输入，现在更加顺畅
- 修复“热门标签”导致的高 CPU 占用问题

## v0.5.2

Changes

- 支持“热门标签”功能

## v0.5.1

Changes

- 支持 .net AOT

## v0.5.0

Changes

- 支持激活已有的窗口，而不是打开一个新的
- 导入收藏夹时，将会把文件夹当做 tag 进行导入
- 在管理 UI 弹出编辑框时，自动对焦“添加 tag”文本框
- 支持在添加 tag 时使用逗号分隔表示多个 tag
- 在控制面板中添加“用户隐私协议”的说明
- 更小的安装包
- 使用 Indexed db 作为数据库以改进性能
- 添加了一个“喜欢该项目”的按钮，以便用户可以为项目提供支持

## v0.4.3

Changes

- Tag 相关 UI 改进
- “添加 Tag”的用户体验改进

## v0.4.1

- 安装包更小，仅为 5MB
- 添加用户隐私协议的说明

## v0.4.0

- 支持通过云端同步的标签
- 支持通过拼音进行搜索
- 新的图标

## v0.3.1

目标框架修改为 .net 6

## v0.3

支持通过快捷键激活管理界面

## v0.2

首次公开发布