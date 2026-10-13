# 来源 — `data-analytics:data-engineering`

<!-- 由 scripts/build-sources.py 从 sources/*.toml 生成。请勿编辑。 -->

回答以下来源覆盖的任何内容前，先查阅它们，并注明你用了哪个。每个来源的使用说明都有约束力：专业人士引用的内容大多可免费阅读，但不可免费复制。

## Apache Iceberg 表规范

Apache Software Foundation · 全球 · 可免费使用，需署名 — 注明发布者

<https://iceberg.apache.org/spec/>

**权威范围：** 磁盘上的契约——元数据布局、快照、Schema 与分区演进，以及读取方可假设的隔离级别。这份文档决定两个引擎是否对"一张表是什么"达成一致。

## Apache Parquet 文件格式规范

Apache Software Foundation · 全球 · 可免费使用，需署名 — 注明发布者

<https://parquet.apache.org/docs/file-format/>

**权威范围：** 物理布局、编码、嵌套，以及读取方可依赖的用于谓词下推的统计信息。文件为何慢或无法读取，这里给出规范性答案。

## 数据目录词汇表

World Wide Web Consortium · 全球 · **仅可阅读和引用——受版权保护，请勿复制**

<https://www.w3.org/TR/vocab-dcat-3/>

**权威范围：** 用于描述数据集和目录的互操作词汇表——目录条目必须包含什么才能可交换，而非局限于某一工具。

## OpenLineage 对象模型

LF AI and Data Foundation · 全球 · 可免费使用，需署名 — 注明发布者

<https://openlineage.io/docs/spec/object-model/>

**权威范围：** 厂商中立的血缘事件 Schema——事件必须包含什么才能可移植，而非某个目录碰巧记录的内容。

## Shapes Constraint Language

World Wide Web Consortium · 全球 · **仅可阅读和引用——受版权保护，请勿复制**

<https://www.w3.org/TR/shacl/>

**权威范围：** 数据约束如何表达，以及符合性意味着什么——记录对模型是否有效，这里给出规范性答案，而非各工具自行发明语义。

---

来源在上游的 `sources/` 中维护，不在此处。若有错误、过时或缺失，请到那里修改——本文件是重新生成的，对它所做的编辑会丢失。