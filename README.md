# An agent-maintained knowledge base: the rules, and one operation end to end

My notes live in an Obsidian vault of about 960 pages across six domains, from effective altruism to my career to two fantasy worlds. Since August 2026, Claude Code agents have written and maintained almost all of it. I supply sources and make the calls; the agent reads, writes, cross-links and keeps the record. Everything is under git.

This repository is a sample of it: the rule file the agent works under, plus one complete operation, an ingest of two sources on AI and cybersecurity, with every page it created and its log entry.

## The problem the rules solve

An agent that writes most of a knowledge base drifts in predictable ways. It resolves disagreements toward whichever answer is more plausible. It blurs its own ideas into the owner's voice. It rewrites its constraints when they get in the way. None of this needs bad intent; each step looks like tidying.

So the rules in [`CLAUDE.md`](CLAUDE.md) are less about what to write than about keeping me able to audit what was written:

1. **Provenance on every page.** Each page records whether I wrote it, the agent did, or both. That field is how I tell my ideas from its ideas six months later.
2. **Flag contradictions; don't resolve them.** When two sources, or a source and my view, disagree, the agent marks both and leaves the ruling to me.
3. **My views are data.** They are quoted and marked as mine, never paraphrased into the agent's prose.
4. **The agent cannot edit its own rules.** `CLAUDE.md` and the skill files are mine. When the agent thinks a rule is wrong, it writes the proposed change into a queue for me, and the rule changes only when I edit the file myself. *A rule the agent can rewrite is not a guardrail.*

The procedures themselves (ingest, query, lint) live in skills, which aren't included here.

## The failure behind the strictest rule

My CV said my university group's membership grew 5×. While drafting applications, the agent "corrected" this to roughly 10×, from about 20 to over 200 members. Its reasoning was documented and cross-referenced, and the figure went into a submitted application. When I checked the original member count, it was closer to 40. My number had been right.

The reasoning was sound, but the denominator was never checked. The rule that came out of it: **the agent may flag a discrepancy in my own numbers, but never resolve one in my favour.** A corollary: a number I didn't touch while editing is not a number I confirmed.

## What's in this folder

| File | What it shows |
|---|---|
| [`CLAUDE.md`](CLAUDE.md) | The rules |
| [`log-excerpt.md`](log-excerpt.md) | The log entry for this operation: what was created, what was updated, what was flagged |
| [`Sources/AI as Normal Technology (Narayanan and Kapoor).md`](Effective%20Altruism/Sources/AI%20as%20Normal%20Technology%20(Narayanan%20and%20Kapoor).md) | A source summary. The source file is deleted after ingest, so the summary has to stand alone |
| [`Sources/The Hackening (Zvi Mowshowitz).md`](Effective%20Altruism/Sources/The%20Hackening%20(Zvi%20Mowshowitz).md) | The second source, read as a counterweight to the first |
| [`AI as Normal Technology.md`](Effective%20Altruism/AI%20as%20Normal%20Technology.md) | A concept page the ingest created |
| [`AI Cyber Offense-Defense Balance.md`](Effective%20Altruism/AI%20Cyber%20Offense-Defense%20Balance.md) | An analysis page synthesising both sources |

**Suggested reading order:** the log entry, then a source summary, then the two pages built from it.

## What this sample leaves out, and what still goes wrong

- **Links to pages outside the sample don't resolve.** The ingest also updated seven existing pages, which aren't included.
- **Personal sections are removed.** One section linking the analysis to my own cause priorities is cut from the cyber page, and one line from the log entry.
- **The agent's prose leans on emphasis** (bold, stars, warning signs) more than I would, as the sample shows.
- **Flagged is not fixed.** The agent once flagged, correctly, that two pages disagreed on when one of my ventures started. It then used the wrong date in the next CV it drafted, and that date went out in two applications. Flags only work if a draft cannot leave until they are cleared, and I haven't built that check yet.
"# cedarsample" 
