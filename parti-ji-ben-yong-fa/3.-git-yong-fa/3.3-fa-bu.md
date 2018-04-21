# 3.3 发布

## Git Url

每本书本都有一个相关联的 Git HTTPS url。GitBook的git服务器暂时还不支持ssh协议。 git url的格式是：

```text
https://git.gitbook.com/{{UserName}}/{{Book}}.git
```

## 认证

git 服务器使用你基本的 GitBook 登录来认证你。当提示的时候，输入你的 GitBook 用户名和密码（你同样可以使用你的 API token）。

## 保存你的凭证

为了避免每次 `push` 的时候输入密码，你可以将你的 GitBook 凭证添加到 `~/.netrc` 文件里。将下面内容添加到 `~/.netrc` 文件中：

```text
machine git.gitbook.com
  login 用户名或邮箱
  password API-TOKEN或密码
```

为了安全起见，我们推荐你使用 API TOKEN，你可以在设置的

## 在命令行创建一个新的仓库

```text
touch README.md SUMMARY.md
git init
git add README.md SUMMARY.md
git commit -m "first commit"
git remote add gitbook https://git.gitbook.com/{{UserName}}/{{Book}}.git
git push -u gitbook master
```

## 推送一个已存在的仓库

```text
git remote add gitbook https://git.gitbook.com/{{UserName}}/{{Book}}.git
git push -u gitbook master
```

> **\[warning\] 注**
>
> 本文引自官网 [help 文档](https://help.gitbook.com/books/how-can-i-use-git.html)

