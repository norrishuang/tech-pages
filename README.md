# tech-pages

个人技术分享静态站点，通过 [GitHub Pages](https://pages.github.com/) 对外发布。

## 使用方式

- 每篇技术分享是一个独立的 HTML 文件，按主题存放在对应目录下（例如 `emr/`）。
- 根目录的 [index.html](index.html) 是站点首页，汇总并链接各主题下的文章，方便直接浏览。
- 新增文章时：
  1. 在对应主题目录下添加 HTML 文件（如果是新主题，新建一个目录）。
  2. 在 `index.html` 中补充一条链接。

## 目录结构

```text
.
├── index.html   # 站点首页，文章导航
├── emr/         # EMR 相关技术文章
└── opensearch/  # OpenSearch 相关技术文章
```

## 现有文章

### EMR

- [EMR Managed Scaling 缩容规则与最佳实践](emr/EMR%20Managed%20Scaling%20%E7%BC%A9%E5%AE%B9%E8%A7%84%E5%88%99%E4%B8%8E%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5.html)

## 部署

本仓库通过 GitHub Pages 直接从 `main` 分支发布，无需额外构建步骤。
