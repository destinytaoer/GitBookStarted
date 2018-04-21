# 4.1 详细参数

## title 标题

设置书本的标题

```javascript
"title" : "Gitbook Use"
```

## author 作者

作者的相关信息

```javascript
"author" : "zhangjikai"
```

## description 描述

本书的简单描述

```javascript
"description" : "记录Gitbook的配置和一些插件的使用"
```

## isbn 版本号

书本的 ISBN。

```javascript
"isbn": "978-3-16-148410-0"
```

## language 语言

使用简体中文

```javascript
"language" : "zh-hans",
```

## gitbook GitBook版本

指定使用的 GitBook 版本

```javascript
"gitbook" : "3.2.2",
"gitbook" : ">=3.0.0"
```

## root  根目录

指定存放 GitBook 文件（除了 book.json）的根目录

```javascript
"root": "."
```

## links 链接信息

在左侧导航栏添加链接信息

```javascript
"links" : {
    "sidebar" : {
        "Home" : "http://zhangjikai.com"
    }
}
```

## styles 自定义样式

自定义页面样式， 默认情况下各generator对应的css文件

```javascript
"styles": {
    "website": "styles/website.css",
    "ebook": "styles/ebook.css",
    "pdf": "styles/pdf.css",
    "mobi": "styles/mobi.css",
    "epub": "styles/epub.css"
}
```

例如使`<h1> <h2>`标签有下边框， 可以在 `website.css` 中设置

```css
h1 , h2{
    border-bottom: 1px solid #EFEAEA;
}
```

## plugins 插件

配置使用的插件

```javascript
"plugins": [
    "disqus"
]
```

Gitbook默认带有5个插件：

* highlight
* search
* sharing
* font-settings
* livereload

如果要去除自带的插件， 可以在插件名称前面加-

```javascript
"plugins": [
    "-search"
]
```

## pluginsConfig 插件配置

配置插件的属性

```javascript
"pluginsConfig": {
    "fontsettings": {
        "theme": "sepia",
        "family": "serif",
        "size":  1
    }
}
```

## structure 结构文件映射

指定 Readme、Summary、Glossary 和 Languages 对应的文件名，下面是这几个文件对应变量以及默认值：

| 变量 | 含义和默认值 |
| :--- | :--- |
| structure.readme | Readme file name \(defaults to README.md\) |
| structure.summary | Summary file name \(defaults to SUMMARY.md\) |
| structure.glossary | Glossary file name \(defaults to GLOSSARY.md\) |
| structure.languages | Languages file name \(defaults to LANGS.md\) |

## variables 全局变量

在模板中使用的变量值。

```javascript
"variables": {
   "myTest": "Hello World"
}
```

