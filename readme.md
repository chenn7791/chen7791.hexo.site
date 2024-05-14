<!--
 * @Author: Chenn
 * @Date: 2024-05-14 15:23:07
 * @LastEditors: Chenn
 * @LastEditTime: 2024-05-14 16:01:03
-->
博客根目录
path/to/blogs => https://github.com/chenn7791/chen7791.hexo.site

实际部署页面
path/to/blogs/.deploy_git => https://github.com/chenn7791/chenn7791.github.io.git


hexo 使用
https://hexo.io/zh-cn/docs/writing

创建文章或者新页面
```shell
$ hexo new [layout] <title>
// layout: 布局  post | draft（草稿） | page
// 默认布局 _config.yml -> default_layout
```
草稿发布
```
$ hexo publish [layout] <title>
// 草稿默认不会显示在页面中，您可在执行时加上 --draft 参数，或是在 _config.yml 中把 render_drafts 参数设为 true 来预览草稿。
 ```