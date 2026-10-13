# 来源 — `technology:api-design`

<!-- 由 scripts/build-sources.py 从 sources/*.toml 生成。请勿编辑。 -->

回答任何这些来源涵盖的问题前，先查阅它们，并注明你引用了哪些。每个来源的使用说明具有约束力：专业人士引用的大部分内容可以免费阅读，但不可免费复制。

## OpenAPI 规范

OpenAPI Initiative，Linux Foundation · 全球 · 可免费使用，需署名 — 注明发布者

<https://spec.openapis.org/oas/latest.html>

**权威范围：** 一份有效的 API 描述文档应包含什么。判定某个文件是真正符合规范，还是仅被某个工具接受。

## RFC 9110：HTTP 语义

IETF · 全球 · **仅可阅读和引用 — 受版权保护，请勿复制**

<https://www.rfc-editor.org/rfc/rfc9110.html>

**权威范围：** HTTP 方法、状态码或请求头的实际含义。判定 PUT 是否幂等、409 还是 422 才正确，以及条件请求要求服务器做什么。

## RFC 9457：HTTP API 的问题详情

IETF · 全球 · **仅可阅读和引用 — 受版权保护，请勿复制**

<https://www.rfc-editor.org/rfc/rfc9457.html>

**权威范围：** API 错误响应体的传输格式。它取代了 RFC 7807，因此也决定了新服务应遵循两者中的哪一个。

## RFC 9700：OAuth 2.0 安全最佳当前实践

IETF · 全球 · **仅可阅读和引用 — 受版权保护，请勿复制**

<https://www.rfc-editor.org/rfc/rfc9700.html>

**权威范围：** 哪些 OAuth 2.0 模式仍然允许使用 — 即不得使用隐式授权和密码授权，必须使用 PKCE，且重定向 URI 必须完全匹配。

## 语义化版本 2.0.0

Semantic Versioning 项目 · 全球 · CC BY — 引用时需署名

<https://semver.org/>

**权威范围：** 版本号递增允许表达什么含义，从而决定某项变更是否需要主版本号提升。它是社区规范而非标准机构，但每个依赖解析器都假定遵循它。

---

来源在上游的 `sources/` 中维护，不在此处。若有错误、过时或缺失，请在那里修改 — 本文件是重新生成的，对它的编辑会丢失。