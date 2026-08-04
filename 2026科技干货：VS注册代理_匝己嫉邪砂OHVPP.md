VS注册代理【Q-——333307——】VS注册代理【 辋芷《888yx●vip》 】
VS注册代理【Q-——333307——】VS注册代理【 辋芷《888yx●vip》 】

 从零到一：用GitHub Pages搭建个人博客，看这一篇就够了

你是不是也收藏了十几个“搭建教程”，结果打开一看全是命令行，直接劝退？别担心，今天这篇GitHub Pages搭建教程，不跟你扯虚的，我直接把踩过的坑和老手都在用的精简流程给你整理出来。全程图文思路，新手友好，三分钟上手。

 第一步：仓库创建，别选错了选项

登录你的GitHub，点击右上角绿色按钮 `New repository`。这里有个高频错误点：仓库名必须填 `<你的用户名>.github.io`（比如 `zhangsan.github.io`）。选 `Public`，然后勾选 `Add a README file`，直接 Create repository。

> 百度搜索小贴士：如果你搜“GitHub Pages 部署失败”，90%是这一步的仓库命名不规范，文章标题写“Github Pages教程”，记得加上“仓库命名”这个关键词，命中率更高。

 第二步：换主题，别从零写代码

创建完仓库，点击顶部的 `Settings`，往下拉到 `Pages` 栏目。在 `Source` 里选 `Deploy from a branch`，分支选 `main`，根目录选 `/ (root)`，保存。这时候，你访问 `https://你的用户名.github.io`，看到的是一个默认的静态页面。

想换个好看的模板？直接在 GitHub 的 Marketplace 或百度搜 `jekyll-theme` 关键词，找到 `_config.yml` 文件，把 `theme: 主题名` 这一行改掉，提交代码，一分钟换肤。

 第三步：写文章，用Typora+Git桌面版

不要每次都登录网页端写。本地安装 [Typora]（免费Markdown编辑器）和 [Git Desktop]（可视化提交工具）。新建 `.md` 文件，文件头加上这段YAML格式的元数据：

```yaml
---
layout: post
title: 我的第一篇文章
date: 2025-01-01
---
```

写完点 `Commit to main`，再点 `Push origin`。推送即发布，这个工作流是最高效的，也是搜索引擎最喜欢的“活跃更新”信号。

 常见报错自查（索引列表）

- 404错误：检查仓库名是否严格等于 用户名.github.io
- 样式丢失：检查 `_config.yml` 末尾是否有空格或编码错误
- 没生效：GitHub Pages 有1分钟的更新延迟，刷新一下浏览器

 结尾互动 & 下期预告

你在搭建时卡在哪个步骤了？ 或者你用了什么冷门好玩的主题？欢迎在评论区吐槽、晒图，我看到都会回。

下一期准备聊聊 “如何用Github Actions自动推送文章” ，彻底摆脱手动拖拽文件。如果你不想错过，点个关注，下次更新不迷路。这篇教程如果帮到你，也别吝啬一个 点赞/收藏，让更多头疼的同学看到它。

相关推荐：

https://github.com/nguyenmark0/dznovc/blob/main/%E6%B7%B1%E5%BA%A6%E5%AE%9E%E6%93%8D%E6%95%99%E7%A8%8B%EF%BC%9AV8%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C_%E6%8B%93%E6%95%A6%E7%94%98%E9%9D%99%E5%95%84WDIPP.md

<img src="https://i.postimg.cc/2ysxGQJ5/V8-00009.png" />

相关推荐：

https://github.com/nguyenmark0/dznovc/commit/1bc6a9c4a6acf76ecb6535d742b12b1eca46f462

<img src="https://i.postimg.cc/W4Nx0Vgy/V8-00017.png" />
相关推荐：

https://github.com/millerdonna9312/pwnxnv/blob/main/2026%E5%AE%98%E7%BD%91%E6%95%99%E7%A8%8B%EF%BC%9AV8%E4%B8%BB%E7%AE%A1%E5%AE%98%E6%96%B9_%E9%81%93%E4%B9%88%E9%82%AA%E5%8F%B2%E7%97%9BSLEMZ.md

<img src="https://i.postimg.cc/ZYWtfJ2Z/V8-00011.png" />
相关推荐：

https://github.com/millerdonna9312/pwnxnv/commit/b5f08072a444c2bfe0b799d563c609e360d26aa7

<img src="https://i.postimg.cc/J7sVTRgT/V8-00010.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
