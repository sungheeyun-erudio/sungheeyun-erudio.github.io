---
date: Wed May 27 18:18:37 KST 2026
last_modified_at: Thu May 28 16:50:31 KST 2026
layout: single
title: "25-May-2026 Pitch Deck Review"
permalink: /deck-review/25-may-2026
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

# Erudio Bio Seed Pitch Deck — Consolidated Panel Review

**Deck:** `Erudio Investor Pitch 2026 05 25.pdf` (12 slides, 4.1 MB, dated 2026-05-25)\
**Panel:** Narrative reviewer • Numbers reviewer • Devil's Advocate\
**Date of review:** 2026-05-27\
**Drafts:** [`/tmp/pitch-review/narrative.md`](/tmp/pitch-review/narrative.md), [`/tmp/pitch-review/numbers.md`](/tmp/pitch-review/numbers.md), [`/tmp/pitch-review/devils.md`](/tmp/pitch-review/devils.md)

**Process note.** Each reviewer received the 12 rendered slide PNGs plus the text extract, and was told the others would push back via SendMessage. In execution the sub-agent sandbox blocked both file writes and inter-agent messaging, so each reviewer produced their draft independently and the orchestrator (this synthesis) reconciled conflicts after the fact, using each reviewer's explicit hand-off notes to the other panelists. Where the three reviews disagreed, the disagreements are surfaced in §3 rather than blended away.

## 1. Headline Verdict

**Consensus: not investable as written, but the underlying science and team are credible enough that a revised deck could be.** The same five-or-six gaps surface from every reviewer's seat:
<span style="color: red;" id="anchor-01"> no ask, no traction, no problem statement, no GTM, statistically thin hero data</span>, three businesses pitched as one.

| Reviewer | Grade | Verdict |
|---|---|---|
| Narrative | **C-** | Two strong assets (bioTCAD/EDA frame, 8/8 vs 1/8 chart) buried under 5 architecture slides; three-market sprawl with no GTM, no ask. |
| Numbers | **D+** | Tech vision wrapped around a single n=8 anecdote whose 95% CI overlaps with the comparator's; no sourced TAM, no ask, no regulatory plan. |
| Devil's Advocate | **REVISIT IN 6 MONTHS** | Three companies in a seed-shaped trench coat; "TCAD-for-pharma" promise invokes Schrödinger but never names them; no ask, no traction, no commercial hire. |

If you sent this deck to a triage-driven seed partner tomorrow, all three reviewers expect a pass — not because the underlying technology is wrong, but because the deck does not contain enough information to write a memo.

## 2. Where All Three Reviewers Agreed (the unanimous fixes)

These are the items every reviewer flagged from their own seat. Fix these first; they cost nothing to disagree about.

1. **No ask, no use of funds, no milestones.** Round size, pre-money, runway, 12-/18-/24-month milestones, prior funding — none present. Numbers calls this "fatal." Devils calls it "I cannot write a memo I cannot price." Narrative calls it "the deck just stops."
2. **No problem statement / no quantified pain.** Slide 2 jumps straight to a stack diagram; the reader never feels urgency. Insert a problem slide before any capability slide.
3. **No competitive landscape, no incumbents named.** Schrödinger, Recursion, Insilico, Iambic, Isomorphic Labs, Chai — zero appear. The Slide 6 "bioTCAD = EDA" frame *invites* the Schrödinger comparison and then ducks it. A competitive slide is non-negotiable.
4. **Three markets, one team, one round → pick one wedge.** Drug development, biodefense, and clinical diagnostics each have different buyers, sales cycles, regulatory paths, and unit economics. All three reviewers independently said: drop two, focus on the third for this raise.
5. **The Synopsys / Samsung / SK Hynix logos on Slide 8 read as partnerships but are almost certainly founder employers.** All three flagged this. Either label them ("founder pedigree") or remove them — leaving them ambiguous is worse than either fix.
6. **"Initial interests from SNUH and Keimyung" is not traction.** All three want it quantified: LOI? signed pilot? paid POC? dollar amount? date?
7. **"Error-free multiplexing" (Slide 3) contradicts "error removal" (Slide 5).** Numbers and Narrative both flagged this. The defensible claim is error *suppression / filtering* — Slide 3's absolute language should be softened.
8. **The bioTCAD/EDA framing on Slide 6 is the strongest single idea in the deck.** All three reviewers agree. They differ on whether it's currently *earned* by the evidence (see §3.1), but they agree it belongs at the front, not buried at slide 6.

