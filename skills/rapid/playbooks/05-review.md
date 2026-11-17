# 5. 审稿与返修

- **模拟审稿**。用 `nature-reviewer`。可点选 `novelty`、`experiments`、`reproducibility`、`robotics` 或 `editor`，也可指定公开可查的研究者审稿准则。默认用新颖性、实验证据和领域三个视角。选多位时把同一稿件交给独立上下文，分别定稿再汇总，无法隔离时标明多视角自审。统计或复现是主要风险时选 K-Dense `peer-review` 的相应审计。公开准则作为模拟评审标准，注明来源。 [Nature reviewer](https://github.com/Yuan1z0825/nature-skills/blob/14ca69710cae192325395a380e9cdd4ae5d9d0c8/skills/nature-reviewer/SKILL.md) · [K-Dense peer review](https://github.com/K-Dense-AI/scientific-agent-skills/blob/ec59a29a03d5c40f73ab40878df04860bc00e876/skills/peer-review/SKILL.md)
- **有真实审稿意见**。用 `nature-response` 逐条映射到修改位置、结果或待补证据。 [Nature response](https://github.com/Yuan1z0825/nature-skills/blob/14ca69710cae192325395a380e9cdd4ae5d9d0c8/skills/nature-response/SKILL.md)

**交接**。按段落、图表或方法锚点给出主要意见和修改。按入口的返修循环接回上游，再输出修订稿和剩余事项。
