---
date: Sat May 30 22:56:26 KST 2026
last_modified_at: Sat May 30 23:42:43 KST 2026
layout: single
title: "30-May-2026 Pitch Deck Review 2"
permalink: /deck-review/30-may-2026
toc: true
toc_label: "&nbsp;Table of Contents"
toc_icon: "fa-solid fa-music"
toc_sticky: true
author_profile: true
---

posted: {{ page.date| date: "%d-%b-%Y" }}
&
updated: {{ page.last_modified_at| date: "%d-%b-%Y" }}
{: .notice--primary}

<style>
table, tr, td, th {
    font-size: inherit !important;
    font-family: inherit !important;
}
</style>

# Erudio Bio Seed Pitch Deck — v2 Review

**Deck:** `Erudio Investor Pitch 2026 05 30.pdf` (24 slides, 15.1 MB, dated 2026-05-30)\
**Prior review:** [`output/pitch-review.md`](pitch-review.md) (v1 dated 2026-05-25, 12 slides)\
**Date of this review:** 2026-05-30\

**What changed since v1:** the user expanded the deck from 12 → 24 slides, applying many but not all of the v1 recommendations. New material concentrated in Slides 2–7, 12, 13, 14, 16, 21. Carry-over slides include the Biodefense bullets (Slide 22) and the hero validation chart (Slide 18). The user noted up-front that ask / use-of-funds / milestones are not yet added.

---

## 1. Headline

| Reviewer | v1 grade | v2 grade | Movement |
|---|---|---|---|
| Narrative | C- | **B-** | Real structural arc now exists (problem → vision → tech → biz model → competition → applications → team). Slide 1 still wasted; three-market focus problem unresolved. |
| Numbers | D+ | **C+** | Gates grant + named JDA + $60B TAM + named competitors are real wins. New "1000x", "ADI IP", and "$60B TAM" all need sourcing. Slide 18 hero chart unchanged. |
| Devil's Advocate | REVISIT IN 6 MONTHS | **REVISIT IN ~3 MONTHS** | The deck is now memo-able for a soft-pass. Still not investable today (no ask, no powered benchmark, no commercial hire). |

---

## 2. Where the revisions clearly landed (big wins)

1. **NEW Slide 2 Executive Summary** carries the hook the previous Slide 1 was missing. Gates Foundation $1M grant + named JDA negotiations with SNUH/Keimyung + $60B TAM + bioTCAD framing all show up. *This is the most important single change in the deck.*
2. **NEW Slide 3 ("Why Do We Make Life-Altering Decisions with Incomplete Data?")** — real problem statement with a cited source (Bains/DDW), framing the "cross-reactivity / limited testing / doctor-deduction-bottleneck" pain in plain English.
3. **NEW Slide 16 ("Drug Development is Very Inefficient — Fails 90% and Costs $2.6B")** — quantified pain slide for bioTCAD specifically. Names the Hit → Lead → Preclinical → IND → Clinical funnel. The "in-vitro / in-silico / in-vivo" framing is sharp.
4. **NEW Slide 13 Business Model** — razor/blade + SaaS, 70% margin claim, named revenue components (instrument, chip + flowcell, reagent kit, software). Tells the investor *how Erudio gets paid*, which v1 never did.
5. **NEW Slide 14 Competitive Landscape** — names real competitors (Luminex, Olink, Lino Biotech, ProteinSimple, Depixus, LUMICKS). v1 had none. (Caveats in §4.)
6. **Slide 11 retool** — the cytokine-immunoassay slide now has IL-6 / IL-8 / TNF-α actually shown, a 3-panel "Challenge → Filtering → Corrected Multiplex Readout" story, and the punchline "Cross-reactivity removed. Multiplex performance restored." This is the cleanest narrative arc on the deck. Numbers reviewer specifically called this slide more defensible than the bioTCAD hero chart — you've now earned that.
7. **Slide 21 Drug Development engine diagram** — replaced the v1 box diagram with a real input/processing/output engine schematic. Named outputs: binding prediction, functional simulation, candidate prioritization, experimental guidance.
8. **Slide 22 Biodefense visual upgrade** — ruggedized hardware photo, "DOZENS, HUNDREDS, THOUSANDS!" scalability bar, FIELD HEALTH AGENCY-style insignia, "ONE PLATFORM, ONE SAMPLE" lifecycle bar (Pre-deployment / Deployment / Post-deployment / Core Technology). Visually the strongest slide in the deck. (Bullet text still needs updating — §3.)
9. **Slide 23 Clinical Diagnostic visual upgrade** — hospital workflow, SNUH and Keimyung logos in color, "PREVENTATIVE SCREENING / DIAGNOSTIC WORKUP / LONGITUDINAL MONITORING" core-tech bar.

