# Writing Spec Kit — README

A structured workflow for creative and expository writing, modeled on the software delivery spec kit. Designed specifically for work involving philosophical prose, the Zine project, and any writing that moves between expository argument and rhetorical/poetic voice.

---

## How to Use This Kit

### Starting a new piece
1. Open `contract-template.md`
2. Fill it out completely — especially the "one sentence this piece must earn" and the "protected elements"
3. If you cannot fill out the contract, the piece is not ready to draft

### Revising or consolidating existing material
1. Run `workflows/audit-prompt.md` on the document first (builds term map, proposition map, poetic phrase map)
2. Select the right skill from `writing-skills.md` using the Quick Skill Selection table at the bottom
3. Run the revision using `workflows/revision-prompt.md` as the section-level protocol
4. Check output against the relevant touchstone in `touchstones/`

### Deciding which skill to use
See the Quick Skill Selection table in `writing-skills.md`. The most common situations:
- **One draft, mixed expository/rhetorical content** → Skill 8
- **Two drafts, same piece** → Skill 4 (rhetorical) or Skill 2 (expository)
- **Two texts from different frameworks** (Aquinas + Steiner, etc.) → Skill 8 piecemeal
- **Assembling the Zine** → Skill 7 after all beats are consolidated

### After finishing a piece
Add any new decision rules to `decision-rules.md`. Note what the piece resisted in the contract's "Notes on resistance" field.

---

## Files in This Kit

| File | What it's for |
|------|--------------|
| `index.md` | Full workflow reference with phase-by-phase guidance |
| `README.md` | This file — start here |
| `contract-template.md` | Fill out before drafting any piece |
| `writing-skills.md` | Full 8-skill taxonomy with procedures |
| `skills-quick-ref.md` | One-paragraph summaries for quick recall |
| `decision-rules.md` | Standing rules from all revision work |
| `touchstones/rhetorical-touchstone.md` | Quality standard for rhetorical prose |
| `touchstones/expository-touchstone.md` | Quality standard for expository prose |
| `agent-prompt.md` | System prompt for a specialized writing agent |
| `zine-session-log.md` | Template for logging Zine editing sessions |

### Linked workflow files (in parent vault)
| File | What it's for |
|------|--------------|
| `workflows/audit-prompt.md` | Pre-revision consistency audit — run first |
| `workflows/revision-prompt.md` | 9-step section-level revision protocol |

---

## The Zine Project

The primary active project. Key files:

| File | Role |
|------|------|
| `Writing Projects/Zine/_rhetorical/index.md` | Beat sheet with status tags — check before every session |
| `Writing Projects/Zine/_rhetorical/02b-perception-form-trees/reference.md` | Canonical definition authority — check any term here first |
| `Writing Projects/Zine/reference.md` | Extended reference (Steiner, Berry, OOO, Teilhard) |
| `Writing Projects/Zine/_expository/synthesis-map.md` | Cross-tradition map and gap list |
| `Writing Projects/Zine/_rhetorical/spine/zine-tree-constancy-to-stewardship.md` | The through-line — do not edit |
| `writing-spec-kit/zine-session-log.md` | Log every editing session |

**Framework authority for the Zine:** When Aquinas and Steiner conflict, Aquinas governs the expository layer; Steiner may appear in the rhetorical layer as a parallel or tension, flagged explicitly. OOO and Berry are supplementary — they clarify or extend, they do not override.

---

## How to Invoke This Kit With an Agent

### Option 1 — CLAUDE.md (automatic)
A `CLAUDE.md` file exists at the vault root. Any Claude Code session in this directory will automatically load it. It tells the agent to check this kit before starting any writing task.

### Option 2 — Agent prompt (for deep Zine work)
`writing-spec-kit/agent-prompt.md` contains a full system prompt for a specialized writing agent. To invoke it:
- Paste the contents at the start of a new conversation, or
- Tell Claude: *"Read writing-spec-kit/agent-prompt.md and operate as that agent for this session"*

### Option 3 — Remind the agent
At the start of any session involving writing, say:
> "Check writing-spec-kit/index.md and writing-spec-kit/writing-skills.md before we start."

This is enough for most revision sessions where the full agent prompt isn't needed.

---

## What This Kit Does Not Cover

- **Grammar and line editing** — that's Skill 3's Blueprint step, not a separate workflow
- **Research** — the david-need-prep.md in `Philosophy-Science/bagua-aquinas/` is the model; no template exists yet
- **Sourcing discipline** — the oldtime-history project models this; no formal skill yet
- **Memoir** — no contract exists for the memoir project; it needs one before the kit applies
