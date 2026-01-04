---
title: 扉页
layout: home
nav_order: 0
---

# 聚焦用 Jekyll 编写图书

![one-book-one-website](assets/images/facebook.jpg){: style="float: right"}[Jekyll] 是一款将使用简单标识语言（例如 Markdown）编写的内容转换为网页，并提供运行网站的软件。那么，我们能不能将书的内容通过简单标识语言进行编写，然后在利用 [Jekyll] 将其转换为网页，而且通过目录将整本书组织成一个网站的形式呢？理论上是可行的。可能需要一些思维的转换，例如我们可以将网站的“首页”变成图书的“序言”了。

如果整本书以一个网站的形式呈现，如果作者愿意，可以将其托管到一些网站，例如 [GitHub Pages] 等，这样就可以实现图书的共享了。如果作者不想共享，也可以自己保留整个网站。而且，整个图书网站应该也可以将其转换成 EPUB 或者 PDF 格式等。

*******

This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^1] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

If you want to maintain your docs in the `docs` directory of an existing project repo, see [Hosting your docs from an existing project repo](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md#hosting-your-docs-from-an-existing-project-repo) in the template README.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
