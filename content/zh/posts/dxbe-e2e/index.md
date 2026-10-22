---
title: dxbe 端到端部署
date: 2026-10-20T10:00:00+08:00
tags: [部署, 静态站点]
slug: dxbe-e2e
translationKey: dxbe-e2e
summary: 从 GitHub 安装 dxbe，构建站点，再部署到 GitHub Pages。
---

这个站点用于验证 `dxbe` 从 GitHub 安装到 GitHub Pages 部署的完整链路。

## 本地构建

安装、构建和检查都在博客仓库里完成：

```bash
npm ci
npx dxbe check
```

构建产物在 `dist/`，搜索索引由 Pagefind 生成。

## 公式

行内公式 $E = mc^2$，块级公式：

$$
sum_{i=1}^{n} i = rac{n(n+1)}{2}
$$

## 内部链接

返回[关于页面](/about/)，或切换到[英文版本](/en/posts/dxbe-e2e/)。项目页部署时，这两个链接都应该带上仓库的 base path。
