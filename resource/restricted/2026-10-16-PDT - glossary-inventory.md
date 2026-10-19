---
date: Fri Oct 16 23:35:00 PDT 2026
last_modified_at: Sun Oct 18 21:46:59 PDT 2026
layout: single
title: "Erudio Glossary Inventory"
permalink: /glossary/inventory/erudio
categories:
 - glossary
tags:
 - glossary
 - Erudio Bio
 - biotech
toc: true
toc_label: "&nbsp;Table of Contents"
toc_icon: "fa-solid fa-book"
toc_sticky: true
author_profile: true
---

posted: {{ page.date| date: "%d-%b-%Y" }}
&amp;
updated: {{ page.last_modified_at| date: "%d-%b-%Y" }}
{: .notice--primary}

<!--style>
	.page__content table {
	  font-size: calc(var(--body-font-size) * 0.75);
	}
</style-->

<style>
	.page__content table {
		font-size: calc(var(--body-font-size) * 0.85);
		font-family: inherit;
	}

	#glossary { display: table; width: 100%; table-layout: fixed; }
	#glossary th:nth-child(1) { width: 7%; }
	#glossary th:nth-child(2) { width: 18%; }
	#glossary th:nth-child(3) { width: 55%; }
	#glossary th:nth-child(4) { width: 20%; }
	.page__content th { text-align: center !important; }
</style>

Prepared by Sunghee Yun (Co-Founder & CTO) · personal study notes

# Erudio Glossary Inventory

Working inventory of terms from biologics, binding kinetics, and US biodefense and regulatory policy. Short descriptions only; full explanations are built separately.

## 1. Glossary

Sorted case-insensitively. CDC appears twice on purpose — two different terms that share an acronym.

