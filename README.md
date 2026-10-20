# Skills

My agent skills, packaged as a Claude Code plugin.

## Installation

### Claude Code

```bash
claude plugins marketplace add geunwoojun99/skills
claude plugins install geunwoo-skills@geunwoo
```

Or, from inside a session:

```
/plugin marketplace add geunwoojun99/skills
/plugin install geunwoo-skills@geunwoo
```

### Codex, and other agents

```bash
npx skills@latest add geunwoojun99/skills
```

## Skills

### Productivity

- **[one-thing](./skills/productivity/one-thing/SKILL.md)** (user-invoked): Name the session's ultimate goal and the single lever that makes every other task easier or unnecessary. ([한국어](./skills/productivity/one-thing/SKILL.ko.md) · [简体中文](./skills/productivity/one-thing/SKILL.zh-CN.md) · [日本語](./skills/productivity/one-thing/SKILL.ja.md))

Each skill's `SKILL.md` is in English. Korean, Simplified Chinese and Japanese translations live next to it for reading; agents load only `SKILL.md`.
