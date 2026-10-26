# Peihan Li 的个人博客

基于 [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)，部署到 https://andyli429.github.io。

## 本地预览

安装 Ruby 3.3 和 Bundler 后运行：

```sh
bundle install
bundle exec jekyll serve
```

## 内容与配置

- `_posts/`：博客文章。DSpark 是保留完整样式与脚本的独立 HTML 文章。
- `_tabs/`：分类、标签、归档、项目及关于页面。
- `_config.yml`：站点信息、语言、头像和主题设置。
- `_data/contact.yml`：侧栏社交链接。

## 发布

推送到 `master` 后，GitHub Actions 自动构建、检查内部链接并部署。
也可在 Actions 中手动运行 **Build and Deploy**。

DSpark 的搜索摘要使用文章描述，避免将独立 HTML 的内嵌样式与脚本收录到搜索索引。
