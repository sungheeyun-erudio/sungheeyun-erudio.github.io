---
date: Tue Jun 30 13:46:44 PDT 2026
last_modified_at: Tue Jun 30 13:51:55 PDT 2026
layout: single
title: "AI Strategy Review — bioTCAD RFI Proposal"
permalink: /ai-strategy/fda-rfi
categories:
 - AI strategy
tags:
 - AI
 - strategy
 - FDA
 - RFI
toc: true
toc_label: "&nbsp;Table of Contents"
toc_icon: "fa-solid fa-music"
toc_sticky: true
author_profile: true
---

**Erudio Bio, Inc. — Confidential Internal Document**

**Re:** Erudio Bio RFI response to FDA Operation TrailBlazer / Expedited IND Pilot (Docket FDA-2026-N-4699)

**Purpose:** Identify where the whitepaper's treatment of AI is missing, underdeveloped, or strategically incomplete — at the paper's own technical level (*microscopic*) and in the broader sense of Erudio's AI strategy (*macroscopic*).

**Audience tags:** **[Cook]** = computational-biology reviewer (technical scrutiny) · **[Zeta]** = chief of staff / attorney (regulatory defensibility) · **[Kyle]** = acting commissioner / investor-level (headline & strategy)

# Part 1 — Review Memo

## The core reframe (lead with this)

