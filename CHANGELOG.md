# ODSF Changelog

The OSINT Defense & Security Framework (ODSF) is published at https://psysecure.com/odsf/. This repository mirrors released artifacts; the canonical source is maintained privately by PsySecure, and published version strings are immutable: any content change bumps the version.

## [0.2.0] — 2026-06-10

Public Draft. First release under Creative Commons Attribution 4.0 International, which now governs all framework content including the prior drafts.

- 5 focus areas, 34 subcategories, 163 controls. Three controls added since the 0.1.x line: outbound email and domain authentication posture (FA3.SC2.C6, citing RFC 9989/9990/9991), calendar and scheduling exposure governance (FA4.SC5.C6), and external vulnerability disclosure intake (FA5.SC2.C6, citing RFC 9116).
- New conventions section: the normative/informative boundary, routing semantics, the illustrative-examples rule for tool and vendor names, and the status of planned companion artifacts.
- New 12-term glossary, including the first published definition of the Control Confidence Gap.
- New assessment section: scope statement (self-assessment only at 0.2.0), a 0-4 control-implementation rubric with not-applicable and risk-accepted dispositions, a four-tier finding-severity reference, and a 27-control baseline subset for small organizations.
- Alignment is NIST CSF 2.0 orientation at category level, explicitly marked as orientation metadata; control-level crosswalks to external standards ship separately as ODSF mapping packs.
- Release metadata embedded in the canonical JSON: license, attribution, release date, canonical URL, schema version, and structured contributors with a disclosure statement.
- Framework-wide editorial pass: requirement-language rewrites of early-draft controls, vendor-neutrality and absolute-claims sweeps, and typography normalization.

Artifacts:

- `odsf-v0.2.0.pdf` (109 pages) SHA-256 `f8f8075c08926ba612d0085d6137bdbda8cd1d40c92ccfdcfdb64f1a48cfe6f8`
- `odsf-v0.2.0.json` (canonical) SHA-256 `29c987c2ffb985a530c8fc5bf5391b4fe70f0650d2452d79640888068bc34bbc`

## [0.1.3] — internal only

Stabilization series on the 0.1.2 base; never exported or published.

## [0.1.2] — 2025

Draft iteration, 159 controls. Published to the retired odsf.psysecure.com catalog; the export carried no license statement.

## [0.1.1] — 2025

Initial public draft; the export carried a CC BY-SA 4.0 notice. From the 0.2.0 effective date, all framework content including the prior drafts is licensed CC BY 4.0 (see LICENSE.md, section 6.1).
