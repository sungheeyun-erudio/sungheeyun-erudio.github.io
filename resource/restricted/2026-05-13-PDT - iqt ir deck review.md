---
date: Wed May 13 14:18:08 PDT 2026
last_modified_at: Wed May 13 14:20:31 PDT 2026
layout: single
title: "IQT IR Deck Review"
permalink: /deck-review/iqt
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

# Erudio Bio — Bridge Funding Pitch Deck: Consolidated Critique
**Deck:** Erudio Bio ASW Presentation 3-10-26 v4  
**Review date:** 2026-05-13  
**Reviewers:** narrative-reviewer · numbers-reviewer · devil's advocate  

---

## Executive Summary

The deck presents a genuinely interesting underlying technology (VSA platform, Stanford spin-out, 10 years of development, 21 patents) with a credible and relevant military use case. However, as a **bridge funding pitch**, it is structurally incomplete and contains several claims that will actively damage credibility with sophisticated investors. The three most urgent problems are: **(1) there is no stated funding ask anywhere in the deck, (2) the product is explicitly labeled "Notional" after 10 years of development, and (3) the headline financial savings claims ($18B / $500B) are entirely unsourced.** These are not polish issues — they are disqualifying for most investor conversations.

**Overall evidence quality: 3/10**

---

## I. NARRATIVE REVIEW

### Story Arc
**Rating: Moderate — right structure, broken transitions**

The deck follows a defensible problem → solution → evidence → team sequence. However, several transitions break down:

- **Slides 3→4 gap:** Slide 3 frontloads chip architecture specs (9mm × 36mm, 400 actuators per sensor) before establishing why they matter operationally. A non-engineer audience loses the thread here. The "one sample, one run" simplicity diagram (Slide 4) is the clearest communication in the deck — it should appear earlier.
- **Slides 9→10 gap:** Slide 9 makes bold scalability claims ("only ones who can," "<1 year delivery"), then Slide 10 labels the product image **"Notional."** This sequence destroys rather than builds confidence.
- **No closing argument:** The deck ends on a contact slide with no funding ask, no use-of-proceeds, no milestone roadmap, no call to action. The narrative simply stops.

### Investor Hook
**Rating: Strong on mission framing; weak on emotional specificity**

The BLUF format (Slide 2) is smart for a DoD audience. But "Boost the fighting force's ability to perform at individual and system level" is broad enough to describe dozens of defense health companies. The use-case specifics that create visceral stakes — one sick SOCOM operator degrading a 12-man team; a cytokine storm misdiagnosed in-theater — exist in Slides 6–8 but never surface in the opening hook.

### Clarity
**Rating: Adequate on problem, poor on solution accessibility**

The stated problem (warfighter readiness) is real but framed as a goal rather than a gap. The deck never quantifies the current failure state: how many deployments are degraded by preventable illness? What is today's time-to-diagnosis in theater? Slide 4's single-sample diagram is the deck's single most effective communication asset. The "doctor-in-a-box" phrase (Slide 10) is memorable and concrete — it arrives too late.

### DoD/Government Audience Fit
**Partially works — strong instincts, inconsistent execution**

| Works | Does Not Work |
|---|---|
| BLUF format is native to military communication culture | $500B Medicare/Medicaid/VA claim is civilian healthcare framing with no DoD bridge logic |
| Lifecycle-of-deployment framework matches how program offices think | No procurement pathway (OTA, SBIR, AFWERX, DIU) mentioned anywhere |
| SOCOM, submarine IDC, CBD defense, Gulf War Illness show domain knowledge | "Bridge funding" is VC language; TRL framing would resonate better with DoD program offices |
| CIA/DoD-affiliated advisors (Karyn Eliot, Phil Ferro) add institutional credibility | "Notional" product image is a red flag for any DoD evaluator who has seen vaporware pitches |

### Missing Narrative Elements

| Missing Element | Investor Impact |
|---|---|
| **Funding ask** | A bridge pitch without a dollar amount is not a pitch |
| **Use of proceeds** | No milestone map showing what this capital buys |
| **Traction / proof points** | No pilot, no LOI, no SBIR/STTR, no field validation cited |
| **Competitive landscape** | "Only ones who can" claim floats without a competitive map |
| **Regulatory strategy** | No FDA, CLIA waiver, or DoD qualification pathway mentioned |
| **IP details** | 21 patents cited with no breakdown (granted vs. pending, scope) |
| **Financial projections** | None — not even directional revenue scenarios |
| **Exit / return narrative** | No IPO, acquisition, or licensing scenario described |
| **Risk acknowledgment** | Absence of risk framing reads as naivety or evasiveness |

