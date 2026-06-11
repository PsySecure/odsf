# ODSF Changelog

The OSINT Defense & Security Framework (ODSF) is published at https://psysecure.com/odsf/. This repository carries the official releases; the working source is maintained privately by PsySecure, and published version strings are immutable: any content change bumps the version.

## [0.3.0] — 2026-06-11

Public Draft. The release that makes honest scoring proportionate at every organization size, on a leaner catalog.

- 150 controls (163 at 0.2.0): thirteen verified duplicates merged with coverage preserved. Control IDs are never renumbered or reused; every retired ID resolves to its successor through the new `retired_controls` registry embedded in the canonical JSON (schema 1.1).
- Every control now names an evidence core: the two or three fields that prove the outcome, which scoring levels 2-3 require, with documented organization-defined equivalents accepted. The fuller field lists in implementation guidance become the level-4 verification depth.
- Every control carries applicability: the smallest organization scale where it is ordinarily proportionate (micro, small, mid, large) plus a condition predicate for conditional lanes (public mobile apps, governed canary signals, executives, and similar); a false predicate makes the control not applicable rather than failing.
- New framework-level threat model: the collect, correlate, then pretext-and-exploit reconnaissance path each focus area interrupts, and five generic adversary archetypes (opportunistic fraud operator, targeted intrusion crew, doxing and harassment actor, persona infiltrator, persistent targeted collector) mapped to the controls that counter them.
- Coverage added across the cycle: hiring-pipeline persona fraud (synthetic candidates, fake recruiters, fraudulent IT workers), an employee doxing and harassment response lane with HR ownership, certificate-transparency issuance hygiene, origin reachability behind CDN or WAF, named lookalike-domain detection mechanisms, AI training-corpus persistence as recorded residual risk, and a completed executive-protection consent architecture.
- Assessment refinements: Critical severity now requires active exploitation or incident linkage; a satisfied-by-reference routing rule ends double bookkeeping where another program owns the work; reference cadences on twelve inherently periodic controls; and a documented consultancy-delivered adoption path for micro organizations. The baseline holds at 27 controls.
- Navigation metadata: controls that explicitly reference other controls now carry a derived `related_controls` field.

Artifacts:

- `odsf-v0.3.0.pdf` (140 pages) SHA-256 `40e76d39738392f4241ceaecc36c957bcc1fab1d463c578bd686025316d073b8`
- `odsf-v0.3.0.json` (canonical) SHA-256 `2357165d1271132161e3b64c77f461f82376ab37f7e1845f73037bc951411662`

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

## [0.1.2] — July 2025

Draft iteration, 159 controls. Versioned July 14, 2025 and published to the since-retired odsf.psysecure.com catalog on July 15, 2025, with the live build stamped July 16, 2025; the export carried no license statement.

## [0.1.1] — May 2025

Initial public draft: framework development began May 9-10, 2025, with contributor review across the v0.1.x drafts (see the framework acknowledgements); the export carried a CC BY-SA 4.0 notice. From the 0.2.0 effective date, all framework content including the prior drafts is licensed CC BY 4.0 (see LICENSE.md, section 6.1).
