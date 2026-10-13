# 来源 — `security:data-protection-and-encryption`

<!-- 由 scripts/build-sources.py 从 sources/*.toml 生成。请勿编辑。 -->

回答这些问题覆盖的任何内容前，先查阅以下来源，并注明你引用了哪些。每个来源的使用说明具有约束力：专业人士引用的大部分内容可免费阅读，但不可免费复制。

## FIPS 140-3：加密模块安全要求

NIST · 美国 · 公有领域（美国政府）— 可自由引用

<https://csrc.nist.gov/pubs/fips/140-3/final>

机器可读版本：<https://csrc.nist.gov/projects/cryptographic-module-validation-program/validated-modules>

**权威范围：** 加密模块是否通过验证及其验证等级。这不是关于加密质量的评价，而是联邦及众多受监管买家所依赖的认证事实。

## NIST SP 800-57 第 1 部分：密钥管理建议

NIST · 美国 · 公有领域（美国政府）— 可自由引用

<https://csrc.nist.gov/pubs/sp/800/57/pt1/r5/final>

**权威范围：** 已批准的算法和密钥长度、按密钥类型划分的密码使用期，以及完整的密钥生命周期。是判断密钥可使用多久、某长度是否仍可接受的裁判依据。

## PCI 数据安全标准

PCI 安全标准委员会 · 全球 · **需要账户 — 引用即可；由用户自行获取**

<https://www.pcisecuritystandards.org/document_library/>

**权威范围：** 客服人员是否可以通过电话获取卡号、该通话是否可录音，以及工单附件和屏幕共享中的卡片数据必须如何处理。由合格评估师进行评估，因此具有真正的决定性效力。

---

来源在上游的 `sources/` 中维护，不在此处。如果某个来源有误、过时或缺失，请在上游修复——本文件是重新生成的，对其编辑将会丢失。