---

## II. NUMBERS REVIEW

### Quantitative Claims Audit (18 claims assessed)

| Claim | Source | Assessment |
|---|---|---|
| $9M private capital | Stated (Slides 2, 3) | Plausible but unverified; unclear if NIH/Gates grants are included or separate |
| 21 patents | Stated (Slide 2) | Unverified; no breakdown of granted vs. pending, geography, or claim scope |
| 10 years development | Stated (Slide 3) | Consistent with Stanford spin-out timeline; plausible |
| 1,000 tests per run | Stated (Slides 3, 10) | **Not demonstrated.** Appendix shows 6 assays (IL-2, IL-4, IL-6, IL-10, IFN-γ, TNF-α). Gap of 166× with no bridging data. |
| Results in <30 minutes | Stated (Slides 3, 10) | Unvalidated at claimed multiplex scale |
| <100ul blood sample | Stated (Slide 10) | Unvalidated across full multiplex panel |
| 400 actuators per sensor | Stated (Slide 3) | Consistent with appendix SEM images; technically plausible |
| 30 microarrays currently on chip | Stated (Slide 9) | Consistent with appendix data |
| ~2.6M commercial antibodies | Cited (Lee et al. 2000; Juncker et al. 2014) | The Juncker citation is from 2014 (acceptable); the Lee citation is **from 2000** — 26 years old — for a market size figure that is likely outdated |
| "Expandable to thousands" (assays) | Stated (Slide 9) | No supporting data in deck or appendix |
| Deliver warfighter capability <1 year | Stated (Slide 9) | No regulatory, development, or validation timeline provided to support this |
| "Only ones who can execute immunoassays at scale" | Stated (Slide 9) | **Factually false** (see Section III) |
| $18B DoW savings | Stated (Slide 11) | **Zero citations, zero methodology, zero timeframe** |
| >$500B Medicare/Medicaid/VA savings | Stated (Slide 11) | **Zero citations, zero methodology, zero timeframe.** Figure approaches entire annual Medicare fee-for-service budget. |
| "Nearly eliminate mis/delayed diagnoses" | Stated (Slide 11) | Extraordinary clinical claim with no supporting data |
| Signal recovery: 12% / 56% / 71% | Appendix (Slide 20) | Internally consistent data — but **12% signal recovery at 0.1 ng/ml** raises serious questions about clinical sensitivity at low analyte concentrations |
| Ronald W. Davis $15B+ exits | Stated (Slide 12) | Plausible given Stanford Genome Tech Center pedigree |

### Six Investor Red Flags

1. **$18B/$500B unsourced:** Highest single credibility risk. Will cause investors to distrust surrounding claims.
2. **1,000 tests vs. 6 demonstrated:** The headline performance claim is 166× beyond what the appendix validates.
3. **"Only ones who can" competitive exclusivity:** Demonstrably false without precise scoping (see Section III).
4. **12% signal recovery at low concentration:** If the platform is to serve as a clinical-grade diagnostic, sensitivity at the 0.1 ng/ml range must be substantially better.
5. **26-year-old citation** for antibody library size: signals the deck has not been updated with current literature.
6. **"Notional" product image:** Signals TRL 4–5, not near-commercial. Inconsistent with "<1 year delivery" claim.

### Missing Financial Data (Standard for Bridge Pitch)

A bridge round pitch deck normally contains: funding ask amount · use-of-proceeds breakdown · burn rate · runway · revenue or ARR (if any) · financial projections (3-year) · prior round terms and valuation · Series A thesis and expected size · investor names (if any following on) · competitive pricing data. **None of these are present.**

---

## III. DEVIL'S ADVOCATE: THE CASE FOR PASSING

