VS官网下载【Q-——333307——】VS官网下载【 辋芷《888yx●vip》 】
VS官网下载【Q-——333307——】VS官网下载【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

你是否想过拥有一个完全属于自己的技术博客？不需要买服务器，不需要备案，甚至不需要花一分钱——GitHub Pages 免费托管配合 Hexo 静态博客框架，已经成为开发者搭建个人品牌的首选方案。今天这篇教程，我将带你从零开始，完成环境配置、主题美化、SEO优化和自动部署，让你30分钟上线自己的博客。

 为什么选择 Hexo + GitHub Pages？

- 零成本：GitHub 提供无限流量和 300MB 空间，适合个人站点。
- 极速访问：静态页面加载快，且天然支持 HTTPS。
- 生态丰富：Hexo 拥有 400+ 主题和插件，扩展性强。
- 工作流友好：用 Markdown 写作，git 管理版本，自动部署脚本一键更新。

 第一步：环境准备

在开始之前，请确保你的电脑上已安装 Node.js（推荐 LTS 版本）和 Git。没有安装的读者可以在官网下载，安装时勾选“添加到 PATH”。

 第二步：安装 Hexo 并初始化项目

打开终端，执行以下命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo server
```

看到 `INFO Hexo is running at http://localhost:4000` 就说明本地环境搭建成功。在浏览器访问该地址，你应该能看到默认的 Hexo 页面。

> 小提示：如果 `npm` 下载速度慢，可以换成淘宝镜像源：`npm config set registry https://registry.npmmirror.com`

 第三步：部署到 GitHub Pages

1. 在 GitHub 上新建仓库，仓库名务必是 `你的用户名.github.io`。
2. 安装自动部署插件：
   ```bash
   npm install hexo-deployer-git --save
   ```
3. 编辑根目录下 `_config.yml`，找到 `deploy` 字段，修改为：
   ```yaml
   deploy:
     type: git
     repo: https://github.com/你的用户名/你的用户名.github.io.git
     branch: main
   ```
4. 执行 `hexo clean && hexo generate && hexo deploy`，等待几十秒后，访问 `https://你的用户名.github.io` 即可看到你的线上博客。

遇到 404 怎么办？ 别慌，去仓库的 Settings -> Pages，把分支改为 `main` 并保存，GitHub 会自动重新构建。

 第四步：主题配置与个性化

推荐使用广受欢迎的 Next 主题，支持暗黑模式、站内搜索、评论系统。

```bash
git clone https://github.com/theme-next/hexo-theme-next themes/next
```

然后在 `_config.yml` 中把 `theme: landscape` 改为 `theme: next`，刷新页面即可看到效果。你可以在 `themes/next/_config.yml` 中开启侧边栏社交链接、打赏二维码、数学公式支持等功能。

 第五步：SEO 优化与收录

想让文章被百度、Google 抓取，需要完成两件事：

1. 安装 SEO 插件，自动生成站点地图：
   ```bash
   npm install hexo-generator-sitemap --save
   ```
2. 在 `_config.yml` 中添加 `sitemap` 配置，并提交到搜索引擎站长平台。

建议在每篇文章的 `front-matter` 中填写正确的 `keywords` 和 `description`，这不仅帮助搜索引擎理解内容，也能提升点击率。

 互动作业：动手实践

纸上得来终觉浅，读完这篇文章，不妨动手完成以下挑战：

1. 在侧边栏加上你的 GitHub 链接 和 头像。
2. 发布一篇技术日记，并提交到你的在线仓库。
3. 在评论区分享你的博客地址，我看到后会去访问学习。

坚持输出是技术成长最快的方式。如果你在搭建过程中卡壳了，欢迎点赞收藏这篇文章，并在评论区留言，我会第一时间帮你排查问题。

---

相关阅读： [推荐5款小众但超高效率的开发者工具](/)  |  [如何写出高可读性的技术文档](/)

> 本文首发于本人博客，转载请联系授权。如果觉得有用，点个 在看 让更多朋友看到，感谢支持！

相关推荐：

https://github.com/underwoodcassidy5/coqdxx/blob/main/%E5%85%B1%E8%B5%B4%E6%96%87%E5%BF%83%E4%B9%8B%E7%BA%A6%EF%BC%9AVS%E4%B8%BB%E7%AE%A1%E5%AE%98%E6%96%B9_%E8%B5%8F%E6%80%9D%E4%BF%A8%E6%8D%95%E9%A2%9CCPQIR.md

<img src="https://i.postimg.cc/W4Nx0Vgy/V8-00017.png" />

相关推荐：

https://github.com/underwoodcassidy5/coqdxx/commit/113021d34a085a3a39b273724b0f9ad521024ea0

<img src="https://i.postimg.cc/SsKVxN8Z/V8-00004.png" />
相关推荐：

https://github.com/gutierrezjessica05/nukelg/blob/main/2026%E5%AE%98%E6%96%B9%E7%94%84%E9%80%89%EF%BC%9AVS%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C_%E6%98%A7%E7%84%89%E8%B4%AB%E8%BD%BD%E6%8A%91QKEZT.md

<img src="https://i.postimg.cc/ZYWtfJ2Z/V8-00011.png" />
相关推荐：

https://github.com/gutierrezjessica05/nukelg/commit/1eff21ef7327a9d59dc2302965b739ab3871fb83

<img src="https://i.postimg.cc/3Rw9xJm7/V8-00005.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
