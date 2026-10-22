---
title: Deploying dxbe end to end
date: 2026-10-20T10:00:00+08:00
tags: [deployment, static-site]
slug: dxbe-e2e
translationKey: dxbe-e2e
summary: Install dxbe from GitHub, build the site, and deploy it to GitHub Pages.
---

This site checks the full path from installing `dxbe` from a GitHub release to deploying on GitHub Pages.

## Local build

Install, build, and check inside the blog repository:

```bash
npm ci
npx dxbe check
```

The output goes to `dist/`; Pagefind builds the search index.

## Math

Inline math $E = mc^2$, and a display equation:

$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

## Internal links

Return to the [about page](/en/about/), or switch to the [Chinese version](/posts/dxbe-e2e/). With a project-page deployment, both links should include the repository base path.
