# agentweave

From in the loop to on the loop.

You're **in the loop** when you approve every action, re-engage agents after each turn, manually dispatch work, and babysit progress. You're **on the loop** when you design the system, step back, and check in on your terms.

Agentweave is a suite of composable [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugins that move you from one to the other — each removing a different bottleneck that keeps you stuck.

| Bottleneck | Product | Tagline | Install |
|---|---------|---------|---------|
| **Behavioral** | [**Tension**](https://github.com/agentweave/tension) | A dial for agent autonomy. | `claude plugin install tension@agentweave` |
| **Temporal** | [**Shuttle**](https://github.com/agentweave/shuttle) | Give your agent a todo list. | `claude plugin install shuttle@agentweave` |
| **Coordination** | [**Cortex**](https://github.com/agentweave/cortex) | Give your agents a chief of staff. | `claude plugin install cortex@agentweave` |
| **Infrastructure** | [**Spindle**](https://github.com/agentweave/spindle) | Spin up agents that stay up. | *Coming soon* |

## How they compose

Pick what you need. Each tool works standalone.

- **Solo dev** — Tension + Shuttle. Dial in the behavior, queue up tasks, walk away.
- **Agent team** — add Cortex. A chief of staff dispatches work to agents through a shared folder of markdown files.
- **At scale** — add Spindle. Deploy agents to Kubernetes, talk to them via Telegram.

## The idea

Instead of operating agents directly, you engineer the **harness** — the behavioral boundaries, task queues, coordination protocols, and infrastructure that agents work within. Then you step back and let agents run.

## Philosophy

- Skills are prompts, not code. No runtime, no build step.
- Plain markdown over custom formats. YAML frontmatter over config files.
- Each tool works standalone. Compose only when you need to.
- Open source, MIT licensed, no telemetry.

Learn more at [agentweave.github.io](https://agentweave.github.io).
