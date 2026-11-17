# 快科研 Rapid

Rapid 把 ARIS、Orchestra、Nature Skills 和 K-Dense 的科研技能串成一个 paper workflow。给它一个想法、研究目录、已有结果或稿件，它会选当前适用的技能，从已有材料接着做。

| 步骤 | 默认路线 | 什么时候切换或补用 |
|---|---|---|
| 1. 选题与定位 | ARIS `research-refine` | 方向还很宽，用 `idea-discovery` 先收敛 |
| 2. 查新与作者调研 | ARIS `novelty-check` | 查作者、引用关系或引文元数据时用 Nature 或 K-Dense |
| 3. 资源与实验证据 | ARIS `experiment-plan` | 结果已有，直接用 `paper-claim-audit` 对齐主张和证据 |
| 4. 写稿与主图 | Orchestra `ml-paper-writing` + `nature-figure` | 需要会议 LaTeX 骨架时用 ARIS `paper-write` |
| 5. 审稿与返修 | `nature-reviewer`，可点选视角 | 统计与复现深查用 K-Dense，真实审稿意见用 `nature-response` |
| 6. 投稿准备 | ARIS `paper-compile` + venue 官方规则 | 换 venue 用 `resubmit-pipeline` |

选题之后先确认最近的工作做到了哪一步，再估算数据、算力、时间和最小实验。用同一批证据写 Results、出主图和审稿。遇到有实质影响的审稿意见，回到对应步骤修，后续环节接着用更新后的产物。

## 用法

把 [skills/rapid/SKILL.md](skills/rapid/SKILL.md) 的仓库路径交给能读该仓库的 agent，让它按需打开同目录 playbook。GitHub 上游链接固定到具体版本。可以在当前工作区使用，无需全局安装。

> 按 Rapid 接着写这个项目。自动选各环节的 skill，复用现有实验，先出英文初稿和主图。审稿点 novelty、experiments 和 robotics。

也可以指定 `只做查新和资源评估`、`从现有 Results 开始` 或 `reviewer: reproducibility`。仅有想法时，能交付选题评估和实验路线，Results 取自实际运行。

## 上游项目

- [ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep)
- [Orchestra AI Research Skills](https://github.com/Orchestra-Research/AI-Research-SKILLs)
- [Nature Skills](https://github.com/Yuan1z0825/nature-skills)
- [K-Dense Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills)
