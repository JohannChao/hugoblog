---
title: "UserDoc"
slug: User-Document
date: 2023-10-27T14:44:43+08:00
categories:
- userDoc
tags:
- userDoc
thumbnailImagePosition: left
thumbnailImage: //d1u9biwaxjngwg.cloudfront.net/japanese-test-post/peak-140.jpg
summary: 这是一个简单用户说明
showActions: true
showSocial: true
---

{{< toc >}}

# Hugo Quick start

## Create a site

```
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
hugo server
```
## Add content

```
hugo new content posts/my-first-post.md
```

## Publish the site

```
# 启动Hugo的开发服务器来查看站点,包含草稿内容
hugo server -D
# 启动Hugo的开发服务器来查看站点,不包含草稿内容
hugo server 
# 发布网站，不希望包含草稿、未来或过期的内容
hugo
```



# tranquilpeak主题说明

[主题演示](https://tranquilpeak.kakawait.com/archives/)

## 前置事项说明
- disqusIdentifier: 定义一个唯一字符串，用于在 Disqus 系统中查找页面的线程。
- keywords: 为搜索引擎定义关键字。也可以在hugo配置文件中定义全局关键字。
- clearReading: 隐藏所有文章页面的边栏，让文章占满整个页面以提高阅读效率，并欣赏宽幅图和	封面图片。如果 params.sidebarBehavior 等于 3 或 4 则无用（true：启用，false：禁用）。	    默认行为：主题配置文件中的 params.clearReading 值。
- autoThumbnailImage: 如果没有缩略图，则自动选择封面图片或文章图库中的第一张照片作为缩略图。 autoThumbnailImage 会覆盖主题配置文件中的 autoThumbnailImage 设置。
- thumbnailImage: 索引视图中显示的图像。
- thumbnailImagePosition: 在索引页面标题右侧（右侧、左侧或底部）显示缩略图。 该设置会覆盖主题配置文件中的 thumbnailImagePosition 设置。
- metaAlignment: 元（标题、日期和类别）对齐方式（右对齐、左对齐或居中对齐）。默认行为：左对齐
- coverImage: 在帖子视图中以全尺寸显示在帖子顶部的图片。如果未配置缩略图，封面图片也将用作缩略图。
- coverSize: 部分：封面图像占屏幕高度的一部分（60%），完整：封面图像占整个屏幕高度。
- coverCaption: 在封面图片下添加标题
- coverMeta:  in：在封面图片上显示帖子元（标题、日期和类别）, out：像往常一样在封面图片下显示元（标题、日期和类别）。默认行为：in
- gallery: 图片显示在帖子末尾的图片库（带花式框）中。如果未配置缩略图和封面图片，则使用第一张照片作为缩略图
- comments: true：显示帖子的评论。 
- showDate: true：为真时显示日期（默认值）
- showTags: true：显示此页面的标签。
- showPagination: true：显示分页。
- showSocial: true：显示社交按钮，如分享到 Twitter、Facebook...
- showMeta: true：显示帖子元（日期、类别）。
- showActions: true：显示帖子操作（导航、分享链接）。
- summary: 在主页上显示自定义摘录文本。
- link: 覆盖指定文章/页面的默认 URL/链接。


