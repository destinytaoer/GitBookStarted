# 7. 域名解析

正常情况下，你可以通过 `http://{author}.gitbooks.io/{book}/content/` 来访问你的书，如果要设置自己的域名来访问本书，请按下面步骤设置。

## 添加记录

在你的域名解析中添加一条 **CNAME** 记录，值为：`www.gitbooks.io`。

## 设置域名

在你的**书的设置**页面，找到 `Domains`，在 `Domain for content` 里，添加你的域名即可，然后点击保存。如果解析正确，会显示**绿色提示**，过一定时间即可通过域名访问。否则，请检查你前面记录的设置以及域名是否正确。

![](https://help.gitbook.com/assets/dns-check.png)

## 参考

* [Can I use a custom domains for my book?](https://help.gitbook.com/books/can-i-use-custom-domain.html)

