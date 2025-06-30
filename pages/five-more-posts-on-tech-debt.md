---
type: Page
title: Five More Posts on Tech Debt
description: null
icon: null
createdAt: '2025-06-05T13:05:06.833Z'
creationDate: 2025-06-05 06:05
modificationDate: 2025-06-14 12:03
tags: [techdebt]
coverImage: null
---

My previous page on this [Ten Articles on Tech Debt](Ten%20Articles%20on%20Tech%20Debt.md) missed a few excellent sources.

## Technical Debt (intro guide)

[https://www.productplan.com/glossary/technical-debt/?hl=en-US](https://www.productplan.com/glossary/technical-debt/?hl=en-US)

Good introductory article. Digestible for beginners.

> If you want a simple answer: technical debt is neither good nor bad, it’s debt.

Fair, I guess. Dangerous in the wrong hands, though.

> Technical staff, he says, often are tasked with trying to explain technical debt to business staff, who may not immediately see the implications. “The main issue seems to be that, unlike financial debt, technical debt is much less visible, and so people have an easier time ignoring it,” he suggests.

Bingo. Business staff love to borrow for their goals and have technical staff pay it off. Then they turn around and complain about technical staff taking longer to deliver. Things start to spiral from there with expanded padding in estimates and eroding quality as burned out engineers stop trying.

- My favorite part is the list from “[Towards an Ontology of Terms on Technical Debt](https://pdfs.semanticscholar.org/3ab6/bd6fd72110a18f2d9d442cab03369a6017c5.pdf)"

  - Architecture Debt
  - Build Debt
  - Code Debt
  - Defect Debt
  - Design Debt
  - Documentation Debt
  - Infrastructure Debt
  - People Debt
  - Process Debt
  - Requirement Debt
  - Service Debt
  - Test Automation Debt
  - Test Debt

## Tech Debt - by Martin Fowler

[https://martinfowler.com/bliki/TechnicalDebt.html?hl=en-US](https://martinfowler.com/bliki/TechnicalDebt.html?hl=en-US)

> Cruft has a quick impact, slowing down the very new features that are needed quickly. Teams who do this end up maxing out all their credit cards, but still delivering later than they would have done had they put the effort into higher internal quality.

Preach! Also love the often cited [TechnicalDebtQuadrant](https://martinfowler.com/bliki/TechnicalDebtQuadrant.html).

Martin is an Engineer's champion. He's clever with detail and cites good sources.

## Similarities Between Tech Debt and 'Money' Debt

A delightful comparison in a table.
[https://marcgg.com/blog/2025/02/20/tech-debt/](https://marcgg.com/blog/2025/02/20/tech-debt/)

> Often people only see the “ship faster” part, but forget about the rest… just like they see how nice the new car will be while forgetting about the 8% interest.

This is a great blog. There's a cool post about [Force Multipliers](https://marcgg.com/blog/2020/06/04/force-multipliers/) that talks a little about team composition, too.

## Technical Debt Explained (by Codacy)

A good comprehensive overview including explanation, analysis, and solutions.
[https://blog.codacy.com/technical-debt](https://blog.codacy.com/technical-debt)

Generally good stuff. I might nitpick about its `get_user_data` example bordering on an unproductive part of Uncle Bob Clean Code theory that favors over-abstraction, too much indirection of logic, and ultimately makes code worse. That's a topic for another page.

## It's not your codebase

Sean Goedecke has some interesting takes. This one is counterintuitive, with a healthy dose of balance. A lot of online advice sells ideas about "high ownership" using words like "empower" or "accountability" so much that I'm not sure they mean what the authors think they mean. This post advocates boundaries and trust. I don't totally buy it. However, I also feel like he's got a point.

[https://www.seangoedecke.com/not-your-codebase/](https://www.seangoedecke.com/not-your-codebase/)

He presents a steelman argument about Engineers resisting managers incentivized for tech debt...

> Engineers should fight against this, because it’s in their interest to not trash their own codebases, and it’s in the broader company interest to maintain a healthier codebase long-term (even if individual managers disagree).

... then counters

> This does sometimes happen. But it’s a deeply cynical way of looking at your work. I’ve worked with managers and product managers who were only interested in short-term gain. But I’ve also worked with managers and product managers who genuinely wanted to do the right thing, and only pushed for short-term gain when there was actually a strong reason.

Paint me gray and call me cynical then! Perhaps I've been burned too many times. People play to their incentives and rules. I often see moral hazard and tragedy of the commons at play as bad code happens to good people, and then good people get blamed. Would trust and shared responsibility be better? Of course. Do humans reliably work like that? Show me more proof. The best part of the post is a reminder that the code and its debt ultimately belong to the company. We're just the help.

## Related

[Ten Articles on Tech Debt](Ten%20Articles%20on%20Tech%20Debt.md)
