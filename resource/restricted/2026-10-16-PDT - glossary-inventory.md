---
date: Fri Oct 16 23:35:00 PDT 2026
last_modified_at: Sun Oct 25 01:50:13 PDT 2026
layout: single
title: "Biotech, Biophysics and Regulatory Glossary"
permalink: /glossary/inventory/erudio
categories:
 - glossary
tags:
 - glossary
 - biotech
 - biophysics
 - regulatory
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
	#glossary th:nth-child(1) { width: 5%; }
	#glossary th:nth-child(2) { width: 16%; }
	#glossary th:nth-child(3) { width: 61%; }
	#glossary th:nth-child(4) { width: 18%; }
	.page__content th { text-align: center !important; }
</style>

Prepared by Sunghee Yun (Co-Founder & CTO) · personal study notes

# Biotech, Biophysics and Regulatory Glossary

Terms from biologics and antibody engineering, binding kinetics and single-molecule biophysics, and US biodefense and drug-regulatory policy. Written for someone coming to the field from outside it.

## 1. Glossary

Sorted case-insensitively. CDC appears twice on purpose — two unrelated terms that share an acronym. Entries that belong together as a pair (brand and INN, technique and instrument, acronym and its counterpart) are cross-referenced in the Note column.

| # | Term | Explanation | Note |
|:-:|:-:|:--|:--|
| 1 | 510(k) | FDA's premarket notification pathway for medical devices. Instead of proving safety and effectiveness from scratch, the applicant shows the device is *substantially equivalent* to one already legally marketed (the "predicate"). Far faster and cheaper than a full premarket approval, and the usual route for a new diagnostic instrument. |  |
| 2 | adalimumab | The antibody molecule sold as Humira. An anti-TNF-α IgG: it binds and neutralizes tumor necrosis factor alpha, a cytokine that drives inflammation. Used in rheumatoid arthritis, Crohn's disease and psoriasis. | the INN; Humira is the brand |
| 3 | ADCC | **Antibody-dependent cellular cytotoxicity.** An antibody coats a target cell; an NK cell grabs the antibody's Fc stem through its Fcγ receptor and kills the target. One of the two main ways an antibody drug destroys a cell rather than merely blocking it. | pairs with CDC (immunology) |
| 4 | AFM | **Atomic force microscopy.** A sharp tip on a flexible cantilever is brought to a surface; the cantilever's deflection measures force at the piconewton scale. Used for imaging, and — with a molecule tethered between tip and surface — for pulling single bonds apart. |  |
| 5 | analyte | The molecule being measured. In SPR and BLI it is specifically the one flowed in solution over the sensor, as opposed to the ligand immobilized on it. | pairs with ligand |
| 6 | APL | **Johns Hopkins University Applied Physics Laboratory** (Laurel, Maryland) — the largest university-affiliated FFRDC, working across defense, space and health technology. |  |
| 7 | ARPA-H | **Advanced Research Projects Agency for Health.** Created in 2022 inside HHS and modeled on DARPA: program managers with their own authority and budget place bets and kill them, instead of peer review deciding. PM terms run 3–5 years. Uses OTA-style flexible agreements and funds platforms and capabilities, where NIH tends to fund hypothesis-driven biology. |  |
| 8 | ASPR | **Administration for Strategic Preparedness and Response**, inside HHS. Runs US medical preparedness and has owned the Strategic National Stockpile since 2018. BARDA sits within it. |  |
| 9 | B cell | The lymphocyte that makes antibodies. Each B cell produces one antibody specificity; on activation it multiplies and its descendants secrete that antibody in quantity. Class switching happens here. |  |
| 10 | BAA | **Broad Agency Announcement.** An open federal call for research proposals in a stated area, rather than a solicitation for a specific deliverable. One of the two realistic doors into defense research money for a small company, alongside an OTA. |  |
| 11 | BARDA | **Biomedical Advanced Research and Development Authority**, inside ASPR at HHS. Funds the advanced development of medical countermeasures — the stretch between a research result and something the government can buy — and purchases for the Strategic National Stockpile. |  |
| 12 | beachhead | Military: the first strip of shore captured and held in an invasion, from which to push inland. Business: the first small, winnable market, taken deliberately as the base for expanding into a larger one. | 교두보 |
| 13 | BLI | **Bio-layer interferometry.** A label-free binding method: molecules accumulating on the tip of a fiber-optic probe change the thickness of a layer, shifting an interference pattern. Gives k_on, k_off and K_D. Probe dips into a well rather than fluid flowing past a chip, which is the main practical difference from SPR. |  |
| 14 | CBRN | **Chemical, biological, radiological, nuclear** — the four classes of mass-casualty threat agent. |  |
| 15 | CBRND | **Chemical, Biological, Radiological, Nuclear Defense** — the defense mission covering those four threat classes. |  |
| 16 | CDC (agency) | **Centers for Disease Control and Prevention**, the US public-health agency, based in Atlanta. Held the Strategic National Stockpile until it moved to ASPR in 2018. | not the immunology CDC below |
| 17 | CDC (immunology) | **Complement-dependent cytotoxicity.** C1q binds a cluster of antibody Fc stems on a target cell, triggering the complement cascade, which assembles a pore in the cell membrane and kills it. The other main antibody killing mechanism alongside ADCC. | not the agency above |
| 18 | CDER | **FDA Center for Drug Evaluation and Research.** Reviews drugs, including biosimilars. Monoclonal antibodies moved here from CBER in 2003. | one of FDA's centers |
| 19 | CDRH | **FDA Center for Devices and Radiological Health.** Reviews medical devices, including in vitro diagnostics via the 510(k) pathway. Separate staff and standards from CDER. | one of FDA's centers |
| 20 | CHO | **Chinese hamster ovary** cells — the default production cell line for antibody drugs since the 1980s. The line dates to 1957 (Theodore Puck). Grows in suspension, takes human-like glycosylation, and does not support most human viruses, which simplifies viral safety. |  |
| 21 | CPE | **Capability Program Executive.** A US defense acquisition role and office, named by the portfolio it manages — the same naming pattern as the older PEO (Program Executive Office). The letters denote both the office and the person heading it. | see CPE CBRND |
| 22 | CPE CBRND | **Capability Program Executive for Chemical, Biological, Radiological and Nuclear Defense.** Manages US investment in CBRN defense equipment and medical countermeasures for the Joint Force. One of four components of the Chemical and Biological Defense Program. Formerly JPEO-CBRND. | renamed; many still say JPEO-CBRND |
| 23 | Crohn's disease | Chronic autoimmune inflammation of the gut, anywhere from mouth to anus but most often the terminal ileum. Treated with anti-TNF antibodies among other things. |  |
| 24 | CWMD | **Countering Weapons of Mass Destruction Office** — DHS's biodefense arm. Runs BioWatch, the national environmental biosurveillance programme, which has been criticised for slow turnaround and false alarms. |  |
| 25 | cytokine | A small signalling protein of the immune system — TNF-α, the interleukins, the interferons. Cells release them to instruct other cells; blocking one is how several antibody drugs work. |  |
| 26 | DFS | **Dynamic force spectroscopy.** Pull on a bond at a known loading rate and record the force at which it breaks; repeat many times and the distribution of rupture forces reveals the energy landscape — barrier heights and positions — not just the equilibrium affinity. Conventionally done one bond at a time by AFM. |  |
| 27 | DHS | **Department of Homeland Security.** Created in 2002 from 22 merged agencies. For biodefense the relevant parts are CWMD and the Science & Technology Directorate. Has its own budget and OTA authority. |  |
| 28 | DoD | **Department of Defense** — the long-standing name for the same department now also called the Department of War. | do not mix DoD and DoW in one document |
| 29 | DOE | **U.S. Department of Energy.** Despite the name, one of the largest US science funders: it runs the 17 national laboratories (Oak Ridge, Argonne, Livermore, Berkeley, Los Alamos and others) and the biggest US supercomputers — Frontier, Aurora, El Capitan. Hence it owns the Genesis Mission. Nuclear-weapons stewardship is why it appears in national-security contexts. | 미국 에너지부 |
| 30 | DoS | **Department of State** — the US foreign ministry. In biodefense it owns the diplomatic side: the Biological Weapons Convention, threat-reduction and biosecurity engagement programmes abroad. |  |
| 31 | DoW | **Department of War** — the current name of the US defense department, formerly and still widely called the Department of Defense (DoD). | see DoD |
| 32 | DTRA | **Defense Threat Reduction Agency** — the US defense agency responsible for countering weapons of mass destruction. |  |
| 33 | ELISA | **Enzyme-linked immunosorbent assay.** An antibody captures the target on a plate; a second, detection antibody carrying an enzyme binds it and turns a substrate colourful. The workhorse protein assay — cheap, sensitive, and labelled, which is why it reports presence and amount but not binding kinetics. |  |
| 34 | EMA | **European Medicines Agency** — the EU's drug regulator, based in Amsterdam. The European counterpart to FDA's drug centers. |  |
| 35 | Fab | **Fragment, antigen-binding** — the two arms of the antibody Y, each ending in the variable region that grips the target. Fab binding is what gives an antibody its specificity. | pairs with Fc |
| 36 | FAR | **Federal Acquisition Regulation** — the rulebook governing ordinary US federal procurement: cost-accounting standards, audit rights, mandatory clauses, bid protests. Its overhead is why OTAs exist as an alternative, and its IP clauses can give the government broad rights in contractor technical data. | pairs with OTA |
| 37 | Fc | **Fragment, crystallizable** — the stem of the antibody Y. It carries no target specificity; instead it talks to the immune system, binding Fcγ receptors on NK cells (ADCC), C1q (CDC) and FcRn (which recycles the antibody and gives it a long half-life). Carries the N297 glycan. | pairs with Fab |
| 38 | FDA | **Food and Drug Administration** — the US regulator for drugs, biologics, devices, food and tobacco. Organised into centers: CDER (drugs), CBER (vaccines, blood, gene therapy), CDRH (devices). |  |
| 39 | FFRDC | **Federally Funded Research and Development Center.** A nonprofit funded by the government to supply long-term technical expertise in the public interest. The defining condition is that it may not compete with industry and has no commercial stake, which is what lets it see vendors' proprietary information and advise the agency honestly. Examples: Johns Hopkins APL, MITRE, RAND, MIT Lincoln Laboratory, the DOE national labs. In practice they are the government's trusted technical evaluators — gatekeepers, and potentially advocates. |  |
| 40 | Genesis Mission | A US Department of Energy initiative to apply AI to scientific discovery, established by executive order on 24 November 2025. Sits at DOE because the national labs and the largest supercomputers are already there. |  |
| 41 | globulin | A family of globular blood proteins, historically separated from albumin by solubility. Antibodies are the gamma fraction — hence "gamma globulin" and "immunoglobulin". |  |
| 42 | glycosylation | Sugar chains attached to a protein after it is built. Not encoded in the gene: the pattern depends on the producing cell and the process conditions, which is why two manufacturers' versions of the same antibody can differ. On IgG the key site is N297 on the Fc, where the glycan shapes how strongly the antibody engages Fcγ receptors and complement. |  |
| 43 | HCP | **Host-cell protein** — proteins made by the production cell line (usually CHO) that must be purified away from the drug. Residual levels are measured by an ELISA raised against the whole host-cell proteome, not against one protein. |  |
| 44 | HELP | The US Senate Committee on **Health, Education, Labor, and Pensions** — jurisdiction over FDA, drugs and public health, so health legislation passes through it first. The House counterpart is Energy and Commerce. |  |
| 45 | Herceptin | Trastuzumab (Genentech/Roche) — an anti-HER2 antibody for HER2-positive breast cancer. Works partly by blocking HER2 signalling and partly by Fc-mediated killing (ADCC). Known for cardiotoxicity (심장독성). |  |
| 46 | HHS | **Department of Health and Human Services** — the US federal health department. FDA, CDC, NIH, ASPR and BARDA all sit under it. |  |
| 47 | homeostasis | The body's self-regulation toward a stable internal state — temperature, pH, glucose, ion balance — through feedback. |  |
| 48 | Humira | AbbVie's brand of adalimumab, and the reference case for why US biosimilars did not cut prices. AbbVie was spun out of Abbott in 2013. US biosimilar entry finally came in January 2023, from Amgen, Sandoz, Samsung Bioepis, Celltrion and others — the date set by patent settlements rather than by science. Even then savings were slow, because AbbVie's rebates to pharmacy benefit managers kept the net cost of Humira competitive and because plain biosimilars could not be substituted at the counter without an interchangeability designation. | 브랜드명; molecule = adalimumab |
| 49 | IgG | **Immunoglobulin G** — the main antibody class in blood and the class nearly all antibody drugs belong to. Two heavy chains and two light chains in a Y, two Fab arms and one Fc stem. |  |
| 50 | immunoglobulin | The formal name for an antibody, abbreviated Ig. Classes: IgG, IgA, IgM, IgD, IgE. | 면역글로불린 |
| 51 | IND | **Investigational New Drug** application — FDA permission to give an experimental drug to humans. Filed before clinical trials; FDA has 30 days to object. |  |
| 52 | INN | **International Nonproprietary Name** — the generic name of a drug substance, assigned by the WHO and the same worldwide. Antibodies end in *-mab*; the preceding syllables encode the target and the source. | e.g. adalimumab vs brand Humira |
| 53 | IVD | **In vitro diagnostics** — tests performed on a sample taken out of the body (blood, urine, swab, tissue), as opposed to *in vivo*. In the US, IVDs are regulated by FDA's device center, typically via 510(k). Global market roughly $100–130B. | 체외진단; 체외진단의료기기 |
| 54 | junk DNA | The roughly 98% of the human genome that does not code for protein. The name has aged badly: much of it is regulatory, structural or transcribed, which is what the ENCODE project set out to map. |  |
| 55 | K_D | **Equilibrium dissociation constant** — k_off / k_on. Units of concentration (M). It is the free-partner concentration at which half the target is occupied, and it says where a binding reaction settles, not how fast it gets there. See *Biophysics Intuitions* below for the readings that make it intuitive. | 비교는 자유 농도 또는 다른 쌍의 K_D와 — never against 1 |
| 56 | k_off | **Dissociation rate constant.** Units s⁻¹ — a frequency. How often a given bound pair comes apart, per second. It needs no partner: a bound complex breaks on its own schedule, which is why k_off does not depend on concentration. | pairs with k_on |
| 57 | k_on | **Association rate constant.** Units M⁻¹s⁻¹. Not a frequency on its own — it is a per-encounter sticking coefficient, which becomes a frequency only when multiplied by a partner concentration: k_on × [partner] has units of s⁻¹. That is why binding depends on concentration and unbinding does not. | pairs with k_off |
| 58 | Keytruda | Pembrolizumab (Merck) — an anti-PD-1 checkpoint inhibitor. It does not attack the tumour; it blocks a brake that tumours use to switch off T cells, releasing the immune response. Among the best-selling drugs in the world. |  |
| 59 | ligand | Two senses, which is why context matters. In biochemistry, any molecule that binds a target — the drug, the hormone, the substrate. In SPR and BLI, specifically the molecule immobilised on the sensor surface, as opposed to the analyte flowed over it. | both senses in use |
| 60 | metagenomics | Sequencing all the genetic material in a sample at once, without culturing or isolating organisms first, then working out what is present from the sequences. |  |
| 61 | MITRE | A nonprofit FFRDC operator running several federally funded centers for DoD, FAA, IRS, CMS and the intelligence community. Known outside government for the ATT&CK and CVE security catalogues. |  |
| 62 | monoclonal antibody | One identical antibody, produced by the descendants of a single cell clone — hence a defined molecule that can be manufactured and regulated as a drug, unlike the mixture obtained from an immunised animal. | 단일클론항체 |
| 63 | NCATS | **National Center for Advancing Translational Sciences** — the NIH institute for the machinery of getting discoveries from lab to clinic, rather than for any one disease. |  |
| 64 | NCI | **National Cancer Institute** — the largest of the NIH institutes. |  |
| 65 | NIH | **National Institutes of Health** — the main US funder of biomedical research, made up of 27 institutes and centers, in Bethesda, Maryland. |  |
| 66 | NK cell | **Natural killer cell** — a lymphocyte that kills without prior sensitisation. In ADCC it is the executioner: it binds the Fc stems of antibodies coating a target cell and destroys it. |  |
| 67 | nucleic acids | DNA and RNA collectively — the information molecules, long chains of four nucleotides. Contrast with proteins, chains of twenty amino acids. The distinction matters for detection: a method that reads nucleic acids cannot see a protein toxin. | 핵산 |
| 68 | OCET | **FDA Office of Counterterrorism and Emerging Threats** — sits inside FDA's Office of the Chief Scientist and is FDA's home for medical countermeasures, CBRN preparedness and stockpile questions. |  |
| 69 | oligo | **Oligonucleotide** — a short synthetic strand of DNA or RNA, typically tens of bases, made to order. Used as primers, probes, tethers and therapeutics. |  |
| 70 | ONC | **Office of the National Coordinator for Health Information Technology** — the HHS office for health-data standards and interoperability. |  |
| 71 | Operation TrialBlazer | An HHS initiative announced 22 June 2026 to speed clinical trials and IND review; applications ran 15 September – 30 October 2026. |  |
| 72 | OPHPR | **Office of Public Health Preparedness and Response.** Sits under **CDC**, not FDA — worth noting, because the two are easily conflated in writing about preparedness. | under CDC |
| 73 | OSTP | **Office of Science and Technology Policy** — in the Executive Office of the President. Advises the President on science and technology and coordinates science policy across agencies; its Director usually serves as the President's science advisor. |  |
| 74 | OTA | **Other Transaction Authority.** Congress gave certain agencies (DoD/DoW, DHS, NASA, NIH, ARPA-H) authority to enter agreements that are legally *not* procurement contracts, grants or cooperative agreements — and so are not bound by the FAR. Used mainly for prototype projects, with a path to follow-on production. For a small company the three attractions, in order: **intellectual property terms are negotiable** rather than set by FAR clauses; the timeline runs in months rather than years; and many OTAs run through consortia, which lowers the overhead of competing. | pairs with FAR |
| 75 | PBM | **Pharmacy benefit manager** — the intermediary that negotiates drug prices for insurers and employers. Manufacturers pay rebates off list price to secure formulary position, so a drug's *net* cost can be far below its list price. This is the mechanism that blunted Humira biosimilar savings. |  |
| 76 | PCR | **Polymerase chain reaction** — amplifies a target DNA or RNA sequence millions of times, so that even a few copies become detectable. The technique behind COVID tests. Its strength and its limit are the same fact: it detects genetic material only. |  |
| 77 | psoriasis | A chronic autoimmune skin disease — scaly plaques from accelerated skin-cell turnover. Treated with anti-TNF and other biologics. |  |
| 78 | QRI | **Qualified Research Institution** — a term from FDA's Expedited IND Pilot: an institution vetted by FDA to participate in the programme. |  |
| 79 | RAND | The **RAND Corporation** — the original postwar FFRDC, founded in 1948 out of a US Air Force project. Policy analysis and research rather than hardware; birthplace of much of systems analysis and game-theoretic strategy. |  |
| 80 | residual DNA | Leftover host-cell DNA in a purified drug product. Regulators cap it — on the order of 10 ng per dose, with fragments kept short (under about 200 base pairs) so that no intact gene could be carried over. |  |
| 81 | RFI | **Request for Information** — a government request for input on a subject, with no money attached and no award. Used to shape a future programme and to find out who is out there. | pairs with RFP |
| 82 | RFP | **Request for Proposals** — a solicitation for bids on a defined deliverable, with an award at the end. | pairs with RFI |
| 83 | S&T Directorate | **DHS Science and Technology Directorate** — the department's research-and-development arm, which buys and tests technology for all of DHS. |  |
| 84 | SBIR | **Small Business Innovation Research** — the federal programme that sets aside a share of agency R&D budgets for small companies, in phases (feasibility, development, commercialisation). |  |
| 85 | SLEP | **Shelf-Life Extension Program** — FDA's programme of testing stockpiled federal medicines past their labelled expiry so that usable lots are not discarded. An expiry date is a conservative prediction made at approval; SLEP replaces the prediction with a measurement on the actual lot. |  |
| 86 | SPR | **Surface plasmon resonance.** A label-free binding method: molecules landing on a thin metal sensor surface change the local refractive index, shifting the angle at which light is absorbed. Yields k_on, k_off and K_D. Requires a purified analyte at known concentration — for specificity, and because k_on cannot be fitted without a known [analyte]. |  |
| 87 | Strategic National Stockpile | **SNS** — the US federal reserve of medicines, vaccines and medical supplies for emergencies. Run by ASPR since 2018, previously by CDC. |  |
| 88 | T cell | A lymphocyte that either kills infected or abnormal cells directly (cytotoxic T cells) or directs other immune cells (helper T cells). Distinct from B cells, which make antibodies. |  |
| 89 | VSA | **Versatile Smart Assay** — Erudio Bio's parallel force-spectroscopy platform: many bonds measured per well under applied force, with an optical readout, giving rupture distributions rather than population averages. | the one company-specific term here |
{: #glossary}

## 2. Biophysics Intuitions

The same quantity seen from several angles — several readings that each make a different part of it obvious. Not an exhaustive list.

| Term | Ways to read it |
|:-:|:--|
| K_D | **(1) The balance equation.** At equilibrium, k_on [A]<sub>free</sub> [B]<sub>free</sub> = k_off [AB]. Read each side as *count × frequency*: on the left, how many productive encounters happen per second; on the right, how many bound pairs break per second. Equilibrium is where the two flows match.<br><br>**(2) The price per unit of odds.** Rearranged: [B]<sub>free</sub> = (k_off/k_on) × [AB]/[A]<sub>free</sub> = K_D × [AB]/[A]<sub>free</sub>. Read it as the free-partner concentration needed to sustain a given bound-to-free split of A. K_D is the price, in concentration, of one unit of bound-to-free odds. When the odds are 1:1 — half bound — the required free-partner concentration *is* K_D.<br><br>**(3) The net rate, which is a difference rather than a ratio.** d[AB]/dt = k_on[A][B] − k_off[AB] = k_on([A][B] − K_D[AB]). The net rate has units of M/s and says which way the system is moving and how fast; K_D has units of M and says only where it stops. K_D is the zero-crossing; k_on sets the speed of approach.<br><br>**(4) Fraction bound.** fraction = [drug]/([drug] + K_D) — unit-free, with [drug] the free drug concentration, which is approximately the total when drug is in excess. The cleanest form for intuition: at [drug] = K_D, half the target is occupied; ten times K_D gives about 91%. |
| k_on vs. k_off | **Why one depends on concentration and the other does not.** Breaking is a private event: a bound pair comes apart on its own schedule, so k_off is a frequency (s⁻¹) and needs no partner. Binding requires two parties to meet, so k_on cannot be a frequency — it is a per-encounter coefficient (M⁻¹s⁻¹) that becomes a frequency only once multiplied by a partner concentration. Hence k_on × [partner] has units of s⁻¹, and bound complexes, being far apart from one another, never need to find each other to break. |
| Energy landscape | **What force measurement adds.** Equilibrium methods report where a reaction settles. Pulling on a bond tilts its energy landscape — force multiplied by distance subtracts from each barrier — so the rate of escape rises with force in a way that depends on the barrier's *position*, not only its height. Measuring rupture across loading rates therefore recovers the shape of the landscape: how many barriers, how tall, how far out. Two pairs with identical K_D can have entirely different landscapes, and behave differently under load.<br><br>The usual single-peak diagram is the simplest possible case; real interfaces generally have several barriers, and the slowest step — the rate-limiting one — is whichever is hardest to cross from the direction being travelled. |
| Survival curves | **Why a distribution beats an average.** Each measured bond contributes one rupture event; thousands of them give a survival curve, which is a histogram, not a single number. A population that is 95% intact and 5% degraded shows a second mode in that curve and is invisible in an averaged affinity. This is what makes rupture statistics useful for equivalence and stability questions rather than only for ranking affinities. |

## 3. The six biosimilar bills

Four Senate bills plus two House companions, all in the 119th Congress (January 2025 – January 2027; anything not passed by then dies and must be reintroduced). "S." = Senate bill, "H.R." = House bill; a bill must pass both chambers in identical form, which is why companion bills are introduced in parallel. Health bills go through the Senate HELP committee (House counterpart: Energy and Commerce); the antitrust bill went to Judiciary instead. Statuses as of July 2026 — re-verify before citing.

| Bill | Name | Sponsors | What it does | Status | What it changes |
|:--|:--|:--|:--|:--|:--|
| S.1414 / H.R. 9661 | Expedited Access to Biosimilars Act | Senate: Paul (R-KY), Lee (R-UT), Hassan (D-NH). House (introduced 15 July 2026): Langworthy (R-NY), Schrier (D-WA) | Removes the default requirement that a biosimilar applicant run a comparative clinical efficacy study; FDA keeps the authority to require one case by case | Ordered reported by HELP, 22 July 2026 | **The testing burden.** If clinical trials are no longer the default, analytical evidence of equivalence becomes the whole case — which raises the standard demanded of analytical methods |
| S.1954 / H.R. 5526 | Biosimilar Red Tape Elimination Act | Senate: Lee (R-UT), Luján (D-NM), Paul, Hassan, Schmitt, Ossoff. House (September 2025): Pfluger (R-TX), Landsman (D-OH) | Deems every FDA-licensed biosimilar *interchangeable* with its reference product, so pharmacists can substitute automatically; no switching studies required. Preserves exclusivity already earned by first interchangeables | Introduced in three consecutive Congresses; this time ordered reported favourably by HELP 17 June 2026 and placed on the Senate calendar 27 July | **Substitution friction** — the barrier that kept pharmacists from swapping in the Humira era. Raises the stakes on equivalence: if any approved biosimilar can be auto-substituted, "are these two truly the same?" becomes a question asked at every counter |
| S.1096 | Preserve Access to Affordable Generics and Biosimilars Act | Klobuchar (D-MN), Grassley (R-IA) + eight cosponsors (5 D, 3 R) | Bans *pay-for-delay*: a settlement in which the brand gives a generic or biosimilar maker anything of value — cash, or a promise not to launch an authorised generic — in exchange for delayed entry is presumed anticompetitive. FTC enforces | Ordered reported by Judiciary, 3 April 2025 — earliest to clear committee; earlier versions passed the Senate and died in the House | **Anticompetitive settlements.** Antitrust, not science. Explains part of why Humira biosimilars were held off until 2023: AbbVie settled with every challenger on a 2023 entry date |
| S.3510 | Biosimilar Inspection Modernization Act of 2025 | Budd (R-NC), Hassan (D-NH) | Expands remote regulatory assessments, convenes a meeting on mutual recognition agreements with foreign regulators, requires an FDA plan on domestic inspections | Has not moved | **Inspection logistics.** Peripheral to the evidence question |

One line to hold onto: the bills attack three different things — **testing burden** (S.1414), **substitution friction** (S.1954) and **anticompetitive settlements** (S.1096) — plus inspections (S.3510). Often cited alongside them, but not bills: FDA's 29 October 2025 announcement on dropping clinical efficacy studies for some biosimilars, the Langworthy/Schrier press release, and David Lim's *Politico* piece of 21 July 2026 on Hill momentum.

## 4. Key Contrasts

Short passages worth keeping whole — each one a distinction that decides what a measurement can and cannot claim.

### PCR reads genes, not function

PCR amplifies a target gene sequence millions of times so that even a few copies become detectable. That is the key to its strength *and* its limit: it detects **nucleic acids only**. It cannot see a protein toxin such as botulinum or ricin, which carry no nucleic acid of their own, and it cannot tell whether the organism it found is alive and active or long dead. A method that measures *binding* rather than sequence is not restricted this way, because what it detects is whatever its sensor is built to grab.

### What is actually wrong with the fielded incumbent

BioFire's FilmArray (bioMérieux) is the US military's fielded biothreat panel, and it is sample-to-answer PCR — roughly two minutes of hands-on time, a result in about an hour. So "needs heavy sample prep" is not its weakness; that claim gets corrected by anyone who has used one. Its real limits are three: it is PCR, so it sees nucleic acids only (no toxins, no live-versus-dead); it needs mains power and a controlled environment; and it runs one cartridge per panel. The accurate criticism is that **it detects genes, not function**.

### Why SPR stays in the research lab

Standard SPR practice is one purified analyte at a known concentration, and both halves of that requirement are structural rather than incidental.

**Specificity.** SPR's readout is mass landing on the sensor surface; it cannot identify what the mass is. In serum, blood or an environmental sample, non-specific fouling registers identically to real binding. Adding more spots to the array adds more false positives, not more information.

**The arithmetic.** Extracting k_on means fitting the observed rate k<sub>obs</sub> = k_on[analyte] + k_off, which requires **[analyte]** as a known input. A sample of unknown composition at unknown concentrations makes k_on unfittable in principle, not merely in practice.

Thirty years of engineering has not moved SPR into the clinic, and this is why. A force-based readout has a native answer to the first problem — non-specific adhesion ruptures differently from a specific bond, so the measurement itself supplies the specificity that sample preparation otherwise has to provide.

### Array SPR multiplexes the library, not the sample

Carterra's LSA is SPR plus a microfluidic printhead that arrays hundreds of *distinct* ligands on one sensor surface. Worth being precise about what that parallelises: many candidate molecules, **one analyte at a time**. That is a screening geometry — "which of my 384 candidates binds this target best?" — not a detection geometry. Reading many targets out of one unknown sample is the opposite axis, and it is the axis SPR's mass-based readout cannot serve.
