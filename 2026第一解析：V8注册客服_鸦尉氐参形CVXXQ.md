V8注册客服【Q-——333307——】V8注册客服【 辋芷《888yx●vip》 】
V8注册客服【Q-——333307——】V8注册客服【 辋芷《888yx●vip》 】

 从0到1：如何用Github Pages搭建个人技术博客（附完整教程）

> 还在羡慕技术大牛的个人站点？其实你也能免费拥有，只需三步。

作为一名开发者，长期在Github上提交代码之余，我一直想拥有一个属于自己的技术博客。对比了WordPress、Hexo等方案后，最终选择了Github Pages + Jekyll。因为它免费、支持自定义域名，更重要的是——所有内容都由Git管理，写博客就像提交代码一样优雅。

 第一步：创建Github仓库

登录Github，点击右上角“+”号，选择“New repository”。仓库名必须严格遵守格式：`你的用户名.github.io`。比如我的用户名是“TechWrite”，仓库名就应该是`TechWrite.github.io`。勾选“Public”后，点击创建即可。

 第二步：启用Pages服务

进入仓库页面，点击“Settings”，在左侧菜单找到“Pages”。在“Branch”选项中选择“main”分支，点击保存。系统会自动生成一个网址，大约等待2分钟后，你就能通过`https://你的用户名.github.io`访问站点模板了。

 第三步：写第一篇文章

回到本地，将仓库克隆到电脑上：
```bash
git clone https://github.com/你的用户名/你的用户名.github.io.git
```
在根目录新建`_posts`文件夹，创建名为`2025-03-15-welcome-to-my-blog.md`的文件。文件头部必须包含元数据：
```yaml
---
layout: post
title: 欢迎来到我的技术博客
date: 2025-03-15
---
```
下方用Markdown语法写正文，保存推送到Github，刷新页面，文章便发布成功。

---

 进阶技巧：让博客更好看

- 换主题：搜索“Jekyll Themes”，下载后替换`_config.yml`中的`theme`字段
- 绑定域名：在Pages设置页填写你的域名，再到DNS服务商添加CNAME记录
- 评论区：接入Gitalk，让访客可以用Github账号留言

> 如果你在搭建过程中遇到任何报错，欢迎在评论区留言或私信我，看到都会回复。

---

 写在最后

Github Pages不仅适合写技术博客，还可以用来做个人简历、项目文档站。它最大的意义在于：让你专注于输出内容，而不必操心服务器维护。如果你还没试过，今天就可以动手操作，有问题随时在评论区交流。期待看到你的第一个站点上线！

如果这篇文章对你有帮助，请点个赞或分享给身边的朋友，你们的支持是我持续输出的最大动力！

相关推荐：

https://github.com/cruzdenise0/avxylh/blob/main/%E5%85%B1%E8%B5%B4%E6%96%87%E5%BF%83%E4%B9%8B%E7%BA%A6%EF%BC%9AV8%E7%BD%91%E5%9D%80%E4%B8%BB%E7%AE%A1_%E5%B1%A5%E5%81%BE%E5%BB%8A%E8%8A%AD%E8%B0%A1SSGNB.md

<img src="https://i.postimg.cc/d05pBf9J/V8-00019.png" />

相关推荐：

https://github.com/cruzdenise0/avxylh/commit/366c5f4e4876766a6af014a3068aed53e0d0a22a

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />
相关推荐：

https://github.com/hamiltonlinda25/thgubw/blob/main/2026%E6%9D%83%E5%A8%81%E4%B8%93%E8%AE%BF%EF%BC%9AV8%E4%B8%BB%E7%AE%A1%E5%A8%B1%E4%B9%90_%E7%89%A2%E9%AA%84%E5%A3%AC%E7%B2%B1%E5%B1%8EJPDBV.md

<img src="https://i.postimg.cc/90Rpy8Ls/V8-00008.png" />
相关推荐：

https://github.com/hamiltonlinda25/thgubw/commit/0a45f5a4d86f67d37cf10e675bcb5ebe6ff26ce9

<img src="https://i.postimg.cc/W4Nx0Vgy/V8-00017.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
