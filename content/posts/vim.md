---
date: '2024-12-24T16:52:21+08:00'
draft: true
title: '第二篇文章'
summary: "本文主要介绍了vim的常见用法"
---
## vscode + vim 

* [参考配置视频](https://www.bilibili.com/video/BV1z541177Jy/?p=15&share_source=copy_web&vd_source=26e761dc49fea97602712326612c0845)

* [tmux教程](https://www.ruanyifeng.com/blog/2019/10/tmux.html)

### vim模式

* 普通（Normal）模式
* 插入模式
* 命令模式
* 可视模式

## Normal模式

### 光标移动

* ```
  w 跳到下一个单词开头
  b 跳到本单词或上一个单词开头  begin
  e 跳到本单词或下一个单词开头  end
  ge 跳到上一个单词结尾
  ```

* ```
  0 跳到行首
  ^ 跳到从行首开始第一个非空字符
  $ 跳到行尾
  gg 跳到第一行
  G 跳到最后一行
  ```

* ```
  f{char} 光标跳到当前行下个{char}所在位置
  F{char} 光标反向跳到当前行上一个{char}所在位置
  
  t{char} 光标跳到当前行下个{char}的前一个字符所在位置
  T{char} 光标反向跳到当前行上一个{char}的后一个字符所在位置
  
  ; 重复上一次的字符查找操作
  , 反向重复上一次的查找操作
  ```