---

## 3. Carried-over issues that did NOT get fixed (from v1 list)

| Fix from v1 review | Status in v2 |
|---|---|
| #1 Add Ask slide / use of funds / milestones | **Missing** (user-acknowledged) |
| #2 Pick one wedge | **Not done.** Tech Stack (Slide 6) and Applications section (Slides 20–23) still pitch three markets. |
| #3 Rewrite Slide 1 | **Not done.** Slide 1 is still the generic logo + tagline. The hook moved to Slide 2; Slide 1 itself is still a wasted slide. |
| #5 Name Schrödinger et al. in competitive view | **Partial.** Slide 14 names *assay* competitors. No competitive view for *bioTCAD* (Schrödinger FEP+, Iambic, Isomorphic, Recursion, Insilico). |
| #6 Replace Slide 7/18 hero chart with powered benchmark | **Not done.** Slide 18 is unchanged. Same n=8, same unnamed comparator, same anchor-in-train-set issue. |
| #8 Anchor IP claim with USPTO numbers | **Not done.** Slide 9 still "21 issued patents" with no table. Made *worse* by new ADI claim — see §4.1. |
| #9 Label Synopsys/Samsung/SK Hynix logos | **Not done.** Slide 19 still has them unlabeled at the bottom. Same logos now also reappear on Slide 24 (Team) without labels. |
| #11 Soften absolute language | **Not done.** "Error-free multiplexing" still on Slide 9. "Requirement for every launch" still on Slide 17. "20% of world's economy" appears on **two** slides (5 and 23) — propagation, not retraction. |
| #12 Commercial hire on team | **Not done.** Team unchanged. |
| #13 Disclose Carterra conflict | **Not done.** |
| **Carry-over** | Slide 22 Biodefense bullets still the old "GWOT to Great Power Competition / Need to defend / Flexible, efficient solution from CBRND to Readiness" — *exactly* the text Option B (in our last exchange) rewrote. Just hasn't been applied yet. |
| **Carry-over typo** | Slide 23 still says "**single sayer networks**" — should be "single-payer networks". |

---

## 4. New issues introduced by the v2 additions

### 4.1 The "Analog Devices" claim on Slide 2 creates IP confusion

> "Part of IP Licensed from ADI"
> "Erudio Bio and Analog can be a key player in a fast-growing high margin business at the cross between biotechnology and AI."

- **Conflicts with the "Stanford spin-out" framing** still on Slide 9. Is the core IP Stanford-licensed, ADI-licensed, or Erudio-assigned?
- **"Erudio Bio and Analog can be a key player"** — grammar issue, and "Analog" alone is not a brand.
- **No date, no scope, no exclusivity.** "Part of IP" is unusually vague.

See §7.3 for a rewrite template.

### 4.2 "1000x more AI-enhanced biodata" on Slide 2 is exactly the kind of number that gets killed
1000x what? Vs. which baseline? Per sample? Per dollar? Per hour? Same problem as v1's "MASSIVELY multiplexed" — unsourced order-of-magnitude on the front. Either source it ("1000x more biodata per microliter of sample vs. Luminex xMAP") or change to a sourced comparison.

