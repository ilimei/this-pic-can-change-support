# 这图能改｜GitHub Pages 静态站

此目录包含网站首页、隐私说明、使用支持和 App 图标。页面使用原生 HTML 与内嵌 CSS，没有 JavaScript、CDN、分析或跟踪脚本；页面间和图片均使用相对路径，适用于仓库根目录或项目子路径部署。

## 预期发布配置

- 目标仓库：`this-pic-can-change-support`
- 目标分支：`codex/pages`
- GitHub Pages 发布源：`codex/pages` 分支根目录
- 预期网址：<https://ilimei.github.io/this-pic-can-change-support/>

发布时将本目录内的站点文件放到目标仓库 `codex/pages` 分支的根目录。以上是预期配置；本说明不表示仓库、Pages 设置或网站已经创建、部署或验证。

## 文件

- `index.html`：产品简介
- `privacy.html`：App 与网站托管数据的隐私说明
- `support.html`：常见问题和客服邮箱
- `assets/app-icon.png`：App 图标
- `.nojekyll`：让 GitHub Pages 按原样发布静态文件

## 本地预览

可直接在浏览器打开 `index.html`；也可在本目录运行一个本地静态文件服务器。无需安装构建工具或依赖。

网站托管方的数据收集方式以 [GitHub Pages 文档](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection)和 [GitHub 一般隐私声明](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)为准。
