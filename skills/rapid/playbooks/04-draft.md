# 4. 写稿与绘图

- **论文正文**。默认用 Orchestra `ml-paper-writing`，从现有仓库、实验结果和核实引文组织贡献、方法、结果与限制。写摘要、结果和讨论时，按 [写得直接](result-framing.md#3-写得直接) 突出证据最强的发现，删掉重复防御。需要新建会议 LaTeX 骨架时选 `paper-write`。使用当前 venue 的正式模板。 [Orchestra ML paper writing](https://github.com/Orchestra-Research/AI-Research-SKILLs/blob/773a52944ba4747a18bd4ae9ade53fff041adcbc/20-ml-paper-writing/ml-paper-writing/SKILL.md) · [ARIS paper-write](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/paper-write/SKILL.md)
- **主图**。用 `nature-figure`，从主张确定 panel，从第 3 步结果源出图，保留可编辑代码和 PDF/SVG。方法图有现成组件定义时复用，按真实数据流绘制。 [Nature figure](https://github.com/Yuan1z0825/nature-skills/blob/14ca69710cae192325395a380e9cdd4ae5d9d0c8/skills/nature-figure/SKILL.md)
- **稿件有正文后**。用 `paper-claim-audit` 把正文、表图和附录的关键数字、比较方向和限定条件回对原始结果。用 `citation-audit` 核对新增、改写或未核过的引文，确认原论文支持引用所在的句子，尤其是 novelty、baseline 和归因。返修时复用前一轮已核记录。 [ARIS paper-claim-audit](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/paper-claim-audit/SKILL.md) · [ARIS citation-audit](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/citation-audit/SKILL.md)

**完成条件**。指定范围有可读源稿，同一版图表、源码和引文随稿交付。关键数字和比较可回到第 3 步。用户要 PDF 时，走第 6 步的编译分支，打开实际输出检查指定的章节或图表。
