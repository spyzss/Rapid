# 3. 资源与实验证据

- **需要设计或补实验**。用 `experiment-plan` 将查新后留下的主张映射到对照、指标、数据切分、最小 pilot 与消融。估算可复用数据与代码、缺失输入、GPU 型号与卡时、墙钟时间和存储。机器人项目按需估算真机或仿真时段、样本和人工。写明估算依据与范围，将依赖顺序和最小可行方案一起交付。需要执行且在授权和预算内时，优先用项目现有入口，按需采用 `experiment-bridge` 的计划到结果流程。 [ARIS experiment-plan](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/experiment-plan/SKILL.md) · [ARIS experiment-bridge](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/experiment-bridge/SKILL.md)
- **已有实验结果**。用 `result-to-claim` 判断观测支持多强的主张，再决定保留、收窄还是补测。区分开发、结果挑选与独立确认用的数据，核对 baseline 用的是同一评测口径。缺证据时只补能区分解释的实验。 [ARIS result-to-claim](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/result-to-claim/SKILL.md)

- **效应或不确定性会改变结论时**。先确认统计单位、配对或聚类关系及现有分析计划，再按需计算效应量和区间。统计方法和假设检查用 `statistical-analysis`，现成分析与稿件报告的对齐用 `nature-statistics`。 [K-Dense statistical analysis](https://github.com/K-Dense-AI/scientific-agent-skills/blob/ec59a29a03d5c40f73ab40878df04860bc00e876/skills/statistical-analysis/SKILL.md) · [Nature statistics](https://github.com/Yuan1z0825/nature-skills/blob/14ca69710cae192325395a380e9cdd4ae5d9d0c8/skills/nature-statistics/SKILL.md)

- **核心主张依赖定理时**。用 `proof-checker` 核假设、证明缺口和边界条件，将成立范围同步到正文和附录。 [ARIS proof-checker](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/proof-checker/SKILL.md)

**交接**。沿用项目结果表或实验报告，为每条核心主张记录结果或证明的位置、关键条件、证据边界，以及使用它的段落、表格或图。第 4 步用它写稿，第 5 步用它定位分歧，第 6 步用它整理复现入口。还没运行时交付预算、运行顺序和验收信号，记录结果待测。
