V8主管测速【Q-——333307——】V8主管测速【 辋芷《888yx●vip》 】
V8主管测速【Q-——333307——】V8主管测速【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

你是不是也曾想过拥有一个属于自己的博客？不用租服务器、不用买域名，完全免费，还能自定义主题——没错，我说的就是 GitHub Pages + Hexo 这套组合。今天这篇教程，我会手把手带你从零开始搭好一个个人博客，全程踩坑经验分享，保证你看完就能动手。

 为什么选择 GitHub Pages 和 Hexo？

很多新手纠结用什么建站工具。我的建议很直接：GitHub Pages 免费、稳定、支持自定义域名，而 Hexo 基于 Node.js，生成静态页面速度快，主题丰富，特别适合写技术文章的人。

对比 WordPress 或 Typecho，Hexo 不需要数据库，部署起来也简单——你只需要把生成的文件推送到 GitHub 仓库，剩下交给它就行。

 搭建前的准备工作

你需要准备这几样东西：

- 一个 GitHub 账号（没有的话先注册）
- 本地安装 Git 和 Node.js
- 一个顺手的代码编辑器，比如 VS Code

环境确认无误后，我们开始动手。

 第一步：安装 Hexo 并初始化项目

打开终端，执行下面的命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

这几行命令会帮你搭建好一个基础博客框架。如果你想自定义站点信息，打开 `_config.yml` 文件，修改 `title`、`author` 等配置项。

 第二步：创建 GitHub 仓库并部署

在 GitHub 上新建一个仓库，仓库名格式必须是 `你的用户名.github.io`。然后回到本地终端，执行：

```bash
npm install hexo-deployer-git --save
```

接着修改 `_config.yml` 中的 deploy 配置，把仓库地址填进去，最后运行：

```bash
hexo clean && hexo generate && hexo deploy
```

大约等一分钟，你的博客就能在 `https://你的用户名.github.io` 上访问了。

 第三步：挑选并安装主题

Hexo 有大量高颜值主题。访问 [Hexo Themes](https://hexo.io/themes/) 挑一个你喜欢的，用 Git 克隆到 `themes` 目录，然后在 `_config.yml` 中切换主题名称，最后重新部署即可。

小技巧：建议选择有移动端适配和 SEO 优化功能的主题，对收录更有帮助。

 常见问题与避坑指南

问题一：部署后样式丢失怎么办？  
检查 `_config.yml` 中的 `url` 是否为真实站点地址，路径配置错误会导致 CSS 加载失败。

问题二：提交文章后页面没更新？  
先清除浏览器缓存，如果你启用了 CDN，记得刷新缓存。

 让你的博客被更多人看到

文章发布只是第一步，想让内容真正被人搜索到，还需要做一些简单的 SEO 优化：

- 安装 `hexo-generator-sitemap` 插件生成站点地图
- 每篇文章合理使用 H2/H3 层级
 小结

今天我们一起完成了从环境安装到博客部署的全流程。说实话，这个过程并不复杂，关键是动手实践。如果你在搭建过程中遇到了任何问题，欢迎在评论区留言，我看到后会第一时间回复你。

也欢迎在 GitHub 上 fork 我的博客源码做参考（地址在文章开头），你的 Star 和关注是我持续更新的动力。

下一期预告：如何给自己的博客配置一个专属域名（.com），敬请期待！

---

如果你觉得这篇教程有用，点个赞让我知道，我会继续更新更多实战干货。

相关推荐：

https://github.com/millerdonna9312/pwnxnv/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%EF%BC%9AV8%E7%BD%91%E5%9D%80%E5%A8%B1%E4%B9%90_%E6%9E%97%E8%AF%9F%E6%B6%9B%E6%97%81%E6%B2%83DRYMM.md

<img src="https://i.postimg.cc/2SFPqybC/V8-00015.png" />

相关推荐：

https://github.com/millerdonna9312/pwnxnv/commit/0edd47e2a2f6105b4f3077476786e279ed43675c

<img src="https://i.postimg.cc/c4YqSXdK/V8-00012.png" />
相关推荐：

https://github.com/clarkalyssa3349/mrznkk/blob/main/2026%E7%A7%91%E6%8A%80%E4%B8%A5%E9%80%89%EF%BC%9AV8%E7%BD%91%E5%9D%80%E5%B9%B3%E5%8F%B0_%E9%87%8F%E7%84%95%E9%A5%BA%E5%8F%B2%E9%A6%85LRYYY.md

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />
相关推荐：

https://github.com/clarkalyssa3349/mrznkk/commit/886cc23d28f62f6123e54ea3390ffbaa629c2198

<img src="https://i.postimg.cc/2SFPqybC/V8-00015.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
