# MBAN5530 IA4 — Session Handoff: Per-Slide Speaking Scaffold

**Black Point Analytics · 28 May 2026**
**Subject deck:** `MBAN5530_IA4_GTSv9.html` (23 content slides + 2 dividers)
**Purpose of this handoff:** convert the finished deck into per-slide speaking *beats* (not a script) so the recording hits Outstanding on Presentation (30% of the Q1 rubric). The other two criteria (Stakeholders 50%, Learnings 20%) are already at the Outstanding ceiling in the artifact; this document is the delivery layer.

---

## How to use this (read once)

> **Voice retention — binding.** These are beats, not lines. Each slide gives you the *moves* to hit and the *must-say* anchors, deliberately under-written so you talk *to* them, not *read* them. The rubric rewards "entirely in your own words with no reliance on reading." If you memorize sentences, you will sound like you are reciting; if you internalize beats, you will sound like you know it. Talk to the beats.

**What "Outstanding on Presentation" looks like, concretely:**
1. **You are explaining, not reading.** Eyes up, slides as backdrop. The beats below are deliberately fragmentary so you cannot read them.
2. **One idea per slide, landed.** Each slide has a single *landing* (the one thing the viewer should leave with). Say it, pause, advance.
3. **Transitions are spoken, not silent.** Each slide has a one-line bridge into the next. Continuity is what separates a deck-read from a discussion.
4. **Numbers are said with meaning, not recited.** "+0.6 points" means nothing alone; "+0.6 points, which maps to thirty percent higher mortality" is the move.
5. **You cite the paper out loud, once, early.** "Obermeyer, Powers, Vogeli, and Mullainathan, 2019."

**Two verbal-only landmines (from OC-02 / OC-04):**
- Say **"named the next day by reporting"** when you name Optum, so the Tier B fact is honest aloud.
- Keep **"principles" (8) and "components" (11) distinct.** Never call the eleven components "principles."

**Pacing:** the deck carries time cues, but you pace on camera, so treat them as relative weights, not a clock. The two long slides (Black patients, the regulator climax) deserve the air; the connective stakeholders move fast.

---

## INTRO (4 slides) — earn attention, then frame

### 1.1 · Access is uneven before any algorithm
- **Landing:** inequality is already in the room before the model arrives.
- **Beats:** picture doing everything right and still not reaching care (transport, time, a chunk of the paycheck) → your own Nova Scotia experience, the Truro MRI reschedule → flip it: someone nearby with flexibility uses the same system fine → so the system already spends less on the people with less access.
- **Must-say anchor:** "the inequality is in the room before any model shows up."
- **Bridge:** "Now watch what happens when we train a model on that spending and call it need."

### 1.2 · The case in one breath
- **Landing:** one sentence of what the case *is*, so the rest is interpretation not exposition.
- **Beats:** one real algorithm → US hospitals used it to flag patients for extra care → ranked by predicted cost on the assumption costlier means sicker → that assumption broke along racial lines.
- **Cite here:** "Obermeyer, Powers, Vogeli, and Mullainathan, 2019."
- **Bridge:** "Three numbers anchor the whole thing, and they're three different findings, so keep them separate."

### 1.3 · The three figures
- **Landing:** these are three *distinct* experiments; do not blur them.
- **Beats:** 84% = kept the model, changed the target to combine cost with real illness measures; missed illness fell from ~49k to ~7.7k → 17.7→46.5% = a what-if, if the score had tracked health the Black share flagged jumps, and the *size of the jump is the size of the problem* → $1,801 = at the same illness level the system spent less, and the model read "cheaper" as "healthier."
- **Must-not:** do not say the 84% and the 46.5% are the same finding.
- **Bridge:** "So the headline isn't that the algorithm was broken."

### 1.4 · Frame: Right algorithm, wrong target
- **Landing:** the engineering was fine; the *target* was wrong, and a cost stand-in launders existing inequality into a neutral-looking number.
- **Beats:** point at the curve, 4.8 vs 3.8 conditions at the cutoff, same score sicker patients → name it once: **"proxy laundering"** → measured on the wrong output, you quietly breach the principles you thought you were honoring.
- **Coined term:** say "proxy laundering" *once*, here, and never again. It is your IA4 signature the way "procured-principles paradox" was IA1's.
- **Bridge:** "Start where the harm starts."

---

