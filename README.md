# Perfect CLAUDE.md

A Claude Code skill that turns a brain dump into two files: a personal `CLAUDE.md` (how Claude works with you) and a `goals.md` (what you're working toward and why).

Built for first-time setups. You talk, it writes, it reads both files back to you for corrections.

## Install

Paste this into Claude Code:

> Install the perfect-claude-md skill: clone https://github.com/amart-builder/perfect-claude-md to a temp folder, copy the folder containing SKILL.md into ~/.claude/skills/perfect-claude-md, delete the temp clone, then tell me to restart Claude Code.

## Use

Restart Claude Code, then:

```
/perfect-claude-md
```

Paste your introduction. Ramble. Voice-to-text is perfect. It will ask one batch of follow-up questions for whatever you left out, then write both files into `~/Desktop/Projects/System Prompts/` (with a link so Claude Code finds CLAUDE.md) and read them back.

By [Edge AI](https://joinedgeai.com).
