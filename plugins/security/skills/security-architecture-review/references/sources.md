# 来源 — `security:security-architecture-review`

<!-- 由 scripts/build-sources.py 从 sources/*.toml 生成。请勿编辑。 -->

回答以下来源覆盖的任何内容前，先查阅它们，并注明你用了哪个。每个来源的使用说明都有约束力：专业人士引用的大多数内容可免费阅读，但不可免费复制。

## FedRAMP 基线与自动化内容

GSA · 美国 · 公有领域（美国政府）— 可自由引用

<https://www.fedramp.gov/rev5/documents-templates/>

机器可读：<https://github.com/GSA/fedramp-automation>

**权威范围：** 向美国联邦政府销售云服务时，低、中、高影响级别分别适用哪些 SP 800-53 控制项，以及每项需要什么证据。

## MITRE ATT&CK

The MITRE Corporation · 全球 · 可免费使用，需署名 — 注明发布方

<https://attack.mitre.org/>

机器可读：<https://github.com/mitre-attack/attack-stix-data>

**权威范围：** 对手战术与技术的通用词汇表 — 如何命名一种行为，使检测规则、威胁模型和事件报告指向同一事物。

## NIST 网络安全框架 2.0

NIST · 美国 · 公有领域（美国政府）— 可自由引用

<https://www.nist.gov/cyberframework>

**权威范围：** 基于结果的词汇 — 治理、识别、保护、检测、响应、恢复 — 董事会和客户最常要求安全项目对标的就是这套。

## NIST SP 800-53 Rev. 5 — 信息系统的安全与隐私控制

NIST · 美国 · 公有领域（美国政府）— 可自由引用

<https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final>

机器可读：<https://github.com/usnistgov/oscal-content>

**权威范围：** 美国联邦系统接受评估所依据的控制目录，也是 FedRAMP 和许多私有框架继承的控制词汇来源。

## OWASP 应用安全验证标准

OWASP Foundation · 全球 · CC BY-SA — 引用需署名；相同方式共享，因此不要并入本仓库

<https://owasp.org/ASVS/>

**权威范围：** 三个保障级别下可测试的应用安全需求 — 当"让它安全"需要变成验收标准时，写进规格的就是这个。

## OWASP Top 10

OWASP Foundation · 全球 · CC BY-SA — 引用需署名；相同方式共享，因此不要并入本仓库

<https://owasp.org/www-project-top-ten/>

**权威范围：** 客户问卷或渗透测试报告会围绕其组织的应用安全风险类别。

---

来源在上游 `sources/` 中维护，不在此处。若有错误、过时或缺失，请在那里修改 — 本文件是重新生成的，对它所做的编辑会丢失。