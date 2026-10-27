---
tags: [analysis]
domain: ea
provenance: wiki
sources: 2
updated: 2026-10-26
---

# AI Cyber Offense-Defense Balance

**Does AI that finds software vulnerabilities help defenders more than attackers?** It is the cleanest live test of the two AI worldviews, because cyber is the one domain where both agree capability is arriving now. [[Effective Altruism/AI as Normal Technology]] predicted defender advantage; the October 2026 attack wave ([[Effective Altruism/Sources/The Hackening (Zvi Mowshowitz)]]) is the first large body of evidence.

---

## The two positions

**Defender advantage** ([[Effective Altruism/Sources/AI as Normal Technology (Narayanan and Kapoor)|Narayanan and Kapoor 2025]]): defenders can point AI at their own systems and fix what it finds before attackers look. Google's LLM-augmented fuzzing found more bugs. Restricting bug-finding models therefore disarms defenders, while motivated attackers train their own. Their caveat: this holds "unless this offense-defense balance changes."

**Transition-favours-offense** (Soares, Buterin, Zvi Mowshowitz): finding bugs in **already-deployed** software before attackers is a race, not a structural advantage. Defenders must find *and* patch *and* get every user to update; attackers need one unpatched system, and every patch announces the bug.

## The evidence from October 2026

| Observation | Bears on | Direction |
|---|---|---|
| The PHP flaws were **found by defenders** (OpenAI's Sol, via Daybreak), not attackers | who finds first | defense |
| Defenders found it **1 August**; exploitation began **17 October**; the embargo broke anyway | whether a lead is enough | offense: an **11-week** lead ran out |
| **46.1%** of version-revealing PHP sites run end-of-life branches | the patch tail | offense: much of the internet cannot be fixed, only replaced |
| A frontier model rediscovered the bug from the prompt "find bad vulnerabilities in PHP" | how cheap discovery is | symmetric, which favours whoever needs fewer successes |
| Project Glasswing missed the bug for six months; a behind-the-frontier model found it | whether defenders run ahead | offense (Soares); roon: a capacity gap, not a structural one |
| **~$50 per breach**, 100+ of 1,200+ companies, open-source Cairn with DeepSeek | cost of attack | offense |
| Old **dumb** vulnerabilities ("123456"; a CA key of "4") exploited at scale | attack surface | offense: AI makes neglect findable |
| Open Code's team hit **model refusals mid-incident** until given Daybreak access | defender access | offense: safeguards bind defenders too |
| The Internet Archive used Claude to patch legacy PHP versions overnight | remediation speed | defense |
| McKenzie: ~**$500B** of security backfill in the US would be unaffordable without agents | remediation cost | defense, conditional on agents being used |

**Net:** the first round went to defenders, narrowly and partly by luck. Both Zvi and the normal-technology authors read it as **an update against reliable defender advantage**. Narayanan and Kapoor concede they underestimated how fast cyber capability could rise and "no longer confidently assume the offense-defense balance will hold" ([normaltech.ai, September 2026](https://www.normaltech.ai/p/the-ai-as-normal-technology-view)).

## The distinction that settles most of the dispute

**Buterin:** cyber is **"endgame defense-favoring but the transition will be hard."** The endgame needs formal verification and minimal trusted computing bases, which make software correct rather than merely patched. The transition is the period when a huge stock of buggy deployed code meets cheap discovery. Both sides can be right: Narayanan and Kapoor about the endgame, Soares and Zvi about the transition. **The transition is where the damage happens.** Casey Handmer's estimate of hundreds of thousands of discoverable vulnerabilities and Jason Clinton's "hold on for ~18 months" put its length at roughly one to two years.

## What the policy fight is about

- **Diffuse vs restrict.** Narayanan and Kapoor: diffuse capability so defenders have it; nonproliferation creates monoculture and single points of failure. Zvi: "we'll diffuse anyway" is not an argument, yet access for **defenders** is too conservative. The real threat is a steady ramp from those who already have access, not one rogue actor with a frontier model for a day.
- **The two converge on defender access.** Both want KYC-backed defender programmes widely offered, more money for patching, and government leadership. Narayanan and Kapoor add that Daybreak's ~$1B and Glasswing's ~$100M are mostly credits, while CISA faces a ~$700M cut and a one-third staff reduction.
- **They diverge on open weights.** The surge is plausibly driven by a cheap new DeepSeek model; GLM-5.3 is the strongest open offensive model. China's draft export controls (prohibiting AI malicious-code generation, restricting AI vulnerability mining) show that even the main open-weight sponsor wants the option to stop. **A good coding model cannot be made unable to write exploits**, so open frontier coding models and cyber restrictions cannot both hold for long.

## Next Steps

- **Watch the next disclosure cycle.** Whether OpenAI's "similar findings to increase sharply" arrive with defenders still first, and whether lead time grows or shrinks, decides whether October was the transition's worst point or its start.
- **Does cyber generalise to bio?** Soares says bio is harsher; Drake Thomas sees no new information for bio. The normal-technology authors call bio risk mostly democratization and leave it to procurement screening.

## Related Pages

- [[Effective Altruism/AI as Normal Technology]] · [[Effective Altruism/Sources/AI as Normal Technology (Narayanan and Kapoor)]]
- [[Effective Altruism/Sources/The Hackening (Zvi Mowshowitz)]]
- [[Effective Altruism/Cause Prioritization/AI Risk is from agency]] · [[Effective Altruism/AI Risk in a Diffuse Transition]] · [[Effective Altruism/Civilizational Resilience]]
- [[Effective Altruism/Multipolar Traps]] — the red queen race as a multipolar trap
