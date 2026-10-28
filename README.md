# Hey, I'm Warley

**Product-minded builder working on AI agents and on-chain systems.**

I ship tools that make agents do real work rather than demos: reconstructing APIs from
their published contracts, automating the last mile of tedious processes, and
backtesting strategies against live market data. I care more about whether a thing runs
correctly than whether it looks impressive.

I build from Lagos, Nigeria, and I work in plain language: small scoped changes, tests
before features, honest labels on anything that is not real data.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white)
![EVM](https://img.shields.io/badge/EVM-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

## Selected work

### API reconstruction

**[pump.fun developer API](https://github.com/lalalune/pumpfun-source)** (contributor) -
A reconstruction of pump.fun's services from captured binaries. I took the backend from
stub responses to native implementations of **25 of the 67 documented operations**:
users, profiles, posts, competitions and the follow graph. Two pull requests merged
([#537](https://github.com/lalalune/pumpfun-source/pull/537),
[#544](https://github.com/lalalune/pumpfun-source/pull/544)), a third open
([#575](https://github.com/lalalune/pumpfun-source/pull/575)).

The part I am proudest of is not the endpoint count. It is that every response is
validated against the project's own published OpenAPI document in the test suite, so a
renamed field fails in CI instead of in a consumer, and synthetic data is labelled with
a response header so nobody can mistake it for captured evidence.

### Agent tooling

**[Winnower](https://github.com/TheWarley1/winnower)** - An agent (Strands Agents SDK)
that runs the repetitive end of a job hunt end to end: scanning boards, filtering
against fit rules, shortlisting with reasons, drafting tailored letters and tracking
follow-ups.

**[apply-last-mile](https://github.com/TheWarley1/apply-last-mile)** - A small toolkit
for the last mile of an application: driving a real browser over CDP, filling forms
that no API exposes, and rendering a CV to PDF with no layout guesswork.

**[transcript-cleaner-skill](https://github.com/TheWarley1/transcript-cleaner-skill)** -
Turns raw YouTube auto-captions into structured markdown, rotating across model
providers to survive rate limits.

### Markets

**[poly-weather](https://github.com/TheWarley1/poly-weather)** - Forecasting and
paper-trading system for weather prediction markets. Logs forecasts, scores them with
Brier backtests against METAR observations, and tracks a paper portfolio so a strategy
has to prove itself on data before it touches capital.

## How I work

- **Tests before features.** A test that cannot fail is worse than no test, so I replace
  vacuous assertions when I find them, including my own.
- **Contracts over guesses.** When a schema is published, the code conforms to it and the
  suite proves it.
- **Labels on everything.** Data is marked live or synthetic. A stub says it is a stub.
- **Small, reviewable changes.** A 300 line change that can be read end to end beats a
  6,000 line one that cannot.

## Currently

Looking for product management roles and graduate programmes where I can work on AI
products or on-chain systems. I am comfortable moving between the roadmap conversation
and the code that proves whether the plan holds.

## Reach me

- Email: **github@thewarley.xyz**
- X: [@horlar_warley](https://x.com/horlar_warley)
