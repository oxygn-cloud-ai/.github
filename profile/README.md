<div align="center">

# Oxygn

**AI short deliverable consulting (SDC) and open-source tools for financial services businesses and developers**

Singapore &nbsp;&bull;&nbsp; [oxygn.cloud](https://www.oxygn.cloud)

---

</div>

## What We Build

We build open-source developer tools that make AI coding agents more capable, flexible, and productive. Our projects extend [Claude Code](https://docs.anthropic.com/en/docs/claude-code) and other AI agents with skills, plugins, model routing, and cross-project memory.

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

### [gsd-omega](https://github.com/oxygn-cloud-ai/gsd-omega) &nbsp; `Python` &nbsp; `MIT`

Cross-project memory for AI-assisted development. A GSD plugin that ensures every decision Claude makes in one project informs the next — patterns compound, mistakes never repeat.

```bash
npx @oxygn-cloud-ai/gsd-omega
```

### [gsd-plugins](https://github.com/oxygn-cloud-ai/gsd-plugins) &nbsp; `Python` &nbsp; `MIT`

The shared infrastructure and registry for all GSD plugins. Follows Obsidian's community plugin model, adapted for GSD / Claude Code workflows. Plugins hook into Claude Code's lifecycle events and are fail-open by design.

### [goose2](https://github.com/oxygn-cloud-ai/goose2) &nbsp; `Rust` &nbsp; `Apache-2.0`

Fork of [Goose](https://github.com/block/goose) — an extensible, open-source AI agent that automates engineering tasks. Works with any LLM, supports multi-model configuration, and integrates with MCP servers.

### [docs](https://github.com/oxygn-cloud-ai/docs) &nbsp; `MDX` &nbsp; `MIT`

Documentation site powered by [Mintlify](https://mintlify.com). Covers usage guides, API references, and tutorials for Oxygn projects.

## Getting Started

Most Oxygn tools are designed to work with **Claude Code**. If you're new:

1. Install [Claude Code](https://docs.anthropic.com/en/docs/claude-code)
2. Install [claude-skills](https://github.com/oxygn-cloud-ai/claude-skills) for an instant toolkit of slash commands
3. Install [uam](https://github.com/oxygn-cloud-ai/uam) if you want to use non-Anthropic models

## License

Each project is independently licensed — see individual repos for details. Most use the [MIT License](https://opensource.org/licenses/MIT).
