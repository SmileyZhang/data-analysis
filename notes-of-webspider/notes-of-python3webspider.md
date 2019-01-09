### 常用链接整理
[scrapy官方文档](https://doc.scrapy.org/en/latest/index.html)
### cmd常用命令行整理
进入当前文件夹内的下一级（如`name`）文件夹：
```
cd name
```
返回上一级文件夹：
```
cd ..
```
列出当前文件夹内的所有文件和下一级文件夹：
```
dir
```
按树形结构展示当前文件夹内的所有文件夹（不止下一级）：
```
tree
```
按树形结构展示当前文件夹内的所有文件和文件夹（不止下一级）：
```
tree /f
```
按树形结构展示当前文件夹内相对路径为`\name\`的所有文件和文件夹（不止下一级）：
```
tree name /f
```
### 写这篇笔记时偶然获得的一些小tips
windows下文件路径分隔符为`\`，网址分隔符为`/`。
### 13.2 scrapy基本操作
#### 目的
爬取quotes.toscrape.com（一共10页）的所有谚语、作者、标签。
#### 步骤
打开anaconda prompt，依次输入指令：
```
scrapy
scrapy startproject tutorial
```
此时在`user\username\`下会出现新文件夹`tutorial`，里面是新项目的基本文件，框架如下：
```
│  scrapy.cfg
│
└─tutorial
    │  items.py
    │  middlewares.py
    │  pipelines.py
    │  settings.py
    │  __init__.py
    │
    ├─spiders
    │  │  __init__.py
    │  │
    │  └─__pycache__
    └─__pycache__
```
继续输入指令：
```
cd tutorial
scrapy spider quotes quotes.toscrape.com
```
`tutorial\spiders\`下会出现文件`quotes.py`，用于设置爬取和解析规则。
修改`item.py`：
```python
# -*- coding: utf-8 -*-

# Define here the models for your scraped items
#
# See documentation in:
# https://doc.scrapy.org/en/latest/topics/items.html

import scrapy


class QuoteItem(scrapy.Item):
    # define the fields for your item here like:
    # name = scrapy.Field()
    text = scrapy.Field()
    author = scrapy.Field()
    tags = scrapy.Field()
```
前后对比：
![items.py对比](https://upload-images.jianshu.io/upload_images/15820840-1881e27847c82a2d.JPG?imageMogr2/auto-orient/strip%7CimageView2/2/w/416)