### 4.3 Slide 14 Competitive Landscape — right idea, wrong execution

- **The 2×2 "Data amount" × "Data quality" with Erudio alone in the upper-right** is the most clichéd competitive-slide format. Every investor who has seen >50 decks is trained to be skeptical when the pitching company sits alone in the magic quadrant.
- **Competitor set is incomplete.** Listed: Luminex, Olink, Lino Biotech, ProteinSimple, Depixus, LUMICKS — all *multiplex assay / single-molecule biophysics*. This covers VSA but **not bioTCAD**. Need a second slide or split landscape for Schrödinger (FEP+), Iambic, Isomorphic Labs, Recursion, Insilico, Chai.
- **Carterra is missing** from the competitor list — and Tim Germann (Carterra CCO) is on the advisory board. That conflict is now even more conspicuous.

### 4.4 Executive Summary (Slide 2) is overloaded
Six headline claims on one slide. Even sophisticated readers can absorb at most three. Ranking:
1. **Keep**: Gates Foundation $1M grant (third-party validation, real money).
2. **Keep**: bioTCAD framing line ("measurement-calibrated, physics-based drug discovery platform").
3. **Keep**: Hospital JDA in advanced negotiation (real, specific, signed-deal-adjacent).
4. *Demote to IP slide*: the ADI line — and rewrite (§4.1).
5. *Demote or remove*: "1000x" claim (until sourced — §4.2).
6. *Demote to market slide*: $60B TAM (needs methodology — full drug-discovery R&D spend? FEP/MD software market? Addressable-to-bioTCAD SAM? Big difference).

See §7.2 for a rewritten Exec Summary.

### 4.5 Slide 5 Global Urgency now states "20% of world's economy" as a giant 20% callout
You upgraded the visual weight of the figure that the numbers reviewer flagged as overstating reality by ~2× (WHO/OECD: global health spend ~10% of world GDP; ~17% is US). When the number is wrong, making it bigger makes it worse. Defensible replacement: *"Global health spending reached ~$9 trillion in 2023 (≈10% of world GDP, growing ~4% real per year) — WHO GHED."*

### 4.6 Slide 17 bioTCAD intro now has a side-by-side "semiconductor TCAD ↔ pharmaceutical bioTCAD"
Strong visual addition. But the slide *still* keeps "bioTCAD will be as widely used as semiconductor EDA: **a requirement for every launch**" as the punchline. The visual makes the analogy compelling; the bold punchline makes it risky. Soften to "bioTCAD aims to become a standard tool for medicinal-chemistry teams developing novel modalities."

### 4.7 Slide 6 Tech Stack — improved but still pitches three markets
The revised Tech Stack is genuinely better (named applications, cleaner layering). But by naming **Doctor-in-a-box / bioTCAD / Clinical Diagnostics / Biodefense / Drug Development** explicitly, it locks in the three-market sprawl right at the top. If you accept the v1 recommendation to focus the VC deck on drug development, this slide needs a single-wedge version.

### 4.8 Section dividers (Slides 8, 15, 20)
Three nearly-blank section dividers in a 24-slide deck = ~12% of slides are navigational. Fold into the section's first content slide; saves 3 slides.

---

## 5. Prioritized edits for the next pass

Stack-ranked by investor impact, accounting for ask/use-of-funds/milestones being already on the queue.

