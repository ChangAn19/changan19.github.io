# 内容来源与核验

核验日期：2026-09-29。

- 姓名（Chan Xu）、单位、4 项研究兴趣、6 篇论文范围及初始作者顺序来自用户提供的 [Google Scholar 主页](https://scholar.google.com/citations?user=MgbQBswAAAAJ&hl=en&pagesize=100)。
- 中文姓名“许阐”通过 [NIMTE 官方论文目录](https://cnitech.cas.cn/research/archives/article/index_86.html) 中 Upper-Limb 论文的中英文作者对应关系确认。
- 论文题名、完整作者、刊物、DOI、正式卷期页码通过各篇 DOI 的 Crossref 注册元数据核对；具体 API URL 保存在 `content.json` 的 `metadata_source`。
- 2025 TII 另有 [NIMTE 官方新闻](https://www.nimte.ac.cn/news/progress/202502/t20250227_7536719.html) 与 [方灶军官方主页](https://english.nimte.cas.cn/scientists/faculty/202512/t20251210_1135837.html) 交叉确认。
- EVT 论文另有 [NIMTE 官方新闻](https://www.nimte.ac.cn/news/progress/202607/t20260703_8237602.html) 支持。

信息取舍：

- 没有确认职称、学历和邮箱，故未填入。
- 没有用户提供的授权头像，使用姓名与文字标识。
- MAEIE 论文在机构目录有 2026 年记录；主页采用 Google Scholar、会议名称和 Crossref 出版日期对应的 2025 年。
- 未确定正式卷期的 Early Access 论文不将临时页码 1–N 当作正式分页写入。
- 只使用 Scholar 主页列出的 6 篇论文，未导入同名作者的其他论文。
- 初版没有从本地工作区复制或发布论文 PDF。2026-09-29 更新根据作者明确指定的接收稿添加了下述论文及 PDF。

## 已接收论文更新

Interaction-Stiffness-Guided Basis Allocation in Dynamic Movement Primitives for Efficient Skill Transfer：

- 作者指定接收日期为 2026-09-25，DOI 为 `10.1109/TII.2026.3738846`，要求单列 Accepted 栏目。
- 题名、9 位作者及顺序按作者提供的 12 页 PDF 首页提取；首页注明已被 IEEE Transactions on Industrial Informatics 接收。
- 发布副本新增一页作者稿说明，列出接收日期、DOI、引文与 IEEE 版权声明；后续 12 页原稿内容流逐页保持一致。未修改作者原文件。
- 本条未虚构 Scholar 条目、卷期或正式分页；BibTeX 明确记录 Accepted for publication。

政策与部署：

- [IEEE 发表后分享政策](https://journals.ieeeauthorcenter.ieee.org/become-an-ieee-journal-author/publishing-ethics/guidelines-and-policies/post-publication-policies/)
- [GitHub Pages 创建指引](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [GitHub Pages 自定义工作流](https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages)

## Research Works 版式更新

- 按作者指定的 [Chang Xu 主页](https://chang-xu.github.io/) 参考简洁白底、青色强调和横向论文列表，独立实现样式和筛选功能；没有复制该站的个人资料、照片、论文图片或代码。
- 页面主内容只保留 Research Works；Accepted 作为其中独立分组，保留原接收日期、DOI、PDF 与版权声明。
- SC-DMPs 缩略图来自作者指定原始 PDF 第 4 页 Fig. 1（已发布 PDF 对应第 5 页），仅裁去页眉、图注及外围正文，保留完整图内内容。
- 主题标签依据已有论文标题分类，仅用于列表筛选，不构成新增研究成果或评奖信息。

## 其余论文配图

作者授权从其论文整理目录中的对应 PDF 提取以下原图。按首页题名和作者核对后，以图中实际边界裁切为 PNG，保留完整图内内容和原始比例。

| 主页论文 | 原 PDF 页码及图号 | 站点图片 |
| --- | --- | --- |
| Extreme Value Theory-Driven Robust Feature Selection With Application to Estimation of Interaction Stiffness | 第 4 页 Fig. 1，NF-MRMR 总览 | `assets/evt-feature-selection.png` |
| Learning Neural Autonomous Dynamical Systems From Few Demonstrations | 第 4 页 Fig. 1，few-shot NADS 框架 | `assets/neural-ds-overview.png` |
| Geometric Regularization for Robust Learning of Neural Autonomous Dynamical Systems From Demonstrations | 第 4 页（印刷页 11843）Fig. 2，GR-NADS 方法总览 | `assets/geometric-ds-overview.png` |
| sEMG-Only Interaction Stiffness Estimation for Contact-Rich Human-Robot Collaboration | 第 4 页 Fig. 1，实验平台与任务示意 | `assets/semg-stiffness-overview.png` |
| Robust Feature Selection by Removing Noise Entropy Within Mutual Information for Limited-Sample Industrial Data | 第 3 页（印刷页 3915）Fig. 1，MNFR-MR 框架 | `assets/noise-entropy-selection.png` |
| An Upper-Limb Endpoint Stiffness Estimation Method for High-Load Tasks | 第 2 页 Fig. 1，方法框架 | `assets/upper-limb-stiffness.png` |

本次更新仅增加现有论文的配图，原 PDF 保留在作者本机；主页原有论文信息、接收稿下载地址和版权声明沿用既有记录。
