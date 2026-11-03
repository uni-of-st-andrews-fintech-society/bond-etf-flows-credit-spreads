# AI use log

Load-bearing AI use only. This feeds the AI disclosure in the paper's appendix.
AI can write code; humans review every methodology choice and every reference.
AI never iterates against out-of-sample results.

Template:

```
## YYYY-MM-DD — <task>
- Tool:
- What it produced:
- What a human verified, and how:
```

---

## 2026-11-03 — Phase 0 repo scaffolding
- Tool: Claude Code (Claude Opus 5.5)
- What it produced: the folder layout and READMEs, the five empty log files, the `PREREG.md` skeleton, the expanded top-level `README.md` and `.gitignore` additions. No data, analysis code or methodology choices.
- What a human verified, and how: Reviewed by ashaji518 on 2026-11-03. Checked that the folders match the framework's repo layout table, that logs/ holds the five logs from the logging table, that .gitignore excludes data/raw/ and .env, that PREREG.md is an unregistered draft with no hypotheses or dates, and that no data, keys or code were committed.
