# Bigfa
A theme for Typecho

演示网站：https://dearjohn.cn

![image](https://raw.githubusercontent.com/jozhn/Bigfa/master/screenshot.jpg)

## Getting Started
- Star本项目
- 下载本项目
- 解压并重命名为`Bigfa`
- 上传至theme文件夹下
- 启用

## Features
- `Instantclick.js` 全页面AJAX加载
- `Prism.js` 代码高亮
- `lately.js` [文章时间](https://github.com/Tokinx/lately)
- `view-image` [轻量级灯箱](https://github.com/Tokinx/ViewImage)
- 静态资源CDN设置
- 分类页面(新建页面选择模板即可)

## TO-DO List
- [ ] 完善设置
- [ ] 精简代码
- [ ] Disqus评论————暂时是原生评论，自用disqus

## 必需插件
[Stat](https://github.com/jozhn/Stat-for-Typecho)(统计文章浏览数)

## 已知Bug
若某分类下无文章的话，其分类页面的分类名称与slug均无输出，这是Typecho一直没有解决的问题，暂时无解。

## 使用方法
- 侧边栏的缩略图来自文章里的附件中第一张图片,请先在后台设置默认缩略图
- 关于页面和分类页面需要手动选择模板新建页面
- 分类的缩略图请自己上传到`Bigfa/img/category/`目录下，并命名为目录slug+`.jpg`
- 头像和logo在后台设置
- 在希望使用灯箱的图片前后分别插入代码`<ul class="view-image">`和`</ul>`