| # | Term | Stands for / one-liner | Note |
|:-:|:-:|:--|:--|
| 1 | 510(k) | FDA premarket notification pathway for devices substantially equivalent to an existing one |  |
| 2 | adalimumab | molecule in Humira; anti-TNF-α IgG |  |
| 3 | ADCC | antibody-dependent cellular cytotoxicity — NK cell grabs Fc, kills the target cell |  |
| 4 | AFM | atomic force microscopy |  |
| 5 | analyte | the molecule being measured (in SPR/BLI, the one in solution) |  |
| 6 | ARPA-H | Advanced Research Projects Agency for Health |  |
| 7 | ASPR | Administration for Strategic Preparedness and Response (HHS; owns the SNS since 2018) |  |
| 8 | B cell | lymphocyte that makes antibodies |  |
| 9 | BAA | Broad Agency Announcement — open call for research proposals |  |
| 10 | beachhead | military: the first strip of shore captured and held in an invasion, from which to push inland; business: the first small, winnable market used as the base for expanding into the big one | 교두보 |
| 11 | BLI | bio-layer interferometry |  |
| 12 | CBRN | chemical, biological, radiological, nuclear |  |
| 13 | CBRND | Chemical, Biological, Radiological, Nuclear Defense |  |
| 14 | CDC (agency) | Centers for Disease Control and Prevention |  |
| 15 | CDC (immunology) | complement-dependent cytotoxicity — C1q binds clustered Fc, cascade punches a pore |  |
| 16 | CDER | FDA Center for Drug Evaluation and Research — reviews drugs incl. biosimilars; Erudio's biosimilar/RFI work is with this center |  |
| 17 | CDRH | FDA Center for Devices and Radiological Health — reviews devices incl. IVDs via 510(k); the center a VSA clinical-diagnostics clearance goes through; separate reviewers from CDER |  |
| 18 | CHO | Chinese hamster ovary (cells) — the default factory for antibody drugs |  |
| 19 | CPE | Capability Program Executive — DoD/DoW acquisition role and office named by the portfolio it manages; see CPE CBRND |  |
| 20 | CPE CBRND | Capability Program Executive for Chemical, Biological, Radiological and Nuclear Defense — manages DoW's CBRN defense equipment and medical countermeasures for the Joint Force; formerly JPEO-CBRND |  |
| 21 | Crohn's disease | autoimmune inflammation of the gut; treated with anti-TNF |  |
| 22 | cytokine | small immune-signaling protein (TNF-α, IL-6, …) |  |
| 23 | DFS | dynamic force spectroscopy |  |
| 24 | DOE | U.S. Department of Energy | 미국 에너지부. Despite the name, a top US science funder — runs the 17 national labs and the biggest supercomputers (Frontier, Aurora, El Capitan), hence owns the Genesis Mission; nuclear-weapons stewardship is why it shows up in national-security contexts |
| 25 | DoW | Department of War |  |
| 26 | DTRA | Defense Threat Reduction Agency |  |
| 27 | ELISA | enzyme-linked immunosorbent assay |  |
| 28 | EMA | European Medicines Agency |  |
| 29 | Fab | fragment, antigen-binding — the two arms of the Y |  |
| 30 | Fc | fragment, crystallizable — the stem of the Y that talks to the immune system |  |
| 31 | FDA | Food and Drug Administration |  |
| 32 | FFRDC | Federally Funded Research and Development Center (e.g., Johns Hopkins APL) |  |
| 33 | Genesis Mission | DOE AI-for-science initiative (Executive Order, Nov 24 2025) |  |
| 34 | globulin | globular blood proteins; antibodies are the gamma fraction |  |
| 35 | glycosylation | sugar chains attached to a protein after synthesis; process-dependent, not in the gene |  |
| 36 | HCP | host-cell protein — CHO proteins that must be purified out |  |
| 37 | HELP | Senate Health, Education, Labor, and Pensions committee |  |
| 38 | Herceptin | trastuzumab (Genentech/Roche); anti-HER2 |  |
| 39 | HHS | Department of Health and Human Services |  |
| 40 | homeostasis | the body's self-regulation toward a stable internal state |  |
| 41 | Humira | AbbVie's brand of adalimumab | full story: AbbVie, adalimumab, 2023 US biosimilar entry, PBM rebates |
| 42 | IgG | immunoglobulin G — the main antibody class in blood and the class nearly all antibody drugs belong to |  |
| 43 | immunoglobulin | formal name for antibody (Ig) |  |
| 44 | IND | Investigational New Drug (application) — FDA permission to dose humans |  |
| 45 | INN | International Nonproprietary Name — the generic drug name (e.g., adalimumab) |  |
| 46 | IVD | in vitro diagnostics — tests on a sample taken out of the body, vs. in vivo; VSA is an IVD device, regulated by FDA's device center via 510(k); global market ~$100–130B | 체외진단; device category 체외진단의료기기 |
| 47 | junk DNA | the ~98% of the genome that doesn't code for protein |  |
| 48 | K_D | equilibrium dissociation constant — k_off / k_on |  |
| 49 | k_off | dissociation rate constant |  |
| 50 | k_on | association rate constant |  |
| 51 | Keytruda | pembrolizumab (Merck); anti-PD-1 checkpoint inhibitor |  |
| 52 | ligand | (biochemistry) molecule that binds a target; (SPR/BLI) the molecule immobilized on the sensor | both senses |
| 53 | metagenomics | sequencing all genetic material in a sample at once |  |
| 54 | monoclonal antibody | one identical antibody made by one cell clone |  |
| 55 | NCATS | National Center for Advancing Translational Sciences |  |
| 56 | NCI | National Cancer Institute |  |
| 57 | NIH | National Institutes of Health |  |
| 58 | NK cell | natural killer cell — the executioner in ADCC |  |
| 59 | nucleic acids | DNA and RNA collectively — the information molecules, chains of four nucleotides; contrast with proteins, chains of twenty amino acids | 핵산 |
| 60 | OCET | FDA Office of Counterterrorism and Emerging Threats | inside FDA's Office of the Chief Scientist; home of MCM / CBRN / stockpile work |
| 61 | oligo | oligonucleotide — short synthetic DNA/RNA strand |  |
| 62 | ONC | Office of the National Coordinator for Health IT |  |
| 63 | Operation TrialBlazer | HHS initiative (June 22 2026) to speed trials/INDs; applications Sept 15–Oct 30 2026 |  |
| 64 | OPHPR | Office of Public Health Preparedness and Response | under CDC, not FDA |
| 65 | OTA | Other Transaction Authority — flexible federal contracting outside the FAR |  |
| 66 | PBM | pharmacy benefit manager — negotiates drug prices and rebates for insurers |  |
| 67 | PCR | polymerase chain reaction — amplifies a target DNA/RNA sequence so trace amounts become detectable; sees genetic material only, so blind to toxins and to live-vs-dead (BioFire FilmArray is the fielded incumbent) |  |
| 68 | psoriasis | autoimmune skin disease; treated with anti-TNF |  |
| 69 | QRI | Qualified Research Institution — FDA Expedited IND Pilot term |  |
| 70 | residual DNA | leftover host-cell DNA in the drug product; limited by regulators |  |
| 71 | RFI | Request for Information — questions only, no money |  |
| 72 | RFP | Request for Proposals — a deliverable to bid on |  |
| 73 | SBIR | Small Business Innovation Research (grants) |  |
| 74 | SLEP | Shelf-Life Extension Program |  |
| 75 | SPR | surface plasmon resonance |  |
| 76 | Strategic National Stockpile | SNS — federal reserve of medical countermeasures, run by ASPR |  |
| 77 | T cell | lymphocyte that kills infected cells or directs other immune cells |  |
| 78 | VSA | Versatile Smart Assay (Erudio's platform) |  |
{: #glossary}

## 2. Biophysics Intuitions

The same quantity seen from several angles — several important readings, not an exhaustive list.

| Term | Ways to read it |
|:-:|:--|
| K_D | (1) Balance equation: k_on [A][B] = k_off [AB] — count × frequency on each side.<br>(2) [B]_free = K_D × [AB]/[A]_free — K_D is the price per unit of bound-to-free odds.<br>(3) Net binding rate: d[AB]/dt = k_on ([A][B] − K_D [AB]) — K_D is the zero-crossing, k_on sets the speed.<br>(4) Fraction bound = [drug]/([drug] + K_D) — unit-free; [drug] ≈ total drug when drug is in excess (favorite). |

## 3. The six biosimilar bills

Four Senate bills plus two House companions, all in the 119th Congress (Jan 2025 – Jan 2027; anything not passed by then dies and must be reintroduced). "S." = Senate bill, "H.R." = House bill; a bill must pass both chambers in identical form, which is why companion bills are introduced in parallel. Health bills go through the Senate HELP committee (House: Energy and Commerce); the antitrust bill went to Judiciary instead. Statuses as of July 2026 — re-verify before citing.

| Bill | Name | Sponsors | What it does | Status | Relevance to VSA |
|:--|:--|:--|:--|:--|:--|
| S.1414 / H.R. 9661 | Expedited Access to Biosimilars Act | Senate: Paul (R-KY), Lee (R-UT), Hassan (D-NH). House (introduced July 15, 2026): Langworthy (R-NY), Schrier (D-WA) | Removes the default requirement that a biosimilar applicant run a comparative clinical efficacy study; FDA keeps the authority to require one case by case | Ordered reported by HELP, July 22, 2026 | **The one that creates VSA's market.** If clinical trials are no longer the default, *analytical* proof of equivalence becomes the whole case — the gap VSA claims to fill (testing burden) |
| S.1954 / H.R. 5526 | Biosimilar Red Tape Elimination Act | Senate: Lee (R-UT), Luján (D-NM), Paul, Hassan, Schmitt, Ossoff. House (Sept 2025): Pfluger (R-TX), Landsman (D-OH) | Deems every FDA-licensed biosimilar *interchangeable* with its reference product, so pharmacists can substitute automatically; no more switching studies. Preserves exclusivity already earned by first interchangeables | Introduced in three consecutive Congresses; this time ordered reported favorably by HELP June 17, 2026 and placed on the Senate calendar July 27 | Attacks *substitution friction* (the Humira-era barrier), not testing. Raises the stakes on equivalence: if every approved biosimilar can be auto-swapped, "are these two truly the same?" becomes a patient-level question — a stronger argument for a rigorous functional test |
| S.1096 | Preserve Access to Affordable Generics and Biosimilars Act | Klobuchar (D-MN), Grassley (R-IA) + eight cosponsors (5 D, 3 R) | Bans *pay-for-delay*: any settlement in which the brand gives a generic/biosimilar maker anything of value (cash, or a promise not to launch an authorized generic) in exchange for delaying entry is presumed anticompetitive; FTC enforces | Ordered reported by Judiciary, April 3, 2025 — earliest to clear committee; earlier versions passed the Senate and died in the House | Antitrust, not science — VSA does not address it. Explains part of why Humira biosimilars were held off until 2023 (AbbVie settled every challenger on a 2023 date). Part of the "system is rigged, Congress is unrigging it" story, not the VSA pitch |
| S.3510 | Biosimilar Inspection Modernization Act of 2025 | Budd (R-NC), Hassan (D-NH) | Expands remote regulatory assessments, convenes a meeting on mutual recognition agreements with foreign regulators, requires an FDA plan on domestic inspections | Has not moved | Manufacturing-inspection logistics; peripheral to VSA |

One line to hold onto: the bills attack three different things — **testing burden** (S.1414), **substitution friction** (S.1954), **anticompetitive deals** (S.1096) — plus inspections (S.3510). Only the first is VSA's tailwind directly; the others raise demand for biosimilars, which raises demand for a fast equivalence test. Often cited alongside them, but not bills: FDA's Oct 29, 2025 announcement on dropping clinical efficacy studies for some biosimilars, the Langworthy/Schrier press release, and David Lim's Politico piece (July 21, 2026) on Hill momentum.

## 4. Key Contrasts

Short passages worth keeping whole — each one a distinction that decides what VSA can claim.

### PCR vs. VSA

PCR (polymerase chain reaction) is the DNA-copying technique behind COVID tests: it amplifies a target gene sequence millions of times so even a few copies become detectable. That's the key to its strength *and* its limit — it detects genetic material, so it can't see toxins (botulinum, ricin — proteins, no DNA) and can't tell whether what it found is alive or active. That's the contrast VSA wants to draw.

### BioFire vs. VSA

BioFire FilmArray (bioMérieux; the US military's fielded biothreat panel) is sample-to-answer PCR — about 2 minutes hands-on, result in about an hour — so "heavy sample prep" is not its weakness. Its real limits are that it's PCR, so it only sees nucleic acids (not toxins, not protein agents, not whether an agent is still active); it needs power and a controlled environment; and it runs one cartridge per panel. The accurate knock, and VSA's actual advantage: it detects genes, not function — it can't tell a live threat from dead material or see toxins.
