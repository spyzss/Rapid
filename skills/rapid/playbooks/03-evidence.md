# 3. 资源与实验证据

- **需要设计或补实验**。用 `experiment-plan` 将查新后留下的主张映射到对照、指标、数据切分、最小 pilot 与消融。估算可复用数据与代码、缺失输入、GPU 型号与卡时、墙钟时间和存储。机器人项目按需估算真机或仿真时段、样本和人工。写明估算依据与范围，将依赖顺序和最小可行方案一起交付。需要执行且在授权和预算内时，优先用项目现有入口，按需采用 `experiment-bridge` 的计划到结果流程。 [ARIS experiment-plan](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/experiment-plan/SKILL.md) · [ARIS experiment-bridge](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/experiment-bridge/SKILL.md)
- **已有实验结果**。用 `result-to-claim` 判断观测支持多强的主张，再按 [选实验结果与写结论](result-framing.md) 选主表证据、界定可成立的说法。只有结论取决于缺失证据时才安排最小补测。 [ARIS result-to-claim](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/result-to-claim/SKILL.md)

- **效应或不确定性会改变结论时**。先确认统计单位、配对或聚类关系及现有分析计划，再按需计算效应量和区间。统计方法和假设检查用 `statistical-analysis`，现成分析与稿件报告的对齐用 `nature-statistics`。 [K-Dense statistical analysis](https://github.com/K-Dense-AI/scientific-agent-skills/blob/ec59a29a03d5c40f73ab40878df04860bc00e876/skills/statistical-analysis/SKILL.md) · [Nature statistics](https://github.com/Yuan1z0825/nature-skills/blob/14ca69710cae192325395a380e9cdd4ae5d9d0c8/skills/nature-statistics/SKILL.md)

- **核心主张依赖定理时**。用 `proof-checker` 核假设、证明缺口和边界条件，将成立范围同步到正文和附录。 [ARIS proof-checker](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/proof-checker/SKILL.md)

**完成条件**。

- **计划**。每条待检验的主张有对照、指标、最小实验和判读规则。计划有预算与运行顺序，标清已有结果和待测项。
- **结果**。从产物确认实际跑完的范围，区分已启动、已结束、有可用结果。沿用项目结果表或报告，为每条核心主张记下结果或证明位置、版本、关键条件、证据边界和使用位置。这份记录供写稿、审稿和投稿复现共用。若现有结果只够支撑部分结论，按 [结论指南](result-framing.md) 确定能交付的主张及缺口。
