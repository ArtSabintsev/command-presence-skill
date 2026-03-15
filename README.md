# Command Presence

A [Claude Code](https://claude.ai/code) skill for drafting high-stakes communications with strategic persuasion, clarity, and confidence — that sound like a human wrote them.

## What It Does

Command Presence helps you draft emails, messages, and responses that control the frame and move conversations forward on your terms. Built for cold outreach, fundraising, investor relations, sales, negotiation, and leadership communication.

It automatically detects your message type and applies the right rules:

| Type | What It Does |
|------|-------------|
| **Cold Outreach** | 60-90 word SDR/BDR emails. Lead with them, one soft CTA. |
| **Warm Follow-Up** | Reference the connection, new angle, clear ask. |
| **Investor Pitch** | Traction proof, scarcity, confidence. Not needy. |
| **Investor Update** | Metrics up front, own the misses, clear asks. |
| **Reply/Response** | Analyze their message first, then pace and lead. |
| **Objection Handling** | Acknowledge, reframe, redirect. Never argue. |
| **Negotiation** | Interests not positions, BATNA-aware tone. |
| **Saying No** | 2-3 sentences. Direct, gracious, door open. |
| **Internal/Team** | Action-oriented, skip pleasantries. |
| **Re-engagement** | Zero pressure, self-aware, door open. |

## Sounds Human, Not AI

Every message passes the "would a real person actually type this?" test. The skill enforces:

- **Banned words** — 50+ AI-tell words that flag text as machine-generated (delve, leverage, seamless, robust, etc.)
- **Banned phrases** — "I hope this finds you well," "don't hesitate to reach out," and 25+ others
- **Banned formatting** — max 1 em dash per email, no semicolons in casual writing, no bullet points in cold emails
- **Required signals** — contractions always, varied sentence length, sentence fragments, specificity over vagueness

Sources: [anti-slop-writing](https://github.com/adenaufal/anti-slop-writing), AI writing research on perplexity/burstiness metrics.

## Persuasion Frameworks

Synthesizes principles from:

- **Never Split the Difference** (Chris Voss) — tactical empathy, labeling, accusation audit, calibrated questions, no-oriented questions
- **Win Bigly** (Scott Adams) — frame control, pacing and leading, thinking past the sale, high-ground maneuver
- **Pre-suasion** (Robert Cialdini) — priming, attention channeling, unity principle
- **Influence** (Robert Cialdini) — reciprocity, scarcity, authority, social proof, consistency, liking
- **Crucial Conversations** (Patterson, Grenny, et al.) — navigating high-stakes emotional exchanges
- **Getting to Yes** (Fisher & Ury) — principled negotiation, BATNA, interests not positions, mutual gain
- **Extreme Ownership** (Jocko Willink & Leif Babin) — no hedging, simplify, own the outcome
- **Laws of Human Nature** (Robert Greene) — reading people, mirroring values, tailoring to type

## Cold Outreach Frameworks

Six frameworks for SDR/BDR cold email, sourced from [ColdIQ GTM Skills](https://github.com/sachacoldiq/ColdIQ-s-GTM-Skills) and Josh Braun's copywriting principles:

- **Before/After (BAB)** — paint the pain, show the better state, bridge with your solution
- **Problem/Agitate/Solve (PAS)** — name the problem, make it vivid, present the fix
- **Pattern Interrupt** — break their expectation of what a cold email looks like
- **Do The Math** — quantify the problem and ROI with real numbers
- **Upfront Value** — give something useful before asking for anything
- **Ask Before Pitch** — lead with a question that surfaces their pain

Plus Josh Braun's 5 principles: write with an eraser, be cheeky, be specific, show don't tell, use loss aversion.

## Install

```bash
npx skills add ArtSabintsev/command-presence-skill
```

## Usage

Invoke with `/command-presence` in any Claude Code session:

```
/command-presence draft a cold email to [person] about [context]
/command-presence reply to this: [pasted message]
/command-presence rewrite this more confidently: [pasted text]
/command-presence handle this objection: [pasted objection]
/command-presence follow up with [person] about [topic]
/command-presence cold outreach to [prospect] for [product]
```

The skill detects the message type from your request, applies the right rules for tone/length/structure, and drafts accordingly. It will ask clarifying questions if needed.

## License

MIT
