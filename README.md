# Chan Xu · 许阐

Personal academic homepage: https://changan19.github.io/

This repository contains the published static homepage. GitHub Pages serves the
`main` branch from `/(root)`. The page includes its own CSS and JavaScript, so no
build system, external fonts, or paid service is required.

The homepage focuses on Research Works, with publication thumbnails, year groups,
topic and first-author filters, English/Chinese switching, and PDF downloads.

## 更新主页

- `index.html`：已发布主页，可以直接编辑文字。
- `publications.bib`：论文引用文件。
- `academic-homepage-source.zip`：完整可编辑源码，含 `content.json`、生成器、样式与自动发布工作流。
- `SOURCES.md`：公开资料的核验来源。

建议下载并解压源码包，编辑 `content.json` 后运行 `python build.py` 和
`python package_site.py`，再将生成的 `upload/` 内文件上传替换当前仓库文件。
提交到 `main` 后 GitHub Pages 会更新网站。

如改用源码包中的 GitHub Actions 发布方式，请先按源码 README 保留目录结构，
再在 Settings → Pages 中将 Source 改为 GitHub Actions。

## 作者接收稿

主页单独列出 Accepted / 已接收论文，并显示接收日期、DOI 和作者接收稿下载。
PDF 与 index.html 一起上传到仓库根目录，链接与文件名必须对应。
添加接收稿前，请按每篇论文的出版协议确认版本与分享权利，在 PDF 首页及网页
条目加入相应版权声明、完整引文与 DOI。不要将非开放获取论文的出版商排版版
或校样当作接收稿上传。

IEEE policy: https://journals.ieeeauthorcenter.ieee.org/become-an-ieee-journal-author/publishing-ethics/guidelines-and-policies/post-publication-policies/