1. **Fix the ADI / Stanford IP story** (§4.1, copy in §7.3). Until clear, the deck reads as "core IP unowned."
2. **Rewrite Slide 1.** Borrow from the strongest Exec Summary line + Gates grant. (Copy in §7.1.)
3. **Source or replace "20%", "1000x", and "$60B"** (§4.2, §4.5). Three citations. Half a day of work.
4. **Apply the Biodefense Option B bullet rewrite to Slide 22.** (Reproduced in §7.4 for convenience.)
5. **Fix Slide 14 Competitive Landscape** (§4.3) — drop the 2×2 cliché; add bioTCAD competitors; include or differentiate Carterra.
6. **Replace Slide 18 hero chart** with a powered benchmark, even if interim. If you can't get n=30 yet, at least *re-caption* honestly.
7. **Soften absolutes** — "error-free" → "error-suppressed" (Slide 9); "a requirement for every launch" → "a standard tool for novel-modality medchem" (Slide 17).
8. **Label or remove the Synopsys/Samsung/SK Hynix logos** on Slides 19 and 24.
9. **Tighten the Executive Summary** to three headline claims (§4.4, copy in §7.2).
10. **Fix the "single sayer networks" typo** on Slide 23 → "single-payer networks."
11. **Disclose the Carterra relationship** — either on the competitive slide as differentiation, or as a footnote on Tim Germann's advisory listing.
12. **(Acknowledged, coming):** Ask slide + use of funds + 12/18/24-month milestones.

---

## 6. Two structural questions worth answering before the next pass

- **Is this the VC seed deck, the strategic/government capability brief, or both?** v1 recommended a two-deck strategy. v2 is still trying to be both. The single biggest tightening lever is to commit to one.
- **What is the Erudio / ADI / Stanford relationship in one sentence?** This is now ambiguous in a way that v1 was not. The ADI line is potentially a *huge* asset (strategic partner, distribution channel, manufacturing access) — but only if it's stated unambiguously.

---

## 7. Copy-paste-ready text for the next pass

The text below is ready to type directly into PowerPoint. Bullet markers will be added by the slide layout; copy text only.

### 7.1 Slide 1 — Hook (replaces generic logo + tagline)

Pick one of these three. Title remains "Erudio Bio" with the logo; the second line replaces "Data Driven AI for Effective Medicine."

**Option A — concrete, three proof points (recommended)**

> Measurement-calibrated AI for drug discovery and clinical diagnostics.
> Backed by the Bill & Melinda Gates Foundation. Clinical JDA in advanced negotiation with Seoul National University Hospital and Keimyung University Dongsan Hospital.

**Option B — tighter, two proof points**

> Measurement-calibrated AI for drug discovery and clinical diagnostics.
> Gates-Foundation-backed. Clinical JDAs in advanced negotiation in South Korea.

**Option C — bioTCAD-first (if you commit to drug-development-as-wedge for the VC deck)**

> bioTCAD — measurement-calibrated, physics-grounded AI for medicinal chemistry in novel chemical space.
> Backed by a $1M Bill & Melinda Gates Foundation grant.

---

### 7.2 Slide 2 — Tightened Executive Summary (3 claims, not 6)

Replace the current 6-bullet Executive Summary with this. Four labeled sections; only one claim per section.

> **WHAT WE DO**
> Erudio Bio combines a chip-based biophysics platform (VSA) with a hybrid physics-grounded AI engine (bioTCAD) to generate high-fidelity biological data at scale and to predict molecular behavior in novel chemical space — the regime where AI-only models break down.
>
> **THIRD-PARTY VALIDATION**
> $1M Bill & Melinda Gates Foundation grant validating bioTCAD for early-stage drug discovery.
>
> **COMMERCIAL TRACTION**
> Joint Development Agreement in advanced negotiation with Seoul National University Hospital and Keimyung University Dongsan Hospital — preventative screening as the first clinical wedge.
>
> **WHY NOW**
> Drug discovery still fails 90% of candidates and costs ~$2.6B per approval; AI-alone approaches have hit a credibility wall outside familiar chemical space — exactly what bioTCAD's measurement-anchored hybrid approach is designed to close.

Items demoted off this slide:
- **"Part of IP Licensed from ADI"** → moves to a dedicated IP slide (§7.3 copy).
- **"1000x more AI-enhanced biodata"** → removed until sourced.
- **"$60B drug discovery TAM"** → moves to the competitive/market slide with WHO/Evaluate/IQVIA-style methodology.

