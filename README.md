# rl-environments

Last updated: 2026-11-10

Provide reusable environments and task protocols for independent reinforcement-learning consumers.

**Status: planned.** This repository currently contains specifications and an implementation backlog. It has no executable engine or installable package.

## Independent use

Read [the component specification](docs/specs/README.md) and choose its first bounded implementation task. No runtime dependency or installation is required to use the specification.

## Ownership

Environment dynamics, observations, actions, rewards, termination rules, fixtures, and task-specific validation.

Outside this component: LLM RL post-training algorithms, a general trainer, or the Open Evals scoring platform.

## Compose

Use independently, or register a pinned version in [Lab](https://github.com/alvarovillalbaa/lab). A dependency on Lab is never required. Libraries connect through declared dependencies or explicit artifact/job interfaces.

[Specification and next work](docs/specs/README.md) · [Extraction provenance](docs/sources/lab-provenance.json)

MIT applies to the code and authored documentation in this repository. External datasets, model weights, provider services, and third-party projects retain their own terms.
