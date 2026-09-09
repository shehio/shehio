### Shehab Yasser

I build and debug the infrastructure that agents run on. Most of my recent work is on agent
evaluation harnesses — the layer between a model and a task where trials fail for reasons that
have nothing to do with the model, and where a bad harness quietly turns an infrastructure
timeout into an "agent failure" in your results table.

Before that: backend engineering on distributed systems, and a degree in financial mathematics.
Both turn out to be the right training for this. Evals are a distributed systems problem wearing
an ML costume — sandboxes, retries, streaming, idempotency, partial failure — and deciding what
a noisy score actually tells you is a statistics problem.

#### What I'm Working On

- **RSI (recursive self-improvement) and AI Safety**
- **Agent safety and evaluation harnesses**
- **Training infrastructure**
- **Optimizer comparison for tool-using agents**

#### Selected Work

- [world-models](https://github.com/shehio/world-models) — [shehio.github.io/world-models](https://shehio.github.io/world-models/),
  chess and Go distilled from Stockfish and KataGo on a single GPU into AlphaZero's 20x256 ResNet:
  **2,301 Elo** chess (95% CI [2,190, 2,601]).
- [ps-env](https://shehio.github.io/ps-env/): a headless PlayStation 1 wrapped as an RL environment,
  with a Nature-DQN agent that learns Crash Bandicoot from raw pixels
- [rl-playbook](https://github.com/shehio/rl-playbook) — [rlplaybook.com](https://rlplaybook.com),
  a visual timeline of deep RL's landmark papers from DQN forward
- [rl](https://github.com/shehio/rl) / [tabular-rl](https://github.com/shehio/tabular-rl) — RL agents
  with nothing abstracted away, from tabular methods up through PPO
- [cassandra-playground](https://github.com/shehio/cassandra-playground) — Cassandra-style
  anti-entropy repair in Go: gossip protocol with Merkle trees
- [Project-Nash](https://github.com/shehio/Project-Nash) — Nash equilibria, Lemke–Howson, minimax,
  simplex; the game theory I keep reaching for in multi-agent settings

#### Publications

- [HarnessOpt-Bench: Evaluating LLMs at Harness Optimization](https://arxiv.org/abs/2608.06301):
  co-authored, arXiv:2608.06301

#### Background
Distributed systems and infrastructure — gossip protocols with Merkle trees, Temporal.io workflows,
Terraform on AWS. Quantitative finance — portfolio optimization, stochastic programming, derivative
pricing. Python, Go, Rust, TypeScript, Java.
