# 简介

这是一个用于 B 站评论区的油猴脚本，用来补全楼中楼子回复的最小上下文。

当某条子回复实际是在回复另一条子回复时，鼠标悬停在这条回复上，即可弹出一个小浮窗，展示这条回复的最小链路：

- 主评论
- 被回复的那条子回复
- 当前回复

适合解决 B 站楼中楼里“看不懂这条回复到底在回谁”的问题。

## 功能特点

- 悬停触发，无需额外按钮
- 只在“回复子回复”的评论上显示上下文
- 主评论默认折叠，减少浮窗占用
- 自动补全主评论、父回复和当前回复之间的最小链路

## 演示

<img src="https://raw.githubusercontent.com/W-ArcherEmiya/bilibili-comment-context-completion/main/assets/demo.gif" alt="演示动图" width="720">

## 安装

先安装浏览器扩展 [Tampermonkey](https://www.tampermonkey.net/)。

然后通过 Greasy Fork 安装脚本：

[安装 B站评论上下文补全(Bilibili)](https://greasyfork.org/zh-CN/scripts/572814-b%E7%AB%99%E8%AF%84%E8%AE%BA%E4%B8%8A%E4%B8%8B%E6%96%87%E8%A1%A5%E5%85%A8-bilibili)

## 项目地址

GitHub：

https://github.com/W-ArcherEmiya/bilibili-comment-context-completion
