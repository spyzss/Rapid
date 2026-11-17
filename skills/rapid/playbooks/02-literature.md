# 2. 查新与作者调研

- **判新颖性**。用 `novelty-check` 查最接近前作，按任务、机制、实验设置逐条比较。给出具体重合、仍可成立的差异和检索覆盖；主要结论回到原论文。 [ARIS novelty-check](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/blob/9f30e834d24a337dbdd06fb20a1150d4376dfa59/skills/skills-codex/novelty-check/SKILL.md)
- **按作者或引文追工作**。用 `nature-academic-search` 查作品和引用链，按 OpenAlex ID、ORCID、机构或代表作消歧。正文引文需要核 DOI、元数据或生成 BibTeX 时，使用 `citation-management`。 [Nature academic search](https://github.com/Yuan1z0825/nature-skills/blob/14ca69710cae192325395a380e9cdd4ae5d9d0c8/skills/nature-academic-search/SKILL.md) · [OpenAlex Authors](https://help.openalex.org/data/authors/) · [K-Dense citation management](https://github.com/K-Dense-AI/scientific-agent-skills/blob/ec59a29a03d5c40f73ab40878df04860bc00e876/skills/citation-management/SKILL.md)

**完成条件**。与最近前作的每项关键差异都能指回可查的论文、章节或实验设置。交付核实过的引文、最接近的 baseline 和比较条件。发现重合时携证据回第 1 步。检索覆盖有限时，按实际查过的范围写 novelty。