### 1. Ten Years, $9M, and a "Notional" Image
The single most damaging fact in the deck. After a decade of development and $9M spent, the product image is explicitly labeled **"Notional."** That is not a prototype. The appendix demonstrates cytokine detection at bench scale with 6 analytes. The gap between a Stanford lab chip and a suitcase-sized device that works in the field in 30 minutes, operated by non-specialists, is measured in years and tens of millions of dollars — neither of which the deck accounts for. The deck offers no explanation for why 10 years of effort has produced 30 microarrays and a concept image.

### 2. The DoD Sales Problem
Even if the product existed today, the go-to-market is a regulatory minefield the deck completely ignores:
- **FDA clearance** is required for any diagnostic used on military personnel. No 510(k), De Novo, or EUA strategy mentioned.
- **CLIA waiver** is required for point-of-care use. Not mentioned.
- **DoD procurement cycles** for unproven medical diagnostics run 3–7 years through USAMRDC, DHA, and relevant PEO offices. No SBIR Phase I/II, OTA, CRADA, or AFWERX engagement mentioned.
- **No named customer.** No LOI. No pilot site. No contracting officer. The use cases are aspirational bullet points, not active engagements.

### 3. The "Only Ones" Claim Is False
Slide 9 states: *"We are the only ones who can execute immunoassays at scale."* This is directly contradicted by:
- **Luminex xMAP** — multiplexed immunoassay platform, up to 500 analytes, commercially deployed globally for 20+ years, FDA-cleared
- **Bio-Rad Bio-Plex** — multiplexed cytokine panels, widely deployed
- **Quanterix Simoa** — ultrasensitive single-molecule array, FDA-cleared, used in military research
- **Meso Scale Diagnostics (MSD)** — electrochemiluminescence multiplexing, broad clinical/pharma use
- **Fluidigm/Standard BioTools, Seer Bio, Olink Proteomics** — all executing multiplexed protein detection at scale

This claim does not survive a basic literature search. An investor who spots it will discount every other claim in the deck.

### 4. Lab Bench to Battlefield Is Not a Footnote
The validation gap between appendix data and product promise is enormous:
- **Analytical validation:** sensitivity, specificity, and reproducibility across 1,000 analytes not demonstrated (only 6 shown, with 12% signal recovery at low concentration)
- **Operational validation:** no data for untrained operators in dust, humidity, temperature extremes, or movement
- **Scalability:** "roll out speed is dependent on funding and number of parallel developments" is an admission that the claimed capability does not exist and has no timeline

### 5. No Ask = Not a Pitch
There is no funding amount, no use-of-proceeds, no burn rate, no runway, and no financial model anywhere in this deck. A "bridge" pitch that does not state what it is bridging to — what milestone, at what cost, to what Series A — is not a bridge pitch. It is a request to write a check into a vacuum. This tells investors: the team does not know what they need, OR they know the number is uncomfortable and are avoiding disclosure.

### 6. The $500B Claim Destroys Credibility
Slide 11 claims the platform could save Medicare/Medicaid/VA >$500B. This figure approaches the entire annual Medicare fee-for-service budget. Claiming to save it — with no citations, no methodology, no timeframe, and the word "could" doing all the work — signals that the team does not understand what they are claiming, or is hoping investors won't check. Sophisticated investors will check immediately, and the deck will lose them at that moment.

### 7. Advisors Are Not Operators
The advisory board is impressive on paper. But advisors do not build products, close DoD contracts, or navigate FDA submissions. The 4-person operating team has no disclosed regulatory affairs expertise, no track record of taking a diagnostic to market, and no demonstrated history of winning government contracts. Strong advisors with an unproven operating team is a common pre-failure pattern in deep-tech startups.

### 8. No Market Traction at All
No customers. No LOIs. No SBIRs. No named DoD program offices. No VA contacts. No pharma partnerships. Prior investors are implied by the $9M figure but not named — and if they are not participating in this bridge, that is a significant negative signal the deck buries through omission.

---

## IV. CROSS-REVIEWER CONFLICTS

These are points where reviewers' analyses directly conflict or contradict each other — the most important signals for revision:

