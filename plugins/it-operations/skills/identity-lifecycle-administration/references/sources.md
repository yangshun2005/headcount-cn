# 来源 — `it-operations:identity-lifecycle-administration`

<!-- 由 scripts/build-sources.py 从 sources/*.toml 生成。请勿编辑。 -->

在回答这些来源涵盖的任何问题前，先查阅它们，并注明你引用了哪些。每个来源的使用说明都具有约束力：专业人士引用的大部分内容可免费阅读，但不可免费复制。

## NIST SP 800-207：零信任架构

NIST · 美国 · 公有领域（美国政府）— 可自由引用

<https://csrc.nist.gov/pubs/sp/800/207/final>

**权威用于：** 零信任指什么——策略引擎、管理员与执行点模型，以及各项原则——以免供应商在对话中途重新定义该术语。

## NIST SP 800-63：数字身份指南

NIST · 美国 · 公有领域（美国政府）— 可自由引用

<https://csrc.nist.gov/pubs/sp/800/63/4/final>

机器可读版本：<https://pages.nist.gov/800-63-4/>

**权威用于：** 每个身份、认证器和联邦保证级别要求什么——尤其是指出强制定期轮换密码和组成规则并不在其中。

## OpenID Connect Core 1.0

OpenID Foundation · 全球 · **仅可阅读和引用——受版权保护，请勿复制**

<https://openid.net/specs/openid-connect-core-1_0.html>

**权威用于：** ID token 是什么、哪些声明是标准的，以及合规方在每个流程中必须做什么。可终结那些以"我们的提供商做法不同"开头的争论。

## RFC 7644：跨域身份管理系统协议

IETF · 全球 · **仅可阅读和引用——受版权保护，请勿复制**

<https://www.rfc-editor.org/rfc/rfc7644.html>

机器可读版本：<https://www.rfc-editor.org/rfc/rfc7643.html>

**权威用于：** 身份提供商与下游应用之间如何执行配置和取消配置——端点、patch 语义、过滤，以及规范的用户和组属性。

## RFC 9700：OAuth 2.0 安全最佳当前实践

IETF · 全球 · **仅可阅读和引用——受版权保护，请勿复制**

<https://www.rfc-editor.org/rfc/rfc9700.html>

**权威用于：** 哪些 OAuth 2.0 模式仍然允许——隐式授权和密码授权不得使用、PKCE 是必需的，以及重定向 URI 必须精确匹配。

---

来源在上游的 `sources/` 中维护，不在此处。如果某个来源有误、过时或缺失，请在那里修复——本文件是重新生成的，对它所做的编辑会丢失。