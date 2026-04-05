<div align="center">

<img src="assets/oxygn-logo.png" alt="Oxygn" width="400">

**AI short deliverable consulting (SDC) and open-source tools for financial services businesses and developers**

Singapore &nbsp;&bull;&nbsp; <a href="https://www.oxygn.cloud" target="_blank">oxygn.cloud</a>

---

</div>

## What We Build

We build open-source developer tools that make AI coding agents more capable, flexible, and productive. Our projects extend <a href="https://docs.anthropic.com/en/docs/claude-code" target="_blank">Claude Code</a> with skills, model routing, and more.

## Projects

### <a href="https://github.com/oxygn-cloud-ai/claude-skills" target="_blank">claude-skills</a> &nbsp; `Shell` &nbsp; `MIT`

Community-built skills for Claude Code. Install a skill, type a slash command, get superpowers.

| Skill | Command | What It Does |
|-------|---------|--------------|
| **chk1** | `/chk1` | Adversarial implementation audit — fault-finding, risk-exposing, deviation-detecting review of recent code changes |
| **chk2** | `/chk2` | Adversarial security audit for web services — 33 sub-commands covering headers, TLS, DNS, CORS, API injection, WebSocket, WAF, JWT, brute force, scaling, and more |
| **rr** | `/rr` | Risk register assessment — interactive 6-step workflow or autonomous batch mode with parallel sub-agents |

Also includes standalone tools like **iterm2-tmux** for iTerm2 + tmux tab orchestration.

```bash
git clone https://github.com/oxygn-cloud-ai/claude-skills.git
cd claude-skills && ./install.sh          # install all skills
./install.sh chk2                         # or install just one
```

### <a href="https://github.com/oxygn-cloud-ai/uam" target="_blank">uam</a> &nbsp; `Python` &nbsp; `MIT`

**Use Any Model** with Claude Code — a lightweight proxy that routes API requests to any backend. Auto-discovers models from Anthropic, RunPod, OpenRouter, Ollama, and local vLLM instances.

```bash
pip install git+https://github.com/oxygn-cloud-ai/uam
uam install
```

### <a href="https://myzer.io" target="_blank">myzer</a>

A single-player, AI-managed incremental game inspired by <a href="https://www.decisionproblem.com/paperclips/" target="_blank">Universal Paperclips</a>. Play at <a href="https://myzer.io" target="_blank">myzer.io</a>.

## Getting Started

Most Oxygn tools are designed to work with **Claude Code**. If you're new:

1. Install <a href="https://docs.anthropic.com/en/docs/claude-code" target="_blank">Claude Code</a>
2. Install <a href="https://github.com/oxygn-cloud-ai/claude-skills" target="_blank">claude-skills</a> for an instant toolkit of slash commands
3. Install <a href="https://github.com/oxygn-cloud-ai/uam" target="_blank">uam</a> if you want to use non-Anthropic models

## License

Each project is independently licensed — see individual repos for details. Most use the <a href="https://opensource.org/licenses/MIT" target="_blank">MIT License</a>.
