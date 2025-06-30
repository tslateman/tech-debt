---
type: Page
title: Managing Tech Debt
description: null
icon: null
createdAt: '2025-06-01T20:36:00.150Z'
creationDate: 2025-06-01 13:36
modificationDate: 2025-06-01 14:30
tags: [techdebt, ai-assisted]
coverImage: null
---

See also: [https://g.co/gemini/share/9806265d47b9](https://g.co/gemini/share/9806265d47b9)

The following is an extract from a Gemini [report](https://docs.google.com/document/d/1CP-Aq4-zGe45TaONMUnWxsdef0geVM73nyoWG88X7vY/edit?usp=sharing) after feeding it [Ten Articles on Tech Debt](Ten%20Articles%20on%20Tech%20Debt.md)

## Technical Debt vs. Technical Cruft/Quality Issues

| Category                                 | Intent                                                     | Strategic Value                                         | Causes                                                              | Impact                                                                          | Management                                         |
| :--------------------------------------- | :--------------------------------------------------------- | :------------------------------------------------------ | :------------------------------------------------------------------ | :------------------------------------------------------------------------------ | :------------------------------------------------- |
| Technical Debt ​(Prudent & Deliberate)   | Conscious choice, planned                                  | Enables speed, market validation, competitive advantage | Tight deadlines, MVP focus, calculated risk                         | Increased "interest" (future work)                                              | Planned repayment, integrated into roadmap         |
| Technical Cruft (Reckless/Unintentional) | Unconscious, accidental, or negligent                      | None, hinders progress                                  | Lack of skill/knowledge, neglect, poor practices, unforeseen issues | Compounding complexity, bugs, slowed development, developer frustration         | Cleanup, refactoring, process improvement          |
| Functional Debt                          | Product/UX related, often intentional functional shortcuts | Impacts user satisfaction, marketability                | Time constraints, insufficient research, evolving user expectations | Decreased user satisfaction, reduced product value, missed market opportunities | User research, UX/UI redesign, feature enhancement |

The "interest-to-income" equivalent in the context of technical challenges refers to the proportion of time spent dealing with overhead (maintenance load) compared to building new revenue-generating features.* The objective is not to eliminate all overhead but to maintain it as a manageable fraction of the "tech income".

McKinsey's Technical Debt Ratio (TDR) provides a quantitative metric, linking higher scores (indicating less debt) to higher revenue growth.** The TDR range and its corresponding severity levels are:

## Technical Debt Ratio (TDR) Severity Levels

| TDR Range | Severity Level | Typical Business Impact               |
| :-------- | :------------- | :------------------------------------ |
| 5-15%     | Moderate       | Noticeable development slowdowns      |
| 15-30%    | Significant    | Substantial productivity drain        |
| 30-50%    | Severe         | Critical business risk                |
| >50%      | Extreme        | Potential system replacement required |

The "interest rate" for technical challenges can be approximated using the formula: (Maintenance Hours / Total Development Hours) × (% Attributed to Technical Debt) × 100.10**

#### Works cited

*Tech debt metaphor maximalism - apenwarr, accessed June 1, 2025, [https://apenwarr.ca/log/20230605](https://apenwarr.ca/log/20230605)

**How to Measure Technical Debt: A Guide for IT Stakeholders - Unqork, accessed June 1, 2025, [https://unqork.com/resource-center/guides/how-to-measure-technical-debt-a-guide-for-it-stakeholders/](https://unqork.com/resource-center/guides/how-to-measure-technical-debt-a-guide-for-it-stakeholders/)

***[Ten Articles on Tech Debt](Ten%20Articles%20on%20Tech%20Debt.md)
