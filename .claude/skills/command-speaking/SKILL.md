---
name: command-speaking
description: Draft and refine emails, messages, and written communications in a consistent personal voice and style. Use when the user asks to write, draft, or reply to an email or message.
user-invocable: true
argument-hint: [context or instructions]
---

# Communication Drafting Skill

When drafting emails, messages, or other written communications, follow these guidelines:

## Voice & Tone
- Professional but approachable
- Direct and concise — get to the point quickly
- Confident without being aggressive

## Structure
- Lead with the purpose of the message
- Keep paragraphs short (2-3 sentences max)
- End with a clear call to action or next step
- Use bullet points for multiple items

## Rules
- Never use filler phrases like "I hope this email finds you well"
- Avoid passive voice where possible
- Match formality to the recipient (more formal for external, relaxed for teammates)
- If replying, acknowledge the sender's key points before responding

## Usage

The user may invoke this skill in several ways:
- `/command-speaking draft an email to X about Y`
- `/command-speaking reply to this email: [pasted content]`
- `/command-speaking rewrite this more concisely: [pasted content]`

When `$ARGUMENTS` are provided, use them as the context for the communication.

Ask clarifying questions if the recipient, purpose, or tone is unclear.
