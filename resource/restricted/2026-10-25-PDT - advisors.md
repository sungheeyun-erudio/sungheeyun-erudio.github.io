---
date: Sun Oct 25 01:50:00 PDT 2026
last_modified_at: Sun Oct 25 01:57:02 PDT 2026
layout: single
title: "Erudio Bio — Team and Advisory Board"
permalink: /notes/erudio/advisors
categories:
 - notes
tags:
 - Erudio Bio
 - advisors
 - VSA
toc: true
toc_label: "&nbsp;Table of Contents"
toc_icon: "fa-solid fa-users"
toc_sticky: true
author_profile: true
---

posted: {{ page.date| date: "%d-%b-%Y" }}
&amp;
updated: {{ page.last_modified_at| date: "%d-%b-%Y" }}
{: .notice--primary}

<style>
	.page__content table {
		font-size: calc(var(--body-font-size) * 0.85);
		font-family: inherit;
	}

	#roster { display: table; width: 100%; table-layout: fixed; }
	#roster th:nth-child(1) { width: 18%; }
	#roster th:nth-child(2) { width: 24%; }
	#roster th:nth-child(3) { width: 58%; }

	#lsa { display: table; width: 100%; table-layout: fixed; }
	#lsa th:nth-child(1) { width: 16%; }
	#lsa th:nth-child(2) { width: 42%; }
	#lsa th:nth-child(3) { width: 42%; }
	.page__content th { text-align: center !important; }
</style>

Prepared by Sunghee Yun (Co-Founder & CTO) · internal working notes

# Erudio Bio — Team and Advisory Board

**Internal.** Contains candid assessments of colleagues and open questions about potential conflicts. Not for circulation to the advisors themselves or to investors as written.

The advisory board is usually read as a list of credentials. It is better understood as **three groups**, each covering a different thing the company needs — and one of the three tells a story about the technology that nothing else in the deck tells.

| Group | Who | What it covers |
|:--|:--|:--|
| Commercial | Michael Cola, Tim Germann | How pharma buys; how an instrument in this category is sold |
| Government | Karyn Eliot, Phil Ferro, Bill Chen | How the national-security customer buys, and who evaluates the technology on its behalf |
| The measurement lineage | Ronald Davis, Michael Snyder, William Greenleaf | Three generations of making a measurement massively parallel — ending exactly where VSA sits |

## 1. At a glance

