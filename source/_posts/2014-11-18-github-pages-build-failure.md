---
layout: post
title: "Github pages build failure"
description: "解决更换jekyll主题后Github pages没有响应的问题"
category: Web
tags: [Jekyll]
---

#### 修复Github邮件错误提示Page build failure
具体的症状就是:本地运行**jekyll serve -w**没有什么异常,但是当执行完push后,Github就会发来一封邮件,告知你**Page build failure**.
<!--more-->
邮件内容如下:

> The page build failed with the following error:
> The submodule `_theme_packages/twitter` was not properly initialized with a `.gitmodules` file. For more information, see [https://help.github.com/articles/page-build-failed-missing-submodule
](https://help.github.com/articles/page-build-failed-missing-submodule).

有热心网友已经贴出了相关详细解决方案.

**请参考这篇文章**[Fix failure on Github Pages and Jekyll](http://theloverz.me/note/2013/12/06/fix-failure-on-github-pages-and-jekyll/ "写的很详细哦")

我这里就不再赘述了.
