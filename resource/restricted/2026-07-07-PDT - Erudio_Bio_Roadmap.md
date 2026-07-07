---
date: Tue Jul  7 03:57:38 PDT 2026
last_modified_at: Tue Jul  7 12:43:02 PDT 2026
layout: single
title: "Erudio Bio — Technical, Business & Strategic Roadmap"
permalink: /roadmap/2026/v1
categories:
 - roadmap
tags:
 - roadmap
 - AI strategy
toc: true
toc_label: "&nbsp;Table of Contents"
toc_icon: "fa-solid fa-music"
toc_sticky: true
author_profile: true
---

**Centered on bioTCAD · authored from the CTO / AI vantage**

Prepared by Sunghee Yun (Co-Founder & CTO) · draft for internal alignment

# Framing — one company, two engines, one thesis

Erudio Bio is a single company with **two revenue engines and one underlying thesis.**

- **VSA (Versatile Smart Assay)** — a dynamic-force-spectroscopy (DFS) measurement platform. *Today* it is a diagnostics product (multi-cancer biomarker screening); *structurally* it is a per-molecule, kinetics-resolved measurement instrument.
- **bioTCAD** — measurement-anchored physics + AI simulation for molecular design. *Today* a validated proof-of-concept; *structurally* the design engine that consumes measurement and produces optimized molecules.

**The thesis that unifies them:** biology's bottleneck is not compute or model architecture — it is the absence of high-quality, kinetics-resolved, per-molecule measurement to anchor prediction. Generic force fields and public-data-trained ML both drift from reality on the specific molecule in front of you. Erudio closes that gap by **generating the measurement (VSA) and using it to calibrate the simulation (bioTCAD)** — a loop no competitor has vertically integrated.

**Strategic posture:** *diagnostics pays the bills; bioTCAD is the prize.* VSA revenue (Korea, near-term, non-dilutive-friendly) funds and de-risks the runway while bioTCAD matures into the high-multiple asset.

<!--
**Why this roadmap is authored from the AI seat:** Kee owns the biochemistry, MD, and TCAD lineage. My differentiated contribution — and the axis on which bioTCAD becomes a *platform* rather than a *one-molecule result* — is the AI and software layer: generalization beyond D4V2, automation of today's manual calibration, uncertainty quantification, and the compounding data asset. Sections 2 and 5 carry that weight.
-->

# Mandate & the value we deliver

**Overarching mandate:** *Make biology measurable and predictable* — supply the measurement-anchored ground truth that converts AI from a correlational guesser into a reliable engine for molecular design and diagnosis. In one line: **the measurement layer for AI-era biology.**

Value, by customer:

| Customer | What they need | What Erudio delivers |
|---|---|---|
| **Government — DoW / biodefense** | Rapid, onshore, *auditable* medical-countermeasure design against emerging threats | Measurement-anchored, physics-grounded candidate design + validation that black-box generative models can't audit; first-in-kind binding data; a domestic capability |
| **Government — FDA** | Credible, calibrated in-silico evidence to safely compress pre-IND timelines | bioTCAD as a *qualifiable NAM* delivering confidence-bounded predictions of the molecular determinants (binding, selectivity, MABEL inputs) that govern the first human dose |
| **Pharmaceutical companies** | Better lead candidates, faster, with quantified confidence | bioTCAD as a **drug-discovery platform that compresses and de-risks the lead-to-optimization phase** — higher-quality candidates, fewer synthesize-and-assay cycles |
| **Hospitals / screening centers** | Affordable, accurate, convenient early cancer screening | VSA multi-cancer panel at ~⅓ the cost of separate assays, lower false-positive rate (cross-reactivity filtering), single 10 µL sample |

The through-line: to *each* customer we sell the same core capability — **trustworthy per-molecule measurement, and prediction anchored to it** — packaged as a diagnostic (hospitals), a design platform (pharma), regulatory-grade evidence (FDA), or a national capability (DoW).

# How we deliver it — the bioTCAD + VSA platform

## VSA — the measurement engine

Dynamic force spectroscopy measures single-molecule bond rupture, yielding **unbinding force, on/off kinetics, and specificity** from 50–100 interactions per 10 µL sample, with cross-reactivity filtering. Two faces:

- **As product:** the diagnostics revenue engine (Section 3.4).
- **As infrastructure:** a source of *kinetics-resolved, ground-truth binding labels* — exactly the data public databases lack and AI models starve for.

