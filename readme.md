<!--
 * @Author: Chenn
 * @Date: 2024-05-14 15:23:07
 * @LastEditors: Chenn
 * @LastEditTime: 2024-05-14 17:37:36
-->

Node 版本

```
➜  blogs git:(main) ✗ node -v
v16.14.0
```

博客根目录
path/to/blogs => https://github.com/chenn7791/chen7791.hexo.site

实际部署页面
path/to/blogs/.deploy_git => https://github.com/chenn7791/chenn7791.github.io.git

hexo 使用
https://hexo.io/zh-cn/docs/writing

使用主题
https://github.com/iGuan7u/Acetolog

主题修改-如何修改.njk文件
https://mozilla.github.io/nunjucks/templating.html

yml文件使用
https://www.runoob.com/w3cnote/yaml-intro.html

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
