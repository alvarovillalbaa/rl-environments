# rl-environments specification

Last updated: 2026-11-10

Status: planned. All runtime capabilities below remain planned.

## Responsibility

Environment dynamics, observations, actions, rewards, termination rules, fixtures, and task-specific validation.

## First next work

- [ ] Specify one environment with explicit state, action, reward, and termination semantics.
- [ ] Choose its public interface from an actual trainer requirement.
- [ ] Version environment/task fixtures and separate training observations from held-out evaluation.

## Interfaces and composition

Specify the smallest public API against the first real consumer before implementing it. Use explicit inputs, artifacts, versions, and dependency declarations. A planned interface is not an implementation.

## Acceptance

The first implementation must install/run independently, declare dependencies, include a useful example and focused behavior checks, and record remaining limitations. Do not mark this project implemented solely because the documentation exists.
