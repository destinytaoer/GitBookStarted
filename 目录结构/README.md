# 目录结构
```
.
├── .gitignore
├── book.json
├── README.md
├── SUMMARY.md
├── GLOSSORY.md
├── chapter-1/
|   ├── README.md
|   └── something.md
└── chapter-2/
    ├── README.md
    └── something.md
```

## 1. .gitignore
包含使用 Git 上传时忽略的文件

## 2. book.json
配置文件，后面会[详细讲解](https://destiny0904.gitbooks.io/gitbook/content/配置/)。

## 3. README.md
书籍介绍的页面

## 4. SUMMARY.md
概要文件，左侧的目录就是根据这个文件来生成的，默认对应的文件是 `SUMMARY.md`，可以在 `book.json` 重新定义该文件的对应值。它通过 Markdown 中的列表语法来表示文件的父子关系，下面是一个简单的示例：
```md
# Summary
* [Introduction](README.md)
* [Part I](part1/README.md)
    * [Writing is nice](part1/writing.md)
    * [GitBook is nice](part1/gitbook.md)
* [Part II](part2/README.md)
    * [We love feedback](part2/feedback_please.md)
    * [Better tools for authors](part2/better_tools.md)
```

## 5. GLOSSORY.md
术语表文件，默认对应的文件是 `GLOSSARY.md`。该文件主要存储词汇信息，如果在其他页面中出现了该文件中的词汇，鼠标放到词汇上会给出词汇示意.

文件格式为：
```md
# Git
分散式版本控制软件

# Markdown
Aaron Swartz 跟John Gruber共同设计的排版语言
```