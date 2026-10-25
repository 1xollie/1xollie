# Hi, I'm Oliver

I'm building **[Strandline](https://strandline.dev)**. Run several coding agents on one repo and each branch passes on its own, but the combination still breaks. Strandline sits between the agents and `main`: it tells an agent mid-task when something it depends on changes, and checks the combined work before it lands.

<p align="center">
  <a href="https://strandline.dev"><img src="https://raw.githubusercontent.com/1xollie/strandline-demo/main/strandline-demo.gif" alt="Three Claude agents work on one repo. One changes how retries work, Strandline alerts the agent that depends on it mid-task, it adapts, and the combined work lands clean." width="100%"></a>
</p>

*A real run, sped up: three Claude agents, one repo. The alert reaches the dependent agent while it is still working, and nothing collides.*

## What I can stand behind

- **0 wrong merges across 476 real merge conflicts** replayed from 18 open-source repos. Strandline only lands a merge it can prove is right.
- **11 of 11 repair cheats rejected.** A repair that deletes a test, weakens an assertion or hard-codes the answer is refused before it can land.
- **1,000 agents at once.** Load-tested on one laptop at about 20,000 events a minute, with a p99 of 11.5 ms.
- **The demo above is a real run:** the alert reached the dependent agent 24 seconds in, it adapted, and the whole thing took 78 seconds and $0.018 in model cost.

## Find me

[strandline.dev](https://strandline.dev) · [the demo repo](https://github.com/1xollie/strandline-demo) · [@Oliver_Workman on X](https://x.com/Oliver_Workman)
