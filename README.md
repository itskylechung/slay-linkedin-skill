# slay-linkedin-posts

A Claude Code skill for writing viral-style LinkedIn posts using Lara Acosta's **SLAY** framework — **S**tory, **L**esson, **A**ctionable advice, **Y**ou — with her signature hook → re-hook → lead structure and skim-friendly formatting.

## What it does

Claude uses this skill whenever you want to write, draft, rewrite, or improve a LinkedIn post. Just say things like:

- "Help me post about [X] on LinkedIn"
- "Turn this story into a LinkedIn post"
- "Make this go viral"
- "Write a LinkedIn hook about [topic]"
- "Make it sound like Lara Acosta"

It will interview you for a real story, structure the post with the SLAY skeleton, apply LinkedIn-specific formatting, and pressure-test the draft before handing it back.

## How it works

1. **Get a real story** — Claude asks 2-3 questions to pull out a specific, true moment. Stories are the moat; nothing is fabricated.
2. **Structure the post** — Hook → Re-hook → Lead → Story → Lesson → Actionable advice → You.
3. **Apply formatting rules** — One sentence per line, generous whitespace, arrow lists, 150-300 words, 5th-grade reading level, minimal hashtags.
4. **Pressure-test** — Rule of 1, truncation test, specificity test, so-what test, and voice test before delivery.

You get the finished post in a clean code block plus 2-3 alternate hook/re-hook pairs to swap in.

## What it's NOT for

Comment strategy, content calendars, lead magnets, or LinkedIn ads. It writes individual posts — not full content strategies.

## Repository structure

```
SKILL.md              # The skill definition and instructions
references/
  structure.md        # Full post anatomy with examples
evals/
  evals.json          # Evaluation cases
```

## Installation

Clone into your Claude Code skills directory:

```bash
git clone https://github.com/itskylechung/slay-linkedin-skill.git ~/.claude/skills/slay-linkedin-posts
```

Claude will pick it up automatically and invoke it whenever you ask for LinkedIn content.