## bioTCAD — the design engine

The Phase I seven-stage pipeline (structure prediction → MD relaxation → CD structural measurement → force-field customization → complex simulation → contact-map analysis → measurement-anchored binding-energy extraction), validated on the Vanderbilt cyclic-peptide set: **≥88% bind/no-bind classification vs 37.5% unmodified MD and 25% for the original method.** The core proven capability: *measurement corrects the force field for the specific molecule*, turning generic MD into a molecule-specific predictor.

## The integrated loop — the moat

```
   generative / AI proposal
            │
            ▼
      bioTCAD simulation  ──►  candidate ranking  ──►  synthesize top-k
            ▲                                                │
            │                                                ▼
   force-field calibration  ◄──  VSA / CD / SPR measurement (ground truth)
            │
            ▼
   first-in-kind labeled dataset  ──►  trains every downstream AI model
```

VSA's DFS output feeds bioTCAD's affinity anchoring (via a Bell–Evans interpretation) **directly** — so the measurement that calibrates the simulation is *made in-house*, not bought from third parties. This is the vertical integration competitors cannot replicate, and (see §5.3) it is also the fix for the Phase I affinity-anchor reliability problem.

## Where the AI lives

bioTCAD is already a multi-layer AI system, not a simulator with AI bolted on. Mapped to the five-zone landscape:

- **Zone 1 — AI already latent:** DL structure prediction (AlphaFold3 / RoseTTAFold3), ML force-field potentials (ANI/NequIP/MACE) inside the calibration loop, simulation-based inference for Bayesian calibration, the contact-map classifier, the **labeled-data factory**, and the ranking engine.
- **Zone 2 — AI feeding in:** generative proposal (RFdiffusion / ProteinMPNN), inverse-problem net for CD interpretation, active-learning oracle, GNN force-field selector.
- **Zone 3 — AI derived out:** per-molecule foundation model, affinity surrogate, parameter recommender, thermodynamic-decomposition model.

The strategic asymmetry: **every calibration run produces proprietary, measurement-anchored training data** (Zone 1 data factory → Zone 3 models). The engine and the data asset compound each other. That is the durable advantage, and it is fundamentally an AI advantage.

# Customer-sector strategies

## Pharma — bioTCAD as a lead-optimization platform

**Positioning:** a drug-discovery platform that compresses and de-risks the **lead-to-optimization** phase — reducing the time to a high-quality development candidate and improving the quality (affinity, selectivity, developability) of the molecules that advance.

**Why now:** AI-first discovery (Recursion, Owkin, Tempus) and pharma R&D both hit the same wall — models trained on noisy, heterogeneous public data can't reliably rank true binders vs look-alikes, and can't extrapolate to novel chemotypes (the OOD problem, §5.1). bioTCAD's measurement-anchored physics is the missing high-fidelity filter.

**Engagement ladder (low → high commitment):**
1. **Data licensing** — proprietary measurement-anchored binding datasets ($200–500K / project).
2. **SaaS** — bioTCAD cloud analysis / candidate ranking ($50–200K / year).
3. **Co-development** — milestone-based partnerships on specific targets/series.

**TAM anchor:** AI drug discovery ~$5B (2024), growing 25–35%/yr; the measurement-anchored *training-data* layer beneath it is a distinct, defensible slice.

## FDA — credibility and standard-setting

**Play:** convert the RFI comment letter into a durable regulatory position — get measurement-anchored, model-based candidate analysis recognized as a **qualifiable NAM** under existing V&V-40 / context-of-use / fit-for-purpose machinery, and use pre-IND engagement as the venue.

**Note:** the uncertainty-quantification argument is the regulatory linchpin — context-of-use, model-risk, and fit-for-purpose validation *all* depend on the model knowing when it is reliable, which is exactly what measurement-anchored (via SBI, §5.4) confidence bounds provide and pure ML lacks OOD. This is what makes bioTCAD *admissible*, not just accurate.

**Prize:** if Erudio helps define the data-quality and calibration standards, competitors must meet Erudio-shaped standards — a regulatory moat.

## DoW / biodefense — non-dilutive capability

**Play:** position bioTCAD + VSA as a domestic, auditable medical-countermeasure design-and-validation capability, adjacent to LLNL's GUIDE (hybrid physics + ML for biodefense) and the JPEO-CBRND / BARDA / DTRA / ARPA-H funding vectors.

