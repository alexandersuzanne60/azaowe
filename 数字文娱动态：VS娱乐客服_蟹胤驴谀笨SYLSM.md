VS娱乐客服【Q-——333307——】VS娱乐客服【 辋芷《888yx●vip》 】
VS娱乐客服【Q-——333307——】VS娱乐客服【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

还在羡慕别人拥有独立博客？其实利用 GitHub Pages 和 Hexo，你也能在半小时内免费搭建一个高速、稳定的个人网站。无需购买服务器，甚至不需要懂代码。今天这份保姆级教程，手把手带你搞定。

 为什么选择 GitHub Pages + Hexo？

- 完全免费：托管在 GitHub 服务器上，不花一分钱。
- 加载速度快：全球 CDN 加速，国内访问体验友好。
- 版本管理：文章即代码，自动备份，永不丢失。
- SEO 友好：静态页面天生对搜索引擎蜘蛛爬取友好，利于 百度收录。

 第一步：环境准备（3分钟）

1. 安装 Node.js（推荐 LTS 版本）。
2. 注册一个 GitHub 账号。
3. 本地安装 Git 工具。

> 互动时刻：在评论区留下“开搭”，我会把常见报错排坑清单发给你！

 第二步：本地搭建 Hexo 项目（5分钟）

打开命令行，依次执行：

```bash
npm install -g hexo-cli
hexo init myblog
cd myblog
npm install
```

依次执行后，输入 `hexo s`，浏览器访问 `http://localhost:4000`，看到默认页面即成功。

 第三步：部署到 GitHub Pages（核心）

1. 在 GitHub 新建仓库，命名为 `你的用户名.github.io`。
2. 修改根目录 `_config.yml` 文件：
   - `url` 改为你的 GitHub Pages 地址。
   - `deploy` 配置 `type: git`，并填入仓库地址。
3. 安装部署插件：`npm install hexo-deployer-git --save`。
4. 一键发布：`hexo clean && hexo g && hexo d`。

访问 `https://你的用户名.github.io`，你的个人博客已经上线！

 第四步：SEO 优化与百度收录加速

想要被百度快速索引，务必配置以下三个关键点：

- 提交 Sitemap：安装 `hexo-generator-sitemap` 插件，生成 `sitemap.xml`。
- 配置 robots.txt：允许蜘蛛抓取，禁止后台目录。
- 主动推送：前往百度搜索资源平台添加站点，并验证所有权。

 进阶玩法：自定义域名与主题美化

在仓库的 `Settings` → `Pages` 自定义域名，然后去阿里云添加 `CNAME` 解析记录。主题推荐使用 Next 或 Fluid，内置暗黑模式、阅读统计、文章目录等高级功能。

搭建过程中如果遇到白屏、部署失败或自定义域名解析问题，欢迎在下方留言提问，我会逐一回复。觉得有用，点赞收藏 这篇文章，方便下次搭建时快速查找！

相关推荐：

https://github.com/cruzdenise0/avxylh/blob/main/2026%E7%A7%91%E6%8A%80%E7%88%86%E7%82%B9%EF%BC%9AV8%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C_%E5%AE%89%E5%8E%A9%E9%80%94%E5%81%B6%E7%9F%ADMNBJR.md

<img src="https://i.postimg.cc/d05pBf9J/V8-00019.png" />

相关推荐：

https://github.com/cruzdenise0/avxylh/commit/41abf0b824e860038d48db33d507c314d48a7ca5

<img src="https://i.postimg.cc/d0w4g90d/V8-00002.png" />
相关推荐：

https://github.com/clarkalyssa3349/mrznkk/blob/main/2026%E6%9D%83%E5%A8%81%E8%AE%B2%E8%A7%A3%EF%BC%9AV8%E5%AE%98%E7%BD%91%E5%BC%80%E6%88%B7_%E6%B0%90%E6%96%AD%E8%AF%9A%E9%9F%B6%E5%87%B3QWDEY.md

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />
相关推荐：

https://github.com/clarkalyssa3349/mrznkk/commit/a810b1da1879980e548af8db22be1fc86672aca4

<img src="https://i.postimg.cc/YCfJ40GQ/V8-00016.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
