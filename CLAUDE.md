# Skills repo

## Skill languages

`SKILL.md` is the canonical file and is always written in English. Agents load only `SKILL.md`.

Every skill directory also keeps these translations next to it:

- `SKILL.ko.md` (Korean)
- `SKILL.zh-CN.md` (Simplified Chinese)
- `SKILL.ja.md` (Japanese)

Rules:

- Any change to `SKILL.md` updates every translation in the same commit. A translation never drifts from `SKILL.md`.
- Translations keep the frontmatter of `SKILL.md` unchanged and translate only the body.
- Translations carry the same meaning, not a looser paraphrase. Keep code identifiers and technical terms (CLI, datatype, etc.) as they appear in `SKILL.md`.
- A new skill ships with `SKILL.md` and all translations at once.