## Q1 STAKEHOLDERS (11 slides) — depth on three nodes, speed on the rest

> Strategy for the 50% criterion: go *deep* on the three high-impact nodes (vendor data scientists, Black patients, regulators) and move *fast* through the connective ones. Depth-over-coverage is the Kelley signal. The heat maps do the breadth; your voice does the depth.

### Q1.1 · Vendor data scientists (deep)
- **Landing:** built the model right, picked the outcome wrong; health is biomarkers, not dollars.
- **Beats:** walk the table, not every row, just the two with numbers → blood sugar +0.6 → ~30% higher mortality → blood pressure +5.7 → ~7.6% higher mortality → kidney and anemia worse too → same score, worse health, and the validity breaks right at the label.
- **Bridge:** "And the vendor behind this wasn't fringe."

### Q1.2 · The vendor (Optum)
- **Landing:** an industry leader, not an outlier; scale is the story.
- **Beats:** anonymous in the paper, **named the next day by reporting** as Optum's Impact Pro, a UnitedHealth subsidiary → ~200M Americans reached before any outside audit → when confronted, they replicated the bias on 3.7M of their own patients.
- **Bridge:** "The bias wasn't invented here, it was inherited."

### Q1.3 · Insurance and payers (fast)
- **Landing:** the training signal was already skewed.
- **Beats:** claims approved on cost → that pattern became the label → the model learned a disparity the system already had.
- **Bridge:** "The hospitals that bought it inherited the liability."

### Q1.4 · Hospital executives (fast)
- **Landing:** bought a closed box to control cost, inherited a design they didn't make.
- **Beats:** procurement for cost control → never asked for explainability or societal impact → own the liability anyway.
- **Bridge:** "The doctors only ever saw a number."

### Q1.5 · Treating physicians (fast)
- **Landing:** a score with no explanation anchors the human to the score.
- **Beats:** saw a rank, not the biomarkers → overrode only a small fraction of the bias → human oversight fails when there's no recourse behind the number.
- **Bridge:** "And the people carrying the harm couldn't see it at all."

### Q1.6 · Black patients (deep — let it breathe)
- **Landing:** this is the center; the harm was invisible to the people bearing it.
- **Beats:** sicker at every risk score → 4.8 vs 3.8 at the cutoff, a 26% gap → the biomarkers from earlier → under-served, with no way to see that a number decided it.
- **Pacing:** slow here. This is the moral center of the talk.
- **Bridge:** "And there's a ledger nobody priced."

### Q1.7 · Families and caregivers (fast)
- **Landing:** the unpaid stakeholder no AI law names.
- **Beats:** families absorb the care the system didn't provide → on no balance sheet → no statute lists them.
- **Bridge:** "Accountability finally shows up, and it had to be forced from outside."

### Q1.8 · Auditors and regulators (deep — the climax)
- **Landing:** accountability was external and reluctant; transparency and a transparency problem in one move.
- **Beats:** Obermeyer's team got rare access to inputs, process, and outputs of a live proprietary model → designers handed over access, but only once regulators and legislators forced it, and they requested anonymity to do it → New York Department of Financial Services and Department of Health told operators to stop or justify → this one case has all of it: validity, fairness, human oversight, transparency.
- **Pacing:** this is the longest beat; it is the payoff. Land the "forced from outside" point.
- **Bridge:** "Up the chain sits the parent."

### Q1.9 · UnitedHealth Group (fast)
- **Landing:** owned the tool, ran it for years, fixed it only once public.
- **Beats:** owned it through Optum → the Department of Financial Services letter went to the CEO → confirmed the bias, co-developed the fix, after it was already public.
- **Bridge:** "And this is not one bad apple."

### Q1.10 · Other systems and the broader population (fast)
- **Landing:** the architecture is everywhere; Obermeyer is just the one we saw inside.
- **Beats:** ~200M Americans under tools in this family → industry-wide adoption, no industry-wide audit.
- **Bridge:** "Map all of it and you don't get a handful of stakeholders."

### Q1.11 · The full landscape + Q1 close
- **Landing:** 20+ stakeholders, five layers, one through-line.
- **Beats:** from the data scientists who set the label to the families who absorb the cost to the regulators who came late → the through-line: a reasonable-sounding target, measured on the wrong output, harm pushed to the people who could see it least.
- **Bridge into Q5:** "So what do I take from this into my own work."

---

