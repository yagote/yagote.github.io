---
title: 'Git提交博客到github上报错Connection was reset, errno 10054'
date: 2021-07-24 22:28:12
thumbnail:
tags: Git
categories:
 - Git
 - 博客
---
---
<!--more-->
今天提交内容到博客上时，一直报错 有时是报错：`‘fatal: unable to access'……' Failed to connect to github.com port 443: Timed out’   `      有时是报错：`‘error: RPC failed; curl 28 OpenSSL SSL_read: Connection was reset, errno 10054’`最后是根据错误提示`‘Connection was reset, errno 10054’`来搜索解决方法
最终找到解决方法,在Git中关闭安全认证即可
在Git中进行代码操作

```git
git config --global http.sslVerify "false"
```
再接着就可以提交了