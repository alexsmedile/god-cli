GOD CLI – Smart Orchestrator for Claude, Gemini & Codex

GOD CLI is a command-line orchestrator that makes large-context and multi-agent AI workflows safe, fast, and predictable.
It routes tasks between Claude Code, Gemini CLI, and Codex CLI based on context: repo-wide scans, debugging, or precise patches.

Instead of blindly throwing prompts at one model, GOD CLI applies a routing matrix + validation loop:
	•	🗺️ Gemini → whole-repo analysis & architecture maps (massive context window)
	•	⚡ Codex (GPT-5) → fast reasoning, debugging, planning
	•	🔬 Claude Sonnet 4 → surgical edits, high-precision refactors, orchestration

Key features:
	•	🔄 Automatic task routing (map → diagnose → patch workflows)
	•	✅ Validation built-in (lint, typecheck, test probes before edits)
	•	🛡️ Safety first (read-only by default, explicit approval for edit mode)
	•	💡 Cost-aware (delegates only when cheaper/faster than local execution)

Inspired by cInspired by:
https://www.reddit.com/r/ChatGPTCoding/comments/1lm3fxq/gemini_cli_is_awesome_but_only_when_you_make/

GOD CLI ensures you get that power without chaos.
