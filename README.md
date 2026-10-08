# Yao Open Prompts

[网页导航](https://yaojingang.github.io/yao-open-prompts/) · [完整目录](CATALOG.md) · [English README](README.en.md) · [英文提示词](prompts-en/README.md) · [GitHub 仓库](https://github.com/yaojingang/yao-open-prompts)

《姚金刚提示词合集》的开源版本，一个覆盖提示词工程、工作、学习、内容、营销和生活场景的中英双语 AI 提示词库。

本仓库从原始合集文档、书籍配套模板和后续提示词目录中整理出 **136** 个中文提示词文件，并按场景重新分类。每个提示词保留可复制的正文，去除了原文中不适合放入开源仓库主体的教程推广、效果截图、视频附件说明和 HTML 样式残留。

系列型内容会优先合并成主题合集，例如 `50个 Nano Banana 创意提示词` 和 `Nano Banana PPT 场景提示词合集`，避免仓库目录被大量零散短提示词打散。

近期补充重点来自 `05-Prompts/Generators`、`05-Prompts/Meta`、`05-Prompts/GEO`、`05-Prompts/Scenarios/Learning`、`05-Prompts/Products` 和《AI营销：从SEO到GEO》提示词合集：智能元提示词系统升级到 V1.0，新增了合同生成、产品原型、网页 PPT V3、公众号 HTML、Schema.org GEO、GEO文章AI友好化改造、网页逆向、费曼提问学习、批判思维、36 个内容与运营类实战提示词、25 个 GEO 营销实战模板，以及宽幅知识插画信息图生成器。

## 重点推荐

**[智能元提示词设计与优化系统 V1.0](prompts/01-ai-methods/rtf-meta-prompt-system-v1.md)**：基于 RTF 增强架构，将自然语言需求编译为可直接使用的提示词，也能诊断、重构和优化已有提示词。系统固定交付证据化质量报告与正式提示词，并覆盖部署适配、边界控制和设计级静态测试。查看 [V1.0 升级说明](references/rtf-meta-prompt-system-v1-upgrade-notes.md)。

**[宽幅知识插画信息图生成器](prompts/06-ai-content/wide-knowledge-infographic-generator.md)**：把一段文案提炼为适合社交媒体和 PPT 展示的宽幅知识插画信息图，强调结构提炼、视觉分层和极简中文表达。

**[GEO文章AI友好化改造提示词](prompts/08-ai-marketing/geo-article-ai-friendly-transformation.md)**：面向已有文章做 GEO 优化改造，通过结构化重构、语义优化和证据强化，提升 AI 搜索可见度和引用率。

## 专题入口

**[《课程营销学》17 套配套提示词](prompts/08-ai-marketing/course-marketing/README.md)**：姚金刚创作，按定位 4 套、设计 6 套、售卖 4 套、运营 3 套组织。打开[独立 HTML 导航](https://yaojingang.github.io/yao-open-prompts/course-marketing.html)可搜索、筛选、编辑和一键复制，也可下载后离线使用。另附[逐章使用指南](references/course-marketing-guide.md)和[英文译本](prompts-en/08-ai-marketing/course-marketing/README.md)。原稿 3.5 与 2.6 内容重复，已保留对应说明并按独立正文去重。

**[36 个内容与运营提示词](prompts/06-ai-content/README.md)**：新增提示词已直接并入 `prompts/06-ai-content/`，采用与仓库其他提示词一致的文件命名方式，覆盖短视频文案、人设风格、平台运营、行业内容、直播转化、私域成交、AI 绘画、数据复盘和爆款重构。

**[25 个 GEO 营销实战模板](prompts/08-ai-marketing/README.md)**：从《AI营销：从SEO到GEO》提示词合集拆分，覆盖机会判断、原理分析、内容工程、信源建设、数据监测、增长诊断和合规风险。

**[English README](README.en.md)**：英文说明文档入口，对应导航到 [136 个英文提示词](prompts-en/README.md)，英文提示词按 `prompts/` 的相同路径完整镜像在 `prompts-en/` 下。

## 仓库结构

```text
prompts/                # 按场景分类的提示词正文
prompts-en/             # 英文同步版提示词
references/             # 推荐资源、第三方内容和外部项目索引
templates/              # 新增提示词模板
maintenance/            # 维护、评审、发布检查清单
scripts/                # 目录生成和仓库质量检查脚本
docs/                   # 提示词类型与代表提示词网页
README.en.md            # 英文说明文档
CATALOG.md              # 全量提示词索引
CHANGELOG.md            # 更新记录
CONTRIBUTING.md         # 贡献和持续迭代规则
```

## 分类

| 分类 | 数量 | 说明 |
| --- | ---: | --- |
| AI方法 | 8 | 元提示词、反编译、网页逆向和提示词工程方法。 |
| AI工作 | 10 | 面向企业、合同、销售、客服、产品原型、PPT、网页等生产力场景。 |
| AI学习 | 12 | 学习方法、记忆术、费曼提问、习惯养成和学习助理。 |
| AI生活 | 2 | 健康、亲子歌曲等生活场景。 |
| AI教育 | 4 | 儿童教育、互动学习页面和小游戏创作。 |
| AI内容 | 50 | 写作、润色、标题、公众号 HTML、短视频、内容运营、图像和 PPT 创意。 |
| AI编程 | 1 | 架构设计和编程协作。 |
| AI营销 | 46 | 课程定位、设计、售卖与运营，GEO 内容、信源建设、数据监测、增长诊断和合规风险。 |
| AI思考 | 3 | 批判思维、记忆、标题和思维类灵感提示词。 |

完整目录见 [CATALOG.md](CATALOG.md)。

## 使用方式

1. 在 [CATALOG.md](CATALOG.md) 中按场景找到提示词。
2. 打开对应 Markdown 文件，复制 `Prompt` 区域。
3. 将 `{{变量}}`、`[占位符]` 或示例内容替换为你的真实任务信息。
4. 在目标模型中测试输出，并根据结果记录版本迭代。

## 提示词文件规范

每个提示词文件包含统一 frontmatter：

```yaml
title: 提示词标题
category: 一级分类
subcategory: 子类
source_section: 原合集章节号
author: 作者或来源
version: 提示词版本
created: 创建日期
status: active | draft | third-party-review
tags: 标签列表
```

正文只保留三部分：标题、简介、Prompt。需要展示案例、评测截图、教程链接或长说明时，优先放到 `references/` 或后续的案例目录，不和可复制提示词正文混在一起。

## 持续更新机制

- 新增提示词：复制 [prompt-file-template.md](templates/prompt-file-template.md)，放到对应分类目录。
- 更新提示词：优先在原文件内提升 `version`，并在 [CHANGELOG.md](CHANGELOG.md) 记录变更。
- 调整分类：同步更新 frontmatter 的 `category/subcategory/tags`，然后重新生成目录。
- 质量检查：运行 `python3 scripts/check_repo.py`。
- 重建目录：运行 `python3 scripts/generate_catalog.py`。
- 重建网页：运行 `python3 scripts/generate_webpage.py`。
- 重建《课程营销学》专题：运行 `python3 scripts/generate_course_marketing.py`。
- 刷新英文目录：运行 `python3 scripts/generate_english_readmes.py`。
- 发布节奏：建议使用日期版本，如 `v2026.05.1`，每次发布前走 [release-checklist.md](maintenance/release-checklist.md)。

## 开源与来源策略

本仓库采用 **CC BY 4.0** 作为提示词内容许可；如果后续加入脚本或工具代码，可单独使用 MIT。明显第三方或转载内容不直接并入主提示词库，先放在 `references/` 或标记为 `third-party-review`，确认授权后再发布。
