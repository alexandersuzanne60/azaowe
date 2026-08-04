VS官方地址【Q-——333307——】VS官方地址【 辋芷《888yx●vip》 】
VS官方地址【Q-——333307——】VS官方地址【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

你是不是也遇到过这些问题？想写技术博客，但CSDN广告太多；想用WordPress，服务器成本又太高；想折腾VuePress，配置复杂到想放弃……其实，用 GitHub Pages + Hexo 就能免费搭建一个专属博客，完全掌控数据，还能绑定自己的域名。

 为什么选择Hexo？

在开始之前，先说清楚为什么这套方案值得你花半小时折腾：

- 免费托管：GitHub Pages 提供无限流量静态托管
- 极致速度：纯静态页面，国内访问通过CDN加速也能秒开
- Markdown写作：专注内容，不用跟富文本编辑器较劲
- 主题丰富：官方有200+主题，总有一款适合你的审美

如果你已经在用GitHub，那这套方案几乎是零门槛。下面我们直接进入实操。

 第一步：环境准备（5分钟）

你需要先装好两个工具，Node.js 和 Git。建议去官网下载LTS版本，一路Next安装即可。安装完成后，打开终端（Mac用Terminal，Win用PowerShell），输入以下命令验证：

```bash
node -v
git --version
```

能输出版本号，就说明环境OK了。

 第二步：安装并初始化Hexo（10分钟）

找个干净的文件夹，比如 `myblog`，然后执行：

```bash
npm install -g hexo-cli
hexo init myblog
cd myblog
npm install
```

这一步会下载Hexo框架和默认主题。看到 `INFO  Start blogging!` 字样，初始化就成功了。

小提示：如果 npm 下载慢，先执行 `npm config set registry https://registry.npmmirror.com` 切换国内镜像源。

 第三步：本地预览与写作（5分钟）

启动本地服务：

```bash
hexo server
```

浏览器访问 `http://localhost:4000`，你就能看到默认博客了。以后写文章，只要在 `source/_posts` 文件夹下新建 `.md` 文件，用Typora或VS Code编辑，开头加上这段配置：

```yaml
---
title: 我的第一篇文章
date: 2025-01-01 10:00:00
tags: [随笔]
---
```

写完保存，浏览器刷新就能看到新文章。

 第四步：部署到GitHub Pages（10分钟）

1. 在GitHub上新建仓库，名字必须叫 `你的用户名.github.io`
2. 打开 `_config.yml`，找到 `deploy` 部分，修改为：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

3. 依次执行三条命令：

```bash
npm install hexo-deployer-git --save
hexo clean
hexo deploy
```

等待几十秒，访问 `https://你的用户名.github.io`，你的博客就正式上线了！

 遇到问题怎么办？

最常见的报错是 `Repository not found`，一般有两种原因：
- 仓库名拼写错误
- Git身份未配置

先执行 `git config --global user.name "你的名字"` 和 `git config --global user.email "你的邮箱"`，再重新 `hexo deploy` 即可。

 进阶玩法（可选）

熟练之后，你还可以给博客换主题（比如热门的 `NexT`）、绑定自己的域名（阿里云或腾讯云买个域名，几十块一年）、添加评论系统（比如Giscus）。

---

如果你在搭建过程中卡在哪一步，欢迎在评论区留言，带上你的报错截图，我看到会第一时间回复。顺手点个 Star 支持一下，我会持续更新更多关于博客优化和自动化部署的干货。动手试试吧，你的专属博客只差这几行命令了。

相关推荐：

https://github.com/alvarezcharles0/xilnaw/blob/main/2026%E5%AE%98%E7%BD%91%E7%A7%91%E6%99%AE%EF%BC%9AV8%E5%B9%B3%E5%8F%B0app_%E8%9B%8B%E5%87%A1%E5%B1%85%E7%9F%A3%E6%AF%92INIJJ.md

<img src="https://i.postimg.cc/P5kgrYxk/V8-00014.png" />

相关推荐：

https://github.com/alvarezcharles0/xilnaw/commit/317c1e8f15db3aea3927a9bb63dd7c80bf67dccd

<img src="https://i.postimg.cc/nzw2jbGZ/V8-00006.png" />
相关推荐：

https://github.com/stoneconnor94/facjpk/blob/main/2026%E7%A7%91%E6%8A%80%E7%88%86%E7%82%B9%EF%BC%9AV8%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C_%E4%B8%94%E9%B9%8A%E5%92%8C%E7%A7%B8%E6%B4%9EJKHEV.md

<img src="https://i.postimg.cc/tJZ5FSB6/V8-00007.png" />
相关推荐：

https://github.com/stoneconnor94/facjpk/commit/de918dad587504bcbd4591230ac3e90bce56ec89

<img src="https://i.postimg.cc/nzw2jbGZ/V8-00006.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
