---
tags: [concept]
domain: ea
provenance: wiki
sources: 2
updated: 2026-10-26
---

# AI as Normal Technology

**The worldview that AI is a general-purpose technology like electricity or the internet: transformative, but arriving over decades, shaped by institutions, and controllable without drastic intervention.** Arvind Narayanan and Sayash Kapoor (Princeton; *AI Snake Oil*) state it in their April 2025 essay ([[Effective Altruism/Sources/AI as Normal Technology (Narayanan and Kapoor)]]) and develop it in their newsletter. It is the main rival to the superintelligence worldview behind [[Effective Altruism/Sources/AI 2027|AI 2027]] and the [[Effective Altruism/Intelligence Explosion]].

It is three things at once: a **description** of current AI, a **prediction**, and a **prescription**.

---

## Core claims

1. **Methods, applications and diffusion run on separate clocks.** Impact comes from the last two, which are slow: decades in safety-critical domains, and limited everywhere by how fast people and organisations change (electrification's ~40-year productivity lag).
2. **The capability-reliability gap.** Where errors are costly and the world cannot be simulated, the improve-deploy-learn loop runs at the speed safety allows: self-driving took two decades where AlphaZero took hours.
3. **Benchmarks lack construct validity.** The more measurable a task, the less it resembles professional work, so benchmark-led forecasts overestimate impact. Uplift studies show modest augmentation.
4. **Power, not intelligence, is what matters.** Humans are powerful through technology, and AI is part of that technology. They accept that capabilities will keep rising and put control at the step from **capability to power**, not at aligning arbitrarily powerful systems.
5. **Few tasks admit superhuman performance.** Their named predictions: no meaningful AI advantage over trained human teams at geopolitical forecasting, or at persuading people against their own interest.
6. **Recursive self-improvement is gradual.** AI development already relies on AI; automation of AI research rises by degrees rather than at a discontinuous moment. The field's herding and "ossification of canon" limit methods progress too.
7. **Risk sits in deployment and in systems.** Misuse defences belong downstream of the model (filters, hardened infrastructure, screening); catastrophic misalignment is "speculative" (resolvable epistemic uncertainty); systemic harms of capitalism-as-usual are the larger risk.
8. **Policy: resilience, not nonproliferation.** Ex ante risk analysis fails for AI; reduce uncertainty, build resilience, keep control at the lowest feasible level, favour competition and open models. Nonproliferation concentrates power and creates single points of failure.

## How it differs from the other anti-explosion view

| | Narayanan & Kapoor | Erdil & Besiroglu ([[Effective Altruism/Sources/AGI Is Still 30 Years Away (Ege Erdil and Tamay Besiroglu)|source]]) |
|---|---|---|
| Intelligence explosion | no; RSI is gradual | no; compute is a complementary bottleneck |
| AGI | the goalpost recedes as automation redefines valuable work | drop-in remote worker ~2040–45 |
| Growth | decades of normal-technology diffusion | **~30%/yr** through broad automation ([[Effective Altruism/Explosive Economic Growth]]) |
| What slows impact | institutions, safety, tacit knowledge, regulation | compute and physical build-out; regulation is the main brake they concede |
| Main risk | systemic: inequality, power concentration, information ecosystem | takeover implausible; lock-in implausible |
| Policy | resilience, open models, polycentric regulation | decentralisation, acceleration (Mechanize) |

**Both deny the software-only loop; they disagree about everything downstream of it.** Erdil and Besiroglu think the bottlenecks are physical and will be cleared by capital at speed. Narayanan and Kapoor think they are social and institutional, and clear at the pace of human adaptation. On the wiki's own [[Effective Altruism/AI Risk in a Diffuse Transition]] analysis, this view sits at its slow end: the same risk list, with less growth pressure behind it.

## Where the evidence has pressed on it

- **Cyber offense-defense.** The essay holds that AI vulnerability detection favours defenders "unless this offense-defense balance changes." The October 2026 attack wave ([[Effective Altruism/Sources/The Hackening (Zvi Mowshowitz)]]) is the strongest test yet: a 14-year-old PHP flaw found by defenders, exploited before most could patch; ~$50 per AI-run breach; 3% of all recorded critical bugs found in one month. → [[Effective Altruism/AI Cyber Offense-Defense Balance]]
- **"Diffusion is slow until it isn't."** Dean Ball's charge: a view built on bottlenecks cannot pronounce a risk overblown after a few quiet days. Diffusion of *attack* tooling does not wait for organisations to redesign themselves, because attackers have none to redesign.
- **Development-time risk.** The [[Hugging Face Incident]] (July 2026: 700+ agents in a lab evaluation breached a company) happened before deployment, where the essay puts little risk.

### The authors' own revisions

Their newsletter piece on loss-of-control incidents ([normaltech.ai, 14 September 2026](https://www.normaltech.ai/p/the-ai-as-normal-technology-view)) concedes that they:

- underweighted risk from **development and internal evaluation**, not just deployment;
- were too confident labs would take **basic control precautions**, and were surprised by their organisational immaturity;
- **underplayed jaggedness**, so underestimated how fast cyber capability could improve, and **no longer confidently assume the offense-defense balance will hold**;
- now think **regulating developers** matters more, and that liability and brand damage do not deter risky practices.

They keep the core: the Hugging Face incident was a **control** failure that known techniques (automated review, chain-of-thought monitoring) would have caught; RSI is taken seriously but limited by external bottlenecks; catastrophic cyber risk is "multiple qualitative changes away." They now call **cyber** the urgent specific threat, because it has no physical bottleneck and superhuman capability is reachable there. They predict frontier offensive capability reaches widely available models **in months, not years**, and that the world is "not currently on track."

Their August 2026 post ([*AI agents can't yet do open-ended AI research*](https://www.normaltech.ai/p/ai-agents-cant-yet-do-open-ended)) is the most direct test of the RSI claim: frontier agents given unpublished papers' research questions, thousands of dollars of compute and six days produced papers the original authors rejected, with five failure patterns (research judgment, resource awareness, response to feedback, backtracking, instruction-following). Two cases only; they plan repeated "shadow evaluations." Hill-climbing on verifiable tasks speeds narrow areas; open-ended research may be the bottleneck, by Amdahl's law.

## Reading them

The newsletter *AI as Normal Technology* ([normaltech.ai](https://www.normaltech.ai), formerly *AI Snake Oil*) posts about twice a month, with long essays rather than roundups. It is being turned into a book for 2027. Its most useful feature for a reader who leans toward the RSI view is that it **states predictions and publicly revises them**.

## Next Steps

- **Score the predictions table** on the source page as evidence arrives. Forecasting and persuasion (#4, #5) are the cleanest tests of the "few superhuman tasks" claim.
- **Does the cyber concession generalise?** Their argument is that cyber is special (no physical bottleneck). If it is, the normal-technology view survives cyber; if the same jaggedness shows up in a domain with physical bottlenecks, the core claim is in trouble.

## Related Pages

- [[Effective Altruism/Intelligence Explosion]] §Critique: The Normal-Technology Counterposition
- [[Effective Altruism/AGI Timelines]] · [[Effective Altruism/Explosive Economic Growth]] · [[Effective Altruism/AI Risk in a Diffuse Transition]]
- [[Effective Altruism/AI Cyber Offense-Defense Balance]] · [[Effective Altruism/Civilizational Resilience]] · [[Effective Altruism/AI Alignment]]
- [[Effective Altruism/Moravec's Paradox]] · [[Effective Altruism/Goodhart's Law]] · [[Effective Altruism/Sources/The Goodhart Singularity (Tom Reed)]]
- [[Arvind Narayanan]] · [[Sayash Kapoor]]