## Q5 CAREER LEARNING (6 slides) — the 20%, but also where Presentation is won or lost

> This is your reflection in your own name; voice retention matters doubly. Keep it structural and operational, not a values speech. Bookend back to the Nova Scotia opening at the close.

### Q5 Beat 1 · Governance: built in, not bolted on
- **Landing:** governance is a stack, and it has to be designed in.
- **Beats:** Belenguer 2022, clinical-trial discipline for AI, test before release → EU AI Act, the legal layer, high-risk systems carry real obligations → NIST AI Risk Management Framework, the operational layer, govern/map/measure/manage → underneath: profit, society, model are three pillars in tension, feasible region is where all three hold.
- **Bridge:** "Obermeyer is that whole argument in miniature."

### Q5 Beat 2 · Obermeyer is the microcosm
- **Landing:** same failure mode, much bigger stakes ahead.
- **Beats:** one algorithm, one sector, 2019, principles intact, measurement missing → now scale it to general-purpose AI across every sector → even the pushed-out timelines didn't close the deployment-accountability gap.
- **Bridge:** "And the reason it keeps happening is the toolkit is used in the wrong order."

### Q5 Beat 3 · The toolkit is wrong-ordered
- **Landing:** most deployments stop at step one.
- **Beats:** right order is principles → process governance → model measurement → most stop at principles on paper → you can see it right now: healthcare, hiring, public benefits, financial services → principles without measurement underneath.
- **Bridge:** "And right now the gap is open on both sides at once."

### Q5 Beat 4 · The deployment-accountability gap
- **Landing:** standard without a clock on one side, clock without a standard on the other.
- **Beats:** EU has the standard but delayed it (Digital Omnibus, May 2026) → US has momentum but pulled the AI hiring guidance and is moving against state AI laws → first advanced AI-audit certification launched 2025, gated behind the existing establishment → reassuring for rigor, real question about whose interests it serves; both true.
- **Bridge:** "So where does that leave us."

### Q5 Beat 5 · Build it in, measure the output
- **Landing:** if the market won't export accountability, design it in.
- **Beats:** Brussels effect (the EU exporting standards through market gravity, per Bradford) stays limited for AI → so accountability has to be built in by the people who build, deploy, and audit → output measurable, toolkit governable → a limited Brussels effect makes that the *only* argument left, not a weaker one.
- **Bridge:** "Let me end where I started."

### Q5 Close · Personal carry-forward (bookend)
- **Landing:** the access gap and the measurement gap are the same gap from two ends; build governance in.
- **Beats:** the patient choosing between an MRI in Truro and a paycheck is the same person the algorithm under-counted → we're compromised, not doomed → the difference is built-in vs bolted-on → at Black Point Analytics, build governance in at design time, before a regulator forces it and before harm lands → profit is one of three pillars; the work serves the people downstream, not the story where one bottom line decides whose harm is acceptable.
- **Pacing:** slow, land it, stop. Do not trail off. "Thank you."

---

## Pre-record checklist (do these before you hit record)

1. **Visual check (only thing I couldn't verify):** open the deck, step through Q1.1 and the Q5 close, confirm nothing clips. The sandbox can't render reveal.js. If Q1.1 is still tight, the table is the proof; the heat map can shrink.
2. **Retype, don't recite:** the script scaffolding doc is yours to edit; this handoff is beats. Do one read-through out loud talking *to* the beats, not reading them.
3. **Two landmines:** "named the next day by reporting" for Optum; never call the 11 components "principles."
4. **Cite once, early:** the full author string on slide 1.2.
5. **Coined term once:** "proxy laundering" on the frame slide only.
6. **Bookend:** open and close on the Nova Scotia access scenario.

---

## State of the deliverable (for the next session, if any)

- **Artifact:** `MBAN5530_IA4_GTSv9.html`, Outstanding-band on all three criteria, contract series OC-01→OC-07 complete.
- **Supporting docs in outputs:** OC-01 substrate, OC-02 register, OC-03–05, OC-06/07, ethical-principles reference, script scaffolding, this handoff.
- **Open items, all delivery-side:** the visual check (item 1 above); G's own edit pass on the script; the recording itself.
- **Optional, not built:** the dedicated 8-principle audit slide (Option B from the principles reference). Say the word if you want it before recording.

*G handles the recording. This is the last analyst deliverable unless G requests the audit slide or a post-edit script pass.*
