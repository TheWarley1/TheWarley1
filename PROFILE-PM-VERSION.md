# Hey, I'm Warley

**Product-minded builder: I decide what to build, write down why, then ship it.**

I come at product work from the build side. Most of what I do sits in AI agents and
on-chain systems, where the product questions and the engineering questions arrive
together and cannot be separated: what is worth building, who it is for, what counts as
done, and what we will not build.

I have not come up the big-company PM ladder. I have shipped small things end to end,
written the reasoning down, and kept the evidence honest. That is the habit I would
bring to a product team.

![Product strategy](https://img.shields.io/badge/Product-scoping%20%26%20prioritisation-1F6FEB?style=flat-square)
![Writing](https://img.shields.io/badge/Writing-specs%20%26%20decision%20docs-8250DF?style=flat-square)
![AI agents](https://img.shields.io/badge/AI%20agents-tooling%20%26%20evaluation-2DA44E?style=flat-square)
![On-chain](https://img.shields.io/badge/On--chain-Solana%20%26%20EVM-9945FF?style=flat-square)

## What I do

- **Scope.** Turn a vague opportunity into one bounded slice with a clear finish line,
  then defend the boundary when the slice starts growing.
- **Prioritise.** Choose what not to do, and say out loud what that decision costs. I
  would rather ship a small thing that holds than a large thing with drift in it.
- **Specify.** Write the brief a reviewer can argue with: problem, evidence, constraints,
  and every assumption named rather than buried.
- **Ship and verify.** Stay with the work until it runs. A claim that has not been tested
  is a guess wearing a suit.
- **Communicate plainly.** No jargon as a shortcut for thinking. If a sentence needs a
  diagram to survive, the sentence is wrong.

## Evidence, not adjectives

I would rather show the record than describe myself.

- **Reconstruction work with real scope decisions.**
  [pump.fun's developer API](https://github.com/lalalune/pumpfun-source) documents 67
  operations. I argued my scope from the project's own PRD rather than from personal
  preference, shipped 25 of them natively, and said no to the rest rather than
  half-building all of it. Two pull requests merged
  ([#537](https://github.com/lalalune/pumpfun-source/pull/537),
  [#544](https://github.com/lalalune/pumpfun-source/pull/544)), one open
  ([#575](https://github.com/lalalune/pumpfun-source/pull/575)).
- **Sized for the reviewer, not for the resume.** An early 6,000 line pull request was
  merged but could not be fully reviewed, which is a product failure before it is an
  engineering one. The next contribution was deliberately small enough to read end to
  end, and it landed cleanly.
- **Assumptions written down, not discovered later.** Where a contract was silent I
  recorded the decision in the repo: ten assumptions in one document, twenty in another.
  Reviewers can disagree with a written assumption. They cannot disagree with a silent
  one.
- **Claims that fail loudly.** 230 automated tests and schema conformance checks against
  the project's published API document, so a renamed field breaks the build instead of a
  customer.

## Product principles I work by

1. **The smallest slice that can be judged.** Ship something a real user can react to,
   then react.
2. **Write the assumption down.** An undocumented decision is a future argument.
3. **Prove it, do not describe it.** Tests, transcripts, backtests, receipts.
4. **Numbers before money.** Revenue, cost and downside get stated before a spend, not
   after.
5. **Say what it is not.** A stub is labelled a stub. Synthetic data is labelled
   synthetic. Trust is a product feature.

## Things I have shipped

- **[Winnower](https://github.com/TheWarley1/winnower)** - an agent that runs the
  repetitive end of a job hunt: scanning boards, filtering against fit rules,
  shortlisting with reasons, drafting letters, tracking follow-ups. Built because the
  process was repetitive and the decisions were the only part worth a human.
- **[apply-last-mile](https://github.com/TheWarley1/apply-last-mile)** - the last mile of
  an application, automated: driving a real browser where no API exists, so the boring
  step stops being the reason good work never gets submitted.
- **[poly-weather](https://github.com/TheWarley1/poly-weather)** - a forecasting and
  paper-trading system for weather prediction markets. A strategy has to prove itself on
  data, scored with Brier backtests, before it touches real capital.
- **[transcript-cleaner-skill](https://github.com/TheWarley1/transcript-cleaner-skill)** -
  turns raw auto-captions into structured documents, rotating across model providers to
  survive rate limits.

## Currently

Looking for product management roles and graduate programmes where I can work on AI
products or on-chain systems. I am comfortable in both conversations: the roadmap
conversation, and the one where somebody asks how we know the plan holds.

## Reach me

- Email: **github@thewarley.xyz**
- X: [@horlar_warley](https://x.com/horlar_warley)
