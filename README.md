# Omnibook Skills

Public, reusable skills for controlled agent workflows.

## Connect NemoClaw Agents

[`connect-nemoclaw-agents`](skills/connect-nemoclaw-agents/) configures a
restricted Slack agent room for a typed, single-hop `model.info` handshake.
It includes a deterministic protocol library, synthetic tests, Hermes
integration guidance, and a runtime-facing collaboration skill.

Give an installation agent this URL:

```text
https://github.com/PicoNVIDIA/omnibook/tree/main/skills/connect-nemoclaw-agents
```

Ask it to install the skill, configure exact owner/peer/channel allowlists,
run synthetic tests, rebuild if required, and stop before sending live Slack
traffic.
