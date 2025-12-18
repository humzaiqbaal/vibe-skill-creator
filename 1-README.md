# Vibe Skill Creator - Shareable Package

This package teaches you how to build world-class Claude skills that actually improve output.

## What's Included

| File | What It Does | Lines |
|------|--------------|-------|
| **SKILL.md** | The main skill - guides you through building skills from scratch | 656 |
| **references/bad-skill-patterns.md** | 10 patterns that make skills mediocre (avoid these) | 531 |
| **cold-outreach/SKILL.md** | Example skill built using this process | 455 |

---

## How to Use

### In claude.ai (Projects)
1. Create a new Project
2. Go to Project Settings → Custom Instructions
3. Paste the contents of `SKILL.md`
4. Start chatting: "Help me create a skill for [your domain]"

### In claude.ai (Direct)
1. Upload `SKILL.md` as a file
2. Say: "Use this skill to help me build a skill for [your domain]"

### In Claude Code
1. Save `SKILL.md` to your project's `docs/skills/vibe-skill-creator/` folder
2. Or add to `.claude/commands/` as a slash command
3. Reference it: "Use the vibe-skill-creator skill to help me build..."

---

## What Triggers It

Say any of these:
- "Help me create a skill"
- "Build a skill for [domain]"
- "Improve this skill"
- "Help me make a skill"

---

## What Happens

Claude guides you through a 10-step conversation:

```
1. UNDERSTAND → What skill? What problem?
2. EXPLORE    → See where Claude fails without guidance
3. RESEARCH   → Go deep on the domain (web search)
4. SYNTHESIZE → Extract principles from research
5. DRAFT      → Write initial skill
6. CRITIQUE   → Review against quality criteria
7. ITERATE    → Fix gaps, get feedback
8. TEST       → Use on a real scenario
9. FINALIZE   → Structure properly
10. REFERENCE → Build deep expertise docs (if needed)
```

You don't need to know how to build skills. Just have the conversation.

---

## Study the Example

`cold-outreach/SKILL.md` shows what a finished skill looks like:
- Expert voice (not documentation)
- Principles with WHY (not just WHAT)
- Anti-patterns explicitly named
- Real before/after examples
- Quality checklist

---

## Avoid These Mistakes

Read `references/bad-skill-patterns.md` to understand:
- Documentation voice (sounds like a wiki)
- Procedure over principle (step-by-step without thinking)
- Comprehensive coverage (information overload)
- Missing anti-patterns (what to avoid)
- Friction creation (intermediate documents)

---

## Quick Start

Paste this into Claude:

```
I want to build a skill for [YOUR DOMAIN]. Guide me through the process -
explore where you fail without guidance, research the domain, then help me
build a skill that actually improves your output.
```

Then follow the conversation.

---

## Need More Examples?

Other skills built with this process:
- `direct-response-copy` - Copywriting skill with 1,600 lines of embedded reference material
- `ai-creative-strategist` - Visual creative with separate reference files

Each demonstrates different approaches to skill structure.
