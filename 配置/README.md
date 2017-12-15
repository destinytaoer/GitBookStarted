<!-- ex_nonav -->
# 配置 book.json
首先在你的书的根目录下创建一个 `book.json` 文件。下面是本书的配置：
```json
{
    "title": "GitBook入门",
    "author": "destiny",
    "description": "关于 gitbook 的简单介绍和使用",
    "extension": null,
    "generator": "website",
    "isbn": "",
    "language": "zh",
    "links": {
        "sharing": {
            "all": false,
            "facebook": false,
            "google": false,
            "twitter": false,
            "weibo": false
        },
        "sidebar": {
        }
    },
    "output": null,
    "pdf": {
        "fontSize": 12,
        "footerTemplate": null,
        "headerTemplate": null,
        "margin": {
            "bottom": 36,
            "left": 62,
            "right": 62,
            "top": 36
        },
        "pageNumbers": false,
        "paperSize": "a4"
    },
    "mobi": {
        "fontSize": 12,
        "footerTemplate": null,
        "headerTemplate": null,
        "margin": {
            "bottom": 36,
            "left": 62,
            "right": 62,
            "top": 36
        },
        "pageNumbers": false,
        "paperSize": "a4"
    },
    "styles": {
        "website": "styles/website.css",
        "ebook": "styles/ebook.css",
        "pdf": "styles/pdf.css",
        "mobi": "styles/mobi.css",
        "epub": "styles/epub.css"
    },
    "plugins": ["theme-comscore","github-buttons","github"],
    "pluginsConfig": {
        "github-buttons": {
            "buttons": [{
                "user": "destiny0904",
                "repo": "GitBookStarted",
                "type": "star",
                "size": "small",
                "count": true
              }]
          },
          "github": {
              "url": "https://github.com/destiny0904"
          }
    },
    "variables": {}
}
```

>**[danger] 注意**：在写完配置文件后，一定要通过 [JSONLint](https://jsonlint.com/) 的去验证这个文件的合法性。否则会无法发布。同时，也可以用它来查找错误。