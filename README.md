# Command Presence

A [Claude Code](https://claude.ai/code) skill for drafting high-stakes communications with strategic persuasion, clarity, and confidence.

## What It Does

Command Presence helps you draft emails, messages, and responses that control the frame and move conversations forward on your terms. Built for fundraising, investor relations, negotiation, and leadership communication.

It synthesizes principles from:

- **Never Split the Difference** (Chris Voss) — tactical empathy, labeling, calibrated questions
- **Influence** (Robert Cialdini) — reciprocity, scarcity, authority, social proof, consistency, liking
- **Crucial Conversations** (Patterson et al.) — navigating high-stakes, emotional exchanges
- **Pre-suasion** (Robert Cialdini) — priming, attention channeling, setting the stage
- **Win Bigly** (Scott Adams) — frame control, pacing and leading, thinking past the sale
- **Getting to Yes** (Fisher & Ury) — principled negotiation, BATNA, mutual gain
- **Extreme Ownership** (Jocko Willink) — no hedging, simplify, own the outcome
- **Laws of Human Nature** (Robert Greene) — reading people, mirroring values, tailoring to type

## Install

Clone this repo and symlink the skill into your Claude Code skills directory:

```bash
git clone https://github.com/ArtSabintsev/command-presence-skill.git
ln -s "$(pwd)/command-presence-skill/.claude/skills/command-presence" ~/.claude/skills/command-presence
```

Or if you already have the repo locally:

```bash
ln -s ~/Developer/command-presence-skill/.claude/skills/command-presence ~/.claude/skills/command-presence
```

## Usage

Invoke with `/command-presence` in any Claude Code session:

```
/command-presence draft a cold email to [investor] about [context]
/command-presence reply to this: [pasted message]
/command-presence rewrite this more confidently: [pasted text]
/command-presence handle this objection: [pasted objection]
/command-presence follow up with [person] about [topic]
```

The skill will ask clarifying questions about recipient, relationship, goal, objections, and leverage if needed — then draft accordingly.

## How It Works

Every message follows a structure: **Hook** (earn the next line), **Context** (why now), **Substance** (tight and specific), **Ask** (one clear next step).

The skill enforces voice rules: no filler, no hedging, no passive voice, no over-qualification. Confidence is the baseline.

## License

MIT
