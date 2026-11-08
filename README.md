# XVC Method v4

An AI-native method for designing **time-constrained research plans**. Instead of mapping a whole landscape and spreading effort evenly, it:

1. identifies the **keystone uncertainty** — the one question whose answer dominates the decision;
2. writes out the **what-must-be-true chain** behind the thesis;
3. designs the **cheapest credible kill test** for the weakest link;
4. sets explicit **kill / preserve / escalate** rules before any deeper research;
5. postpones everything that is not dominant.

It designs research; it deliberately does not answer the underlying question or make forecasts.

## Contents

| Path | What it is |
|---|---|
| `SKILL.md` | Entry point in the Agent Skills format (Claude Code, Codex, and other agents that load `SKILL.md`). |
| `PROMPT.md` | The full method instructions. |
| `references/` | Supporting modules: research modes, kill ladder, keystone uncertainty, mechanism decomposition, evidence rubric, worked examples, and more. |
| `agents/openai.yaml` | Display metadata for OpenAI agent surfaces. |

## Use

**As an agent skill:** copy this directory into your agent's skills folder (for Claude Code, e.g. `~/.claude/skills/xvc-method-v4/`). The agent will pick it up when you ask for a research plan.

**As a plain prompt:** paste `PROMPT.md` into any capable LLM as the system or first message, then attach the relevant files from `references/` when the prompt asks for them.

## License

[CC BY 4.0](LICENSE) — you may share and adapt it, including commercially, with attribution to XVC.