## 3. Cross-Reviewer Conflicts and Synthesis

The reviewers disagreed on four substantive points. Each is resolved below with the orchestrator's reconciled recommendation.

### 3.1 Should Slide 7 ("100% vs 12.5%") be promoted to the cover slide?

- **Narrative says YES.** Slide 7 is "the deck's killer slide, buried at #7. '8/8 right where state-of-the-art AI got 1/8' is the entire pitch in one image. Move it forward."
- **Numbers says NO.** With n=8 (one of which is the *anchor used to fit the force field parameters*), Wilson 95% CIs are [63%, 100%] for bioTCAD and [2%, 47%] for the legacy tool — **the intervals overlap.** "100% vs 12.5%" is statistically indistinguishable from "75% vs 25%" at this n. Promoting the chart amplifies the overclaim.
- **Devils piles on.** All eight peptides derive from one 18-mer cyclic antiviral parent. The "legacy in-silico" tool is unnamed. If Erudio ran it themselves in default mode, the 12.5% number is unreliable too.

**Reconciled recommendation.** *Promote the bioTCAD/EDA framing (Slide 6's idea) to Slide 1; do NOT promote the 100% vs 12.5% chart in its current form to anywhere prominent.* Before that chart can carry the front of the deck, it must be replaced with a powered, blinded, out-of-domain comparison (n ≥ 30, named comparator, named operator, public benchmark like FEP+ MERCK-set or PDBBind, scoring rubric stated). Until then, the chart belongs in the appendix as supporting anecdote, not as the cover claim. Narrative's instinct to lead with a *concrete proof point* is correct; the specific proof point currently available isn't strong enough to bear that weight.

### 3.2 Is the bioTCAD/EDA frame brilliant or reckless?

- **Narrative:** "the cleverest pitch frame in the deck. Belongs on Slide 1."
- **Devils:** "dangerously optimistic. Invokes Synopsys/Cadence/Schrödinger directly — Schrödinger has been doing physics-grounded, parameter-validated drug simulation for 30+ years, is publicly traded, and still trades at a discount. A seed deck that picks the boldest possible analogy and then ducks every named incumbent reads as either unaware or evasive."
- **Numbers:** intellectually correct, but "bioTCAD will be as widely used as semiconductor EDA: a requirement for every launch" is overreach against n=8 evidence.

**Reconciled recommendation.** *Keep the frame; earn it.* The frame is the deck's strongest IP — drop it and Erudio becomes another "AI + biology platform." But the frame currently writes checks the evidence cannot cash. Two edits:
- **Name Schrödinger explicitly** on Slide 6 in a single-line "How is bioTCAD different from FEP+/AlphaFold3/[other]?" Two specific differentiators (e.g., measurement-anchored parameter fitting from Erudio's own chip; out-of-distribution behavior in novel chemical space) replace the implicit "we're 8x better than the leader" claim with a defensible "we are differentiated on X and Y."
- **Soften the universality claim** from "as widely used as EDA: a requirement for every launch" to something earned: "a measurement-anchored simulator for medicinal-chemistry teams making novel modalities." Save the "EDA universal-tool" framing for the Series A.

### 3.3 Which wedge to keep, and how harshly to cut?

- **Narrative:** "pick one. Biodefense is the strongest *narrative* (field-deployable, fast actionable decision, government dollars). Pharma is the strongest *frame*. Either commit."
- **Devils:** "drop biodefense and clinical diagnostics. Pitch drug development only — bioTCAD as a paid SaaS/services tool for pharma medicinal-chemistry teams. Come back when the deck has one buyer."
- **Narrative also offered a counter-pre-emption:** "for SBIR / In-Q-Tel / strategic-defense audiences, three-market dual-use breadth is a *feature*, not a bug. If the audience is government rather than VC, my muddled-audience critique is mis-aimed."

**Reconciled recommendation.** *Two-deck strategy.* The fundamental disagreement is audience-dependent: a defense-strategic buyer reads dual-use as strength; a tier-1 VC reads it as lack of focus.
- **For a VC seed round:** use Devils' framing — drug-development-only deck, single buyer (pharma medchem head), single product (bioTCAD-as-service or VSA-instrument-with-bioTCAD-bundle), single milestone path. Demote biodefense + clinical to a one-line "platform optionality" mention in the appendix.
- **For SBIR / In-Q-Tel / DoD / BARDA capability briefings:** retain the three-market deck — biodefense leads, the rest is dual-use.

Erudio is currently using the second deck to try to do the first deck's job. That is the source of the muddle every reviewer flagged.

### 3.4 Slide 5 (cytokine immunoassay) vs Slide 7 (peptide validation) — which is the more defensible hero?

- **Narrative:** Slide 7 is "the killer." Slide 5 is "a results poster."
- **Devils (concession section):** "Slide 5 is more interesting than Slide 7. Force-spectroscopy error removal on 6-plex cytokine speaks to a known assay pain point (multiplex crosstalk) that pharma actually pays to solve — a more believable platform claim than the peptide chart."
- **Numbers:** Slide 5 is concrete but under-quantified (cytokine identities, n, CV%, LoD missing). Slide 7 is dramatic but statistically thin.

**Reconciled recommendation.** *Slide 5 is the more defensible hero; Slide 7 is the more dramatic one.* For an investor who knows assay platforms, Slide 5's claim (eliminated multiplex cross-reactivity at 6-plex, with a path to N-plex) is closer to a fundable product than Slide 7's binding-prediction anecdote. The deck should reframe both:
- **Slide 5 reframe.** Lead with the *problem*: "multiplex immunoassays plateau at 6-plex because cross-reactivity dominates above that." Then the *result*: clean 6-plex, sourced LoD and CV% per analyte, head-to-head vs Luminex/MSD. Then the *implication*: path to 20-plex / 50-plex.
- **Slide 7 reframe.** Already covered in §3.1. Move to appendix until n ≥ 30 blinded benchmark is available.

A defensible re-ordered story is: **Problem (multiplex/in-silico unreliability cost pharma X) → Approach (measurement-anchored hybrid physics+AI = bioTCAD) → Proof Point 1 (Slide 5, quantified) → Proof Point 2 (Slide 7, appendix or right-sized) → Team → Ask.**

## 4. Combined Slide-by-Slide Action List

| Slide | Current title | Combined panel verdict | Action |
|---|---|---|---|
| 1 | Erudio Bio — Data Driven AI for Effective Medicine | Generic title card; wastes the deck's most valuable slide. | Replace with bioTCAD/EDA frame + 1 specific differentiator. Headline must be company-specific, not category-generic. |
| 2 | Erudio Technology Stack | Architecture diagram before problem framing. | Replace with quantified Problem slide. Move stack to slide 4 or appendix. |
| 3 | Multifaceted Data Platform: VSA | Real assets (Stanford, 21 patents, chip), but "error-free" is an overclaim. | Soften "error-free" → "error-suppressed." Cite 21-patent table (USPTO #s, jurisdiction, lead-claim summary). Anchor "10 years" to a founding date. |
| 4 | Erudio VSA and DR-IN-A-BOX | Naming sprawl begins (VSA, DR-IN-A-BOX, AI DR-IN-A-BOX, bioTCAD). | Pick one product naming hierarchy. Make explicit what *one* customer buys. |
| 5 | Validation of Force Spectroscopy Error Removal on 6-plex Cytokine Immunoassay | More defensible than Slide 7 but poorly framed. | Reframe as Problem → Result → Implication. Quantify: cytokine identities, n, replicates, CV%, LoD, head-to-head vs Luminex/MSD. |
| 6 | bioTCAD: Hybrid AI & Physics-based Drug Development | The deck's strongest idea, buried. | Promote the *frame* to Slide 1. Add competitive-differentiation lines (Schrödinger FEP+, AlphaFold3, etc.). Soften "requirement for every launch." |
| 7 | Head-to-Head bioTCAD Validation: 100% vs 12.5% | Dramatic visual; statistically fragile (n=8, anchor in train set, comparator unnamed). | Move to appendix until n ≥ 30 blinded out-of-domain benchmark is run with a named comparator and stated rubric. |
| 8 | Erudio's Technology Breakthrough — The Secret Sauce | Synopsys/Samsung/SK Hynix logos imply partnership but are almost certainly founder employers. "Secret Sauce" tone off for defense/dx buyers. | Label logos explicitly ("founder pedigree"). Replace "Secret Sauce" with neutral title. Tie founder credentials to specific capabilities, not adjectives. |
| 9 | Erudio Application: Drug Development | Third architecture diagram. No customer, no pilot, no price, no workflow a pharma scientist would recognize. | Replace with a real GTM slide: named target customer (Head of Computational Chemistry @ top-20 pharma), pricing model, 12-month pilot plan, 3 named target pharma partners. |
| 10 | Erudio Application: Biodefense | Visually the strongest slide. Audience pivot is jarring. "Dozens, hundreds, thousands" is aspirational not capability. | For the VC seed deck: remove. For a DoD/BARDA capability brief: lead with this slide and re-anchor SBIR/CRADA/program-of-record references. |
| 11 | Erudio Application: Clinical Diagnostic | "20% of world's economy" overstates by ~2× (actual ~10% global, ~17% US). SNUH/Keimyung "initial interests" not quantified. | For VC seed deck: remove. If retained: replace TAM line with WHO GHED + CMS NHE figures; quantify hospital relationships (LOI, date, dollar amount). |
| 12 | Team / Advisory Board | Deck's second-strongest slide. But deck ends here — no ask, no use of funds, no roadmap. | Keep. Add a closing slide 13 with: round size, valuation expectation, use of funds (3–5 buckets, %), runway, 12/18/24-month milestones. Disclose Tim Germann's Carterra CCO role if Erudio's chip is in any way adjacent to LSA. |

## 5. Prioritized Fix List

Numbered roughly by impact-per-effort. The first five are unanimous; the rest reflect synthesis.

1. **Add the Ask slide.** Round size, pre-money, use of funds, runway, 12/18/24-month milestones. Cost: one slide. Impact: turns the deck from a capability brochure into a fundable memo.
2. **Pick a single wedge for the VC version.** Drug development (Devils' choice; most consistent with bioTCAD framing). Remove Slides 10 and 11 from the VC deck. Build a separate one-pager / brief for biodefense.
3. **Rewrite Slide 1.** Replace generic tagline with bioTCAD/EDA frame + one concrete differentiator. Lead the deck with the strongest idea, not a logo.
4. **Insert a quantified Problem slide as Slide 2.** Replace the current architecture diagram. State the pain in pharma medchem dollars / months / failure rates.
5. **Add a competitive landscape slide.** Name Schrödinger, Recursion, Isomorphic Labs, Iambic. Show where bioTCAD sits and what it does that they don't (measurement-anchored parameter fitting from in-house chip biology).
6. **Replace the Slide 7 chart with a powered benchmark.** n ≥ 30, blinded, out-of-domain, named comparator (Schrödinger FEP+ in expert configuration), public benchmark set, stated rubric. Until then, demote to appendix.
7. **Quantify Slide 5.** Cytokine identities, n, replicates, CV%, LoD per analyte, dynamic range, head-to-head vs Luminex/MSD. This is your most defensible product claim — invest in making it bulletproof.
8. **Anchor the IP claim.** "21 issued patents" → table of 5–10 lead patents with USPTO #s, jurisdictions, issue dates, one-line claims. Disclose Stanford license terms (exclusive? field-limited? royalty? sublicense rights?).
9. **Label the Synopsys/Samsung/SK Hynix logos** as founder employers (or remove them).
10. **Quantify the hospital traction.** SNUH and Keimyung as named LOIs/pilots with dates and dollar amounts, or remove. Same for Synopsys-Samsung-SK Hynix.
11. **Soften absolute language.** "Error-free" → "error-suppressed." "Requirement for every launch" → "measurement-anchored simulator." "Massively multiplexed" → state demonstrated and target plex counts. "20% of world's economy" → sourced WHO/CMS figures.
12. **Add a commercial hire to the team slide** (or be explicit about the search). A former Head of Computational Chemistry at a top-20 pharma, or a SaaS-for-bio CRO operator, at founder-level equity. Cola as advisor is not a CCO.
13. **Disclose the Carterra conflict.** Tim Germann is CCO of Carterra Bio, an adjacent biophysics company. Either explain the differentiation explicitly or move him off the formal advisory.

## 6. Path to "Investable"

What the panel collectively believes Erudio needs in the next 6 months to convert a "pass" into a "soft yes":

- **One wedge picked, named in the deck, and selling.** Three paying pharma pilots in the $50K–$250K range. LOIs count for one meeting; signed POs change the conversation.
- **A defensible hero benchmark.** n=30 blinded out-of-domain head-to-head against Schrödinger FEP+ (in expert configuration, ideally run by a third party or with the protocol pre-registered). Beat them on a documented subset of chemistries; tie on the rest.
- **A commercial hire on the cap table.** Customer-side credibility at founder level — not at advisor level.
- **An ask slide with milestones.** Round, runway, use-of-funds, what the next 18 months produce, what triggers the Series A.
- **A 1-line patent moat statement.** What the top 5 independent claims fence, and how Erudio's biophysics chip is differentiated from Carterra's LSA.

The underlying scientific idea — measurement-anchored, physics-grounded, AI-augmented simulation, with the measurement instrument built in-house — is the right idea, and the team's chip + biophysics + optimization-trained AI composition is genuinely rare. The deck is currently doing that idea a disservice by burying it under three architecture diagrams, three application slides for three different audiences, and a hero statistic that's statistically indistinguishable from a coin flip at the demonstrated sample size. Fix the deck; the company is more credible than the deck makes it look.

## Appendix A: Reviewer hand-off notes (preserved verbatim, would have been SendMessage exchanges)

The sub-agent sandbox prevented direct peer-to-peer messaging, but each reviewer drafted explicit hand-offs to the other two. These are captured here so the user can see where each reviewer pre-emptively conceded or pushed back on the others' likely arguments.

**Narrative → Numbers.** "My narrative review is final. Two places I'm exposed if your numbers come back ugly: (1) I declared Slide 7 the deck's killer slide on the strength of '100% vs 12.5% / 8 designs' — if n=8 collapses or the comparison setup is cherry-picked, my entire top-of-deck reordering breaks; (2) Slide 6's '21 patents / 10 years' and 'Synopsys/Samsung/SK Hynix' do load-bearing credibility work — if any are misleading, my Slide-8 critique (under-explained logos) becomes a much harsher 'remove these' call." → *Numbers confirmed both exposures. The reconciled recommendation in §3.1 routes around the Slide 7 problem by promoting the bioTCAD frame (Slide 6's idea) rather than the chart.*

**Narrative → Devils.** "Push me on recommendation #3 (pick one wedge). Plausible counter: for SBIR / In-Q-Tel / strategic-defense audiences, three-market dual-use breadth is a *feature*, not a bug — and 'GWOT to Great Power Competition' may be intentionally aimed at a non-VC buyer. If that's the actual audience, my muddled-audience critique is mis-aimed and the deck is more coherent than I'm giving it credit for." → *Devils held the harder line ("drop biodefense and clinical from the seed pitch"). Reconciled in §3.3: two-deck strategy.*

**Devils → Narrative.** "Three structural problems hurt the story even more than the science: (1) Slides 9–11 read as three separate companies; (2) Slide 6's 'bioTCAD = EDA' promise is a check the rest of the deck does not cash, because no incumbent (Schrödinger, Recursion, Iambic, Isomorphic) is named; (3) Slide 11's '20% of the world's economy' is a TAM-substitute that signals the company doesn't know who its first 10 customers are."

**Devils → Numbers.** "Two figures need scrubbing. (1) Slide 7's '100% vs 12.5%' — n=8, one chemical series, one of the eight is the anchor used to fit the force field. Effective sample size is 7, and '12.5% legacy' likely reflects an unoptimized run. (2) Slide 3's '10 years development, 21 issued patents' — confirm issuance vs. application, jurisdictions, assignee. Also confirm whether Slide 8's Synopsys/Samsung/SK hynix logos represent customer relationships, employer affiliations, or aspirational targets — that distinction is material." → *Numbers' audit table confirmed all three flags.*

**Numbers → Narrative.** "Numbers issues that hurt narrative credibility: 'Error-free' (slide 3) contradicts 'error removal' (slide 5); 'bioTCAD will be a requirement for every launch' (slide 6) lands as overreach against n=8 evidence; 'Initial interests' presented as traction is unquantified; Synopsys/Samsung/SK Hynix logos imply partnership; appear to be former employers."

**Numbers → Devils.** "Strongest bull data: Slide 5's force-spectroscopy + Bayesian filtering on 6-plex cytokine is falsifiable and demonstrated; founder pedigree (Stanford + TCAD industry) is real; Davis/Snyder/Greenleaf advisory is top-tier. Strongest bear data: n=8 with overlapping confidence intervals (8/8 CI [63–100%] vs 1/8 CI [2–47%] overlap); no ask, no traction, no regulatory plan, no sourced TAM; pattern of unhedged absolutes signals founder overclaiming; '$15B+ exits' advisor attribution unverifiable." → *Devils' concessions section accepted Slide 5 as more interesting than Slide 7; reconciled in §3.4.*
