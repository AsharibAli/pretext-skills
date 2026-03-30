# pretext-skills

AI Agents skill for [@chenglou/pretext](https://github.com/chenglou/pretext) — the fastest DOM-free multiline text measurement & layout library.

Pretext replaces expensive DOM measurements (`getBoundingClientRect`, `offsetHeight`) with pure-arithmetic text layout that's 300–600× faster and pixel-perfect across Chrome, Safari, and Firefox. This skill teaches your AI agent how to use it correctly.

## What It Covers

- **Fast path** — measure text height without DOM reflow (`prepare` → `layout`)
- **Rich path** — render text on Canvas/SVG/WebGL, flow around obstacles, shrink-wrap containers
- API selection guidance, caching strategies, font/CSS matching, and common gotchas
- Full language support: CJK, Arabic, Thai, emoji, mixed-bidi, and more

## Installation

```bash
npx skills add asharibali/pretext-skills
```

Works across 40+ agents including Claude Code, Cursor, Cline, Copilot, and Windsurf.

**Manual install (Claude Code)**
```bash
cd ~/.claude/skills
git clone https://github.com/asharibali/pretext-skills.git
```

---

Made with ❤️ by [Asharib Ali](https://github.com/asharibali) for the frontend community.

Star ⭐ this repo if it helps you!
