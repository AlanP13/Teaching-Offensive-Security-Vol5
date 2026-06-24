# Teaching Offensive Security

### A Lifecycle-Sequenced Curriculum from Kali to MITRE ATT&CK

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20821927.svg)](https://doi.org/10.5281/zenodo.20821927)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Companion repository for **Volume 5 of 10** in the **Engineering-to-Research Monograph Series** by **Alan Biju Palayil**.

> Effective offensive-security education is a hands-on apprenticeship in the attacker's mindset: sequenced along the attack lifecycle, anchored to MITRE ATT&CK and the kill chain, deepened to the machine, looped into defense, and grounded in ethics throughout.

---

## Contents

- [About this repository](#about-this-repository)
- [The monograph](#the-monograph)
- [Framework at a glance](#framework-at-a-glance)
- [Repository structure](#repository-structure)
- [Figures](#figures)
- [How to cite](#how-to-cite)
- [The Engineering-to-Research series](#the-engineering-to-research-series)
- [Versioning](#versioning)
- [License](#license)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

---

## About this repository

This repository is the companion to the technical report *Teaching Offensive Security: A Lifecycle-Sequenced Curriculum from Kali to MITRE ATT&CK*. It holds the paper, the source figures, and a planned open educational resource (OER) version of the curriculum: project briefs, the lecture spine, and the NICE/Bloom assessment mapping. The archival record of the paper lives on Zenodo with a permanent DOI.

The paper documents a curriculum the author designed and delivered (ECE 222), and distills it into transferable design principles for offensive-security education.

---

## The monograph

- **Title:** Teaching Offensive Security: A Lifecycle-Sequenced Curriculum from Kali to MITRE ATT&CK
- **Series:** Engineering-to-Research Monograph Series, Volume 5 of 10
- **Type:** Technical report / educational whitepaper
- **Version:** 1.1 (June 2026)
- **DOI:** [10.5281/zenodo.20821927](https://doi.org/10.5281/zenodo.20821927) (version 1.1)
- **Paper:** [`paper/08_Monograph_5_Teaching_Offensive_Security.pdf`](paper/08_Monograph_5_Teaching_Offensive_Security.pdf)

**Abstract.** There is a persistent gap in cybersecurity education between knowing about attacks and being able to perform and counter them. This report presents and defends a curriculum design developed while designing and delivering an introductory cybersecurity engineering course: lead with the attacker's mindset, scaffold the danger, sequence by the attacker lifecycle, anchor to ATT&CK and the kill chain, teach exploitation down to the machine, loop back into detection and forensics, and embed ethics and law throughout. The design is aligned to the NIST/NICE workforce framework and observable, project-based assessment.

---

## Framework at a glance

**Lifecycle-sequenced curriculum:** environment (Kali), reconnaissance and scanning, network attacks, exploitation, detection, forensics, with ethics and law throughout.

**Design Principle 1 (Mindset Before Tools).** Effective offensive-security education teaches the attacker's mindset, scaffolded along the attack lifecycle and deepened to the level of the machine, so that learners understand techniques rather than memorize tools. Every offensive skill is paired with its defensive counterpart and its legal boundary.

**Synthesized contributions.**

1. A lifecycle-sequenced, project-based curriculum design.
2. The "one technique, three chairs" pedagogical device (attacker, defender, investigator).
3. A workforce-and-assessment alignment to NICE and Bloom.
4. A practitioner-educator vantage and its transferable design principles.

---

## Repository structure

```text
teaching-offensive-security-vol5/
├── README.md
├── LICENSE                      # CC BY 4.0 (paper, figures, and course materials)
├── CITATION.cff
├── .zenodo.json                 # Zenodo deposit metadata (root-level name required)
├── paper/
│   ├── 08_Monograph_5_Teaching_Offensive_Security.pdf
│   └── 08_Monograph_5_Teaching_Offensive_Security.docx
├── figures/
│   ├── vol5_fig1_curriculum_lifecycle.svg / .png
│   └── vol5_fig2_one_technique_three_chairs.svg / .png
└── course/
    └── README.md                # planned OER: project briefs, lecture spine, NICE/Bloom mapping
```

---

## Course materials

The course originated as ECE 222 Introduction to Cybersecurity Engineering. The planned OER in `course/` will provide sanitized, reusable versions of the four hands-on project briefs (Kali fundamentals; scanning; penetration testing; intrusion detection and forensics), the lecture spine, and the assessment rubric mapped to NICE work roles and Bloom levels. All offensive material is framed for an isolated, authorized lab environment.

---

## Figures

1. **Figure 1, the lifecycle-sequenced curriculum.**
2. **Figure 2, one technique, three chairs** (attacker, defender, investigator).

Provided as editable SVG and rendered PNG.

---

## How to cite

A machine-readable [`CITATION.cff`](CITATION.cff) is included; GitHub renders a "Cite this repository" button from it.

**IEEE.** A. B. Palayil, "Teaching Offensive Security: A Lifecycle-Sequenced Curriculum from Kali to MITRE ATT&CK," Engineering-to-Research Monograph Series, vol. 5, 2026. doi: 10.5281/zenodo.20821927.

```bibtex
@techreport{palayil2026teaching,
  author      = {Palayil, Alan Biju},
  title       = {Teaching Offensive Security: A Lifecycle-Sequenced Curriculum from Kali to MITRE ATT&CK},
  institution = {Engineering-to-Research Monograph Series},
  number      = {Volume 5 of 10},
  year        = {2026},
  version     = {1.1},
  doi         = {10.5281/zenodo.20821927},
  url         = {https://doi.org/10.5281/zenodo.20821927}
}
```

---

## The Engineering-to-Research series

This is Volume 5 of a ten-volume program that turns a decade of engineering and research training into one coherent research identity, ending in explainable-AI governance. All ten volumes are published on Zenodo:

| Vol | Title | DOI |
|----|----|----|
| 1 | Securing Connected Systems | [10.5281/zenodo.20733453](https://doi.org/10.5281/zenodo.20733453) |
| 2 | Computer Architecture as a Security Discipline | [10.5281/zenodo.20821993](https://doi.org/10.5281/zenodo.20821993) |
| 3 | Getting the Foundations Right | [10.5281/zenodo.20828879](https://doi.org/10.5281/zenodo.20828879) |
| 4 | Embedded-to-Edge-AI Reference Architecture | [10.5281/zenodo.20784402](https://doi.org/10.5281/zenodo.20784402) |
| 5 | **Teaching Offensive Security** | [10.5281/zenodo.20821927](https://doi.org/10.5281/zenodo.20821927) — this volume |
| 6 | Governance as the Integration Layer | [10.5281/zenodo.20828631](https://doi.org/10.5281/zenodo.20828631) |
| 7 | Scalable Analytics for Enterprise Decisions | [10.5281/zenodo.20828327](https://doi.org/10.5281/zenodo.20828327) |
| 8 | Data Mining for Financial Systems | [10.5281/zenodo.20802595](https://doi.org/10.5281/zenodo.20802595) |
| 9 | Whether, Why, and For Whom | [10.5281/zenodo.20829174](https://doi.org/10.5281/zenodo.20829174) |
| 10 | From Embedded Systems to Explainable AI Governance | [10.5281/zenodo.20829270](https://doi.org/10.5281/zenodo.20829270) |

---

## Versioning

This repository follows the monograph version. Version 1.1 corresponds to its Zenodo deposit; future revisions are released as new Zenodo versions under the same concept DOI and tagged here with matching GitHub releases.

---

## License

Paper, figures, and course materials are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0). See `LICENSE`.

---

## Author

**Alan Biju Palayil**
Independent Researcher; Doctoral Researcher, University of the Cumberlands; Financial Systems Practitioner.
ORCID: [0009-0004-8302-5090](https://orcid.org/0009-0004-8302-5090)
GitHub: [@AlanP13](https://github.com/AlanP13)

---

## Acknowledgments

This work originated in the author's design and delivery of ECE 222 Introduction to Cybersecurity Engineering (an ECE 497 Special Problems project) and ITMS 538 at the Illinois Institute of Technology, with penetration-testing material from ITS-834 at the University of the Cumberlands. The author acknowledges the instructors and students whose engagement informed the course design. All synthesis, analysis, and writing are the author's own and were written from scratch for publication.
