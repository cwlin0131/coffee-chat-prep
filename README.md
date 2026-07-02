# Coffee Chat Prep

A reusable **agent skill** for preparing, running, and following up on high-ROI founder peer coffee chats and networking meetings, end to end: **Before → During → After**.

## Why this exists

Hi, I'm [CW (Chi Wei) Lin](https://portaly.cc/cw), founder and CEO of [Portaly](https://portaly.cc). I've been building startups for over a decade. In 2026, while expanding from Asia into the US, I started running founder peer coffee chats to learn a new market and build a network from zero.

This repo is the playbook I distilled from those chats: how I prepare before each one, what I watch for during, and how I follow up after. The names and cases inside are fictional placeholders, but the workflow is the one I actually use.

> **Mindset first:** no one is obligated to help you. Every invitation and ask must be polite and carry genuine gratitude. That attitude comes before any tactic here.
>
> **Core belief:** the ROI of a founder coffee chat isn't how many lessons you extract. It's whether the other person still thinks of *you* six months later. The whole workflow is built to serve that.

---

## What it does

| Phase | When | Output |
|---|---|---|
| 🅾 Request | Signing up in a community | Etiquette for a high-hit-rate comment (real account, filled profile, who you are / what you do / what to discuss) |
| 🅰 Prepare | Before | Prep note: relationship-type call + takeaway goal + talking outline + short/long CTAs |
| 🅱 Live | During | Conversation beat sheet + observation cues + chemistry check (optional one-page cheat sheet) |
| 🅲 Follow-up | Within 24h | 24h deliverable + lightweight debrief + relationship-layer tracking |

## Why it's different

- **Relationship-first, not extraction.** A takeaway written as "get N lessons" is treated as an anti-pattern.
- **Node typing**: classify each contact as *Broadcast*, *Playbook*, or *Ally* to decide what the meeting is actually for.
- **Chemistry detection**: a small set of live signals (do they reciprocate when you go first?) that decide how much to invest afterward.
- **Give before you take**: a structured "what do you most want to solve right now?" beat before offering anything.
- **Anti-pattern checklist**: seven hard-earned mistakes to self-check against before delivering a prep.

## Files

| File | What it is |
|---|---|
| `SKILL.md` | The full three-phase workflow + checklists |
| `question-bank.md` | A categorized library of questions (GTM, fundraising, positioning, product, peer-mirror, …) to draw from per node type |
| `README.md` | This file |
| `LICENSE` | CC BY 4.0 |

## Using it

This is written as an **Agent Skill** (for Claude Code or any agent framework that supports a skills directory). Drop the folder into your skills location and the agent triggers it when you ask to *prep / run / debrief* a meeting. It also reads fine as a **standalone human playbook**: open `SKILL.md` and follow the phases yourself.

### Host-specific hooks to adapt

The workflow references a few host conveniences. Swap them for your own equivalents (or ignore them when reading it as a playbook):

- An **interactive question prompt** to confirm the meeting's takeaway goal (so the goal is chosen by you, not assumed by the agent).
- A **PDF export** for the on-site one-page cheat sheet.
- A **contacts notes folder** (lightweight CRM) for tracking each relationship's status over time.
- A **separate user-interview skill** for meetings that are really product-feedback sessions.

## Customize

- Edit `question-bank.md` to your domain and keep appending questions that worked after each chat.
- Tune the node filters and chemistry signals to your own network. The defaults are starting points, not rules.
- All names, companies, and cases in the workflow are **illustrative placeholders**. Replace them with your own context.

## License

Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Free to use, modify, and commercialize with attribution:

> Based on [Coffee Chat Prep](https://github.com/cwlin0131/coffee-chat-prep) by [CW Lin](https://github.com/cwlin0131)

Examples are fictional and for illustration only.
