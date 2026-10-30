---
date: Fri Oct 16 23:35:00 PDT 2026
last_modified_at: Thu Oct 29 17:40:34 PDT 2026
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

	.igg-figure {
		display: block;
		margin: 1.8em auto;
		text-align: center;
	}
	.igg-figure svg {
		display: block;
		width: 100%;
		max-width: 520px;
		height: auto;
		margin: 0 auto;
	}
	.igg-figure figcaption {
		display: block;
		width: 100%;
		margin: 0.5em auto 0;
		text-align: center;
		font-size: calc(var(--body-font-size) * 0.8);
		opacity: 0.7;
	}
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
| 13 | BHK | **Baby Hamster Kidney** cells — a line established in 1961 from one-day-old Syrian hamster kidneys, usually BHK-21. The other hamster line in biomanufacturing alongside CHO, used for products CHO expresses poorly, notably clotting factors such as Factor VIII. A reminder that the cell line is part of the product: CHO and BHK glycosylate differently. | pairs with CHO |
| 14 | BLI | **Bio-layer interferometry.** A label-free binding method: molecules accumulating on the tip of a fiber-optic probe change the thickness of a layer, shifting an interference pattern. Gives k_on, k_off and K_D. Probe dips into a well rather than fluid flowing past a chip, which is the main practical difference from SPR. |  |
| 15 | BPCIA | **Biologics Price Competition and Innovation Act**, passed in 2010 as part of the Affordable Care Act. Created the abbreviated licensure pathway for **biosimilars** — the biologics counterpart to the Hatch-Waxman route that gave small-molecule drugs their generics. Establishes the two tiers (*biosimilar* and the higher bar of *interchangeable*), grants the reference product 12 years of exclusivity, and sets out the patent-exchange procedure known as the patent dance. It is the statute every biosimilar argument ultimately refers back to. | 2010; the biosimilar statute |
| 16 | CAE | **Component Acquisition Executive** — the single official holding acquisition decision authority for one component of the US defense department. Decides whether a programme starts, continues or stops, and signs the milestone decisions that release funding. The practical distinction: many senior officials can evaluate or endorse; the CAE is the one who can buy. |  |
| 17 | CBD | **Chemical and Biological Defense**, in US defense organisation names — as in ND-CBD and the Chemical and Biological Defense Program (CBDP). Heavily overloaded as an acronym: also cannabidiol in pharma, Convention on Biological Diversity in environmental policy, and central business district in real estate. Spell it out on first use. | see ND-CBD |
| 18 | CBRN | **Chemical, biological, radiological, nuclear** — the four classes of mass-casualty threat agent. |  |
| 19 | CBRND | **Chemical, Biological, Radiological, Nuclear Defense** — the defense mission covering those four threat classes. |  |
| 20 | CDC (agency) | **Centers for Disease Control and Prevention**, the US public-health agency, based in Atlanta. Held the Strategic National Stockpile until it moved to ASPR in 2018. | not the immunology CDC below |
| 21 | CDC (immunology) | **Complement-dependent cytotoxicity.** C1q binds a cluster of antibody Fc stems on a target cell, triggering the complement cascade, which assembles a pore in the cell membrane and kills it. The other main antibody killing mechanism alongside ADCC. | not the agency above |
| 22 | CDER | **FDA Center for Drug Evaluation and Research.** Reviews drugs, including biosimilars. Monoclonal antibodies moved here from CBER in 2003. | one of FDA's centers |
| 23 | CDRH | **FDA Center for Devices and Radiological Health.** Reviews medical devices, including in vitro diagnostics via the 510(k) pathway. Separate staff and standards from CDER. | one of FDA's centers |
| 24 | CHO | **Chinese hamster ovary** cells — the default production cell line for antibody drugs since the 1980s. The line dates to 1957 (Theodore Puck). Grows in suspension, takes human-like glycosylation, and does not support most human viruses, which simplifies viral safety. |  |
| 25 | CIV | **Civilian** — the designator appended to a civil-service employee's name in US defense correspondence, the counterpart to the uniformed suffixes USA, USN, USAF, USMC. Appears inside email display names, which encode the whole org location: *Lastname, Firstname MI CIV OSD P&R*. | pairs with HON, SES |
| 26 | CPE | **Capability Program Executive.** A US defense acquisition role and office, named by the portfolio it manages — the same naming pattern as the older PEO (Program Executive Office). The letters denote both the office and the person heading it. | see CPE CBRND |
| 27 | CPE CBRND | **Capability Program Executive for Chemical, Biological, Radiological and Nuclear Defense.** Manages US investment in CBRN defense equipment and medical countermeasures for the Joint Force. One of four components of the Chemical and Biological Defense Program. Formerly JPEO-CBRND. | renamed; many still say JPEO-CBRND |
| 28 | Crohn's disease | Chronic autoimmune inflammation of the gut, anywhere from mouth to anus but most often the terminal ileum. Treated with anti-TNF antibodies among other things. |  |
| 29 | CWMD | **Countering Weapons of Mass Destruction Office** — DHS's biodefense arm. Runs BioWatch, the national environmental biosurveillance programme, which has been criticised for slow turnaround and false alarms. |  |
| 30 | cytokine | A small signalling protein of the immune system — TNF-α, the interleukins, the interferons. Cells release them to instruct other cells; blocking one is how several antibody drugs work. |  |
| 31 | DFS | **Dynamic force spectroscopy.** Pull on a bond at a known loading rate and record the force at which it breaks; repeat many times and the distribution of rupture forces reveals the energy landscape — barrier heights and positions — not just the equilibrium affinity. Conventionally done one bond at a time by AFM. |  |
| 32 | DHA | **Defense Health Agency** — the agency that runs the US Military Health System: military hospitals and clinics worldwide, the TRICARE health plan, medical logistics and medical IT. Created in 2013; absorbed the Army, Navy and Air Force hospitals between 2018 and 2021. The division of labour that matters: the Health Affairs policy office sets policy and owns the budget, DHA executes and buys. | executes; Health Affairs sets policy |
| 33 | DHS | **Department of Homeland Security.** Created in 2002 from 22 merged agencies. For biodefense the relevant parts are CWMD and the Science & Technology Directorate. Has its own budget and OTA authority. |  |
| 34 | DoD | **Department of Defense** — the long-standing name for the same department now also called the Department of War. | do not mix DoD and DoW in one document |
| 35 | DOE | **U.S. Department of Energy.** Despite the name, one of the largest US science funders: it runs the 17 national laboratories (Oak Ridge, Argonne, Livermore, Berkeley, Los Alamos and others) and the biggest US supercomputers — Frontier, Aurora, El Capitan. Hence it owns the Genesis Mission. Nuclear-weapons stewardship is why it appears in national-security contexts. | 미국 에너지부 |
| 36 | DoS | **Department of State** — the US foreign ministry. In biodefense it owns the diplomatic side: the Biological Weapons Convention, threat-reduction and biosecurity engagement programmes abroad. |  |
| 37 | DoW | **Department of War** — the current name of the US defense department, formerly and still widely called the Department of Defense (DoD). | see DoD |
| 38 | DTRA | **Defense Threat Reduction Agency** — the US defense agency responsible for countering weapons of mass destruction. |  |
| 39 | ELISA | **Enzyme-linked immunosorbent assay.** An antibody captures the target on a plate; a second, detection antibody carrying an enzyme binds it and turns a substrate colourful. The workhorse protein assay — cheap, sensitive, and labelled, which is why it reports presence and amount but not binding kinetics. |  |
| 40 | EMA | **European Medicines Agency** — the EU's drug regulator, based in Amsterdam. The European counterpart to FDA's drug centers. |  |
| 41 | Fab | **Fragment, antigen-binding** — the two arms of the antibody Y, each ending in the variable region that grips the target. Fab binding is what gives an antibody its specificity. | pairs with Fc |
| 42 | FAR | **Federal Acquisition Regulation** — the rulebook governing ordinary US federal procurement: cost-accounting standards, audit rights, mandatory clauses, bid protests. Its overhead is why OTAs exist as an alternative, and its IP clauses can give the government broad rights in contractor technical data. | pairs with OTA |
| 43 | Fc | **Fragment, crystallizable** — the stem of the antibody Y. It carries no target specificity; instead it talks to the immune system, binding Fcγ receptors on NK cells (ADCC), C1q (CDC) and FcRn (which recycles the antibody and gives it a long half-life). Carries the N297 glycan. | pairs with Fab |
| 44 | FDA | **Food and Drug Administration** — the US regulator for drugs, biologics, devices, food and tobacco. Organised into centers: CDER (drugs), CBER (vaccines, blood, gene therapy), CDRH (devices). |  |
| 45 | FFRDC | **Federally Funded Research and Development Center.** A nonprofit funded by the government to supply long-term technical expertise in the public interest. The defining condition is that it may not compete with industry and has no commercial stake, which is what lets it see vendors' proprietary information and advise the agency honestly. Examples: Johns Hopkins APL, MITRE, RAND, MIT Lincoln Laboratory, the DOE national labs. In practice they are the government's trusted technical evaluators — gatekeepers, and potentially advocates. |  |
| 46 | Genesis Mission | A US Department of Energy initiative to apply AI to scientific discovery, established by executive order on 24 November 2025. Sits at DOE because the national labs and the largest supercomputers are already there. |  |
| 47 | globulin | A family of globular blood proteins, historically separated from albumin by solubility. Antibodies are the gamma fraction — hence "gamma globulin" and "immunoglobulin". |  |
| 48 | glycan | A sugar chain — the structure attached to a protein during glycosylation. On IgG the significant one sits at N297 on the Fc, where its composition tunes engagement with Fcγ receptors and complement. | pairs with glycosylation |
| 49 | glycogen | The storage form of glucose in liver and muscle; literally *sugar-former*. Belongs to the glyco- family (Greek *glykys*, sweet) that makes 당화 decode: glyco + -syl (group) + -ation (process) maps onto 糖 + 化. | etymology anchor for glycosylation |
| 50 | glycosylation | Sugar chains attached to a protein after it is built. Not encoded in the gene: the pattern depends on the producing cell and the process conditions, which is why two manufacturers' versions of the same antibody can differ. On IgG the key site is N297 on the Fc, where the glycan shapes how strongly the antibody engages Fcγ receptors and complement. |  |
| 51 | HCP | **Host-cell protein** — proteins made by the production cell line (usually CHO) that must be purified away from the drug. Residual levels are measured by an ELISA raised against the whole host-cell proteome, not against one protein. |  |
| 52 | HELP | The US Senate Committee on **Health, Education, Labor, and Pensions** — jurisdiction over FDA, drugs and public health, so health legislation passes through it first. The House counterpart is Energy and Commerce. |  |
| 53 | Herceptin | Trastuzumab (Genentech/Roche) — an anti-HER2 antibody for HER2-positive breast cancer. Works partly by blocking HER2 signalling and partly by Fc-mediated killing (ADCC). Known for cardiotoxicity (심장독성). |  |
| 54 | HHS | **Department of Health and Human Services** — the US federal health department. FDA, CDC, NIH, ASPR and BARDA all sit under it. |  |
| 55 | homeostasis | The body's self-regulation toward a stable internal state — temperature, pH, glucose, ion balance — through feedback. |  |
| 56 | HON | **The Honorable** — the courtesy title marking a Senate-confirmed political appointee (a *PAS* position: Presidentially Appointed, Senate-confirmed). On a distribution list, HON versus SES versus a military rank distinguishes appointee from career civilian from uniformed officer at a glance. | pairs with SES, CIV |
| 57 | Humira | AbbVie's brand of adalimumab, and the reference case for why US biosimilars did not cut prices. AbbVie was spun out of Abbott in 2013. US biosimilar entry finally came in January 2023, from Amgen, Sandoz, Samsung Bioepis, Celltrion and others — the date set by patent settlements rather than by science. Even then savings were slow, because AbbVie's rebates to pharmacy benefit managers kept the net cost of Humira competitive and because plain biosimilars could not be substituted at the counter without an interchangeability designation. | 브랜드명; molecule = adalimumab |
| 58 | IgG | **Immunoglobulin G** — the main antibody class in blood and the class nearly all antibody drugs belong to. Two heavy chains and two light chains in a Y, two Fab arms and one Fc stem. | see *Molecules in Depth* |
| 59 | immunoglobulin | The formal name for an antibody, abbreviated Ig. Classes: IgG, IgA, IgM, IgD, IgE. | 면역글로불린 |
| 60 | IND | **Investigational New Drug** application — FDA permission to give an experimental drug to humans. Filed before clinical trials; FDA has 30 days to object. |  |
| 61 | INN | **International Nonproprietary Name** — the generic name of a drug substance, assigned by the WHO and the same worldwide. Antibodies end in *-mab*; the preceding syllables encode the target and the source. | e.g. adalimumab vs brand Humira |
| 62 | ITC | **Isothermal titration calorimetry.** Measures binding by heat: ligand is injected in aliquots and the instrument records the power needed to hold sample and reference cells at the same temperature. One experiment yields K_D, stoichiometry *n* and enthalpy ΔH measured directly, with ΔS derived. Everything stays in solution, so nothing is perturbed by immobilisation. Limits: no kinetics at all — never k_on or k_off separately; needs milligram quantities; about an hour per measurement. The richest equilibrium method, and still an equilibrium method. | 등온적정열량법 |
| 63 | IVD | **In vitro diagnostics** — tests performed on a sample taken out of the body (blood, urine, swab, tissue), as opposed to *in vivo*. In the US, IVDs are regulated by FDA's device center, typically via 510(k). Global market roughly $100–130B. | 체외진단; 체외진단의료기기 |
| 64 | junk DNA | The roughly 98% of the human genome that does not code for protein. The name has aged badly: much of it is regulatory, structural or transcribed, which is what the ENCODE project set out to map. |  |
| 65 | K_D | **Equilibrium dissociation constant** — k_off / k_on. Units of concentration (M). It is the free-partner concentration at which half the target is occupied, and it says where a binding reaction settles, not how fast it gets there. See *Biophysics Intuitions* below for the readings that make it intuitive. | 비교는 자유 농도 또는 다른 쌍의 K_D와 — never against 1 |
| 66 | k_off | **Dissociation rate constant.** Units s⁻¹ — a frequency. How often a given bound pair comes apart, per second. It needs no partner: a bound complex breaks on its own schedule, which is why k_off does not depend on concentration. | pairs with k_on |
| 67 | k_on | **Association rate constant.** Units M⁻¹s⁻¹. Not a frequency on its own — it is a per-encounter sticking coefficient, which becomes a frequency only when multiplied by a partner concentration: k_on × [partner] has units of s⁻¹. That is why binding depends on concentration and unbinding does not. | pairs with k_off |
| 68 | Keytruda | Pembrolizumab (Merck) — an anti-PD-1 checkpoint inhibitor. It does not attack the tumour; it blocks a brake that tumours use to switch off T cells, releasing the immune response. Among the best-selling drugs in the world. |  |
| 69 | LCDR | **Lieutenant Commander** — US Navy and Coast Guard officer rank, pay grade O-4; equivalent to Major in the Army, Air Force and Marines. On a Pentagon staff, typically the working-level action officer who drafts the paper and tracks whether a tasking gets answered. | 해군 소령 |
| 70 | ligand | Two senses, which is why context matters. In biochemistry, any molecule that binds a target — the drug, the hormone, the substrate. In SPR and BLI, specifically the molecule immobilised on the sensor surface, as opposed to the analyte flowed over it. | both senses in use |
| 71 | metagenomics | Sequencing all the genetic material in a sample at once, without culturing or isolating organisms first, then working out what is present from the sequences. |  |
| 72 | MITRE | A nonprofit FFRDC operator running several federally funded centers for DoD, FAA, IRS, CMS and the intelligence community. Known outside government for the ATT&CK and CVE security catalogues. |  |
| 73 | monoclonal antibody | One identical antibody, produced by the descendants of a single cell clone — hence a defined molecule that can be manufactured and regulated as a drug, unlike the mixture obtained from an immunised animal. | 단일클론항체 |
| 74 | NCATS | **National Center for Advancing Translational Sciences** — the NIH institute for the machinery of getting discoveries from lab to clinic, rather than for any one disease. |  |
| 75 | NCI | **National Cancer Institute** — the largest of the NIH institutes. |  |
| 76 | ND-CBD | **Nuclear Deterrence and Chemical and Biological Defense** — the Assistant Secretary portfolio that owns US nuclear deterrence policy together with the whole chemical and biological defence policy and programme portfolio. Successor to the older NCB designation, and the policy parent of the CBRN defence programmes. Sits under the Under Secretary for Policy, which is a different chain from military medicine under Personnel and Readiness. | policy parent of CBRND |
| 77 | NIH | **National Institutes of Health** — the main US funder of biomedical research, made up of 27 institutes and centers, in Bethesda, Maryland. |  |
| 78 | NK cell | **Natural killer cell** — a lymphocyte that kills without prior sensitisation. In ADCC it is the executioner: it binds the Fc stems of antibodies coating a target cell and destroys it. |  |
| 79 | nucleic acids | DNA and RNA collectively — the information molecules, long chains of four nucleotides. Contrast with proteins, chains of twenty amino acids. The distinction matters for detection: a method that reads nucleic acids cannot see a protein toxin. | 핵산 |
| 80 | OCET | **FDA Office of Counterterrorism and Emerging Threats** — sits inside FDA's Office of the Chief Scientist and is FDA's home for medical countermeasures, CBRN preparedness and stockpile questions. |  |
| 81 | oligo | **Oligonucleotide** — a short synthetic strand of DNA or RNA, typically tens of bases, made to order. Used as primers, probes, tethers and therapeutics. |  |
| 82 | ONC | **Office of the National Coordinator for Health Information Technology** — the HHS office for health-data standards and interoperability. |  |
| 83 | Operation TrialBlazer | An HHS initiative announced 22 June 2026 to speed clinical trials and IND review; applications ran 15 September – 30 October 2026. |  |
| 84 | OPHPR | **Office of Public Health Preparedness and Response.** Sits under **CDC**, not FDA — worth noting, because the two are easily conflated in writing about preparedness. | under CDC |
| 85 | optical tweezers | A tightly focused laser that traps a micron-scale dielectric bead: refraction changes the light's momentum, and the intensity gradient pulls the bead toward the focus. The trap behaves as a spring, so force = trap stiffness × displacement from centre, readable to a fraction of a piconewton. Arthur Ashkin's work, 1970s–80s; Nobel Prize in Physics 2018. In single-molecule geometry the molecule is tethered between a trapped bead and a bead on a micropipette, usually through double-stranded DNA handles that hold it clear of the bead surfaces. Stretch and relax cycles give force-extension curves; hysteresis between the two paths is the signature of a non-equilibrium measurement. Range roughly 0.1–100 pN — gentler and finer than AFM. | 광집게 — not *optimal* tweezers |
| 86 | OSD | **Office of the Secretary of Defense** — the Secretary's own headquarters staff: the policy, personnel, acquisition, intelligence and comptroller offices that run the department, as distinct from the military services and the combatant commands. *OSD-level* means department-wide. | renamed OSW; see DoD / DoW |
| 87 | OSTP | **Office of Science and Technology Policy** — in the Executive Office of the President. Advises the President on science and technology and coordinates science policy across agencies; its Director usually serves as the President's science advisor. |  |
| 88 | OSW | **Office of the Secretary of War** — the renamed OSD under the Department of War designation. Same body, same role; both forms circulate during the transition. | = OSD |
| 89 | OTA | **Other Transaction Authority.** Congress gave certain agencies (DoD/DoW, DHS, NASA, NIH, ARPA-H) authority to enter agreements that are legally *not* procurement contracts, grants or cooperative agreements — and so are not bound by the FAR. Used mainly for prototype projects, with a path to follow-on production. For a small company the three attractions, in order: **intellectual property terms are negotiable** rather than set by FAR clauses; the timeline runs in months rather than years; and many OTAs run through consortia, which lowers the overhead of competing. | pairs with FAR |
| 90 | OUSD | **Office of the Under Secretary of Defense** — the staff organisation under one Under Secretary, always written with the domain in parentheses: OUSD(P&R), OUSD(Policy), OUSD(A&S), OUSD(R&E). | renamed OUSW |
| 91 | OUSW | **Office of the Under Secretary of War** — the renamed OUSD, same convention: OUSW(P&R) and so on. | = OUSD |
| 92 | P&R | **Personnel and Readiness** — the Under Secretary domain covering military personnel, health affairs, training and force readiness. Health Affairs and the Defense Health Agency sit beneath it. Not to be confused with *Preparedness and Response*, which is ASPR at HHS — a different department entirely. | ≠ ASPR, ≠ OPHPR |
| 93 | PBM | **Pharmacy benefit manager** — the intermediary that negotiates drug prices for insurers and employers. Manufacturers pay rebates off list price to secure formulary position, so a drug's *net* cost can be far below its list price. This is the mechanism that blunted Humira biosimilar savings. |  |
| 94 | PCR | **Polymerase chain reaction** — amplifies a target DNA or RNA sequence millions of times, so that even a few copies become detectable. The technique behind COVID tests. Its strength and its limit are the same fact: it detects genetic material only. |  |
| 95 | psoriasis | A chronic autoimmune skin disease — scaly plaques from accelerated skin-cell turnover. Treated with anti-TNF and other biologics. |  |
| 96 | QRI | **Qualified Research Institution** — a term from FDA's Expedited IND Pilot: an institution vetted by FDA to participate in the programme. |  |
| 97 | RAND | The **RAND Corporation** — the original postwar FFRDC, founded in 1948 out of a US Air Force project. Policy analysis and research rather than hardware; birthplace of much of systems analysis and game-theoretic strategy. |  |
| 98 | residual DNA | Leftover host-cell DNA in a purified drug product. Regulators cap it — on the order of 10 ng per dose, with fragments kept short (under about 200 base pairs) so that no intact gene could be carried over. |  |
| 99 | RFI | **Request for Information** — a government request for input on a subject, with no money attached and no award. Used to shape a future programme and to find out who is out there. | pairs with RFP |
| 100 | RFP | **Request for Proposals** — a solicitation for bids on a defined deliverable, with an award at the end. | pairs with RFI |
| 101 | S&T Directorate | **DHS Science and Technology Directorate** — the department's research-and-development arm, which buys and tests technology for all of DHS. |  |
| 102 | SBIR | **Small Business Innovation Research** — the federal programme that sets aside a share of agency R&D budgets for small companies, in phases (feasibility, development, commercialisation). |  |
| 103 | SES | **Senior Executive Service** — the senior career civil-service tier just below political appointees. SES officials persist across administrations and usually hold the deep subject expertise and the institutional memory of why earlier attempts failed. | 고위공무원단 |
| 104 | SLEP | **Shelf-Life Extension Program** — FDA's programme of testing stockpiled federal medicines past their labelled expiry so that usable lots are not discarded. An expiry date is a conservative prediction made at approval; SLEP replaces the prediction with a measurement on the actual lot. |  |
| 105 | SPR | **Surface plasmon resonance.** A label-free binding method: molecules landing on a thin metal sensor surface change the local refractive index, shifting the angle at which light is absorbed. Yields k_on, k_off and K_D. Requires a purified analyte at known concentration — for specificity, and because k_on cannot be fitted without a known [analyte]. |  |
| 106 | Strategic National Stockpile | **SNS** — the US federal reserve of medicines, vaccines and medical supplies for emergencies. Run by ASPR since 2018, previously by CDC. |  |
| 107 | T cell | A lymphocyte that either kills infected or abnormal cells directly (cytotoxic T cells) or directs other immune cells (helper T cells). Distinct from B cells, which make antibodies. |  |
| 108 | USN | **United States Navy** — the branch suffix following a uniformed officer's name and rank, as in *LCDR Mark Fisher, USN*. The convention exists because a joint staff mixes officers from every service with civilians; the parallel suffixes are USA (Army), USAF (Air Force), USMC (Marine Corps), USCG (Coast Guard) and USSF (Space Force). | pairs with CIV |
| 109 | VSA | **Versatile Smart Assay** — Erudio Bio's parallel force-spectroscopy platform: many bonds measured per well under applied force, with an optical readout, giving rupture distributions rather than population averages. | the one company-specific term here |
{: #glossary}

## 2. Biophysics Intuitions

The same quantity seen from several angles — several readings that each make a different part of it obvious. Not an exhaustive list.

| Term | Ways to read it |
|:-:|:--|
| K_D | **(1) The balance equation.** At equilibrium, k_on [A]<sub>free</sub> [B]<sub>free</sub> = k_off [AB]. Read each side as *count × frequency*: on the left, how many productive encounters happen per second; on the right, how many bound pairs break per second. Equilibrium is where the two flows match.<br><br>**(2) The price per unit of odds.** Rearranged: [B]<sub>free</sub> = (k_off/k_on) × [AB]/[A]<sub>free</sub> = K_D × [AB]/[A]<sub>free</sub>. Read it as the free-partner concentration needed to sustain a given bound-to-free split of A. K_D is the price, in concentration, of one unit of bound-to-free odds. When the odds are 1:1 — half bound — the required free-partner concentration *is* K_D.<br><br>**(3) The net rate, which is a difference rather than a ratio.** d[AB]/dt = k_on[A][B] − k_off[AB] = k_on([A][B] − K_D[AB]). The net rate has units of M/s and says which way the system is moving and how fast; K_D has units of M and says only where it stops. K_D is the zero-crossing; k_on sets the speed of approach.<br><br>**(4) Fraction bound.** fraction = [drug]/([drug] + K_D) — unit-free, with [drug] the free drug concentration, which is approximately the total when drug is in excess. The cleanest form for intuition: at [drug] = K_D, half the target is occupied; ten times K_D gives about 91%. |
| k_on vs. k_off | **Why one depends on concentration and the other does not.** Breaking is a private event: a bound pair comes apart on its own schedule, so k_off is a frequency (s⁻¹) and needs no partner. Binding requires two parties to meet, so k_on cannot be a frequency — it is a per-encounter coefficient (M⁻¹s⁻¹) that becomes a frequency only once multiplied by a partner concentration. Hence k_on × [partner] has units of s⁻¹, and bound complexes, being far apart from one another, never need to find each other to break. |
| Energy landscape | **What force measurement adds.** Equilibrium methods report where a reaction settles. Pulling on a bond tilts its energy landscape — force multiplied by distance subtracts from each barrier — so the rate of escape rises with force in a way that depends on the barrier's *position*, not only its height. Measuring rupture across loading rates therefore recovers the shape of the landscape: how many barriers, how tall, how far out. Two pairs with identical K_D can have entirely different landscapes, and behave differently under load.<br><br>The usual single-peak diagram is the simplest possible case; real interfaces generally have several barriers, and the slowest step — the rate-limiting one — is whichever is hardest to cross from the direction being travelled. |
| Survival curves | **Why a distribution beats an average.** Each measured bond contributes one rupture event; thousands of them give a survival curve, which is a histogram, not a single number. A population that is 95% intact and 5% degraded shows a second mode in that curve and is invisible in an averaged affinity. This is what makes rupture statistics useful for equivalence and stability questions rather than only for ranking affinities. |

## 3. Molecules in Depth

Entries that need more room than a glossary line — the molecules and structures that most of the rest assumes.

### IgG — the antibody format

**The name.** *Ig* is immunoglobulin, the formal word for antibody. The *G* comes from **gamma globulin**, and that is a historical accident worth knowing, because it explains a piece of vocabulary that otherwise looks arbitrary.

Run blood serum through electrophoresis at about pH 8.6 and the proteins separate. Separation is mostly by **charge**, not by size: each protein has an isoelectric point (pI), the pH at which its net charge is zero, and at pH 8.6 — above most proteins' pI — they carry net negative charge and migrate toward the positive electrode. How far each one travels depends on its charge-to-size ratio, so they resolve into bands:

| Band | Principal contents |
|:-:|:--|
| Albumin | albumin — strongly negative, travels furthest |
| α₁ | α₁-antitrypsin |
| α₂ | haptoglobin, ceruloplasmin, α₂-macroglobulin |
| β | transferrin, complement C3, some IgA |
| γ (gamma) | the immunoglobulins — barely negative at this pH, so they move least |

Antibodies land in the slowest band, hence *gamma globulin*, hence the G. The older *albumin / globulin* split is older still and comes from solubility: albumin dissolves in pure water, globulins need salt.

Worth distinguishing from **SDS-PAGE**, which separates by molecular weight — SDS coats every protein with uniform negative charge so that only size matters. Native serum electrophoresis keeps each protein's own charge, which is why it sorts by protein family rather than by mass.

**The architecture.** IgG is the Y-shaped molecule.

<figure class="igg-figure">
<svg viewBox="-80 0 800 480" xmlns="http://www.w3.org/2000/svg" role="img" aria-labelledby="igg-title igg-desc">
  <title id="igg-title">Structure of an IgG antibody</title>
  <desc id="igg-desc">A Y-shaped antibody: two Fab arms built from paired heavy and light chains, ending in variable domains that bind antigen, joined by a flexible hinge to an Fc stem of two heavy chains carrying the N297 glycan.</desc>

  <g fill="none" stroke-linecap="round" stroke-linejoin="round">
    <!-- light chains (constant part) -->
    <path d="M 145,86 L 266,231" stroke="currentColor" stroke-opacity="0.45" stroke-width="12"/>
    <path d="M 495,86 L 374,231" stroke="currentColor" stroke-opacity="0.45" stroke-width="12"/>
    <!-- heavy chains, arms (constant part CH1) -->
    <path d="M 165,66 L 320,252" stroke="currentColor" stroke-opacity="0.72" stroke-width="15"/>
    <path d="M 475,66 L 320,252" stroke="currentColor" stroke-opacity="0.72" stroke-width="15"/>
    <!-- heavy chains, Fc stem -->
    <path d="M 306,256 L 306,404" stroke="currentColor" stroke-opacity="0.72" stroke-width="15"/>
    <path d="M 334,256 L 334,404" stroke="currentColor" stroke-opacity="0.72" stroke-width="15"/>

    <!-- variable domains, highlighted -->
    <path d="M 145,86 L 199,151" stroke="#3b82c4" stroke-width="12"/>
    <path d="M 495,86 L 441,151" stroke="#3b82c4" stroke-width="12"/>
    <path d="M 165,66 L 235,150" stroke="#3b82c4" stroke-width="15"/>
    <path d="M 475,66 L 405,150" stroke="#3b82c4" stroke-width="15"/>

    <!-- interchain disulfide bonds -->
    <path d="M 302,236 L 338,236" stroke="#d98a2b" stroke-width="4"/>
    <path d="M 302,286 L 338,286" stroke="#d98a2b" stroke-width="4"/>
    <path d="M 302,306 L 338,306" stroke="#d98a2b" stroke-width="4"/>
  </g>

  <!-- N297 glycans -->
  <g fill="#d98a2b" fill-opacity="0.9">
    <circle cx="288" cy="352" r="7"/><circle cx="273" cy="340" r="7"/><circle cx="273" cy="364" r="7"/>
    <circle cx="352" cy="352" r="7"/><circle cx="367" cy="340" r="7"/><circle cx="367" cy="364" r="7"/>
  </g>
  <g stroke="#d98a2b" stroke-width="2.5" fill="none">
    <path d="M 288,352 L 273,340 M 288,352 L 273,364"/>
    <path d="M 352,352 L 367,340 M 352,352 L 367,364"/>
  </g>

  <!-- antigen-binding sites -->
  <g fill="none" stroke="#3b82c4" stroke-width="2.5" stroke-dasharray="4 3">
    <path d="M 139,58 a 26,26 0 0 1 36,0"/>
    <path d="M 465,58 a 26,26 0 0 1 36,0"/>
  </g>

  <!-- brackets -->
  <g fill="none" stroke="currentColor" stroke-opacity="0.4" stroke-width="2">
    <path d="M 42,52 L 28,52 L 28,214 L 42,214"/>
    <path d="M 548,262 L 562,262 L 562,412 L 548,412"/>
  </g>

  <g font-family="inherit" fill="currentColor">
    <text x="18" y="126" text-anchor="end" font-size="20" font-weight="600">Fab</text>
    <text x="18" y="149" text-anchor="end" font-size="13" fill-opacity="0.65">binds antigen</text>
    <text x="572" y="337" font-size="20" font-weight="600">Fc</text>
    <text x="572" y="360" font-size="13" fill-opacity="0.65">immune</text>
    <text x="572" y="376" font-size="13" fill-opacity="0.65">engagement</text>

    <text x="320" y="30" text-anchor="middle" font-size="13" fill="#3b82c4">antigen-binding site</text>
    <text x="126" y="166" text-anchor="end" font-size="13" fill="#3b82c4">variable (V)</text>
    <text x="126" y="214" text-anchor="end" font-size="13" fill-opacity="0.65">constant (C)</text>
    <text x="126" y="262" text-anchor="end" font-size="13" fill-opacity="0.65">light chain</text>
    <text x="408" y="246" font-size="13" fill-opacity="0.65">hinge</text>
    <text x="408" y="300" font-size="13" fill="#d98a2b">disulfide bonds</text>
    <text x="232" y="352" text-anchor="end" font-size="13" fill="#d98a2b">N297 glycan</text>
    <text x="232" y="420" text-anchor="end" font-size="13" fill-opacity="0.65">heavy chain</text>
  </g>

  <g stroke="currentColor" stroke-opacity="0.32" stroke-width="1.5" fill="none">
    <path d="M 134,161 L 208,142"/>
    <path d="M 134,209 L 268,196"/>
    <path d="M 134,257 L 204,238"/>
    <path d="M 404,242 L 348,250"/>
    <path d="M 404,296 L 344,292"/>
    <path d="M 238,348 L 262,350"/>
    <path d="M 238,416 L 298,396"/>
  </g>

  <!-- glycan attachment to the stem -->
  <g stroke="#d98a2b" stroke-width="2.5" fill="none">
    <path d="M 300,352 L 288,352"/>
    <path d="M 340,352 L 352,352"/>
  </g>
</svg>
<figcaption>Two heavy chains and two light chains. The variable domains at the arm tips differ from antibody to antibody; everything below them is constant within a subclass.</figcaption>
</figure>

- **Fab arms** (fragment, antigen-binding) — the two arms, built from the variable region. These bind the target, and they differ from antibody to antibody. Specificity lives here.
- **Fc stem** (fragment, crystallizable) — the stem, built from the constant region, identical across antibodies of the same subclass. This is the part the immune system reads: NK cells engage it through FcγRIIIa (CD16) to trigger ADCC, and complement binds it for CDC. The N297 glycan sits here, which is why removing a single fucose from that glycan can change ADCC potency by roughly fiftyfold.

So one molecule carries two separable functions: *what it grabs* (Fab) and *what happens next* (Fc). Much of antibody engineering is the business of tuning those two independently.

**Why it dominates.** IgG makes up roughly 75–80% of the antibodies in serum, and is the only isotype that crosses the placenta — which is how a newborn carries its mother's immunity for its first months. More to the point for drug development: essentially every therapeutic monoclonal antibody is an IgG, so "biologic" in a biosimilar context almost always means an IgG.

**Subclasses.** IgG1, IgG2, IgG3 and IgG4 differ in the Fc, and therefore in how strongly they recruit immune effector functions. Choosing among them is a design decision: IgG1 when the antibody should mark a cell for destruction, IgG4 when the Fab should block something without calling in an attack.

**The isotype family.** Five classes, conventionally remembered as *GAMED*:

| Isotype | Where it works | Role |
|:-:|:--|:--|
| IgG | blood, tissue | sustained defence; the therapeutic format |
| IgA | mucus, saliva, breast milk | guards wet surfaces — gut, airway |
| IgM | blood | first responder; a large pentamer made early in an infection |
| IgE | tissue | allergy and antiparasitic response |
| IgD | B-cell surface | receptor; the least understood |

**One detail with clinical consequences.** The gamma band is a broad smear rather than a sharp line, because serum antibodies are **polyclonal** — millions of clones, each with a slightly different sequence and so a slightly different charge. The smear *is* the diversity. A sharp spike in that region means a single clone has come to dominate, which is the **M-protein** of a monoclonal gammopathy and a classic finding in multiple myeloma. The underlying lesson generalizes: the shape of a distribution carries information that any single summary number discards.

## 4. Key Contrasts

Short passages worth keeping whole — each one a distinction that decides what a measurement can and cannot claim.

### Where specificity comes from

Every binding assay faces the same obstacle: real binding has to be separated from everything else that merely sticks. Proteins adsorb onto surfaces through plain physical chemistry — hydrophobic patches, electrostatics — with no recognition involved, and antibodies are among the worst offenders.

There are only two places that separation can happen.

**Before the measurement**, by purifying the sample. This is the only option available to a readout that reports *quantity* rather than *identity*. Mass is mass: an instrument that senses material arriving at a surface cannot tell why it arrived. Specificity must therefore be bought upstream, with purification, controls and clean matrices — which is precisely what keeps such instruments tethered to a laboratory and away from unprocessed samples.

**Inside the measurement**, if the readout can distinguish the two on its own. A force-based readout can: a specific bond and a non-specific adhesion come apart at different forces, so a single force sweep separates them — and the relative size of each step also reports how much of each was present. Specificity becomes an output of the measurement rather than a precondition for it.

The distinction is structural, not a matter of engineering refinement, and it determines which samples an instrument can ever accept.

### PCR reads genes, not function

PCR amplifies a target gene sequence millions of times so that even a few copies become detectable. That is the key to its strength *and* its limit: it detects **nucleic acids only**. It cannot see a protein toxin such as botulinum or ricin, which carry no nucleic acid of their own, and it cannot tell whether the organism it found is alive and active or long dead. A method that measures *binding* rather than sequence is not restricted this way, because what it detects is whatever its sensor is built to grab.

### What is actually wrong with the fielded incumbent

BioFire's FilmArray (bioMérieux) is the US military's fielded biothreat panel, and it is sample-to-answer PCR — roughly two minutes of hands-on time, a result in about an hour. So "needs heavy sample prep" is not its weakness; that claim gets corrected by anyone who has used one. Its real limits are three: it is PCR, so it sees nucleic acids only (no toxins, no live-versus-dead); it needs mains power and a controlled environment; and it runs one cartridge per panel. The accurate criticism is that **it detects genes, not function**.

### Why SPR stays in the research lab

Standard SPR practice is one purified analyte at a known concentration, and both halves of that requirement are structural rather than incidental.

**Specificity.** SPR's readout is mass landing on the sensor surface; it cannot identify what the mass is. In serum, blood or an environmental sample, non-specific fouling registers identically to real binding. Adding more spots to the array adds more false positives, not more information.

**The arithmetic.** Extracting k_on means fitting the observed rate k<sub>obs</sub> = k_on[analyte] + k_off, which requires **[analyte]** as a known input. A sample of unknown composition at unknown concentrations makes k_on unfittable in principle, not merely in practice.

Thirty years of engineering has not moved SPR into the clinic, and this is why. The first of those two limits is the subject of *Where specificity comes from* above: a mass-based readout has no internal way to separate real binding from fouling, so the separation has to be bought upstream.

### Array SPR multiplexes the library, not the sample

Carterra's LSA is SPR plus a microfluidic printhead that arrays hundreds of *distinct* ligands on one sensor surface. Worth being precise about what that parallelises: many candidate molecules, **one analyte at a time**. That is a screening geometry — "which of my 384 candidates binds this target best?" — not a detection geometry. Reading many targets out of one unknown sample is the opposite axis, and it is the axis SPR's mass-based readout cannot serve.
