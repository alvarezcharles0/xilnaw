V8娱乐平台【Q-——333307——】V8娱乐平台【 辋芷《888yx●vip》 】
V8娱乐平台【Q-——333307——】V8娱乐平台【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

你是不是也想拥有一个完全属于自己的技术博客？不用买服务器、不用备案、甚至不用花一分钱——GitHub Pages + Hexo 就是目前最主流的免费博客解决方案。这篇文章手把手带你走通全流程，跟着操作，30分钟就能上线。

 为什么要用 GitHub Pages 托管博客？

- 完全免费：静态托管，无限流量
- 支持自定义域名：绑定自己的域名也很简单
- 版本管理：所有文章都是 Git 仓库里的 Markdown 文件，天然支持回溯
- SEO 友好：生成纯静态 HTML，搜索引擎收录快

 第一步：准备工作

你需要准备：
1. 一个 GitHub 账号（没有的话先去注册）
2. 安装 Node.js（建议 LTS 版本，官网直接下载）
3. 安装 Git（Windows 用户装 Git for Windows）

 第二步：安装并初始化 Hexo

打开终端，全局安装 Hexo 脚手架：

```bash
npm install -g hexo-cli
```

然后初始化博客目录：

```bash
hexo init my-blog
cd my-blog
npm install
```

启动本地预览：

```bash
hexo server
```

浏览器访问 `http://localhost:4000`，看到默认页面就说明搭建成功了。

 第三步：部署到 GitHub Pages

在 GitHub 上新建一个仓库，仓库名必须是 你的用户名.github.io（比如 `lisi.github.io`）。

然后在博客目录安装部署插件：

```bash
npm install hexo-deployer-git --save
```

修改 `_config.yml` 配置文件里的 Deploy 部分：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

最后执行部署命令：

```bash
hexo clean && hexo generate && hexo deploy
```

这样，访问 `https://你的用户名.github.io` 就能看到你的博客啦！

 第四步：写文章与日常维护

发布新文章只需要：

```bash
hexo new "文章标题"
```

生成的文章会放在 `source/_posts/` 目录下，用 Markdown 写好后，再次执行 `hexo g -d` 即可发布。

常用命令速查：
- `hexo clean`：清理缓存
- `hexo generate`：生成静态文件
- `hexo deploy`：推送到 GitHub

 进阶建议：SEO 优化与收录

- 安装 `hexo-generator-sitemap` 插件，自动生成 sitemap.xml
- 在 GitHub 仓库 Settings 里开启 HTTPS
- 记得在百度站长平台提交你的站点地址，加速收录

---

你现在到哪一步了？ 是刚注册 GitHub，还是卡在了部署环节？欢迎在评论区留言，我会针对高频问题更新补充内容。如果这篇文章帮到了你，也请点个赞让更多人看到，你的支持是我持续输出干货的最大动力！

下一期预告：“如何让博客更酷：主题美化+评论功能接入”，关注不错过更新。

相关推荐：

https://github.com/clarkalyssa3349/mrznkk/blob/main/2026%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%EF%BC%9AV8%E4%B8%BB%E7%AE%A1%E7%BD%91%E5%9D%80_%E8%91%B1%E7%BD%A9%E9%99%A1%E7%BA%AB%E8%B5%8CQQLNJ.md

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />

相关推荐：

https://github.com/clarkalyssa3349/mrznkk/commit/b4ced9b2c62314a2a4e1594eab3125dec5411db6

<img src="https://i.postimg.cc/J7sVTRgT/V8-00010.png" />
相关推荐：

https://github.com/cruzdenise0/avxylh/blob/main/2026%E6%9D%83%E5%A8%81%E8%A7%A3%E6%9E%90%EF%BC%9AV8%E4%B8%BB%E7%AE%A1%E5%9C%B0%E5%9D%80_%E5%85%91%E9%95%9C%E8%8A%B3%E4%B9%88%E7%82%AFCJJES.md

<img src="https://i.postimg.cc/P5kgrYxk/V8-00014.png" />
相关推荐：

https://github.com/cruzdenise0/avxylh/commit/06519f9d5775dc012eca260f4b22c7b8e54077a3

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
