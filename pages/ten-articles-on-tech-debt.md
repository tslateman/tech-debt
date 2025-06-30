---
type: Page
title: Ten Articles on Tech Debt
description: null
icon: null
createdAt: '2025-06-01T20:15:34.728Z'
creationDate: 2025-06-01 13:15
modificationDate: 2025-06-14 12:02
tags: [techdebt]
coverImage: null
---

## "Clarifying Technical Debt"

[https://davidedwards.io/blog/2024/12/29/clarifying-technical-debt](https://davidedwards.io/blog/2024/12/29/clarifying-technical-debt)

When you say "tech debt" do you include quality issues?

> clumping quality issues into the nebulous bucket of *technical debt* is that organizations outside of software engineering, product management included, are free to interpret as they wish. It is not uncommon for people to equate technical debt with *“the engineers made a bunch of mistakes or bad decisions”*

Were they necessary shortcuts, even mandated by non-engineers? Do we need new language?

> I would strongly encourage software organizations to eliminate *technical debt* from their vocabulary–particularly when it comes to planning–in exchange for clearly articulated quality improvements connected to business outcomes.

Noble, idealistic concept. *Good luck.* My attempts at these conversations have resulted in non-technical folks getting impatient, eyes glazing over, and people walking away with the wrong understanding and dubious conclusions.

## "Stop saying “technical debt”"

[https://stackoverflow.blog/2023/12/27/stop-saying-technical-debt/](https://stackoverflow.blog/2023/12/27/stop-saying-technical-debt/)

Optimistic. Fine, let's go ahead and set the Platonic ideal.

> How do we minimize maintenance load growth? With [good code stewardship practices](https://chelseatroy.com/2021/10/29/a-rubric-for-evaluating-team-members-contributions-to-a-maintainable-code-base/). We rarely reward, recognize, or teach code stewardship the way that we do feature development skills. But code stewardship skills—documenting systems, recovering context from code, and designing for future changes—make the difference between a team that hums along for a decade or more and a team that repeatedly mires itself in declarations of code bankruptcy, rewrites, and despair.

If only. Surprise! It goes further.

> The Holy Grail? *Negative* maintenance load growth: the kind of growth that makes our code *more* maintainable over time instead of less. The Grail requires even more of the team than a healthy quotidian code stewardship routine. It requires us to look at individual maintenance tasks, track their origins, and address those problems at the source. These chores, backed by empirical evidence, give us something concrete to discuss in meetings about tech debt.

What a dream. Maybe one day. I strive for this, but I fear the bar is too high.

## "Don't ask for permission to do your job correctly"

[https://itnext.io/dont-ask-permission-to-do-your-job-correctly-avoiding-the-technical-debt-trap-51c87e3be822](https://itnext.io/dont-ask-permission-to-do-your-job-correctly-avoiding-the-technical-debt-trap-51c87e3be822)

Say "quick and dirty" one more time. (Samuel L Jackson meme)

> It is a vicious cycle where we build cruft on top of cruft and sooner than later the quick aspect of “quick and dirty” disappears. And that is when you find yourself asking permission to do your job correctly.

Another source noting distinction between debt and cruft. Debt is ok. Cruft has gotta go.

> We can improve by first recognizing things for what they truly are: technical debt or cruft. It is our job to highlight the differences and do our best to not add to the latter.

This one also nobly tries to bring management in, noting the shared responsibility.

> If this is always approached as a “best effort” or “whenever we have time”, you can be sure that it won’t happen in a way that truly moves the needle.

## "Developer philosophy"

[https://qntm.org/devphilo](https://qntm.org/devphilo)

Beware compounding complexity.

> Warning signs to watch for: compounding technical debt. Increasing difficulty in making seemingly simple changes to code. Difficulty in documenting/commenting code. Difficulty in onboarding new developers. Dwindling numbers of people who know how particular areas of the codebase actually work. Bugs nobody understands.

> Compounding complexity must be fought at every turn. [Alternate between phases of expansion (new features) and consolidation](https://knowledge.csc.gov.sg/ethos-issue-21/how-to-build-good-software/#:~:text=good%20software%20involves-,alternating%20cycles%20of%20expanding%20and%20reducing%20complexity,-.%20As%20new%20features).

See also: [Beware the Complexity Merchants](https://chrlschn.dev/blog/2025/05/beware-the-complexity-merchants/) and DHH's [Merchants of Complexity](https://world.hey.com/dhh/merchants-of-complexity-4851301b)

## ​"How to Build Good Software" (linked from Developer philosophy)

[https://knowledge.csc.gov.sg/ethos-issue-21/how-to-build-good-software/](https://knowledge.csc.gov.sg/ethos-issue-21/how-to-build-good-software/)

The ol' "gotta break a few eggs to make an omelette" - but you gotta clean up after, too!

> Building good software involves alternating cycles of expanding and reducing complexity. As new features are developed, disorder naturally accumulates in the system. When this messiness starts to cause problems, progress is suspended to spend time cleaning up. This two-step process is necessary because there is no such thing as platonically good engineering: it depends on your needs and the practical problems you encounter.

Balanced take. Goes on with an example and highlighting the challenge of getting it right.

> Even a simple user interface such as Google’s search bar contains a massive amount of complexity under the surface that cannot be perfected in a single iteration. The challenge is managing this cycle, letting it get messy enough to make meaningful progress, but not letting it get so complicated that it becomes overwhelming.

## "Quantifying Technical Debt"

[https://chelseatroy.com/2021/01/14/quantifying-technical-debt/](https://chelseatroy.com/2021/01/14/quantifying-technical-debt/)

Every part adds weight. All code is some form of debt.

> Every software feature adds maintenance load.

> If maintenance load outstrips maintenance limit by enough, or for long enough, you get fires, outages, and breakdowns. The team spends a lot of time on call and ends up stressed out. They’re trying to write new features while keeping the existing product duct taped together.

Excellent related post: [This series on socializing changes in the workplace](https://chelseatroy.com/2018/02/25/how-to-socialize-big-changes-at-work-part-1-start-at-the-grassroots-level/) (Helpful for getting started on changing your team’s relationship with maintenance load)

## "Tech debt metaphor maximalism"

[https://apenwarr.ca/log/20230605](https://apenwarr.ca/log/20230605)

There are so many delightful quotes from this one, it's hard to choose. I'll cheat and pick one that brings up the interest-to-income part of the metaphor while linking to a good xkcd.

> In the tech world, the interest-to-income equivalent is how much time you spend dealing with overhead compared to building new revenue-generating features. Again, getting to zero overhead is probably not worth it. I like this [xkcd explanation](https://xkcd.com/1205/) of what is and is not worth the time:

## "How to stop wasting engineering time on technical debt"

[https://www.stepsize.com/blog/how-to-stop-wasting-engineering-time-on-technical-debt](https://www.stepsize.com/blog/how-to-stop-wasting-engineering-time-on-technical-debt)

Some debt is good.

> Think of your technical debt budget like your site reliability budget. Provided it's [prudent technical debt](https://martinfowler.com/bliki/TechnicalDebtQuadrant.html) you're taking on—and you remain below the maximum amount of tech debt you can tolerate before affecting your customers and business—you should be increasing the amount to take more risks and beat your competitors.

Prioritize.

> Put simply, your goal is to identify the intersection of things you'll work on this sprint, month, or quarter, and the parts of your codebase that have tech debt. Pay off the debt in that intersection, but not outside of it.

## "Garbage Collect Your Technical Debt"

[https://ieeexplore.ieee.org/document/9520328](https://ieeexplore.ieee.org/document/9520328)

Technical take, treat it like memory management.

> When developers take a break from writing features to fix tech debt, that’s like a garbage collector pausing to clean up garbage.

Upon bankruptcy, strategy must change.

> If you declare bankruptcy and decide to rewrite the system, it is critical to re-evaluate your tech debt algorithm. Don’t keep using an algorithm tuned to a finite game and hope it’s suitable for an infinite game. It’s a good time to try the balanced algorithm, both avoiding tech debt through good design practices and cleaning up the inevitable debt through refactoring.

## ​"The complete guide to technical debt management"

[https://www.rst.software/blog/technical-debt-management](https://www.rst.software/blog/technical-debt-management)

This post is pretty comprehensive, albeit a little generic and boring. However, I've said "good engineering is boring" before, so perhaps this is more valuable than my gut reaction to it.

> Maintaining a technical debt management backlog also helps to reduce the payoff costs. Just like financial debt increases over time, technical debt increases too: the more outdated, the greater costs will be incurred on the payoff. It’s thus critical that businesses pay an active role in assessing the backlog and prioritizing items to be paid off rather than leaving technical debt to be dealt with by the development team on their own (they will always have other pressing priorities to address).

A coordinated, organized effort to manage the ongoing problem. Nothing game-changing, but still useful. Giving names to the problems is helpful. If the devil is in the details, we must know the demon's name to cast it out!

## Related

[Tech Debt in 2025](Pages/Tech%20Debt%20in%202025.md)

[Five More Posts on Tech Debt](Pages/Five%20More%20Posts%20on%20Tech%20Debt.md)

[Managing Tech Debt](Pages/Managing%20Tech%20Debt.md)
