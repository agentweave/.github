# agentweave

Composable tools that get the human out of the loop.

Four open-source plugins for Claude Code, each targeting a different dimension of agent autonomy:

| | Product | What it does | Install |
|---|---------|-------------|---------|
| **Behavioral** | [**Tension**](https://github.com/agentweave/tension) | A dial for agent autonomy. | `claude plugin install agentweave/tension` |
| **Temporal** | [**Shuttle**](https://github.com/agentweave/shuttle) | Give your agent a todo list. | `claude plugin install agentweave/shuttle` |
| **Coordination** | [**Cortex**](https://github.com/agentweave/cortex) | Give your agents a chief of staff. | `claude plugin install agentweave/cortex` |
| **Infrastructure** | [**Spindle**](https://github.com/agentweave/spindle) | Spin up agents that stay up. | *Coming soon* |

## How they compose

No single tool solves everything. Pick what you need:

- **Solo dev** — Tension + Shuttle. Dial in the behavior, queue up tasks, walk away.
- **Agent team** — add Cortex. A chief of staff coordinates workers through a shared folder of markdown files.
- **At scale** — add Spindle. Deploy agents to Kubernetes, talk to them via Telegram.

## Philosophy

- Skills are prompts, not code. No runtime, no build step.
- Plain markdown over custom formats. YAML frontmatter over config files.
- Each tool works standalone. Compose only when you need to.
- Open source, MIT licensed, no telemetry.