**Differentiators for this audience:**
- **Auditability** — physics-grounded, measurement-anchored predictions are inspectable in a way black-box generative models are not (a dual-use / trust advantage).
- **Data-provider angle** — GUIDE openly states the binding data it needs doesn't exist; VSA generates exactly that. Erudio can be a data/validation partner, not only a bidder.
- **Onshore** — aligns with the national-competitiveness rationale driving current policy.

**Funding character:** non-dilutive, milestone-based — extends runway without dilution while diagnostics revenue scales.

## Hospitals / screening centers — the VSA diagnostics engine (Korea-first)

**Model (B2B2C):** hospitals and health-screening centers adopt the VSA benchtop reader and run the validated **6-marker multi-cancer panel** (AFP, CA19-9, CA125, CEA, FT4, TSH) on patient serum.

**Revenue (three streams):**
1. **Hardware** — VSA reader systems (70%+ gross margin).
2. **Consumables** — microfluidic chips + reagent kits (recurring).
3. **Per-sample fee** — ₩150,000–300,000 / test.

**Value to the hospital:** ~⅓ the cost of six separate assays, fewer false positives (cross-reactivity filtering), single-sample convenience — into a Korean market of 15M+ annual health screenings.

**Anchor partners:** SNU Bundang Hospital (IRB in progress; 15M+ patient-data access on approval), Keimyung Dongsan (multi-site validation), Shanghai General (JDA). Regulatory via MFDS with C&R Research (device 1st-grade notification + separate cartridge approval).

**Strategic role:** near-term cash flow + a real-world data stream that (longer-term) feeds the same measurement-anchored data asset.

# Roadmap & milestones

Quarterly through 2027, then annual. Four workstreams: **bioTCAD/AI**, **VSA diagnostics**, **Regulatory & Government**, **Corporate/Funding**. (Dates are targets; ✦ marks the AI-differentiated deliverables.)