---

### 7.3 IP-clarification one-liner (for Slide 9, or a new dedicated IP slide)

The right text depends on the *actual* relationship between Erudio, Stanford, and Analog Devices. Pick the variant that matches reality and fill in the brackets. If none matches, write a new sentence with the same structure (who owns, who licenses, what scope, what exclusivity).

**Variant 1 — Stanford-licensed core + ADI as additional licensor**

> **Core IP:** [N] issued patents exclusively licensed from Stanford University covering VSA chip architecture and force-spectroscopy methods (10-year R&D heritage). [M] additional patents licensed from Analog Devices covering [specific tech area, e.g., readout electronics / sensor-array addressing] for bio-sensing field-of-use.

**Variant 2 — Stanford and ADI co-licensors of a single tech bundle**

> **Core IP:** chip-architecture, actuation, and readout patents licensed from Stanford University and Analog Devices, with Erudio Bio as the exclusive bio-applications licensee for [scope, e.g., diagnostics + drug discovery].

**Variant 3 — Erudio-assigned, with prior ADI know-how / inventor history**

> **Core IP:** [N] issued patents assigned to Erudio Bio, building on inventor experience at Analog Devices and 10 years of development at Stanford. Filed in [US / PCT / KR / EU].

Whichever you pick, three things must appear in one sentence somewhere on the deck: **assignee / licensee, scope, exclusivity.** Without those, "Part of IP Licensed from ADI" reads as "we don't own our core IP."

Also drop the second ADI sentence ("Erudio Bio and Analog can be a key player...") entirely from the Exec Summary — it's not a fact, it's a hope. If ADI is a strategic partner with named commitments, that goes on a Partnerships slide with terms.

---

### 7.4 Slide 22 — Biodefense bullets (Option B from prior exchange, restated)

To replace the current "GWOT to Great Power Competition / Need to defend against near-peer adversaries / Flexible, efficient solution needed from CBRND to Readiness."

**Bullet 1**
> Peer adversaries now field engineered, signature-unknown bio/chem agents. The threat library is no longer the threat.

**Bullet 2**
> Legacy assays answer "is it X?" Erudio answers "what is it, even if it's new?"

**Bullet 3**
> One chip, sample-to-answer, ruggedized for the forward edge — covering the CBRND-to-readiness continuum on a single platform.

---

### 7.5 Slide 5 — sourced replacement for "20% of world's economy"

Replace the giant "20%" callout with:

> Global health spending reached **~$9 trillion in 2023 — ≈10% of world GDP**, growing ~4% in real terms per year (WHO Global Health Expenditure Database).
>
> Per-capita spending growth in advanced economies is outpacing GDP growth, driven by aging populations.
>
> National health systems treat cost containment as an existential issue.
>
> **Efficient preventative screening is widely seen as the structural solution.**

Same urgency; sourced figure. The "outpacing EU GDP by 3×" line can stay if you can cite a per-capita-growth-rate source for it.

---

### 7.6 Two-word fixes (drop-in)

- Slide 9, body text: **"Error-free multiplexing"** → **"Error-suppressed multiplexing"**
- Slide 17, punchline: **"a requirement for every launch"** → **"a standard tool for novel-modality medicinal chemistry"**
- Slide 23, body text: **"single sayer networks"** → **"single-payer networks"**

---

## 8. What I did not draft (waiting on your input)

- **Ask slide / use of funds / 12-18-24mo milestones** — you said this is coming. Happy to draft a structure when you're ready.
- **Slide 14 Competitive Landscape rewrite** — depends on whether you want a feature-comparison table or a quadrant chart on different (real, measurable) axes. Tell me which and I'll draft it.
- **Slide 18 hero benchmark rewrite** — depends on whether you have new validation data or just want to re-caption the existing chart honestly. Tell me which.
- **IP slide full draft** — depends on the actual Erudio/Stanford/ADI relationship. Tell me the real structure and I'll write the slide.
