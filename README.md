# 仪器与精密测量领域英文文献专业翻译范式

> A professional translation, verification, and PDF-delivery workflow for scientific literature in instrumentation and precision measurement.

![仪器与精密测量领域英文文献专业翻译范式封面](./assets/cover.svg)

[![Release](https://img.shields.io/github/v/release/CodeLab-Aurora/precision-measurement-translation-guide?display_name=tag&sort=semver)](https://github.com/CodeLab-Aurora/precision-measurement-translation-guide/releases/latest)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-0b7285.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Stars](https://img.shields.io/github/stars/CodeLab-Aurora/precision-measurement-translation-guide?style=flat)](https://github.com/CodeLab-Aurora/precision-measurement-translation-guide/stargazers)

这是一套面向仪器科学、精密测量、计量学、光学工程和光电检测等方向的英文科技文献专业翻译范式。它围绕 ChatGPT 辅助工作流，强调术语冻结、图表与公式保真、跨章节核验、可复算评分和发布前质量闸门。

## 适用领域

- 仪器科学与精密测量
- 计量学与测量不确定度
- 光学工程、激光与光栅干涉
- 光电检测、位移测量与信号处理
- 机械误差与多自由度测量

## 核心特点

- 以英文原始 PDF 为最高权威来源，不让旧译文或 OCR 覆盖原文事实。
- 对术语、变量、公式、图内参数和原始表格建立可追溯核验记录。
- 图片与表格采用原始 PDF 图像保真策略，避免重绘、重排和数据漂移。
- 使用 QA-1、QA-2 和 RC 阶段隔离内部审校与正式版本。
- 以问题清单、逐项扣分和硬门槛约束“先打高分、后补理由”的虚假评分。

## 工作流

```mermaid
flowchart LR
    A[结构盘点] --> B[术语冻结]
    B --> C[逐段翻译]
    C --> D[图片与表格保真]
    D --> E[公式三层核验]
    E --> F[跨章节与数值核验]
    F --> G[QA-1 独立审校]
    G --> H[QA-2 盲审式终审]
    H --> I[RC 发布检查]
    I --> J[正式版本]
```

## 阅读与下载

- [在线阅读全文](./guide/仪器与精密测量领域英文文献专业翻译范式.md)
- [从 Releases 下载最新版 Markdown 文件](https://github.com/CodeLab-Aurora/precision-measurement-translation-guide/releases/latest)
- [查看版本变更记录](./CHANGELOG.md)

GitHub 会自动为每个 Release 提供源码 ZIP 和 TAR.GZ。需要关注更新时，可以在仓库页面选择 **Watch → Custom → Releases**。

## 使用方式

1. 阅读指南中的输入文件、术语冻结、正文翻译、图表和公式处理规则。
2. 根据任务阶段使用文末的主提示词、续译提示词、终稿审校提示词或修订提示词。
3. 始终保留英文原始 PDF，并对技术结论、数值、公式和图表进行人工复核。
4. 只有全部质量闸门通过后，才生成并发布正式版本。

## 更新约定

- 小型文字修正通过普通提交保留历史。
- 正式内容升级同步更新指南版本号与 `CHANGELOG.md`，并创建新的 Git 标签和 Release。
- 不覆盖旧版本，不强制重写公开历史。

## 许可

除另有说明外，本仓库中的原创文档与原创配图采用 [Creative Commons Attribution 4.0 International](./LICENSE) 许可。转载、改编和再分发时，请保留作者标识 `CodeLab-Aurora`、原始仓库链接、许可证链接，并说明是否做过修改。

## 免责声明

本项目提供的是翻译与质量控制方法，不构成对任何具体译文准确性、出版合规性或学术适用性的保证。使用者应自行核对原文，并遵守所在机构、期刊、出版社及适用法律关于版权、研究诚信和 AI 辅助工具披露的要求。

本项目为独立的社区文档，与 OpenAI 不存在隶属、合作或官方背书关系。文中涉及的产品和商标归其各自权利人所有。

如果这套范式对你的科研阅读或翻译工作有帮助，欢迎点击右上角 **Star** 收藏。
