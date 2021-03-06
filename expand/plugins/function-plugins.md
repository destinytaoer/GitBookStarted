# 5.2 功能插件介绍

## github-buttons star按钮

在顶部增加 GitHub 的 star、watch、follow 按钮

```javascript
"github-buttons": {
   "buttons": [{
     "user": "destiny0904",
     "repo": "GitBookStarted",
     "type": "star",
     "size": "small",
     "count": true
  }]
}
```

[插件地址](https://plugins.gitbook.com/plugin/github-buttons)

## favicon 页面 logo

更改网站的 favicon.ico

```javascript
"favicon": {
  "shortcut": "assets/images/favicon.ico",
  "bookmark": "assets/images/favicon.ico",
  "appleTouch": "assets/images/apple-touch-icon.png",
  "appleTouchMore": {
    "120x120": "assets/images/apple-touch-icon-120x120.png",
    "180x180": "assets/images/apple-touch-icon-180x180.png"
  }
}
```

[插件地址](https://plugins.gitbook.com/plugin/favicon)

## tbfed-pagefooter 版权页脚

为页面添加版权页脚

```javascript
"tbfed-pagefooter": {
   "copyright":"Copyright &copy zhangjikai.com 2017",
   "modify_label": "该文件修订时间：",
   "modify_format": "YYYY-MM-DD HH:mm:ss"
}
```

[插件地址](https://plugins.gitbook.com/plugin/tbfed-pagefooter)

## anchor-navigation-ex 锚链接、目录等的集合

包含锚链接样式、页面目录、回到顶部、浮动导航

[插件地址](https://plugins.gitbook.com/plugin/anchor-navigation-ex)

## copy-code-button 复制按钮

增加复制按钮

[插件地址](https://plugins.gitbook.com/plugin/copy-code-button)

## expandable-chapters-small 折叠目录

使左侧的章节目录可以折叠

[插件地址](https://plugins.gitbook.com/plugin/expandable-chapters-small)

## edit-link 编辑链接

如果本书托管到 GitHub 中，这个链接将直接链接到当前页的源文件，使得访问者可以编辑、纠错

```text
"edit-link": {
        "base": "https://github.com/USER/REPO/edit/BRANCH",
        "label": "Edit This Page"
}
```

[插件地址](https://plugins.gitbook.com/plugin/edit-link)

## klipse 动态代码演示

集成 Klipse （动态代码演示）

klipse 目前支持下面的语言：

* javascript: evaluation is done with the javascript function eval and pretty printing of the result is done with pretty-format
* clojure\[script\]: evaluation is done with Self-Hosted Clojurescript
* ruby: evaluation is done with Opal
* C++: evaluation is done with JSCPP
* python: evaluation is done with Skulpt
* scheme: evaluation is done with BiwasScheme
* PHP: evaluation is done with Uniter
* BrainFuck
* JSX
* EcmaScript2017
* Google Charts: See Interactive Business Report with Google Charts.

使用示例：

```text
```eval-python
print [x + 1 for x in range(10)]
```
```

[插件地址](https://plugins.gitbook.com/plugin/klipse)

## 其他插件

* [prim](https://plugins.gitbook.com/plugin/prim) 代码高亮
* [emphasize](https://plugins.gitbook.com/plugin/emphasize) 为文字加底色
* [splitter](https://plugins.gitbook.com/plugin/splitter) 使侧边栏宽度可调节
* [sectionx](https://plugins.gitbook.com/plugin/sectionx) 将页面分块显示
* [donate](https://plugins.gitbook.com/plugin/donate) 打赏按钮
* [local-video](https://plugins.gitbook.com/plugin/local-video) 视频播放
* ...

## 参考资料

* [插件-GitBook 使用教程](http://gitbook.zhangjikai.com/plugins.html)
* [Gitbook 的使用和常用插件](https://www.tuicool.com/articles/zee2ui)

