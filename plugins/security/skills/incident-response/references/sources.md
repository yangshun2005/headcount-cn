# 来源 — `security:incident-response`

<!-- 由 scripts/build-sources.py 从 sources/*.toml 生成。请勿编辑。 -->

回答以下来源覆盖的内容前，先查阅它们，并注明你引用了哪些。每个来源的使用说明都有约束力：专业人士引用的多数内容可以免费阅读，但不可免费复制。

## CISA 已知被利用漏洞目录

CISA · 美国 · 公有领域（美国政府）— 可自由引用

<https://www.cisa.gov/known-exploited-vulnerabilities-catalog>

机器可读：<https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json>

**权威范围：** 当前哪些漏洞正被在野利用——唯一能可靠区分"本周修补"与"本季度修补"的列表。

## MITRE ATT&CK

The MITRE Corporation · 全球 · 可免费使用，需署名 — 注明发布者

<https://attack.mitre.org/>

机器可读：<https://github.com/mitre-attack/attack-stix-data>

**权威范围：** 攻击者战术与技术的通用术语——为某种行为命名，使检测规则、威胁模型和事件报告指向同一事物。

## NIST SP 800-61：事件响应建议与考量

NIST · 美国 · 公有领域（美国政府）— 可自由引用

<https://csrc.nist.gov/pubs/sp/800/61/r3/final>

**权威范围：** 事件响应能力必须包含什么，以及每个阶段必须采集哪些证据。当前修订版是一次大幅重写，弃用了旧的四阶段框架，因此不要混用不同修订版的指南。

---

来源在上游的 `sources/` 中维护，不在此处。若有错误、过时或缺失，请在那里修改——本文件是重新生成的，对它的编辑会丢失。