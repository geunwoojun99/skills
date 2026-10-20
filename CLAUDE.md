# Skills repo

## Skill languages

Every skill is maintained in four languages:

| File | Language |
| :--- | :--- |
| `SKILL.md` | English (canonical; the only file agents load) |
| `SKILL.ko.md` | Korean |
| `SKILL.es.md` | Spanish |
| `SKILL.ja.md` | Japanese |

The same applies to any other Markdown file inside a skill directory: write `<name>.md` in English and keep `<name>.ko.md`, `<name>.es.md` and `<name>.ja.md` next to it.

Rules:

- Write `<name>.md` in English first, then translate it.
- Keep all four files synchronized in the same change. Headings, normative rules, code examples and warnings must remain semantically equivalent. A review correction to any language updates the others before the change is complete.
- Translations copy the frontmatter of `<name>.md` unchanged and translate only the body. Keep code identifiers and technical terms as they appear in English.
- Put the same language-link line directly under the frontmatter (or at the top, without frontmatter) of all four files:
  `[English](SKILL.md) · [한국어](SKILL.ko.md) · [Español](SKILL.es.md) · [日本語](SKILL.ja.md)`
- A new skill ships with all four files at once.
- Repository-level files (`README.md`, `CLAUDE.md`, plugin manifests) are English only.
