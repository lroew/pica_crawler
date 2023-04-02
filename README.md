# 项目简介

一个哔咔漫画的下载程序,基于python实现,欢迎各位绅士来捉虫
* 目前已实现按 排行榜/收藏夹/指定关键词 进行下载的功能
* 本项目是基于[AnkiKong大佬开源的项目](https://github.com/AnkiKong/picacomic)编写的,仅供技术研究使用,请勿用于其他用途,有问题可以提issue
* 可以fork这个项目,根据[api文档](https://www.apifox.cn/apidoc/shared-44da213e-98f7-4587-a75e-db998ed067ad/doc-1034189)自行开发功能
* 麻烦给个star支持一下:heart:
*  新增Actions secrets
| secret          | 说明                                                         |
| --------------- | ------------------------------------------------------------ |
| PICA_SECRET_KEY | [AnkiKong提供的secret_key](https://zhuanlan.zhihu.com/p/547321040) |
| PICA_ACCOUNT    | 哔咔登录的账号                                               |
| PICA_PASSWORD   | 哔咔登录的密码                                               |
| EMAIL_ACCOUNT   | 接收漫画的邮箱                                               |
| EMAIL_AUTH_CODE | 邮箱的授权码,[参考qq邮箱的这篇文档](https://service.mail.qq.com/cgi-bin/help?subtype=1&&id=28&&no=1001256) |
| GIT_TOKEN       | [参考这篇文章](http://t.zoukankan.com/joe235-p-15152380.html),只勾选repo的权限,Expiration设置为No Expiration |