## Q3 2026 (current)
- **bioTCAD/AI:** Close Phase I; scope Phase II. Begin CMAP fitting for D1V1 (the peptide LJ alone couldn't solve). Stand up the calibration-library data pipeline that every Zone-3 model depends on. ✦ Prototype the inverse-CD net to remove the manual CD↔DSSP comparison.
- **VSA:** MFDS 품목질의 → 품목허가 preparation with C&R Research; advance SNU Bundang IRB.
- **Regulatory/Gov:** File the RFI comment letter (docket window). Open GUIDE / JPEO-CBRND / BARDA and Fisher/OPHPR pilot conversations.
- **Corporate:** Run the lead-investor / Gates $5M-follow-on process (A2G and others).

## Q4 2026
- **bioTCAD/AI:** ✦ Solve D1V1 via residue-restricted CMAP → *two* validated per-molecule calibrations, not one. First **prospective** design attempt (design a novel candidate, not just classify existing ones). ✦ Affinity-surrogate v0 and parameter-recommender data schema.
- **VSA:** Submit MFDS filing.
- **Regulatory/Gov:** Pre-IND / NAM-qualification pathway engagement; biodefense proposal(s) in progress.
- **Corporate:** Close lead investor / Series A first tranche; trigger Gates follow-on.

## Q1 2027
- **bioTCAD/AI:** ✦ **Parameter-Recommender Network v1** — learn the sequence→calibration-parameter prior so new molecules initialize from learned priors instead of generic defaults (the core generalization lever, §5.1). Extend validated calibration to ~5–10 peptide systems. ✦ Integrate **VSA-DFS as the affinity anchor**, replacing third-party SPR (fixes the Phase I anchor-reliability gap, §5.3).
- **Pharma:** First paid data-licensing pilot.
- **VSA:** MFDS review; first hospital pilot site prep.

## Q2 2027
- **bioTCAD/AI:** ✦ Active-learning oracle in the loop (Bayesian selection of the next molecule to measure) → fewer wet-lab cycles per optimized candidate. Scope **small-molecule bioTCAD** (ADMET/solubility anchoring). SaaS alpha.
- **Pharma:** Second pilot; SaaS early-access.
- **VSA:** **MFDS approval (target)**; first commercial screening-center deployment.

## Q3 2027
- **bioTCAD/AI:** ✦ **Antibody/CDR bioTCAD** (SPR/BLI + structural anchoring of CDR loops). ✦ Affinity surrogate enabling million-scale virtual screens; begin fine-tuning a **per-molecule foundation model** on the accumulated calibration corpus.
- **VSA:** Korean commercialization ramp; expand panel menu.
- **Corporate:** Series B narrative + metrics assembled.

## Q4 2027
- **bioTCAD/AI:** ✦ **Closed-loop autonomous prototype** — LLM agent orchestrating bioTCAD + synthesis procurement + VSA measurement (propose → simulate → synthesize if threshold cleared → measure → recalibrate). ✦ **Selectivity-panel bioTCAD** as a regulatory-grade off-target safety product.
- **Regulatory/Gov:** First NAM-qualification milestone / formal FDA interaction on context-of-use.

## 2028
- **bioTCAD/AI:** General platform across **≥2 modalities** (peptide + small-molecule and/or antibody). SaaS GA; multiple pharma partnerships. ✦ Per-molecule foundation model + **universal calibration prior** (compounding ROI on every past run). ✦ Regulatory AI co-pilot (bioTCAD output → submission language) as a standalone offering.
- **VSA:** Japan / SE-Asia expansion; China via Shanghai General.
- **Corporate:** Series B.

## 2029
- **bioTCAD/AI:** Autonomous design foundry productized; causal/counterfactual layer for mechanistic design; a named biodefense countermeasure program in execution.
- **VSA:** Broadened diagnostic menu (companion Dx, infectious disease); regional scale.

## 2030
- Measurement-anchored foundation models positioned as an industry reference; bioTCAD established as the calibrated-evidence layer beneath AI drug discovery; diagnostics a durable cash engine funding the platform.

# bioTCAD technical roadmap — the AI deep-dive

This is where the platform is won or lost. Phase I proved the *mechanism* on one molecule (D4V2). The job now is to turn a bespoke, manual, single-molecule result into an **automated, general, self-improving platform.** Five problems, in priority order.

## From D4V2-specific to general — the generalization problem

**Where we are:** the customized force field is anchored to *one* peptide. D4V2 succeeded; D1V1 required a different strategy (CMAP). Each new molecule currently implies a bespoke calibration, and some fail. This is, in ML terms, the same **out-of-distribution** issue at the heart of the FDA argument — a calibration fit to D4V2 is by construction anchored to D4V2, and the open question is whether the *approach* transfers.

**The path (learned priors, not per-molecule from scratch):**
1. **Parameter Recommender Network** — train a sequence/topology → calibration-parameter model on the growing calibration library (LJ ε-scaling, the *a*/*b* correction coefficients). New molecules **initialize from a learned prior** instead of generic defaults. This is the direct analog of TCAD process-parameter libraries transferred across device geometries — Kee's world, formalized in ML.
2. **Universal Calibration Prior** — the asymptote of (1): a model that maps molecular topology → measurement-anchored parameters, so calibration converges with *fewer* experiments as the library grows. Every past run appreciates in value — a data asset with compounding ROID.
3. **GNN force-field selector** — learn CHARMM-vs-AMBER (and beyond) per scaffold, removing a human judgment call and an iteration cycle.
4. **Cross-molecule transfer learning** — treat each calibration as a point in parameter space; learn the manifold; interpolate/extrapolate to novel scaffolds with quantified confidence.

**Success metric:** calibration cost per new molecule (wet-lab cycles + compute + human hours) falling toward zero as the library grows; validated accuracy holding across a *held-out* set of molecules never calibrated before (the real OOD test).

## Automating the manual pipeline

**Where we are:** Phase I was heavily manual — hand-iterated LJ fitting, manual CD↔DSSP comparison, human force-field selection, manual measurement-method choice, bespoke analysis scripts. This is the single biggest throughput ceiling.

**The automation stack (each replaces a manual step):**
- **Force-field fitting → Bayesian optimization / active learning.** Replace hand-tuning of LJ (and CMAP) with an optimizer that proposes the next parameter set to try, and — via the active-learning oracle — the next *molecule* to measure. Turns a manual art into a self-directing search.
- **CD interpretation → inverse-problem neural net.** Map raw CD spectra → secondary-structure fractions with calibrated uncertainty, eliminating the manual comparison and feeding the loop faster.
- **Force-field selection → GNN selector** (as §5.1).
- **Screening → affinity surrogate.** A model predicting Kd from contact maps in milliseconds (vs hours of MD) lets us screen libraries orders of magnitude larger than full simulation allows — full MD reserved for the shortlist.
- **Orchestration → agentic pipeline.** An LLM agent wires the stages together (the Zone-5 autonomous foundry), moving from "a scientist runs each stage" to "the system runs the loop, a scientist supervises."

**Success metric:** human-hours per calibrated molecule; end-to-end wall-clock from candidate proposal to calibrated prediction.

## Fixing the affinity anchor — and turning a weakness into the moat

**Where we are:** Phase I's affinity side is the soft spot — third-party SPR disagreed with published BLI by 2–3 orders of magnitude, and the MM/GBSA scaling (Eq. 1) was fit from *two* points with zero validation. Ironically, this is the very SPR-unreliability we argue against in the FDA letter.

**The path:**
1. **Replace the anchor with VSA-DFS.** Bring affinity measurement in-house via VSA's single-molecule force spectroscopy (Bell–Evans), removing dependence on the third-party platform we critique and giving a *kinetics-resolved* anchor richer than an equilibrium Kd. This closes the loop and resolves the letter-vs-report tension in one move.
2. **Validate the scaling model properly.** Grow the (calibrated ΔH/ΔS, measured Kd) set far beyond two points; replace the arbitrary single-condition anchor with a principled multi-measurement fit; consider **simulation-based inference** so the correction carries calibrated uncertainty instead of a point estimate.
3. **Thermodynamic-decomposition model.** Learn enthalpy- vs entropy-dominated signatures across the library → predict which correction strategy a new scaffold needs (encoding med-chem intuition).

**Success metric:** anchor reproducibility (in-house VSA vs external); scaling-model accuracy on held-out molecules; uncertainty calibration.

## Uncertainty quantification — the regulatory and scientific backbone

**Why it's load-bearing:** UQ is simultaneously (a) the FDA admissibility hook (context-of-use / model-risk / fit-for-purpose all assume the model knows when it's reliable), (b) the fuel for active learning (measure where uncertainty is highest), and (c) honest science (know when we're extrapolating).

**The path:** promote bioTCAD from point-estimate calibration to a **Bayesian framework via simulation-based inference** (already named in the provisional). Distinguish epistemic vs aleatoric uncertainty; produce confidence bounds that *widen* as molecules move away from measured anchors. Physics-grounded bounds, not statistical resemblance to a training set — the property pure ML lacks OOD.

**Success metric:** calibration curves (predicted confidence vs realized accuracy); demonstrable widening of bounds on OOD inputs.

## The arc — classification → design → autonomy

The maturity ladder that ties the above together:

1. **Retrospective classification** *(Phase I, done)* — classify 8 known peptides at ≥88%.
2. **Prospective design** *(2026–27)* — design *new* candidates and prospectively validate them (the first true test of the platform).
3. **General platform** *(2027–28)* — learned priors + automation make calibration cheap across molecule classes; SaaS + data licensing productize it.
4. **Autonomous foundry** *(2028–29)* — the closed-loop agent (bioTCAD + synthesis + VSA) runs discovery with human supervision; the per-molecule foundation model and universal prior make each cycle cheaper than the last.

Modality scope expands along the ladder: **peptides → small molecules (ADMET anchoring) → antibodies/nanobodies (CDR loops) → nucleic acids**, plus the selectivity-panel and proteolytic-stability extensions — each an addressable market covered by the existing provisional claims.

# Key risks & open questions

- **Generalization risk (the central technical bet).** Does per-molecule anchoring transfer via learned priors, or does every molecule need bespoke work? §5.1 is the make-or-break; the held-out-molecule test is the honest arbiter.
- **Affinity-anchor validity.** The VSA-DFS anchor (§5.3) must be demonstrably more reproducible than the SPR it replaces, or the scaling model stays fragile.
- **Data-flywheel throughput.** The Zone-3 models need volume; if calibration stays slow/manual (§5.2), the data asset accumulates too slowly to compound.
- **Regulatory timing.** NAM qualification and MFDS approval are external-dependency milestones; treat their dates as targets, not commitments.
- **Focus vs breadth.** The five-zone landscape is deliberately expansive; execution requires sequencing (this roadmap's ordering) rather than pursuing all vectors at once.

# The through-line

Erudio's defensibility is not the simulator and not any single model — it is the **measurement-anchored data loop**: VSA generates ground truth no one else has, bioTCAD turns it into calibrated prediction, and every run enriches a proprietary corpus that makes the next prediction better and cheaper. Diagnostics funds the journey; the FDA and DoW work builds credibility and non-dilutive runway; pharma is where the platform monetizes at scale.

That loop is fundamentally an **AI and software asset**, and where the next two years of value creation will be decided.
