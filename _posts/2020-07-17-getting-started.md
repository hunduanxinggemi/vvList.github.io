---
layout: post
title: 这是一个歌词
featured-img: ruben-santander-69158_lg
---

## Getting started

[GitHub Pages](https://pages.github.com) can automatically generate and serve the website for you.
Let's say you have a username/organisation `my-org` and project `my-proj`; if you locate Jekyll source under `docs` folder of master branch in your repo `github.com/my-org/my-proj`, the website will be served on `my-org.github.io/my-proj`.
The good thing about coupling your documentation with the source repo is, whenever you merge features with regarding content to master branch, it will also be published in the webpage instantly.

1. Just download the source from [github.com/janczizikow/sleek](https://github.com/janczizikow/sleek/) into your repo under `docs` folder.
2. Edit site settings in  `_config.yml` file according to your project.
3. Replace `favicon.ico` and `img/logonav.png` with your own logo.

## Writing content

### Docs

Docs are [collections](https://jekyllrb.com/docs/collections/) of pages stored under `_docs` folder. To create a new page:

**1.** Create a new Markdown as `_docs/my-page.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: My Page
permalink: /docs/my-page/
---

Hello World!
```

**2.** Add the pagename to `_pages/docs.yml` file in order to list in docs navigation panel:

```
- title: My Group Title
  docs:
  - my-page
```

### Blog posts

Add a new Markdown file such as `2017-05-09-my-post.md` and write the content similar to other post examples.

### Pages

The home page is located under `index.md` file. You can change the content or design completely different welcome page for your taste.

In order to add a new page, create a new html or markdown file under root directory and link it in `_includes/header.html`.

### Images TODO

Introduce gulp optimization

Breakpoint | Image Type | Width | Retina
------------ | ------------ | ------------- | -------------
xs |Post Thumb | 535px | 1070px
sm |Post Thumb | 500px| 1000px
md |Post Thumb | 329.375px | 658.75px
lg |Post Thumb | 445.625px | 891.25px
xl |Post Thumb | 353.125px | 706.25px


Breakpoint | Image Type | Width | Retina
------------ | ------------ | ------------- | -------------
xs |Post Hero | 535px | 1070px
sm |Post Hero | 500px| 1000px
md |Post Hero | 329.375px | 658.75px
lg |Post Hero | 445.625px | 891.25px
xl |Post Hero | 353.125px | 706.25px



`歌名：模特`
```
演唱：李荣浩
作词：李荣浩
作曲：李荣浩

穿华丽的服装 为原始的渴望而站着
用完美的表情 为脆弱的城市而撑着
我冷漠的接受 你焦急的等待也困着

像无数生存在橱窗里的模特
除了灯以外 我还能看见什么
除了光以外 我还能要求什么
除了你以外 还能倚赖哪一个

在千里以外 在呼喊的是什么
在百年以后 想回忆的是什么
在离开以前 能否再见那一刻

记得 你的眼睛将会亮着
我的手臂将会挥着
谁说世界早已没有选择
趁着 我会喜怒你会哀乐
唱几分钟情歌
没什么 至少证明我们还活着

像单纯的蝴蝶 为玫瑰的甜美而飞着
像顽皮的小猫 为明天的好奇而睡着
是混乱的时代 是透明的监狱也觉
是不能继续在橱窗里做模特

除了风以外 我还能听到什么
除了尘以外 我还能拒绝什么
除了你以外 还能倚赖哪一个
在千里以外 在呼喊的是什么
在百年以后 想回忆的是什么
在离开以前 能否再见那一刻

记得 你的眼睛将会亮着
我的手臂将会挥着
谁说世界早已没有选择
趁着 我会喜怒你会哀乐
唱几分钟情歌
没什么 至少证明我们还活着

记得 你的眼睛将会亮着
我的手臂将会挥着
谁说世界早已没有选择
趁着 我会喜怒你会哀乐
唱几分钟情歌
没什么 至少证明我们还活着 

```

Happy Ending!
