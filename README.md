# Aleksandr Shulgin — `IShu`

Full-cycle backend engineer. Async **Python** · **Rust** · LLM pipelines & automation.
I take on the unsolved and ship it working.

### Machine-verified mathematics via an AI proving pipeline
I built an agent pipeline that produces **machine-checked Lean 4 / Mathlib proofs**, and used it to contribute to **[Google DeepMind's `formal-conjectures`](https://github.com/google-deepmind/formal-conjectures)** (formalized Erdős problems):

- **[PR #4245](https://github.com/google-deepmind/formal-conjectures/pull/4245)** — proved `f₁(n) = n − 1` for unit-distance configurations on the line (Erdős #1084).
- **[PR #4244](https://github.com/google-deepmind/formal-conjectures/pull/4244)** — closed two long-open computational cases of Erdős #1052 (unitary perfect numbers), including the 24-digit one, with a custom σ\* multiplicativity API — replacing a check the repo had marked *"too slow"* and a `sorry`.

Each proof is checked by the Lean kernel — `#print axioms` clean, no `native_decide`.

### Also building
Low-latency trading bots (Python + Rust), crypto-analytics pipelines, LLM automation, self-hosted services.

🌐 **[shulgin.is-a.dev](https://shulgin.is-a.dev)**  ·  open to work
