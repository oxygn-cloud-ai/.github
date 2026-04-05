<div align="center">

# Oxygn

**AI short deliverable consulting (SDC) and open-source tools for financial services businesses and developers**

Singapore &nbsp;&bull;&nbsp; [oxygn.cloud](https://www.oxygn.cloud)

---

</div>

## What We Build

We build open-source developer tools that make AI coding agents more capable, flexible, and productive. Our projects extend [Claude Code](https://docs.anthropic.com/en/docs/claude-code) with skills, model routing, and more.

## Projects

### [claude-skills](https://github.com/oxygn-cloud-ai/claude-skills) &nbsp; `Shell` &nbsp; `MIT`

Community-built skills for Claude Code. Install a skill, type a slash command, get superpowers. Includes security auditing, risk assessment, project management workflows, and more.

```bash
git clone https://github.com/oxygn-cloud-ai/claude-skills.git
cd claude-skills && ./install.sh
```

### [uam](https://github.com/oxygn-cloud-ai/uam) &nbsp; `Python` &nbsp; `MIT`

**Use Any Model** with Claude Code — a lightweight proxy that routes API requests to any backend. Auto-discovers models from Anthropic, RunPod, OpenRouter, Ollama, and local vLLM instances.

```bash
pip install git+https://github.com/oxygn-cloud-ai/uam
uam install
```

## Getting Started

Most Oxygn tools are designed to work with **Claude Code**. If you're new:

1. Install [Claude Code](https://docs.anthropic.com/en/docs/claude-code)
2. Install [claude-skills](https://github.com/oxygn-cloud-ai/claude-skills) for an instant toolkit of slash commands
3. Install [uam](https://github.com/oxygn-cloud-ai/uam) if you want to use non-Anthropic models

## License

Each project is independently licensed — see individual repos for details. Most use the [MIT License](https://opensource.org/licenses/MIT).
