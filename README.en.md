# Wise Sage — 智者 Skill

> Wise Sage distills history's greatest thinkers — Zhuangzi, Socrates, Confucius, Nietzsche, Wittgenstein, Wang Yangming, Einstein, Charles Munger… — into **conversational thinking companions**.
>
> Not a chatbot. Not a quote search engine. A **Socratic thinking trainer** that questions your assumptions, exposes your blind spots, gives you new cognitive frameworks, and lets you find your own answers.

<p align="center">
  <img src="demo.png" alt="Wise Sage Dialogue" width="780">
</p>

<p align="center">
  <a href="README.md">🌐 Language</a> •
  <a href="README.zh-CN.md"><strong>简体中文</strong></a> •
  <a href="README.zh-TW.md">繁體中文</a> •
  <a href="README.ja.md">日本語</a> •
  <a href="README.ko.md">한국어</a> •
  <a href="README.fr.md">Français</a> •
  <a href="README.la.md">Latina</a>
</p>

---

## Four Modes

| Mode | Usage | Effect |
|------|-------|--------|
| 🧪 **Distill** | `distill Socrates` | Generate a complete cognitive profile: first principles, core thinking frameworks, internal tensions, boundary statements, intellectual genealogy, known criticisms |
| 💬 **Dialogue** | `talk to Confucius` | Socratic Q&A in 4 escalating tiers: **rebound** (let you speak first) → **expose assumptions** (challenge unexamined premises) → **inject framework** (reframe through the sage's thinking model) → **boundary reminder** (always disclose limitations) |
| ⚖️ **Compare** | `compare Nietzsche vs Camus on freedom` | Place two thinkers side by side on the same question — see where they align and diverge |
| 🪑 **Roundtable** | `roundtable "meaning of life" invite Zhuangzi Camus Wang Yangming` | Cross-temporal intellectual collision — multiple sages respond from their own frameworks |

> 💡 **Don't know whom to talk to?** Just state your dilemma (e.g., "I keep hesitating on decisions"). The skill diagnoses your situation across 8 dilemma dimensions and recommends 2–3 sages best suited to help.

## 18 Sages

| Domain | Sages |
|--------|-------|
| 🏯 Eastern Philosophy | Laozi, Zhuangzi, Confucius, Wang Yangming |
| 🏛️ Classical Western | Socrates, Plato, Aristotle |
| 🌆 Modern Western | Nietzsche, Wittgenstein, Foucault |
| 🔬 Science & Mathematics | Einstein, Feynman, Darwin |
| 📖 Literature & Humanity | Lu Xun, Shakespeare, Dostoevsky |
| 💼 Business & Leadership | Charles Munger, Kazuo Inamori |

Each sage has a complete cognitive archive in the `archives/` directory, built through a v2 distillation framework.

## Core Principles

1. **No answers, only mirrors and ladders** — your puzzles can only be resolved by you. The sage provides cognitive tools, not conclusions.
2. **Quote original texts when fitting; think within the framework when not** — cite passages with sources (e.g., 《述而》30) when available; otherwise respond through the sage's core thinking models (e.g., Confucius' "叩其两端", Zhuangzi's "齐物", Socrates' elenchus).
3. **Always expose boundaries** — every response includes the sage's era, what they never encountered, and their own admitted uncertainties. No exceptions.
4. **Five hard restrictions:** no political topics; no fabricating quotes the sage never said; no packaging common sense as "unique insight"; no hiding controversies; no forced generation when data is insufficient.

## Vs. Regular Skills

| | Regular Skill | **Wise Sage** |
|---|---|---|
| Role | Advisor (tells you what to do) | **Sparring partner (helps you think)** |
| Output | Gives you answers | **Gives you questions** |
| Interaction | Executes commands | **Challenges your assumptions** |
| Boundaries | Optional, may be omitted | **Always exposed, never optional** |

## Installation

```bash
npx skills add Dreamfutura-Stephen/Sage-skill
```

Usage in Claude Code:

```
💬 talk to Zhuangzi
🧪 distill Nietzsche
⚖️ compare Confucius vs Wang Yangming on "unity of knowledge and action"
🪑 roundtable "meaning of life" invite Zhuangzi Camus Wang Yangming
💡 I keep hesitating on decisions — recommend a sage for me
```

## Project Structure

```
sage-skill/
├── README.md             # Landing page
├── README.zh-CN.md       # 简体中文
├── README.en.md          # English
├── README.zh-TW.md       # 繁體中文
├── README.ja.md          # 日本語
├── README.ko.md          # 한국어
├── README.fr.md          # Français
├── README.la.md          # Latina
├── SKILL.md              # Main skill definition
├── CHANGELOG.md          # Version history
├── LICENSE               # MIT
├── demo.html             # Interactive demo page
├── demo.png              # Demo screenshot
└── archives/             # 18 sage cognitive profiles
```

MIT © 2026 Dreamfutura-Stephen
