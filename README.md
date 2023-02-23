# Site Develop Guide

## Preparation

### Install Hugo
* For Windows
  1. 在[github release](https://github.com/gohugoio/hugo/releases)中下载预编译程序（下载带有hugo_extended_xxx 的版本，这里使用[hugo_extended_0.110.0_windows-amd64.zip](https://github.com/gohugoio/hugo/releases/download/v0.110.0/hugo_extended_0.110.0_windows-amd64.zip)）；
  2. 下载zip并解压到本地，如C:\Program Files\Hugo，然后将路径添加到环境变量;
  3. 在命令行中执行hugo version可检查安装是否正确;

### Install [hugo-academic-cli](https://github.com/wowchemy/hugo-academic-cli)(Optional)
* Function: Import publications from your reference manager to Hugo(Import publications from BibTex);
* Installation: pip3 install academic==0.5.1;
* Usage(To add a new publication): 
  1. Add the BibTex record of the publication to [publications.bib](./publications.bib) within the root directory of this repo;
  2. Use the cd command to navigate to your website folder(the root directory of this repo) in the terminal;
  3. Import your publications with: `academic import --bibtex publications.bib`;
  4. The generated output in the content/publication folder should be reviewed prior to publishing your site.

## Develop
* 开启本地测试服务器
  * 代码库根目录下开启终端并输入hugo server来启动测试服务器，@http://localhost:1313
  * hugo server会自动侦测源文件变动自动刷新页面
* 网页个性化配置
  * 参考[官方文档](https://wowchemy.com/docs/).
  * Hugo site structure
    > There are 3 main folders for Hugo sites:
    * `content/` for your Markdown-formatted content files (homepage, etc.)
    * `assets/media/` for your media files (images, videos)
    * `config/_default/` for your site configuration files
      * `config.yaml` to configure Hugo (site title, URL, Hugo options, enable page features)
      * `params.yaml` to configure Wowchemy options (SEO, site features)
      * `menus.yaml` to configure your menu links (if the menu is enabled in params.yaml)
      * `languages.yaml` to configure your site’s language or to set language-specific options in a multilingual site
* 网页部署
  * This site is deployed with [Netlify](https://www.netlify.com/)
    > Netlify is free and provides ultra-fast global access, automated deployment when you add content, and automatic HTTPS security.
  * When you commit the modification and push it, the site will be deployed automatically.

# [Hugo Academic Theme](https://github.com/wowchemy/starter-hugo-academic)

[![Screenshot](./preview.png)](https://wowchemy.com/hugo-themes/)

The Hugo **Academic Resumé Template** empowers you to easily create your job-winning online resumé, showcase your academic publications, and create online courses or knowledge bases to grow your audience.

[![Get Started](https://img.shields.io/badge/-Get%20started-ff4655?style=for-the-badge)](https://wowchemy.com/hugo-themes/)
[![Discord](https://img.shields.io/discord/722225264733716590?style=for-the-badge)](https://discord.com/channels/722225264733716590/742892432458252370/742895548159492138)  
[![Twitter Follow](https://img.shields.io/twitter/follow/wowchemy?label=Follow%20on%20Twitter)](https://twitter.com/wowchemy)

️**Trusted by 250,000+ researchers, educators, and students.** Highly customizable via the integrated **no-code, widget-based Wowchemy page builder**, making every site truly personalized ⭐⭐⭐⭐⭐

Easily write technical content with plain text Markdown, LaTeX math, diagrams, RMarkdown, or Jupyter, and import publications from BibTeX.

[Check out the latest demo](https://academic-demo.netlify.app/) of what you'll get in less than 10 minutes, or [get inspired by our academics and research groups](https://wowchemy.com/creators/).

The integrated [**Wowchemy**](https://wowchemy.com) website builder and CMS makes it easy to create a beautiful website for free. Edit your site in the CMS (or your favorite editor), generate it with [Hugo](https://github.com/gohugoio/hugo), and deploy with GitHub or Netlify. Customize anything on your site with widgets, light/dark themes, and language packs.

- 👉 [**Get Started**](https://wowchemy.com/hugo-themes/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy research community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=%23MadeWithWowchemy&src=typed_query)
- ⬇️ **Automatically import your publications from BibTeX** with the [Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli)
- 💡 [Suggest an improvement](https://github.com/wowchemy/wowchemy-hugo-themes/issues)
- ⬆️ **Updating?** View the [Update Guide](https://wowchemy.com/docs/hugo-tutorials/update/) and [Release Notes](https://github.com/wowchemy/wowchemy-hugo-themes/releases)

## We ask you, humbly, to support this open source movement

Today we ask you to defend the open source independence of the Wowchemy website builder and themes 🐧

We're an open source movement that depends on your support to stay online and thriving, but 99.9% of our creators don't give; they simply look the other way.

### [❤️ Click here to become a GitHub Sponsor, unlocking awesome perks such as _exclusive academic templates and widgets_](https://github.com/sponsors/gcushen)

<p align="center"><a href="https://wowchemy.com/templates/" target="_blank" rel="noopener"><img src="https://wowchemy.com/uploads/readmes/academic_logo_200px.png" alt="Hugo Academic Theme for Wowchemy Website Builder"></a></p>

## Demo image credits

- [Open book](https://unsplash.com/photos/J4kK8b9Fgj8)
- [Course](https://unsplash.com/photos/JKUTrJ4vK00)

## Latest news

<!--START_SECTION:news-->
* [Easily make an academic CV website to get more cites and grow your audience 🚀](https:&#x2F;&#x2F;wowchemy.com&#x2F;blog&#x2F;easily-make-academic-website&#x2F;)
* [What&#39;s new in v5.2?](https:&#x2F;&#x2F;wowchemy.com&#x2F;blog&#x2F;whats-new-in-v5.2&#x2F;)
* [What&#39;s new in v5.1?](https:&#x2F;&#x2F;wowchemy.com&#x2F;blog&#x2F;whats-new-in-v5.1&#x2F;)
* [Version 5.0 (February 2021)](https:&#x2F;&#x2F;wowchemy.com&#x2F;blog&#x2F;version-5.0-february-2021&#x2F;)
* [Version 5.0 Beta 3 (February 2021)](https:&#x2F;&#x2F;wowchemy.com&#x2F;blog&#x2F;version-5.0-beta-3-february-2021&#x2F;)
<!--END_SECTION:news-->