| Name | Role / affiliation | What they bring |
|:--|:--|:--|
| Kee-Hyun Paik, PhD | Co-Founder & CEO | Chip, microfluidics, instrumentation, computational mathematics |
| Susanne Baumhueter, PhD | Team | Biology, immunology, project management |
| Sunghee Yun, PhD | Co-Founder & CTO | AI, optimization, software |
| Michael Cola | Advisor — former President, Shire Specialty Pharmaceuticals; former CEO, AEVI Genomic Medicine | Commercial pharma at scale; diagnostics operating experience; public-company and M&A |
| Tim Germann | Advisor — CCO, Carterra | Go-to-market for label-free binding instruments sold into pharma antibody groups |
| Karyn Eliot | Advisor — retired CIA senior executive | National-security acquisition and industry partnerships; 30 years in S&T programmes |
| Phil Ferro | Advisor — virologist; formerly DoD, DoS, HHS, White House | Biodefense policy across four seats; scientific evaluation |
| Bill Chen | Advisor — former hedge fund and VC; national security and FFRDC background | Translating government traction into terms investors price correctly |
| Ronald W. Davis, PhD | Advisor — Prof. Biochemistry & Genetics, Stanford; Director, Stanford Genome Technology Center | Invented measurement methods that created fields; first DNA microarray |
| Michael Snyder, PhD | Advisor — Prof. Genetics, Stanford; Director, Center for Genomics and Personalized Medicine | Protein microarrays; multi-omics; two exits to Thermo Fisher and Illumina |
| William J. Greenleaf, PhD | Advisor — Prof. Genetics, Stanford | Single-molecule force spectroscopy (Block lab); co-inventor of ATAC-seq; parallel protein-binding assays |
{: #roster}

## 2. Commercial

### Michael Cola

The commercial-pharma heavyweight: the person who has sold drugs at scale and knows how big pharma buys.

- **AstraMerck → AstraZeneca** — product development and commercialization, rising through the ranks.
- **Safeguard Scientifics** — President of the Life Sciences Group for five-plus years. While there, Chairman and CEO of **Clarient**, a cancer diagnostics company, and Chairman of **Laureate Pharma**, a contract manufacturer.
- **Shire** — joined 2005 as EVP for Global Therapeutic Business Units; **President of Shire Specialty Pharmaceuticals, 2007 – April 2012**.
- **AEVI Genomic Medicine** — CEO and President from 2013. A genomics-driven drug developer, so he has lived the data-driven discovery pitch from the inside.
- Currently a director at **Vanda Pharmaceuticals**; has served on the board of **Sage Therapeutics**.

**Why he matters.** The rest of the board is science and government. Cola is the one covering *industry*. Specifically: credibility with pharma buyers, who are his peers; diagnostics operating experience via Clarient, which maps onto the clinical-diagnostics market; and public-company and M&A experience, which is what an investor reads as "this company knows what an exit looks like."

### Tim Germann

The only advisor whose day job is selling the closest thing to VSA that exists.

**Carterra** (formerly Wasatch Microfluidics, Salt Lake City) makes the **LSA** — a label-free, high-throughput antibody screening platform combining a microfluidic printhead with SPR. It runs hundreds of binding measurements in parallel from small sample volumes and reports k_on, k_off, K_D plus epitope binning across a whole antibody panel. Customers include Bristol Myers Squibb and Boehringer Ingelheim; PerkinElmer (now Revvity) invested in 2020.

**Why a CCO specifically.** A Chief Commercial Officer owns revenue — pricing, channel, customer relationships. What that brings is the **go-to-market playbook for this exact instrument category**: who holds the budget inside a pharma antibody group, what a placement costs, whether the business is instruments or consumables or service, how long the sales cycle runs, which conferences and opinion leaders matter. Hard to buy and hard to learn from outside.

**The question to have an answer ready for.** Carterra is simultaneously the nearest competitor and the nearest comparable. An investor will ask whether he is a channel or whether his employer is the competition. The honest answer is that the two products sit at different points in the workflow (see section 5), which makes a complementary story available: screen hundreds on an LSA, take the finalists to VSA.

*Caveat: Carterra and its business are well documented publicly; Germann's title and tenure are not. Confirm the bio line before it goes into anything external.*

## 3. Government

### Karyn Eliot

The national-security go-to-market advisor, and the specific role she held is unusually well matched.

Roughly 30 years across US national security science and technology — intelligence operations, acquisitions, policy, industry partnerships. Assignments listed publicly:

- **Director of Industry Partnerships, CIA Directorate of Science & Technology** — her most recent Agency role
- **Technology Lead**, Director of CIA's Operations Group
- **Senior Technical Representative**, Directorate of Operations
- **Deputy Director for Policy**, National Reconnaissance Office
- **Deputy Chief of Station for Technology**, European and DC regions

Now runs **Amplio Partners**, advising on government and commercial engagement across the national security community, and is a senior advisor to **Donovan Capital Group** (Tysons Corner, VA; positions itself as a capital partner to the Department of Defense).

**Why that résumé.** The Directorate of Science & Technology is CIA's technology arm — it builds and buys technical capability. "Director of Industry Partnerships" is, almost by definition, *the office whose function is connecting outside technology companies to agency needs*. Combined with the Deputy Chief of Station for Technology roles, she has seen both ends: how a capability is acquired in Washington, and how it behaves in the field.

She is the counterpart to Cola. He knows how pharma buys; she knows how the national-security customer buys — program offices, BAAs, OTAs, FFRDC intermediaries, multi-year budget cycles.

### Phil Ferro

**Not independently verifiable.** Searches for "Phil Ferro" / "Philip Ferro" in virology or biodefense return nothing relevant. Not a red flag by itself — career government scientists in policy roles often have no public footprint — but it means nothing here is confirmed beyond what the slide claims.

What the claimed profile would mean, decoded: **DoD** (defense), **DoS** (Department of State — the diplomatic side of biodefense: the Biological Weapons Convention, threat-reduction and biosecurity engagement abroad), **HHS** (the civilian health side, presumably ASPR/BARDA or CDC-adjacent), and **White House** (most likely a detail to the NSC or OSTP, where biodefense policy is coordinated across all of the above).

**Why the combination would be valuable.** Each of those is a different piece of one system, and almost nobody has sat in all four. DoD buys countermeasures for soldiers; HHS buys them for civilians and runs the stockpile; State negotiates the treaties; the White House arbitrates. Someone who has worked all four seats knows *which* agency has budget for a given capability and in what fiscal year — the hardest thing for a startup to learn from outside. Being an actual **virologist** on top of that means he can both evaluate the science and route it.

**Action:** get a sourceable bio with one concrete anchor — a programme, a role title. An advisor nobody can look up is worth less than one with a verifiable line.

### Bill Chen

**Also not independently verifiable** — the name is too common to disambiguate without an employer.

The claimed profile is an unusual hybrid: **hedge fund and VC** (understands how investors underwrite a company like this and what diligence probes), **national security background** (understands the government customer), and **FFRDC background** (has been inside one of the trusted-evaluator organisations, so knows how technology gets assessed on the government's behalf).

**Why that hybrid is the most useful one on the list.** Every other advisor is deep in one world. The company's thesis requires translating between two: the story is government money and credibility first, commercial market second, and investors are notoriously bad at valuing government revenue — long cycles, lumpy, non-recurring, hard to compare against software multiples. Someone who has sat on both the investment side and the national-security side can frame a defense contract in terms a VC will price correctly, and can say which government traction actually moves a valuation versus which merely looks good on a slide.

**Status note.** Bill is not an official part-time employee but in practice does part-timer-level work — more involved than a conventional advisory-board member. He is handling a specific external conversation on the company's behalf. He is *not* travelling to the DC meetings; only Kee-Hyun is. "Advisory Board" understates his actual involvement, though whether that belongs on a slide is a separate question.

**Action:** one verifiable anchor in the bio line — a named firm or a named FFRDC — turns an unsearchable name into a credential.

## 4. The measurement lineage

This is the strongest material on the slide and currently the least visible. The three Stanford scientists are not three interchangeable endorsements — they are **three consecutive steps of the same move**, and VSA is the fourth.

> Davis parallelised **DNA** measurement. Snyder parallelised **protein** measurement. Greenleaf parallelised **protein-binding** measurement. VSA adds **force**.

Two of the three are mentor and mentee out of the same Caltech lab, so the scientific judgment on this board comes from one coherent tradition: build the measurement, and the biology follows.

### Ronald W. Davis

- PhD at **Caltech** (1970), on DNA sequence arrangement studied by electron microscopy; postdoc at **Harvard with Jim Watson**; Stanford biochemistry from 1972; has directed the **Stanford Genome Technology Center** since 1994.
- **National Academy of Sciences** (1983). **Gruber Prize in Genetics** (2011), **Warren Alpert Foundation Prize** (2013), NAS Award in Molecular Biology, Rosenstiel Award, Dickson Prize, GSA Lifetime Achievement. **64+ biotechnology patents.**

Four contributions, and the pattern across them is the point:

1. **R-loop electron microscopy** — a method for mapping coding RNA that led directly to the discovery of **RNA splicing**.
2. **First demonstration, with Janet Mertz, of using restriction enzymes to join DNA fragments** — foundational to recombinant DNA.
3. **RFLP genetic linkage mapping** (1980, with Botstein, Skolnick and White) — the paper that made the **Human Genome Project** conceivable.
4. **The first DNA microarray** for gene-expression profiling, with Pat Brown.

Every one is a *measurement method*, not a biological finding.

**Why #4 is the one to lean on.** The microarray is the closest historical analogue to what VSA claims. Before it, gene expression was measured one gene at a time by Northern blot. Brown and Davis made it tens of thousands at once on a glass slide — the same underlying chemistry, massively parallelised — and it created an industry and changed how biology is done.

That is precisely VSA's story: force spectroscopy exists, AFM does it one bond at a time, and Erudio proposes to do it in parallel at enormous scale. **Having the person who did it for gene expression on the advisory board is a far stronger statement than his prize list.** If that connection is not made explicitly when the slide is presented, the best argument on the page is being left unsaid.

**One more thing worth knowing.** Since about 2009, after his son Whitney Dafoe became severely ill, Davis has redirected his work to ME/CFS — he founded Stanford's research centre for it in 2013 and chairs the scientific advisory board of the Open Medicine Foundation. In 2019 his team reported a "nanoneedle" blood-based diagnostic device that separated patients from controls in a small study.

So his current preoccupation is **building a new diagnostic instrument to detect a condition existing tests cannot see** — structurally the same as the clinical-diagnostics case. If there is a scientific conversation to be had with him, that is where the overlap is live rather than historical. It is also personal to him, which cuts both ways: deep engagement where it is relevant, limited bandwidth for anything that is not.

### Michael Snyder

- PhD at **Caltech in Norman Davidson's lab** — the same lab Davis came from — then **postdoc at Stanford under Davis**.
- **Stanford W. Ascherman Professor of Genetics**; **chaired the Genetics department until 2024**; directs the **Center for Genomics and Personalized Medicine**. Previously directed the Center for Genomics and Proteomics at Yale.
- Contributions: **RNA-Seq**, **ChIP-chip → ChIP-seq**, paired-end sequencing, **protein microarrays**, the **first multi-omics analysis of a human**, and leadership of the **ENCODE** production centre.

**Why he matters, in order:**

1. **Protein microarrays.** Davis parallelised DNA measurement; Snyder parallelised *protein* measurement. VSA is, structurally, a protein-interaction array with a force readout — so Snyder has already solved its hard engineering problems: surface chemistry, non-specific binding, readout, reproducibility.
2. **He builds companies out of measurement platforms, repeatedly.** Personalis, Qbio, January AI, Mirvie, Protos, SensOmics, Filtricine, Iollo — plus **Protometrix (acquired by Thermo Fisher)** and **Affomix (acquired by Illumina)**. Both exits went to instrument platform companies buying a measurement technology, which is the exact pattern on offer here. *State the two exits precisely rather than the count of ten; ten names reads as scattershot, two named acquirers reads as a repeatable pattern. And keep the claim at the level that can be sourced — individual outcomes across the other eight vary.*
3. **Multi-omics and continuous profiling.** His research thesis is that health comes from measuring many things about one person over time — the clinical-diagnostics market described from the scientific side.

### William J. Greenleaf

**The closest match to VSA's actual physics of anyone on the board, and nothing on the slide says so.**

- **A.B. Physics, Harvard** (2002); Dip. Computer Science, Trinity College, Cambridge (2003); **PhD in Applied Physics, Stanford** (2008), **advised by Steven Block**.
- Postdoc with X. Sunney Xie at Harvard (2008–2011) on sequencing-by-synthesis. Stanford Genetics faculty from 2011, tenured 2017.
- **NIH Director's Pioneer Award** (2023), E. Bright Wilson Prize (2017), CZI Fellow (2017–2023), Arc Institute Innovation Investigator, Rita Allen Scholar, Damon Runyon Fellow.

**1. He is a direct scientific descendant of single-molecule force spectroscopy.** Steven Block's lab is one of the places the field was built — optical traps measuring molecular motors step by step. Greenleaf's own thesis work built an optical trapping system resolving **RNA polymerase stepping along DNA at ångström resolution**. Same intellectual territory VSA operates in. He is the person on this list who can judge whether the force measurements are sound.

**2. He has already built a massively parallel binding-measurement platform out of an optical instrument.** His lab **repurposed Illumina sequencers for large-scale protein-binding assays** — anti-FLAG antibodies, Argonaute, CRISPR-associated proteins. Architecturally: an instrument with a flow cell and a camera, enormous numbers of immobilised molecules, a binding partner flowed in, optical readout across the whole surface at once. Remarkably close to VSA, minus the force axis.

**3. He models binding thermodynamics and kinetics.** A 2024 *Nature* study from his lab built thermodynamic and kinetic models linking transcription-factor binding microstates to gene expression — the bioTCAD side, not just the VSA side.

**4. He is also a physicist who moved into biology** — the same transition, one field over. Likely the easiest person on the board to have a direct technical conversation with.

**The conflict question to settle internally.** **Protillion Biosciences**, co-founded in 2019 to commercialise proteomics technology from his lab, raised a Series A in December 2022 led by **ARCH Venture Partners and Illumina Ventures**. He also co-founded **Epinomics** (2013, with Howard Chang), acquired by **10x Genomics** in 2018, and advises Guardant Health and Ultima Genomics.

Protillion is in high-throughput protein-interaction measurement. How close that sits to VSA is an internal judgment, but it is a sharper version of the Carterra question because the technology came out of the advisor's own lab. Be clear about what is in scope for conversations with him, what is not, and whether there is an IP boundary. Investors doing diligence on a Stanford spin-out ask who owns what.

## 5. VSA vs. Carterra LSA

Germann's presence makes this comparison unavoidable, so it is worth having stated precisely. The two are less similar than their one-line descriptions suggest.

| | **Carterra LSA (SPR)** | **VSA** |
|:--|:--|:--|
| Physics | Mass landing on a surface shifts the refractive index | Pull on bonds, time when they break |
| **What the sample must be** | **One purified analyte at known concentration** — required for specificity, and because k_on cannot be fitted without [analyte] | **Unpurified, unknown composition** |
| **Multiplexing axis** | The **library**: hundreds of distinct ligands, one analyte at a time → "which of my candidates binds this target?" | The **sample**: many targets read out of one sample at once → "what is in here?" |
| **Source of specificity** | Sample preparation — purify first, because the readout cannot separate specific binding from non-specific fouling | The measurement itself — non-specific sticking ruptures differently from a real bond |
| What you learn | k_on, k_off, K_D; epitope binning | The energy landscape: barrier structure, bond lifetime under load, a distribution rather than an average |
| Where it sits | Upstream R&D — discovery screening | Characterisation, equivalence, and detection in real samples |
| Maturity | Shipping for years, installed base, reviewers know how to read SPR data | Pre-commercial; a new method carrying a validation burden |
{: #lsa}

**The two middle rows are the investor-facing ones.** They say the company is not a faster version of an existing instrument but a measurement that works where the existing one structurally cannot — for a reason that is a property of the physics, not an engineering gap someone could close.

**The maturity row is the honest counterweight**, and it is better stated voluntarily than discovered on a diligence call.

Three positioning rules that follow:

1. **Do not claim throughput against SPR.** On distinct pairs screened, Carterra wins and has for years. The honest benchmark for the ~1,000× figure is **single-molecule DFS (AFM)** — the technique that actually produces this data today, one bond at a time. Concretely: a full survival curve for one binding pair takes **two weeks or more** by AFM and **30 minutes** here.
2. **Do not claim "label-free."** The term means no reporter tag; a capture antibody is not a label. A fluorescence readout is not label-free. If no conjugation of the customer's own molecule is required, the accurate and equally strong claim is **"no labelling of your sample required"** or "no sample preparation or conjugation step."
3. **Use the complementary story.** Screen hundreds on an LSA, take the finalists to VSA. It turns an awkward question about Germann into a partnership answer.

Carterra's own history is also a useful precedent to cite: a company that took a well-understood binding measurement, parallelised it with microfluidics, built a real business selling into pharma antibody groups, and ended with a strategic investor on the cap table. Same market, same buyers, demonstrated willingness to pay.

## 6. Accuracy flags for the slide

Each of these is the kind of thing a diligence call checks.

| Item | Problem | Fix |
|:--|:--|:--|
| "Former President of Shire plc" (Cola) | He was President of *Shire Specialty Pharmaceuticals*, one business unit — a big job, not president of the company | "Former President, Shire Specialty Pharmaceuticals" |
| "($62B sale to Takeda)" (Cola) | He left in April 2012; the acquisition closed January 2019, seven years later | "(Shire later sold to Takeda for $62B)" — signals the calibre of company without implying he ran the sale |
| "$15B+ technology start-up exits" (Davis) | Not verifiable from public sources; no company list or exit values published | Name two or three actual companies, or drop the number |
| "Dir. Stanford Human Genome Center" (Snyder) | The centre he directs is the **Center for Genomics and Personalized Medicine** | Correct the name |
| "Prof. Genetics" (Snyder) | Undersells a former department chair | "Former Chair, Department of Genetics, Stanford" |
| "Prof. Genetics and Applied Physics" (Greenleaf) | His appointment is in Genetics; Applied Physics is where his PhD is from | Confirm whether he holds a courtesy appointment; otherwise just Genetics |
| Greenleaf's one-line description | He is the only advisor whose expertise is VSA's core physics, and the line does not say so | "Co-inventor of ATAC-seq; single-molecule force spectroscopy (Block lab); NIH Director's Pioneer Award" |
| "DoD" here vs. "DoW" elsewhere in the deck | Mixed usage reads as slides assembled at different times | Pick one and use it throughout |
| CIA seal | A retired officer as advisor confers no right to display the Agency's seal; unauthorised use of a federal agency seal is restricted and reads as implying official endorsement | Remove it |
| Named serving officials | A serving program director named in material that circulates to investors | Confirm permission was asked |

**And the structural point.** For three world-class scientists and three serious government operators, every description is one positional line. The slide says *who they are* and never *why they are on this board*. Reorganising the page around the three groups above, with one relevance clause each, would turn a name list into an argument — and would surface the Davis-microarray and Snyder-protein-array parallels, which are the most persuasive material available and currently appear nowhere.
