# VA Claim Scout — Changelog

**Repository:** github.com/claimscout/VA-Claim-Scout

---

### v0.3.2 (September 2026)

**Note:** This entry reflects what is present in the shipped files.

#### Added / Strengthened
- **Citation Confidence Rule** (Pro + README): Standalone mandatory rule. Model must output `⚠️ LOW CONFIDENCE CITATION` with plain-language description and verification pointer instead of inventing authorities. A confident citation is still not a verified citation.
- **"Works With a Living Plan"** (Pro + README): Explicit single-pass design statement, three habits (Correction Log, pre-save consistency check, Guess → confirmed), independence note, and `Claim Scout, audit my living plan.` command.
- **Cross-Denial-Collision Check** (Pro Red Team): New theories checked against language already used in prior denial letters; collisions must be surfaced.
- **README:** Stronger "Every Citation Must Be Verified" section and explicit warning that Lite/free-tier models are more likely to invent citations.

#### Known gap
- **Lite** has not yet received the full port of the Citation Confidence Rule, living-plan section, audit command, and cross-denial check. This remains the next priority — Lite targets the models most prone to citation invention.

Framework Signature on Pro is VACS-0.3.2.

### v0.3.1 (March 2026)
- Framework Signature VACS-0.3.1
- Cross-framework detection and routing
- Attorney detection and VSO role clarification
- Plain English Summary and Your Next Move
- "run everything" and "walk me through it" commands
- Welcome menu

### Earlier versions
See repository history for v0.3, v0.2, v0.1.1, v0.1.
