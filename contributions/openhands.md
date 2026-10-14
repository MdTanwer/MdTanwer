# OpenHands software-agent-sdk

[All pull requests](https://github.com/OpenHands/software-agent-sdk/pulls/MdTanwer) · [Back to profile](../README.md)

Python work on the agent SDK: typed contracts instead of runtime attribute probes, conversation lifecycle, and runtime suspension.

| Pull request | Detail |
|---|---|
| [#5357](https://github.com/OpenHands/software-agent-sdk/pull/5357) | Replaced settings and tool metadata probing with typed APIs. |
| [#5293](https://github.com/OpenHands/software-agent-sdk/pull/5293) | Typed ACP capability and session contracts. Replaced 23 runtime attribute probes with a typed dataclass/Protocol boundary. CI violation baseline 98 → 75, with no regressions across 578 tests. |
| [#5343](https://github.com/OpenHands/software-agent-sdk/pull/5343) | Declare lifecycle capabilities on base classes. Removes runtime attribute probes across local and remote conversations, condensers, and events. |
| [#5199](https://github.com/OpenHands/software-agent-sdk/pull/5199) | Suspend idle Docker containers when a conversation reaches a terminal state. Lock-guarded lease checks and full-history resume, aimed at host RAM and disk exhaustion. |
| [#5576](https://github.com/OpenHands/software-agent-sdk/pull/5576) | Detect serialized LLM calls across conversations. |
| [#5554](https://github.com/OpenHands/software-agent-sdk/pull/5554) | Derive settings schema facts from JSON Schema. |
| [#5451](https://github.com/OpenHands/software-agent-sdk/pull/5451) | Restore risk-labelling guidance when a custom system prompt is used. |
| [#5477](https://github.com/OpenHands/software-agent-sdk/pull/5477) | Prefer a PATH ACP binary only when it matches the pinned version. |
| [#5371](https://github.com/OpenHands/software-agent-sdk/pull/5371) | Typed retry and LLM delegation contracts. |
| [#5219](https://github.com/OpenHands/software-agent-sdk/pull/5219) | Stop the browser-use tool from disappearing on unlocked installs. |
