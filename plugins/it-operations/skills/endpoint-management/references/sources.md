# 来源 — `it-operations:endpoint-management`

<!-- 由 scripts/build-sources.py 从 sources/*.toml 生成。请勿编辑。 -->

回答这些问题覆盖的任何内容前，先查阅以下来源，并注明你用了哪个。每个来源的使用说明都有约束力：专业人士引用的多数材料可免费阅读，但不可免费复制。

## CIS Benchmarks

Center for Internet Security · 全球 · **需要账号 — 可引用；由用户自行获取**

<https://www.cisecurity.org/cis-benchmarks>

**权威范围：** 特定产品版本的共识加固基线，含两个配置级别。非国防领域的 STIG 等价物，也是多数商业审计引用的基线。

## NIST SP 800-124：移动设备安全管理指南

NIST · 美国 · 公有领域（美国政府）— 可自由引用

<https://csrc.nist.gov/pubs/sp/800/124/r2/final>

**权威范围：** 移动端点的基线控制集，以及移动策略争论所围绕的部署模式区分——企业所有、个人启用、自带设备。

## NIST SP 800-40：企业补丁管理规划指南

NIST · 美国 · 公有领域（美国政府）— 可自由引用

<https://csrc.nist.gov/pubs/sp/800/40/r4/final>

**权威范围：** 一个站得住脚的补丁计划应包含什么——维护窗口、分阶段部署，以及这一立场：放任某项未打补丁必须有书面的补偿控制，而非默不作声。

## Security Technical Implementation Guides

Defense Information Systems Agency, US Department of Defense · 美国 · 公有领域（美国政府）— 可自由引用

<https://public.cyber.mil/stigs/>

机器可读版本：<https://public.cyber.mil/stigs/downloads/>

**权威范围：** 给定操作系统、虚拟机监控程序或设备的精确必需配置，逐项设置并标注严重级别。当两名管理员对某个加固取值有分歧时，以此为准。

---

来源在上游的 `sources/` 中维护，不在此处。若有错误、过时或缺失，请在上游修正——本文件是重新生成的，对它所做的编辑会丢失。