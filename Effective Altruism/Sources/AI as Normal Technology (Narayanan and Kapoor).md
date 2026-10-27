---
tags: [source-summary]
domain: ea
provenance: wiki
sources: 1
updated: 2026-10-26
---

# AI as Normal Technology — Arvind Narayanan & Sayash Kapoor

**Source:** Knight First Amendment Institute essay, 15 April 2025 ([knightcolumbia.org/content/ai-as-normal-technology](https://knightcolumbia.org/content/ai-as-normal-technology)). Clipped 2026-10-26. ~30,000 words, 119 footnotes (not captured in the clipping).

**Who:** Arvind Narayanan (Princeton computer science) and Sayash Kapoor (Princeton PhD), authors of *AI Snake Oil*. The essay launched the *AI as Normal Technology* newsletter at [normaltech.ai](https://www.normaltech.ai), which continues the framework and is being expanded into a book (planned 2027). → [[Effective Altruism/AI as Normal Technology]]

**What it is:** the essay sets out a **worldview**, not a defence of one proposition. The authors say so and skip point-by-point rebuttals. It is the standard rebuttal to [[Effective Altruism/Sources/AI 2027|AI 2027]], and the wiki's most developed **anti-superintelligence** position. Where Erdil and Besiroglu reject the intelligence explosion and still forecast explosive growth ([[Effective Altruism/Sources/AGI Is Still 30 Years Away (Ege Erdil and Tamay Besiroglu)]]), Narayanan and Kapoor reject **both**: impact arrives over decades.

> *Otto read; not necessarily his view.*

---

## The thesis

"AI is normal technology" is three things at once: a **description** of current AI, a **prediction** about its foreseeable future, and a **prescription** for how to treat it. "Normal" does not mean small: electricity and the internet were transformative general-purpose technologies and still "normal." The contrast is with both utopian and dystopian visions that treat AI "akin to a separate species, a highly autonomous, potentially superintelligent entity."

- Rejects **technological determinism**, and especially AI as an agent determining its own future.
- AI is a tool we **can and should remain in control of**, and staying in control needs no drastic policy or technical breakthrough.
- They aim to describe the **median outcome**. They give no probabilities, but try to make predictions that can show whether AI is behaving like normal technology.
- They reject "fast takeoff," so they decline to picture anything beyond the advanced-AI world of Part II. Industrial Revolution analogy: it was useful to imagine an industrial world, futile to predict electricity or computers.
- "Superintelligence" as usually conceived is called **incoherent**.

---

## Part I — The speed of progress

### Four stages, four clocks

- **Invention:** new AI methods (e.g. LLMs). **Innovation:** products and applications built on them. **Adoption:** an individual or firm's decision to use one. **Diffusion:** the social process by which adoption spreads, which for disruptive technologies needs changes to firm structure, norms and law.
- Each stage has its own **speed limit**, and impact comes from the last two, not from methods.

### Diffusion in safety-critical areas is slow

- *Against Predictive Optimization* (their earlier paper) listed ~**50** applications of ML predicting individual outcomes (criminal risk, insurance risk, child maltreatment). Most use **decades-old regression** on small handcrafted feature sets. Random forests are rare and transformers absent. **Diffusion lags innovation by decades** in consequential domains, mainly for safety reasons.
- **Epic's sepsis model:** looked accurate internally, then **missed two thirds of sepsis cases** in hospitals and flooded physicians with false alerts. One training feature was whether a physician had already prescribed antibiotics, a feature "from the future."
- Obvious-in-hindsight generative failures went untested: Bing's "Sydney" (no one expected long conversations); Gemini's image generator (never tested on historical figures).
- Speed limits are enforced by regulation (FDA medical devices, the **EU AI Act**'s high-risk rules). There are credible worries this regulation is so heavy it becomes "runaway bureaucracy." The 2010 **Flash Crash** produced circuit breakers: regulate new consequential uses as they appear.

### Diffusion is limited by human and institutional change

- **August 2024: 40% of US adults used generative AI**, but infrequently, so it was only **0.5–3.5% of work hours** and a **0.125–0.875 percentage-point** rise in labour productivity.
- The claim that genAI adoption beat PCs (40% in two years vs 20% in three) ignores **intensity of use** and the PC's high price. Measured another way, genAI adoption may have been **much slower** than PC adoption.
- Adoption is about **use, not availability**: workflows and habits take time to change even for a free, instantly released product.
- **Paul A. David on electrification:** dynamos were "everywhere but in the productivity statistics" for nearly **40 years** after Edison's first central station. Gains came only when factories were **redesigned around the production line**, along with new workplace organisation, process control, hiring and training.

### The external world limits innovation

- **Ladder of generality:** each rung (e.g. machine learning replacing hand-written logic) reduces the programmer effort per new task. It is tempting to extrapolate to AGI as a system that needs no applications at all.
- That has held in **simulable, low-stakes domains**: translation via LLMs; **AlphaZero** learning chess from the rules in hours.
- It has not held where errors are costly and the world cannot be simulated. **Self-driving** ran the same improve-deploy-collect loop as AlphaZero, but it took **two decades** because safety limited how far each iteration could scale.
- The **capability-reliability gap** is the recurring barrier to useful agents. Even low-stakes agent tasks (booking travel, customer service) cost enough that learning from real-world experience is hard.
- **Tacit knowledge** is not written down, so feedback loops must run per sector and sometimes per organisation. Privacy and data-sharing rules (e.g. healthcare) limit parallel learning.
- **The bitter lesson is about methods, not applications.** Social-media recommenders run on general ML but still need on the order of **a million lines** of business logic and frontend code.
- **New knowledge needs experiments on people and institutions** (drug trials, economic policy). The social cost of experimenting puts a hard limit on how fast AI can push scientific and social-scientific knowledge. Societies will not, and should not, let AI scale such experiments fast.

### Benchmarks do not measure real-world utility

- GPT-4's reported top-10% bar-exam score says little about practising law: the exam rewards memorised knowledge, which is what LLMs are good at.
- The tasks that would transform a profession (legal filings, strategy) are the ones hardest to evaluate, because they have no single right answer.
- Same gap in software: AI excels at self-contained coding problems, while its real-world SWE impact "appears to be modest" and is hard to measure.
- **"The easier a task is to measure via benchmarks, the less likely it is to represent the kind of complex, contextual work that defines professional practice."** This is a **construct validity** problem, and the AI community consistently **overestimates** real-world impact as a result.
- Only **uplift studies** (build the application, test it with professionals) measure usefulness. They show **modest benefits, more augmentation than substitution**. Copywriters and translators are the exceptions, with substantial job losses.
- **Forecasting** has the same problem. Metaculus's "human-machine intelligence parity" question is defined by exam questions in maths, physics and CS, so forecasters give **95% by 2040**, a figure that says little about impact.

### Economic impacts will be gradual

- Sudden method gains do not translate into impact without innovation and diffusion, which run in a slow feedback loop. Electricity, computers and the internet each took **several decades**.
- Once a task is automated, its cost and value drop relative to human labour, and people move to tasks not yet automated, including tasks that do not exist yet. **The AGI goalpost keeps receding** as automation redefines which tasks are economically valuable. Even if every task done *today* is eventually automated, human labour is not made superfluous.
- Impact therefore arrives at **different times in different sectors**, not as automation of a vast swath of the economy at once.

### Speed limits on methods (their RSI section)

- The argument above holds **even if methods progress could be sped up arbitrarily**, since benefits and risks come from deployment.
- AI/ML papers on arXiv double in **under two years**, but volume is not progress. The field has a history of **herding** (neural nets sidelined for decades), and the transformer has dominated most of a decade despite known limits.
- **Chu & Evans:** across **over a billion citations in 241 subjects**, fields with more papers make it **harder** for new ideas to break through: an **"ossification of canon."**
- Hardware held deep learning back historically; compute and cost limits apply to new paradigms including inference-time scaling; the industry is shifting away from open knowledge-sharing.
- **On recursive self-improvement:** "Perhaps recursive self-improvement in methods is possible, resulting in unbounded speedups in methods. But note that AI development already relies heavily on AI." They expect **a gradual increase in the role of automation in AI development rather than a singular, discontinuous moment** when RSI is achieved.
- **False summits:** each solved benchmark reveals its limits and a new one replaces it. The Turing test was the north star for decades; LLMs arguably pass it while only weakly meeting the expectations behind it. "Moving the goalposts" is what benchmarking should be expected to look like.
- The 1956 Dartmouth organisers hoped for major progress from a "2-month, 10-man" effort. Today's single missing steps (scaling, generalist agents, sample-efficient learning) may not be single steps. In-context learning is already "sample efficient," but only for a limited set of tasks.

---

## Part II — A world with advanced AI

### Power, not intelligence

- "Intelligence," especially across species, is not well defined or measurable on one scale. They reject the species-ladder picture of an intelligence explosion.
- What matters for impact is **power: the ability to modify one's environment.** Humans are powerful because of **technology**, not biology. Ancestral and modern humans barely differ physiologically, so modern humans are already "superintelligent" relative to pre-technological ones.
- **Two causal arrows:** capability → power → loss of control. They **accept that capabilities will likely increase indefinitely.** The superintelligence view gives up on the first arrow and tries to align arbitrarily powerful systems. Theirs is **the opposite: stop systems acquiring catastrophic power.**

### Games mislead

- No useful sense exists in which AI is more intelligent than **people acting with AI**: humans subsume other intelligences into their own through tools.
- Human limits like **speed** explain chess. Where superhuman speed matters (nuclear reactor control), tightly scoped automation does the fast parts and humans control the system.
- **Prediction:** few real-world cognitive tasks let AI blow past humans. Many have high **irreducible error** with humans already near it.
- **Two named predictions:** AI will **not meaningfully outperform trained humans** (especially teams with simple tools) at **forecasting geopolitical events** such as elections, nor at **persuading people to act against their own self-interest.**
- The DeepMind study "Evaluating Frontier Models for Dangerous Capabilities" tested persuasion at no cost or small cost to subjects (e.g. forfeiting a **£20** bonus to charity). Its authors admitted the lack of ecological validity, so the result does not speak to dangerous persuasion.

### Control comes in many flavours

- Model alignment and **human-in-the-loop** are the two extremes, and both have limited roles. Human-in-the-loop (every action approved) either becomes a rubber stamp or is outcompeted, and is **not** the same as human oversight.
- Between them: **auditing**, **monitoring**, system-safety tools (**fail-safes**, **circuit breakers**, redundancy, verification of safety properties), cybersecurity's **least privilege** and access controls, **formal verification** (now applied to AI-generated code), and HCI's **reversible** state-changing actions.
- AI safety research has supplied new tools: LLM judges of proposed actions, systems that learn when to **escalate** to humans, **legible** agent activity, and **hierarchical control** with simpler, reliable systems overseeing capable, unreliable ones. Judged against "align superintelligence," safety research looks unsolved; judged as accident reduction, it has produced "a great abundance of ideas."
- **Prediction:** a growing share of human jobs will be **AI control** and **task specification**, as factory work became monitoring and controlling machines. Karen Levy's truck-driver example: driving is a small part of a trucker's job, and the rest (freight, inspections, repairs, customers, paperwork, yard moves) comes much later.
- Ceding end-to-end control is an ever-present temptation, and its loss of legibility is a **natural check**. Market forces drive this, since poorly controlled AI is too error-prone to pay; regulation should reinforce it.

---

## Part III — Risks

Five types: **accidents, arms races, misuse, misalignment, systemic risks.** Deployers and developers carry primary responsibility for accidents; markets often suffice and regulation fills gaps. Three caveats: arms races; an entity so large that its failure takes civilisation down (a **concentration-of-power** problem, answered by resilience and decentralisation); and agents that "escape" (treated as misalignment). **Military AI is explicitly excluded.**

### Arms races are an old problem

- Safety races to the bottom happened in US garment fire safety (early 20th c.), meatpacking (late 19th/early 20th c.), steamboats (19th), mining (19th–20th), aviation (early 20th). They are **externality** problems, and regulation that makes firms internalise safety costs ends them (process standards, liability, labelling and certification).
- **Self-driving:** Waymo (strong safety culture, best outcomes) leads; Cruise (aggressive) was set to shut down in 2025 after its licence was revoked; Uber sold its unit; Tesla faces lawsuits. They read the **safety–market success correlation as causal.** Regulation was light-touch and **polycentric**, with licence revocation as the check. Aviation held AI to existing standards.
- **Social media is the counter-case:** recommender arms races (TikTok pushing rivals), weak market discipline and slow regulators, because harms are **hard to attribute** and norms are young. Car makers too were not held responsible for safety in the early decades.
- AI will produce some sectors like transport and some like social media, so they call for **"anticipatory AI ethics"** and evidence gathering.
- **Between countries:** accident costs land **locally**, so there is no straightforward reason for an international race. The right analogy is **nuclear power, not nuclear weapons**: there was a weapons race but no power race, and local harms produced a backlash that hobbled nuclear power. US–China rhetoric targets model development, not haphazard adoption. **700 AI bills** were introduced in US state legislatures in 2024, dozens passed. The EU is precautionary (GDPR, DSA, DMA, AI Act); the US regulates after harm.

### Misuse defences must sit downstream of models

- Alignment against misuse is **brittle**, and they think inherently so: **whether a capability is harmful depends on context the model lacks.** Phishing example: profile scraping, target selection, a persuasive email and credential use are each benign; the harm lives in the attacker's orchestration code.
- Giving models enough context to judge intent (e.g. users' personal data) **violates least privilege** and creates exfiltration risk.
- Alignment still reduces harmful outputs, enabled commercial deployment, and adds **friction** for casual attackers.
- Phishing is best stopped by email filtering, browser protections, OS security and user training, defences built over decades against human attackers. **Cyber:** strengthen vulnerability detection rather than restrict capability. **Bio:** procurement and screening.

### AI is useful for defence

- AI already strengthens automated vulnerability detection, threat analysis and attack-surface monitoring. **Google added LLMs to its open-source fuzzing** and found more issues.
- **Claim:** giving defenders powerful AI **often improves the offense-defense balance in their favour**, since defenders can probe and fix their own systems first. Aligning models into uselessness at bug-finding disarms defenders while motivated attackers train their own.
- Measure risk by **offense-defense balance per domain**, which we have agency to shift by investing in defensive applications. → tested in [[Effective Altruism/AI Cyber Offense-Defense Balance]]

### Catastrophic misalignment is a speculative risk

- Misalignment here means acting against developer or user intent through mis-specified objectives, at catastrophic scale.
- **Primary defence is again downstream** (hardened infrastructure, cybersecurity).
- **Speculative risk** means epistemic uncertainty about whether the true risk is zero, resolvable by observation. Asteroid **YR4** (early 2025, ~**2%** impact chance for 2032, later resolved) was speculative; a 10% decade risk of nuclear war is stochastic and not.
- **Paperclip maximiser:** relies on dubious deployment assumptions. Systems must show reliability in low-stakes settings before getting consequential access, and an over-literal "get paperclips from the store as quickly as possible" robot would be shut down at once.
- **Deceptive alignment:** some deceptive behaviour has been observed in leading models. On their view it is "a mere engineering problem," already part of standard safety evaluation. AI improves detection as well as deception; defenders can inspect internals and use defence in depth.
- Long-horizon single-objective RL is the risky design (the boat-racing agent circling for points), but in open-ended real settings such agents will be "more ineffective than they will be dangerous."

### Systemic risks matter more

- Entrenched bias, job losses in specific occupations, worse labour conditions, inequality, **concentration of power**, erosion of trust, information-ecosystem pollution, decline of the free press, democratic backsliding, mass surveillance, authoritarianism. On the normal view these outrank the catastrophic risks, with AI as an **amplifier** of existing instabilities. Industrial Revolution precedent: urbanisation, exploitation, and the rise of socialism and Marxism.
- Maps onto **Kasirzadeh's decisive vs accumulative x-risk**, except that their concern is "simply about the current path of capitalism," not threat actors, and they think such risks are serious but unlikely to be existential.

---

## Part IV — Policy

### Policy under uncertainty

- The camps are entrenched (sceptics coalesced in 2024 around California's **SB 1047**), and expert consensus is unlikely.
- **Compromise fails** because interventions trade off across worldviews: **nonproliferation** may contain superintelligence but worsens normal-technology risks through market concentration; **open-source** builds resilience but could unleash superintelligence. Transparency helps in both.
- **Expected-value reasoning on x-risk probabilities is unviable:** there is no reference class and no deductive model, so estimates are subjective and vary by orders of magnitude. Consequences are uncertain in direction as well as size; infinite disvalue of extinction gives absurd results; restrictions on liberty have unquantifiable costs.
- **Liberal legitimacy:** the state should not restrict freedom on controversial beliefs reasonable people reject. Their reading of the SB 1047 opposition is that many opponents were moved by perceived government overreach given unconvincing justifications.
- Principles: **value pluralism** and **robustness** (policies that help, or at least do not harm, if their assumptions are wrong).

### Reducing uncertainty

Five approaches: **strategic funding of risk research** (e.g. how threat actors actually use AI; the AI Incident Database is valuable but filtered through news selection); **monitoring of use, risks and failures** ("evidence-seeking policies"); **guidance on what evidence counts** (e.g. the "marginal risk" framework for open vs proprietary models); **evidence gathering as a first-rate goal** of any policy; plus evidence synthesis and **adversarial collaborations**.

### The case for resilience

- **Marchant and Stevens:** four approaches to emerging technology. Ex ante: risk analysis and precaution (poorly suited, since AI's risks cannot be ascertained before deployment). Ex post: liability (causation problems and chilling effects) and **resilience**, "the capacity of a system to experience shocks while retaining essentially the same function, structure, feedbacks, and therefore identity"; a "soft landing."
- Resilience means minimising both the severity of harm and the chance that a shock (a bioterror-enabling capability, a weight leak, an open-weight release) becomes harm. It eases the **pacing problem**.
- **Four categories:** (1) **societal resilience broadly** (free press, equitable labour markets); (2) **prerequisites** (risk research funding, transparency for high-stakes developers, technical expertise in government, international cooperation, AI literacy, less fragmentation); (3) **no-regret defences** (early warning systems, defences against identified risks, getting defenders such as software developers to adopt AI, legal protection for researchers, adverse-event reporting, whistleblower protection); (4) **normal-tech-only resilience** that may hinder control of superintelligence (competition including **open model releases**, AI widely available for defence, **polycentric** regulators). The first three should command consensus; pursue the fourth cautiously and stay ready to reverse.

### Against nonproliferation

- Nonproliferation means export controls, licences to build or distribute, banning open weights. They call it **infeasible**: know-how is widespread, training costs are trivial for states, and costs keep falling, so enforcement needs ever more draconian measures and data-centre surveillance gets impractical.
- It **creates risks**: market concentration, **monoculture** (one model's flaw exploitable everywhere, like the 2000s Windows worms), brittleness to leaks or alignment failure, and safety research confined to a few firms.
- **Bio:** real risk, but not an AI risk "any more than it is an internet risk"; existing controls on materials and equipment work against AI-assisted bioterror. **Cyber:** automated vulnerability detection "tend[s] to favor defenders over attackers. Unless this offense-defense balance changes," restricting it is counterproductive.
- **Nonproliferation is a mindset**: control at the most centralised level (governments → model developers → application developers → deployers → end users) vs resilience at the lowest. Examples of nonproliferation-minded measures: unlearning dual-use capabilities, curbing fine-tuning, letting models make safety decisions autonomously, giving models more access to user data to judge intent, and developer-controlled multi-agent "AI organizations." They argue these **increase autonomy, access and organisational ability — superintelligence in the sense of power — and so the very risks they target.**

### Realising the benefits

- Progress is **not automatic**. Jeffrey Ding: **diffusion capacity**, which differs widely between countries, drives national power and growth.
- Regulation can **freeze categories** prematurely: "high-risk" domains where risk varies more within domains than across them (insurance, benefits adjudication, hiring); a supply chain changing fast (developer vs downstream developer vs deployer); binary automated/not-automated rules that discourage graded oversight.
- "Regulation versus diffusion is a false tradeoff." Enabling examples: the **ESIGN Act (2000)**, and the **FAA's 2016 drone rules**, after which registered drones, certified pilots and use cases rose fast. Collective bargaining for publishers against AI firms.
- Invest in **complements of automation**: AI literacy, workforce training, digitisation and **open government data**, grid reliability.
- **Redistribution:** compensate losers, strengthen safety nets, fund arts and journalism via taxes on AI companies.
- **Public-sector adoption:** too fast loses legitimacy (the **NYC chatbot** that told businesses to break the law; dubious **DOGE** uses); too slow outsources government functions to the private sector with less accountability. Nicholas Bagley's **"procedure fetish"** / "runaway bureaucracy."

---

## Final thoughts

Worldviews bundle assumptions, vocabulary, interpretations of evidence, epistemic tools, predictions and possibly values. Their assumption: AI is similar enough to past technologies that diffusion theory applies **absent specific evidence to the contrary**. They "strongly disagree" that genAI adoption is rapid. Their epistemic tools are **disaggregation** (generality levels; methods vs applications vs diffusion) over probability forecasting. They believe some version of their view is widely held but rarely stated, and hope for mutual understanding even without changed beliefs.

Acknowledged reviewers include Gillian Hadfield, Seth Lazar, Dean Ball, Nicholas Carlini, Ajeya Cotra, Jeffrey Ding, Timothy B. Lee, Steve Newman.

---

## The predictions, for scoring

| # | Prediction | Checkable by |
|---|---|---|
| 1 | Slow diffusion stays the norm in high-consequence tasks | adoption in medicine, law, finance decisions |
| 2 | Economic impact over decades, not years; no moment when a vast share of the economy is automated | productivity statistics, sector timing |
| 3 | Automation of AI research rises gradually; no discontinuous RSI moment | lab R&D automation share over time |
| 4 | AI will not meaningfully beat trained human teams at geopolitical forecasting | forecasting tournaments |
| 5 | AI will not meaningfully beat humans at persuading people against their self-interest | persuasion studies with real costs |
| 6 | A growing share of jobs becomes AI control and specification | occupational data |
| 7 | AI-assisted vulnerability detection favours defenders, absent a change in the balance | **Strained by [[Effective Altruism/Sources/The Hackening (Zvi Mowshowitz)|The Hackening]]; the authors retreated from it themselves** → [[Effective Altruism/AI Cyber Offense-Defense Balance]] |
| 8 | No rush to adopt AI haphazardly under US–China race pressure | government deployment behaviour |

---

## Related Pages

- [[Effective Altruism/AI as Normal Technology]] — the worldview as a concept page, with the newsletter's later revisions
- [[Effective Altruism/Intelligence Explosion]] §Critique: The Normal-Technology Counterposition
- [[Effective Altruism/AGI Timelines]] · [[Effective Altruism/Explosive Economic Growth]] · [[Effective Altruism/AI Risk in a Diffuse Transition]]
- [[Effective Altruism/AI Cyber Offense-Defense Balance]] · [[Effective Altruism/Civilizational Resilience]] · [[Effective Altruism/AI Alignment]]
- [[Effective Altruism/Sources/AGI Is Still 30 Years Away (Ege Erdil and Tamay Besiroglu)]] — the other anti-explosion anchor, which keeps explosive growth
- [[Effective Altruism/Sources/The Goodhart Singularity (Tom Reed)]] — the signal bottleneck, a cousin of their capability-reliability gap
- [[Effective Altruism/Moravec's Paradox]] · [[Effective Altruism/Goodhart's Law]]
