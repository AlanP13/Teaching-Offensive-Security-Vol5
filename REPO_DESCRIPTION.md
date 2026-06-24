# GitHub repository description and setup

## Repository name
```
Teaching-Offensive-Security-Vol5
```

## Short description (the GitHub "About" field, keep under ~350 characters)
```
Companion repo for Volume 5 of the Engineering-to-Research monograph series: a lifecycle-sequenced curriculum design for offensive-security education (Kali to MITRE ATT&CK), with the "one technique, three chairs" device and NICE/Bloom alignment. Paper (CC BY 4.0), figures, and a planned open educational resource. DOI pending.
```

## Alternative one-line description (even shorter)
```
A hands-on offensive-security curriculum design, sequenced by the attack lifecycle and grounded in ethics. Monograph Vol. 5 of 10.
```

## Website field
Set to the Zenodo DOI URL once minted:
```
https://doi.org/10.5281/zenodo.20821927
```

## Suggested topics
```
cybersecurity-education, offensive-security, penetration-testing, mitre-attack,
cyber-kill-chain, capture-the-flag, ctf, digital-forensics, intrusion-detection,
nice-framework, open-educational-resource, research-monograph, zenodo
```

## First-release checklist
1. Push all files (README.md, LICENSE, CITATION.cff, .zenodo.json, paper/, figures/, course/).
2. Set the About description and topics above.
3. Reserve the Zenodo DOI, then replace `10.5281/zenodo.20821927` in: README.md (badge + mentions), CITATION.cff, LICENSE, and the paper PDF/DOCX. Re-export the PDF before uploading.
4. Add the OER project briefs under course/ when ready (sanitized for an isolated, authorized lab).
5. Create a GitHub release tagged `v1.0`, and add the DOI to your portfolio and the Publication Status Ledger.

## Note on .zenodo.json
Copy `vol5_zenodo_metadata.json` from the archive into the repo root and rename it exactly `.zenodo.json`. Zenodo reads metadata in this priority order: `.zenodo.json` first, then `CITATION.cff`, then `LICENSE`.

## Publishing reminder
Publish on Zenodo into your "Engineering-to-Research Monograph Series" community, the same community used for Volumes 1, 4, 7, and 8.

## EB1A note
This volume is teaching/leadership evidence (course design and delivery). Pair it with any teaching records, syllabi, or student outcomes you can document.
