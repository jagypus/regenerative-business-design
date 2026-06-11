# Regenerative Business Design — a Claude Skill

A Claude skill for designing **economic actors of tomorrow**: businesses whose value creation regenerates living systems, whose ownership cannot be captured or sold off, whose governance gives voice to nature and future generations, and whose financing matches their real growth physics.

It weaves together:

- **Carol Sanford** — the regenerative paradigm: essence, the stakeholder pentad, working from "regenerate life" rather than "do less harm"
- **The Flourishing Business Canvas** (Antony Upward / Strongly Sustainable Business Model Group) — business models across environment, society, and economy
- **Graham Boyd** — FairShares Commons multi-stakeholder ownership and the ergodicity economics of why pooling beats extraction
- **Steward ownership** (Purpose Foundation lineage) — golden shares, perpetual purpose trusts, foundation ownership, asset locks
- **Nature on the board** — guardianship governance in the spirit of Faith In Nature, House of Hackney, and rights-of-nature law
- **Aunnie Patton Power** (*Adventure Finance* / innovative.finance) — revenue-based finance, demand dividends, redeemable equity, and the rest of the design space between grants and VC

The skill runs in three modes: a Socratic **design dialogue** for founders, a written **blueprint** deliverable, and a **diagnostic** for existing businesses. It is deliberately non-evangelical: every recommendation comes with its honest price tag (smaller capital pool, slower raises, no sale-of-control windfall — and how to design founder upside in anyway).

## Install

**Claude Code** — point Claude at this repo and it installs itself:

```
/plugin marketplace add jagypus/regenerative-business-design
/plugin install regenerative-business-design@regenerative-business-design
```

Or with the skills CLI:

```
npx skills add jagypus/regenerative-business-design
```

**Claude Desktop / Cowork** — add this repo's GitHub URL as a plugin marketplace in Settings → Capabilities, or download `regenerative-business-design.skill` from this repo (or the latest Release) and install it from the chat.

**Manual** — copy `skills/regenerative-business-design/` into your `~/.claude/skills/` directory.

## Usage

Just talk to Claude about your venture. Examples:

- "I'm starting a regenerative agroforestry business in Devon — design the business model, ownership structure, and how we'd finance the first £500k."
- "We have a VC term sheet but I want steward ownership and nature on the board. What are my options?"
- "We're a second-generation family business, B Corp certified. How regenerative are we really?"

## Structure

```
skills/regenerative-business-design/
├── SKILL.md                      # orchestrator: stance, five-layer design stack, three modes
└── references/
    ├── paradigm.md               # Sanford: essence, pentad, paradigm levels; Boyd: ergodicity
    ├── flourishing-canvas.md     # the FBC across environment / society / economy
    ├── ownership-legal.md        # steward ownership, FairShares, trusts, foundations, co-ops
    ├── governance-nature.md      # nature & future generations on the board, voice architecture
    └── finance.md                # instrument toolkit, matching heuristics, honest downside ledger
```

## Caveats

This skill provides design thinking, not legal or financial advice. Legal structures vary by jurisdiction and change over time — implement with qualified local counsel.

## License

MIT