The paper's current Section 3 makes a **contingent** argument: *the high-quality binding data isn't there.* True, but fixable in principle — generate enough data and the objection dissolves. (LLNL's GUIDE is explicitly trying to fix exactly this.)

The stronger, missing argument is **structural**: even with abundant data, machine learning cannot reliably **extrapolate** beyond the region it was trained on — and a novel drug is, *by definition*, out-of-distribution. "Novel" ≡ "OOD." You cannot train your way out of needing to predict the unprecedented, because the molecule you most want to find — a first-in-class candidate — is precisely the one least represented in any training set.

This elevates the critique from "a gap that more data closes" to "a limit inherent to the method." It is the single most important AI addition to the paper. **[Cook]**

**The vocabulary that makes it rigorous:**
- **Interpolation vs. extrapolation** / **in-distribution (ID) vs. out-of-distribution (OOD) generalization**
- **Distribution / covariate shift** — the test molecules don't come from the training distribution
- **Curse of dimensionality** — drug-like chemical space is estimated at ~10⁶⁰ molecules; any dataset covers a vanishingly sparse slice, so almost everything novel is OOD
- **Activity cliffs** — small structural change → large activity change, which breaks ML's core smoothness assumption ("similar inputs → similar outputs"). This is the concrete, named failure mode med-chem reviewers recognize
- **Overconfidence under shift** — ML is typically *most confident exactly when it is extrapolating*; it does not know when it has left the region it understands

**Why physics + measurement-anchoring wins here (the inductive-bias argument):** first-principles physics encodes *mechanism*, and the governing laws (forces, energies) are **invariant** — they do not change when you step outside the training distribution. So physics extrapolates where ML cannot, and per-molecule measurement re-anchors the approximate force field to reality in the new region. The seed already exists in Section 1 ("mechanistic interpretability and extrapolation beyond existing datasets") but is undeveloped and never framed in ML terms. The fix fuses Section 1's throwaway line into Section 3 as its second leg.

## Microscopic gaps — candidates for *this* paper

### M1. Out-of-distribution / extrapolation **[Cook]**
The flagship addition above. Gives Section 3 a structural argument alongside its data-scarcity argument. Drop-in text in Part 2.

### M2. Uncertainty quantification (UQ) **[Cook] [Zeta]**
The paper says "stated uncertainty" once (Section 5) and drops it. For a NAM this is the whole regulatory game: "context of use," "model risk," and "fit-for-purpose validation" are already in the Recommendation, and all three *depend on the model knowing when it is reliable.* ML is badly calibrated OOD; measurement-anchored physics can supply **physically grounded** confidence bounds. This is simultaneously an AI component (epistemic vs. aleatoric uncertainty; calibration; conformal methods) and the regulatory hook Zeta cares about. Currently the most underdeveloped high-value item.

### M3. Specify *how* AI guides the physics **[Cook]**
"AI obtains the initial structure and guides selection of the simulation parameters" is hand-wavy — and ironically the paper's treatment of *its own AI layer* is its thinnest part. Cook will immediately ask *which* AI, doing *which* job, *where* in the pipeline:
- structure proposal (AlphaFold3 / Boltz / ESM-class)?
- ML interatomic potentials accelerating the MD itself (see M5)?
- ML-driven enhanced sampling (which conformations to explore)?
- ML surrogate models for free-energy estimation?

Naming the specific roles is the most direct answer to Kee's literal question ("are we missing AI components?").

### M4. Name the flywheel correctly: **active learning** **[Cook]**
The "AI flywheel" is real but unnamed. The rigorous version is **active learning / optimal experimental design** — use the model's *uncertainty* (M2) to choose which molecules to measure next, maximizing information gained per expensive experiment. This makes "AI-enabling" concrete rather than aspirational, and it links the flywheel to both UQ and the measurement-anchoring. (Adjacent terms: Bayesian optimization, acquisition functions, information gain.)

### M5. ML-augmented force fields (MLIPs) **[Cook]**
Modern MD increasingly uses **ML interatomic potentials** (neural-network potentials approaching quantum accuracy at MD speed). Mentioning this shows AI permeates the *physics* layer, not only the search layer — a sophistication signal for Cook, and a hedge against the implicit framing that "AI = search, physics = compute, and never the twain." Positions bioTCAD's physics as itself modern and AI-accelerated.

## Macroscopic — broader Erudio AI strategy (mostly *not* for this paper)

### X1. The umbrella thesis: Erudio is the **"measurement layer for AI"** **[Kyle]**
Every micro point ladders up to this. Erudio is not competing with AI; it is the ground-truth infrastructure the entire AI-for-bio stack is starving for. The bioTCAD paper is one instance of the thesis. State it once, high, for the Kyle/investor altitude — keep it out of the technical body.

### X2. Data as the moat **[Kyle / investors]**
In an era where models commoditize, the durable asset is the proprietary, **first-in-kind**, measurement-anchored dataset the flywheel produces. GUIDE publicly confirms this data does not exist. Investor-facing (ties to the A2G framing); not FDA-facing.

### X3. VSA + bioTCAD as one closed loop **[strategy]**
Where the two whitepapers connect: **VSA is the measurement engine** that generates the anchoring data at scale → anchors bioTCAD physics → produces first-in-kind datasets → trains better ML → proposes better candidates → VSA measures again. The *vertical integration of measurement + simulation* **is** the Erudio AI strategy. Only fragments belong in the RFI paper, but the whole loop is the real story.

### X4. Regulatory standard-setting as a moat **[Zeta] [Kyle]**
The Recommendation already proposes FDA adopt input-data-quality and model-calibration standards. If Erudio helps *define* them, competitors must meet Erudio-shaped standards. First-mover NAM qualification is strategic positioning, not just a technical ask — frame it that way for Zeta.

### X5. Auditability / AI-biosecurity differentiator **[national-security audience]**
Measurement-anchored, physics-grounded models are inherently more **auditable and controllable** than black-box generative models — a trust differentiator that resonates with the biodefense world (GUIDE / LLNL's Center for Predictive Bioresilience) and bridges to the *other* (VSA / OPHPR) whitepaper's national-security framing. Forward-looking; relevant the moment a government reviewer worries about dual-use generative AI.

## Audience cheat-sheet — who cares about what

| Item | Cook (technical) | Zeta (regulatory) | Kyle (strategic) |
|---|:---:|:---:|:---:|
| M1 OOD / extrapolation | ●●● | ● | ● |
| M2 Uncertainty quantification | ●● | ●●● | — |
| M3 How AI guides physics | ●●● | — | — |
| M4 Active learning (flywheel) | ●● | ● | ● |
| M5 ML force fields (MLIPs) | ●● | — | — |
| X1 "Measurement layer for AI" | ● | — | ●●● |
| X2 Data moat | — | — | ●●● |
| X3 VSA + bioTCAD loop | ● | ● | ●●● |
| X4 Standard-setting moat | — | ●●● | ●● |
| X5 Auditability / biosecurity | ● | ●● | ●● |

**Net:** M1 + M3 are the must-adds for the reviewer who will read hardest (Cook). M2 + X4 are the regulatory spine (Zeta). X1–X3 are the altitude story (Kyle) — keep them in a single framing paragraph or a cover note, not the technical body.

# Part 2 — Suggested Drop-in Text

> Draft prose matched to the whitepaper's voice. Slot in or adapt as needed. Bracketed notes are guidance, not for inclusion.

## 2A. Expanded Section 3 — add the structural (OOD) leg

*Insert after the existing "The data is not there" paragraph, as a second numbered limitation:*

**The deeper limit is structural, not just a matter of data volume.** Machine learning is, at its core, an interpolation engine: it performs well *within* the region of chemical and sequence space its training data covers, and degrades — often sharply, and without warning — when asked to predict *outside* it. This is the out-of-distribution (OOD) generalization problem, and it is not curable by collecting more data, because the molecules of greatest interest are precisely those least represented in any dataset. A genuinely novel, first-in-class candidate is, by construction, out-of-distribution. Drug-like chemical space is estimated at roughly 10⁶⁰ molecules; any conceivable training set occupies a vanishingly small fraction of it, so the frontier where new medicines are found is almost always a region where the model has never seen an example. The failure is compounded by *activity cliffs* — small structural changes that produce large, discontinuous shifts in binding or activity — which violate the smoothness assumption ("similar molecules behave similarly") that statistical learning depends on. And critically, ML models are typically *most confident exactly when they are extrapolating*: they do not signal that they have left the region they understand.

**Physics-based, measurement-anchored simulation does not share this limit.** The governing laws of molecular interaction — the forces and energies that determine binding — are invariant; they do not change when a candidate falls outside any prior dataset. A first-principles simulator therefore extrapolates into unexplored chemical space on mechanism rather than on resemblance to past examples, and per-molecule measurement-anchoring re-calibrates the model to physical reality in precisely the novel region where pure ML is blind. This is why bioTCAD's hybrid is not merely a convenience but a structural necessity: AI proposes and prioritizes within known space; anchored physics carries the prediction into the unknown.

## 2B. New Section 4 subsection — Uncertainty quantification

*Add as a labeled capability under Section 4, "bioTCAD: Hybrid Physics + AI."*

**Calibrated confidence, not just point predictions.** A New Approach Methodology is only usable to a regulator if it reports *when it can be trusted.* bioTCAD distinguishes two sources of uncertainty: irreducible experimental/biological variability (aleatoric) and model-knowledge limits (epistemic), and it reports each prediction with a calibrated confidence bound rather than a bare number. Because the physics layer is anchored to per-molecule measurement, those bounds are physically grounded rather than inferred from statistical resemblance to a training set — and they widen, appropriately, as a candidate moves into regions where measurement anchoring is sparse. This directly supports the fit-for-purpose, context-of-use, and model-risk framework the Recommendation calls for: a determination accompanied by a credible, calibrated uncertainty is a determination a reviewer can act on.

## 2C. Sharpened Section 4 — specify the AI layer

*Replace the existing "AI/ML layer" paragraph with:*

**AI/ML layer.** AI is used where it is genuinely strongest and in clearly delineated roles: (i) *structure proposal* — generating the initial three-dimensional structure of the candidate and its target complex from sequence or chemistry; (ii) *search and prioritization* — exploring chemical or sequence space and triaging which candidates merit full physics treatment; and (iii) *parameter and sampling guidance* — informing which conformational states and simulation parameters the physics layer should focus computational effort on. Where appropriate, machine-learned interatomic potentials further accelerate the molecular-dynamics layer itself, bringing near-first-principles accuracy at tractable cost. In every case AI narrows and accelerates; it does not render the final binding determination — that is the role of the measurement-anchored physics layer.

## 2D. Recast the flywheel as active learning

*Replace the "AI flywheel" paragraph with:*

**AI flywheel — active learning.** Because bioTCAD produces physics-grounded, measurement-anchored property data where high-quality data did not previously exist, it strengthens machine learning rather than competing with it. The platform closes the loop through active learning: the model's own calibrated uncertainty identifies which molecules, if measured next, would most reduce that uncertainty — so each expensive experiment is chosen to maximize information gained rather than run at random. The result is a compounding asset — first-in-kind datasets that improve every downstream model and grow more valuable as the platform runs. bioTCAD is thus AI-enabled and AI-enabling.

## 2E. Fix the broken closing sentence (Section 3)

*The current sentence — "The way out is a method that does both jobs at once and augment with a dash of reality (measurements)." — is grammatically broken and too casual for an FDA submission. Replace with:*

**The way out is a single method that performs both functions — AI-driven search and mechanistic physics — and calibrates the physics to experimental measurement so that its predictions are anchored to reality rather than to approximation.**

## 2F. Optional cover-note framing (macro thesis, for the transmittal — *not* the paper body)

*One paragraph for the email or cover note that carries the paper, pitched at Kyle's altitude:*

**The broader frame.** Erudio's contribution to Operation TrailBlazer is best understood as supplying the *measurement layer* the AI era of drug development lacks. Artificial intelligence has advanced faster than the supply of high-quality, physically grounded experimental data needed to make it reliable for regulatory decisions — a gap federal programs such as LLNL's GUIDE now explicitly aim to fill. bioTCAD, paired with Erudio's measurement platform, generates that data as a by-product of its own operation, turning the bottleneck into a compounding national asset: better measurements anchor better physics, which produces the first-in-kind datasets that make AI itself more trustworthy. The pilot is an opportunity not only to accelerate individual INDs but to establish the data-quality and model-calibration standards on which credible in-silico evidence will rest.

## One open technical question to resolve internally

For M3/M5, the drop-in text states bioTCAD *can* use ML interatomic potentials and specific AI roles. Confirm with the engine's actual implementation before submission — claim only what is true today, and mark the rest as roadmap (consistent with the paper's honest-maturity posture). Over-claiming the AI layer to a reviewer who knows the field (Cook) would cost more credibility than the addition gains.
