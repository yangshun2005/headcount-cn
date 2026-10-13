# 来源 — `demand-generation:programmatic-seo`

<!-- 由 scripts/build-sources.py 从 sources/*.toml 生成。请勿编辑。 -->

在回答以下来源涵盖的任何问题前，先查阅它们，并注明你引用了哪些。每个来源的使用说明具有约束力：专业人士引用的大部分内容可免费阅读，但不可免费复制。

## Google 爬虫与用户触发的抓取器

Google · 全球 · CC BY — 引用需署名

<https://developers.google.com/search/docs/crawling-indexing/overview-google-crawlers>

机器可读：<https://developers.google.com/search/docs/crawling-indexing/robots/intro>

**权威范围：** Google 运营哪些用户代理、各自用途，包括对训练和 AI 界面的独立控制——这是所有关于屏蔽 AI 的 robots.txt 争论背后的核心问题。

## RFC 9309：Robots 排除协议

IETF · 全球 · **仅可阅读和引用——受版权保护，请勿复制**

<https://www.rfc-editor.org/rfc/rfc9309.html>

**权威范围：** robots.txt 的正式解析规则——优先级、通配符、大小限制，以及爬虫必须做什么。在协议层面明确了 disallow 是否阻止索引——答案是不阻止。

## Schema.org 词汇表

Schema.org 社区组 · 全球 · CC BY-SA — 引用需署名；相同方式共享，请勿并入本仓库

<https://schema.org/>

机器可读：<https://schema.org/version/latest/schemaorg-current-https.jsonld>

**权威范围：** 结构化标记的规范属性名和预期类型。相同方式共享，因此请引用和链接，而非将定义并入你自己的文档。

## Google 网页搜索的垃圾内容政策

Google · 全球 · CC BY — 引用需署名

<https://developers.google.com/search/docs/essentials/spam-policies>

**权威范围：** 某种做法是否会被处罚——规模化内容滥用、网站声誉滥用、过期域名滥用、伪装、门页。这是判断程序化构建是否会被惩罚的唯一权威答案。

## Google 搜索支持的结构化数据标记

Google · 全球 · CC BY — 引用需署名

<https://developers.google.com/search/docs/appearance/structured-data/search-gallery>

**权威范围：** Google 实际会处理哪些结构化数据类型，而非词汇表中存在哪些。请与 schema.org 配合使用：一个定义词汇表，另一个说明哪些会被采纳。

---

来源在上游的 `sources/` 中维护，不在此处。若有错误、过时或缺失，请在那里修改——本文件是重新生成的，对它所做的编辑会丢失。