| Conflict | Detail |
|---|---|
| **Narrative strength vs. numbers reality: scale claim** | Narrative-reviewer flagged the lifecycle platform framing as a key strength. Numbers-reviewer found the headline performance claim (1,000 tests) is 166× beyond validated data (6 tests). The platform narrative is built on an unvalidated technical foundation. |
| **"10 years = de-risked" narrative vs. "Notional" product** | Narrative framing treats development tenure as a credibility signal. Both numbers-reviewer and devil's advocate note that 10 years of effort yielding a concept image is evidence of execution risk, not de-risking. |
| **$500B as a "bipartisan appeal story" vs. credibility liability** | Narrative-reviewer identified the extended benefits narrative as a strategic strength for government audiences. Numbers-reviewer and devil's advocate both flag it as the single highest credibility risk — uncited, implausible at face value, and likely to cause investors to distrust adjacent claims. **Consensus: it must be cited with methodology or removed.** |
| **Advisory board as credibility signal vs. operator gap** | Narrative-reviewer and numbers-reviewer treat the advisory board as an asset. Devil's advocate notes the board's impressiveness on paper does not compensate for the absence of regulatory, procurement, and commercialization expertise on the operating team. Both assessments are correct and non-exclusive. |
| **BLUF as audience-appropriate vs. insufficient** | Narrative-reviewer rates BLUF structure as a strength for DoD audiences. Devil's advocate notes that the BLUF doesn't contain a dollar ask — making the communication format correct but the content incomplete. |

---

## V. PRIORITY RECOMMENDATIONS

Ordered by investor impact:

1. **Add the ask.** State the bridge amount, use of proceeds, milestone unlocked, Series A thesis, and valuation basis. A pitch deck without these is not a bridge pitch.

2. **Remove or source the $18B/$500B claims.** These are currently the highest credibility liability in the deck. Either provide a rigorous, cited methodology or remove them. "Could" is not a substitute for evidence.

3. **Replace the "Notional" product image.** Show a real prototype, even at lab scale. If no prototype exists, the deck should honestly describe current TRL and what the bridge capital builds toward. Do not show a concept render and label it "Notional" alongside "<1 year delivery" claims.

4. **Retire or precisely scope the "only ones" claim.** Luminex, Quanterix, MSD, Bio-Rad, and others are in this space. The claim needs either a precise technical differentiator that explains why those platforms don't count, or it needs to be replaced with a specific, defensible competitive advantage statement.

5. **Bridge the 6-to-1,000 assay gap.** Show a roadmap — how many assays validated today, what the development plan is, what funding level achieves what milestone. The headline claim must be grounded in demonstrated data.

6. **Address regulatory pathway.** One slide on FDA strategy (510(k) vs. De Novo vs. EUA), CLIA waiver, and DoD qualification pathway is the minimum required for a medical diagnostic targeting military deployment.

7. **Show any traction.** One LOI, one SBIR, one named program office conversation, one pilot agreement — anything that demonstrates market pull. Customer conversations don't require a signed contract to be disclosed.

8. **Reorder Slides 3–4.** Lead with the operational simplicity ("one sample, one run") before the chip architecture. The "doctor-in-a-box" phrase should appear by Slide 3 at the latest.

9. **Add a competitive landscape slide.** Frame the positioning against Luminex, Quanterix, MSD, etc. with a clear, specific differentiation axis. This converts the "only ones" liability into a strength.

10. **Update citations.** The 2000-era antibody library citation should be replaced with current literature. All savings claims require sources.

---

## VI. WHAT THE DECK DOES WELL

Even the harshest review should acknowledge genuine strengths:

- The **VSA technology** (dynamic force spectroscopy for multiplexed immunoassay discrimination) is scientifically novel and the appendix data, while limited, is internally consistent and shows real technical progress.
- The **BLUF structure** is appropriate for the audience and front-loads strategic value correctly.
- The **lifecycle framework** (pre/during/post deployment) is strategically elegant — it positions Erudio as a platform company rather than a single-use kit vendor.
- The **advisory board** is genuinely impressive: Ronald W. Davis, Michael Snyder, and William Greenleaf are elite Stanford credentials; Karyn Eliot and Phil Ferro add rare dual-use government credibility.
- **"Doctor-in-a-box"** is a memorable, repeatable phrase that will survive the room.
- The **extended benefits framing** (defense budget efficiency + healthcare cost reduction) creates cross-stakeholder appeal — if properly sourced, it could be a genuine differentiator in government pitches.
- The **team composition** (chip/microfluidics, immunology, AI/software, biz dev) is well-rounded for the technical stage.

---

*Consolidated by team-lead from reports by narrative-reviewer, numbers-reviewer, and devil's advocate.*

