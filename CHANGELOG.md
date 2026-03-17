# VA Claim Scout — Changelog

**Repository:** github.com/ClaimScout/VA-Claim-Scout

---

### v0.3.1 (March 2026)
- Updated Framework Signature to VACS-0.3.1
- Tightened cross-framework detection string — scans for `FRAMEWORK SIGNATURE: SSCA-` followed by version number to prevent false triggers on uploaded records
- Added attorney detection logic — scans records for named representatives, presents pick list, identifies VA-only vs. SSDI vs. dual-practice, routes outreach draft accordingly
- Clarified VSO role — VSOs are VA-accredited only and cannot represent before SSA; outreach options updated to reflect this
- Added Plain English Summary section — what is working for the case, what is working against it, written directly for the veteran
- Added Your Next Move section — auto-generates outreach to attorney/representative, VSO coordination message, and VA Help Line summary at end of every full report
- Added "Claim Scout, run everything." — one command produces complete report start to finish
- Added "Claim Scout, walk me through it." — structured one-question-at-a-time guided intake covering service history, conditions, records, employment, medications, prior claims, and SSDI status; uncovers gaps progressively before running the full analysis; works with or without uploaded records
- Replaced cross-framework hard stop with intelligent routing question — when both frameworks are detected, asks whether to focus on VA, SSDI, or get an explanation of how the two work together; routes accordingly without stopping the session
- Added welcome menu — fires on "Claim Scout, help." with clean numbered options; disclaimer scoped to analysis responses only
- Removed version numbers from inside the framework file — version tracked by filename only

### v0.1.1 (March 2026)
- Added Framework Signature (VACS-0.1.1) for cross-framework detection
- Added cross-framework detection logic — detects if SSDI Claim Scout is loaded simultaneously
- Added platform-specific responses for Claude/ChatGPT, NotebookLM, and long conversation drift
- Added graceful exception for SSCA report handoff vs. SSCA framework detection
- Added "Works With SSDI Claim Scout" section
- Added "Claim Scout, read my SSCA report." command

### v0.3 (March 2026)
- Added version tag and update reminder
- Added "Share With a Veteran" section
- Added "Why This Tool Is Free" note
- Added TDIU three-pathway explainer (Schedular, Extraschedular, Functional)
- Added TDIU reality check and evidence checklist
- Added Section 13: Buddy Statement Generator
- Added Section 14: Impact Statement Generator (work, social, family, sexual functioning)
- Added "Claim Scout, check for updates" command
- Added "Claim Scout, write a buddy statement" command
- Added "Claim Scout, write an impact statement" command
- Added Changelog

### v0.2 (March 2026)
- Added Legal Authority Stack (38 CFR, M21-1, CAVC/BVA, Fast Letters, Pending Cases)
- Added Section 0 Command Library
- Added license and credit block
- Added GitHub credit requirement
- Formatted help lines and crisis line as separate ruled blocks
- Added "Claim Scout, help." as primary activation command

### v0.1 (March 2026)
- Initial pre-release merge of v2.0 and proposed v2.1
- Added Kinetic Chain framework
- Added Pyramiding Guardrails
- Added Doctor Script (12B)
- Added TDIU and SMC scans
